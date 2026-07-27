# Draft workflows — Top 3 Problem Cards

**Học viên:** Nguyễn Đức Anh — 2A202601063

> Các con số thời gian là ước lượng hồi tưởng dùng để xác định điểm cần đo, không phải baseline đã kiểm chứng.

## Card #1 — Gom yêu cầu và deadline

### Current state

```mermaid
flowchart LR
    A["Mở LMS<br/>~5 phút"] --> B["Đọc Discord<br/>~5 phút"]
    B --> C["Mở rubric/file<br/>~3 phút"]
    C --> D["Nhận diện và nối<br/>deadline + deliverable<br/>~8–12 phút"]
    D --> E["Chép task/lịch<br/>~3 phút"]
    E --> F["Đối chiếu lại<br/>~2 phút"]

    classDef bottleneck fill:#fee2e2,stroke:#dc2626,stroke-width:2px,color:#7f1d1d;
    class D bottleneck;
```

**Bottleneck:** Nhận diện và nối các field của cùng một bài từ nhiều nguồn.

### Future state

```mermaid
flowchart LR
    A["Rule<br/>Lấy due date có cấu trúc"] --> B["Người dùng<br/>Chọn/paste nguồn được phép"]
    B --> C["AI<br/>Draft field + citation"]
    C --> D{"Rule<br/>Đủ field và không xung đột?"}
    D -->|Có| E["Sinh viên<br/>Mở nguồn, sửa, xác nhận"]
    D -->|Không| X["Gắn cờ<br/>Cần kiểm tra"]
    X --> E
    E --> F["Rule<br/>Ghi task/lịch đã duyệt"]

    classDef human fill:#dcfce7,stroke:#16a34a,stroke-width:2px,color:#14532d;
    classDef ai fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a8a;
    classDef fallback fill:#fef3c7,stroke:#d97706,stroke-width:2px,color:#78350f;
    class B,E human;
    class C ai;
    class X fallback;
```

**Human boundary:** Sinh viên xác nhận từng record trước khi ghi lịch.  
**Fallback:** Thiếu nguồn, xung đột hoặc AI lỗi → checklist thủ công; không tự tạo deadline.

---

## Card #2 — Kiểm tra bài nộp theo rubric

### Current state

```mermaid
flowchart LR
    A["Đọc rubric<br/>~4 phút"] --> B["Mở các file<br/>~2 phút"]
    B --> C["Ánh xạ tiêu chí<br/>với bằng chứng<br/>~8 phút"]
    C --> D["Sửa bài<br/>phụ thuộc lỗi"]
    D --> E["Dò lại<br/>~6 phút"]

    classDef bottleneck fill:#fee2e2,stroke:#dc2626,stroke-width:2px,color:#7f1d1d;
    class C bottleneck;
```

**Bottleneck:** Ánh xạ từng tiêu chí trong rubric với vị trí bằng chứng trong bài.

### Future state

```mermaid
flowchart LR
    A["Rule<br/>Tách rubric thành checklist"] --> B["AI<br/>Đề xuất bằng chứng/trạng thái"]
    B --> C["Sinh viên<br/>Mở vị trí và xác nhận"]
    C --> D{"Đủ tiêu chí?"}
    D -->|Chưa| E["Sinh viên<br/>Sửa mục thiếu"]
    E --> C
    D -->|Đủ| F["Rule<br/>Kiểm checklist cuối"]

    classDef human fill:#dcfce7,stroke:#16a34a,stroke-width:2px,color:#14532d;
    classDef ai fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a8a;
    class B ai;
    class C,E human;
```

**Human boundary:** AI không tự chấm điểm; sinh viên xác nhận bằng chứng và nội dung sửa.  
**Fallback:** AI không tìm thấy không đồng nghĩa bài thiếu; quay về checklist thủ công.

---

## Card #3 — Tìm quyết định cũ trong Discord

### Current state

```mermaid
flowchart LR
    A["Nhớ từ khóa"] --> B["Chọn server/kênh"]
    B --> C["Search keyword/filter"]
    C --> D["Mở và đọc<br/>nhiều thread"]
    D --> E{"Tìm thấy nguồn đúng?"}
    E -->|Có| F["Dùng thông tin"]
    E -->|Không| G["Hỏi lại nhóm"]

    classDef bottleneck fill:#fee2e2,stroke:#dc2626,stroke-width:2px,color:#7f1d1d;
    class D bottleneck;
```

**Bottleneck:** Phải đọc nhiều thread vì từ khóa không khớp cách diễn đạt trong tin nhắn.

### Future state

```mermaid
flowchart LR
    A["Người dùng<br/>Nhập câu hỏi"] --> B["Rule<br/>Giới hạn kênh được phép"]
    B --> C["Search/reranking<br/>theo ngữ nghĩa"]
    C --> D{"Có nguồn đủ mạnh?"}
    D -->|Có| E["Hiển thị đoạn liên quan<br/>+ link message"]
    E --> F["Người dùng<br/>Mở thread và quyết định"]
    D -->|Không| G["Trả chưa tìm thấy<br/>không suy đoán"]
    G --> H["Discord Search<br/>from: in: has:"]

    classDef human fill:#dcfce7,stroke:#16a34a,stroke-width:2px,color:#14532d;
    classDef ai fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a8a;
    classDef fallback fill:#fef3c7,stroke:#d97706,stroke-width:2px,color:#78350f;
    class A,F human;
    class C ai;
    class G,H fallback;
```

**Human boundary:** Người dùng phải mở tin nhắn gốc và tự quyết định thông tin còn hiệu lực hay không.  
**Fallback:** Không có nguồn đủ mạnh → nói chưa tìm thấy và dùng Discord Search có sẵn.

## Chú giải

| Màu | Ý nghĩa |
|---|---|
| Đỏ | Bottleneck hiện tại |
| Xanh lá | Bước con người chịu trách nhiệm |
| Xanh dương | Bước AI hỗ trợ |
| Vàng | Fallback / case cần kiểm tra |
