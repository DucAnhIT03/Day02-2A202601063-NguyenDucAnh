# Workflow nhóm — Before / After và Decision

**Candidate:** Gom yêu cầu và deadline bài tập từ LMS, Discord và rubric  
**Mức can thiệp đề xuất:** Workflow có AI hỗ trợ một bước + Human Review  
**Decision:** `Not Yet`

> Baseline thời gian chưa được đo. Sơ đồ mô tả actor, handoff, bottleneck, boundary và fallback; không khẳng định solution đã đạt target.

## 1. Current workflow

```mermaid
flowchart TB
    subgraph Sources["Nguồn thông tin"]
        LMS["LMS<br/>item có cấu trúc"]
        DIS["Discord<br/>thông báo/đính chính"]
        DOC["Rubric / file / link<br/>deliverable + cách nộp"]
    end

    subgraph Student["Actor: Sinh viên"]
        A["1. Kiểm từng lớp trên LMS"]
        B["2. Đọc Discord"]
        C["3. Mở rubric/file"]
        D["4. Diễn giải + nối thành record<br/>môn, task, deadline, deliverable,<br/>format, cách nộp, source"]
        E["5. Chép record vào task list/lịch"]
        F["6. Mở nguồn đối chiếu trước hạn"]
    end

    LMS --> A
    DIS --> B
    DOC --> C
    A -->|"Handoff qua tab/note/trí nhớ"| B
    B -->|"Handoff qua note tạm/trí nhớ"| C
    C --> D
    D -->|"Record tự tổng hợp"| E
    E --> F

    classDef bottleneck fill:#fee2e2,stroke:#dc2626,stroke-width:3px,color:#7f1d1d;
    classDef source fill:#f3f4f6,stroke:#6b7280,color:#111827;
    class D bottleneck;
    class LMS,DIS,DOC source;
```

**Bottleneck:** Bước 4.  
**Handoff yếu nhất:** Từ nhiều nguồn/tab → trí nhớ/note tạm → record được chép thủ công.

## 2. Future workflow

```mermaid
flowchart TB
    S1["Nguồn có cấu trúc<br/>LMS/lịch chính thức"]
    S2["Nguồn phi cấu trúc<br/>Discord/rubric do người dùng chọn"]

    R1["1. RULE<br/>Lấy field có cấu trúc + source"]
    H1["2. NGƯỜI<br/>Chọn/paste nguồn trong scope"]
    AI["3. AI<br/>Draft record + citation"]
    R2{"4. RULE<br/>Đủ field, đúng format,<br/>không xung đột?"}
    H2["5. NGƯỜI<br/>Mở citation, sửa, xác nhận"]
    R3["6. RULE<br/>Ghi record đã duyệt"]
    OUT["Task list / lịch cá nhân"]

    F1["Thiếu nguồn<br/>→ ghi chưa xác định"]
    F2["Nguồn xung đột<br/>→ hiển thị cả hai"]
    F3["AI lỗi<br/>→ checklist thủ công"]

    S1 --> R1
    S2 --> H1
    R1 --> AI
    H1 --> AI
    AI --> R2
    R2 -->|Pass| H2
    R2 -->|Thiếu nguồn| F1
    R2 -->|Xung đột| F2
    AI -.->|Không chạy/output lỗi| F3
    F1 --> H2
    F2 --> H2
    F3 --> H2
    H2 -->|Xác nhận explicit| R3
    R3 --> OUT

    classDef human fill:#dcfce7,stroke:#16a34a,stroke-width:3px,color:#14532d;
    classDef ai fill:#dbeafe,stroke:#2563eb,stroke-width:3px,color:#1e3a8a;
    classDef rule fill:#f3f4f6,stroke:#4b5563,stroke-width:2px,color:#111827;
    classDef fallback fill:#fef3c7,stroke:#d97706,stroke-width:2px,color:#78350f;
    class H1,H2 human;
    class AI ai;
    class R1,R2,R3 rule;
    class F1,F2,F3 fallback;
```

### Boundary

- AI chỉ tạo draft từ nguồn đã được chọn và phải giữ citation.
- Rule không tự suy ra field thiếu hoặc tự chọn giữa hai nguồn xung đột.
- Sinh viên chịu trách nhiệm mở nguồn, sửa và xác nhận từng record.
- Không xác nhận → không ghi task/lịch.
- Không tự gửi thông báo và không tự nộp bài.

## 3. Before / after

```mermaid
flowchart LR
    subgraph Before["BEFORE — 6 bước, baseline chưa đo"]
        B1["Thu thập nhiều nguồn"] --> B2["Đọc + diễn giải"]
        B2 --> B3["Nối field thủ công"]
        B3 --> B4["Chép task/lịch"]
        B4 --> B5["Kiểm lại"]
    end

    subgraph After["AFTER — 6 bước, mục tiêu giảm effort"]
        A1["Rule lấy field có cấu trúc"] --> A2["AI draft phần phi cấu trúc"]
        A2 --> A3["Rule kiểm schema/xung đột"]
        A3 --> A4["Người review + xác nhận"]
        A4 --> A5["Rule ghi record"]
    end
```

| Metric | Before | After target |
|---|---|---|
| Tổng thời gian | Chưa đo; 20–30 phút/tuần chỉ là ước lượng | Median giảm ≥50% sau khi có baseline |
| Bước người chủ động | 6/6 | 2/6 |
| Bottleneck | Diễn giải + nối + chép | Review và xử lý ngoại lệ |
| Recall deadline/deliverable | Chưa đo | 100% |
| Precision theo field | Chưa đo | ≥95% |
| Traceability | Không bắt buộc | 100% record có source |

## 4. Cây quyết định mức can thiệp

```mermaid
flowchart TB
    P["Candidate problem"] --> Q1{"Pain/volume đã được<br/>validation đủ?"}
    Q1 -->|Chưa| NY["NOT YET<br/>Interview + time log"]
    Q1 -->|Có| Q2{"Input ổn định và logic<br/>viết hết bằng rule?"}
    Q2 -->|Có| RULE["RULE / SCRIPT"]
    Q2 -->|Không| Q3{"Cần tự lập kế hoạch,<br/>nhiều tool/state thay đổi?"}
    Q3 -->|Không| WF["WORKFLOW<br/>AI + Human Review"]
    Q3 -->|Có| Q4{"Lợi ích Agent có vượt<br/>permission/risk không?"}
    Q4 -->|Chưa rõ/Không| WF
    Q4 -->|Có, có controls| AG["AGENT + CONTROLS"]

    classDef selected fill:#dbeafe,stroke:#2563eb,stroke-width:3px,color:#1e3a8a;
    classDef pending fill:#fef3c7,stroke:#d97706,stroke-width:3px,color:#78350f;
    class NY pending;
    class WF selected;
```

**Kết quả hiện tại:** Solution hypothesis là `Workflow`, nhưng quyết định triển khai là `Not Yet`.

## 5. Validation gates và rollback

```mermaid
flowchart LR
    G1["Interview ≥3"] --> G2["Time log"]
    G2 --> G3["Gold set ≥20 mẫu"]
    G3 --> G4["Test checklist/Rule-only"]
    G4 --> G5["Test Workflow có AI"]
    G5 --> D{"Đạt recall 100%,<br/>precision ≥95%,<br/>time giảm ≥50%?"}
    D -->|Có| GO["GO pilot nhỏ"]
    D -->|Không| RB["ROLLBACK<br/>Checklist + Rule/lịch"]
```

## Chú giải

| Màu | Ý nghĩa |
|---|---|
| Đỏ | Bottleneck |
| Xanh lá | Human boundary / bước con người |
| Xanh dương | AI hoặc lựa chọn Workflow |
| Xám | Rule / source có cấu trúc |
| Vàng | Fallback hoặc `Not Yet` |
