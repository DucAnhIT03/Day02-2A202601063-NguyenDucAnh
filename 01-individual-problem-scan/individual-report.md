# Báo cáo cá nhân — Problem Scan

**Họ và tên:** Nguyễn Đức Anh  
**Mã học viên:** 2A202601063  
**Bối cảnh quan sát:** sinh viên đại học học nhiều môn, nhận yêu cầu qua LMS, Discord và tài liệu giảng viên chia sẻ.

> Phạm vi Phase 1 chỉ là nhận diện vấn đề, actor và dấu hiệu quan sát; chưa đề xuất hay lựa chọn giải pháp. Các con số thời gian dưới đây là ước lượng hồi tưởng của cá nhân, không phải kết quả khảo sát. Khi chưa có log, bài ghi rõ trạng thái “chưa đo” thay vì trình bày ước lượng như baseline đã kiểm chứng.

## 1. Scan rộng

### 1.1. Cách hình thành danh sách

Tôi bắt đầu từ các hoạt động mình trực tiếp thực hiện trong học tập và dự án: kiểm tra yêu cầu bài tập, đọc rubric, theo dõi trao đổi nhóm, tìm lại thông tin, chuẩn bị tài liệu và nộp file. Tôi ghi lại pain trước theo câu hỏi “việc gì lặp lại, mất thời gian hoặc khiến người khác phải hỏi lại?”, sau đó mới dùng AI để hỗ trợ phân loại và phản biện cách viết.

AI không được dùng làm bằng chứng rằng một pain có thật. Tôi loại bỏ các gợi ý quá rộng hoặc không gắn với workflow mình nhận biết được. Danh sách cuối chỉ giữ các vấn đề có actor và một biểu hiện có thể quan sát. Những dòng chưa có log định lượng được đánh dấu rõ để đo tiếp, không coi là dữ liệu đã xác nhận.

### 1.2. Bảng scan

| # | Lăng kính | Problem quan sát được | Actor — ai chịu ảnh hưởng? | Dấu hiệu đã quan sát | Trạng thái evidence / cách đo tiếp |
|---:|---|---|---|---|---|
| 1 | Lặp lại; tốn thời gian | Mỗi đầu tuần phải mở nhiều kênh để gom yêu cầu và deadline của từng bài tập | Sinh viên học nhiều môn, trực tiếp là tôi | Việc kiểm tra LMS, Discord và file hướng dẫn lặp lại; cùng một bài có thông tin nằm ở nhiều nơi | Có quan sát trực tiếp; thời gian 20–30 phút/lần là ước lượng, cần time log một tuần |
| 2 | Khó khăn từ người khác | Thành viên nhóm hỏi lại “nộp file gì, đặt tên ra sao?” dù yêu cầu đã xuất hiện trong chuỗi tin nhắn | Thành viên nhóm làm bài; người tổng hợp bài nộp | Trong trao đổi nhóm xuất hiện câu hỏi lặp lại về deliverable, tên file hoặc cách nộp | Có quan sát định tính; cần đếm câu hỏi và số lần sửa file trong một bài nhóm |
| 3 | AI có thể hỗ trợ tốt hơn | Đọc rubric dài nhưng vẫn có nguy cơ bỏ sót deliverable hoặc tiêu chí bắt buộc | Sinh viên chuẩn bị nộp bài, trực tiếp là tôi | Có trường hợp chỉ nhận ra mục còn thiếu khi đối chiếu lại bài với rubric ở cuối quá trình | Có quan sát trực tiếp; cần lưu checklist trước nộp để đếm số mục phát hiện muộn |
| 4 | Lặp lại | Sau mỗi buổi học phải chuyển ghi chú rời rạc thành danh sách việc cần làm | Sinh viên tự quản lý việc học | Hoạt động đọc lại ghi chú và chép action item xuất hiện sau nhiều buổi học | Có quan sát trực tiếp; 10–15 phút/buổi là ước lượng, cần đo bằng time log |
| 5 | Tốn thời gian | Khi làm tiếp một task, phải tìm lại lời giải thích hoặc quyết định cũ trong Discord | Sinh viên và thành viên nhóm dự án | Phải thử lại từ khóa, mở nhiều kết quả và đọc ngữ cảnh thread trước khi xác định đúng thông tin | Có quan sát trực tiếp; cần đo time-to-source cho 5 lần tìm tiếp theo |
| 6 | Lặp lại; khó khăn từ người khác | Thành viên cập nhật tiến độ không cùng cấu trúc nên khó biết task nào đang trễ hoặc ai đang bị kẹt | Cả nhóm bài tập, đặc biệt người điều phối | Một số status thiếu owner, deadline hoặc blocker, dẫn tới phải hỏi bổ sung | Có quan sát định tính; cần đếm số status thiếu field và số lượt hỏi lại trong một tuần |
| 7 | Tốn thời gian | Trước khi ôn tập phải gom slide, PDF, ghi chú và link đang nằm ở nhiều vị trí | Sinh viên chuẩn bị kiểm tra, trực tiếp là tôi | Phải tìm và sắp xếp nguồn trước khi bắt đầu học nội dung; có link hoặc phiên bản tài liệu khó tìm lại | Có quan sát trực tiếp; 45–90 phút/môn là ước lượng cần time log xác nhận |
| 8 | Khó khăn từ người khác | Reviewer thiếu bối cảnh khi mô tả pull request không nêu cách chạy, phạm vi hoặc mục tiêu thay đổi | Người review code và người tạo pull request | Reviewer phải hỏi bổ sung hoặc đọc code để tự suy ra thông tin lẽ ra thuộc phần mô tả | Có quan sát theo workflow dự án; cần đếm comment hỏi lại trên các PR tiếp theo |
| 9 | Lặp lại | Trước khi nộp phải kiểm tra và đổi tên file vì cách đặt tên hoặc vị trí lưu chưa nhất quán | Sinh viên nộp bài; giảng viên nhận bài | Có file phải đổi tên gần thời điểm nộp hoặc khó phân biệt bản nháp với bản cuối | Có quan sát trực tiếp; cần kiểm lịch sử file và đếm số lần đổi tên/upload lại |
| 10 | AI có thể hỗ trợ tốt hơn | Sau khi đọc tài liệu kỹ thuật, khó tự tạo câu hỏi nhắm đúng phần mình chưa hiểu | Sinh viên học nội dung kỹ thuật | Có cảm giác đã hiểu sau khi đọc nhưng bị kẹt khi phải tự giải thích hoặc áp dụng mà không nhìn tài liệu | Có quan sát tự thân; cần dùng pre/post self-test để đo chênh lệch |

### 1.3. Kiểm tra độ phủ bốn lăng kính

| Lăng kính bắt buộc | Problems đại diện | Kết luận |
|---|---|---|
| Lặp lại | #1, #4, #6, #9 | Có nhiều hoạt động xuất hiện theo buổi/tuần hoặc mỗi lần nộp bài |
| Tốn thời gian | #1, #5, #7 | Điểm tốn công nằm ở tìm kiếm, đọc và tổng hợp nhiều nguồn |
| AI có thể hỗ trợ tốt hơn | #3, #10 | Đây là tác vụ đọc hiểu, đối chiếu hoặc tạo nội dung theo ngữ cảnh; chưa kết luận chắc chắn phải dùng AI |
| Khó khăn đến từ người khác | #2, #6, #8 | Pain thể hiện qua câu hỏi lặp lại, thiếu field và thiếu bối cảnh khi handoff |

### 1.4. Kết luận Phase 1

- Có 10 problems, vượt mức tối thiểu 5 nhưng vẫn nằm trong một bối cảnh cụ thể.
- Mỗi problem đều có actor và workflow hoặc thời điểm phát sinh có thể nhận biết.
- Đủ cả bốn lăng kính; một problem có thể thuộc nhiều lăng kính.
- Evidence được phân biệt thành quan sát định tính, ước lượng hồi tưởng và measurement cần thực hiện.
- Chưa lựa chọn giải pháp trong Phase 1; đánh giá No AI / Rule / Workflow / Agent được để sang các phase sau.

## 2. Phase 2 — Top 3 Problem Cards và draft workflow

**Sơ đồ Mermaid riêng:** [01-individual-problem-scan-workflows.md](01-individual-problem-scan-workflows.md)

### 2.1. Chọn Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Gom yêu cầu và deadline bài tập từ nhiều nguồn | Actor, workflow và điểm nghẽn rõ; xảy ra hằng tuần; có thể đo thời gian và tỷ lệ bỏ sót | Baseline 20–30 phút cần time log; quyền truy cập dữ liệu giữa các hệ thống |
| 2 | Kiểm tra bài nộp theo rubric | Phạm vi nhỏ, output kiểm được, có human review | Chất lượng góp ý AI có ổn định giữa các dạng rubric không |
| 3 | Tìm quyết định cũ trong Discord | Pain lặp lại cho cả nhóm; dễ đo thời gian tìm kiếm | Search có sẵn có thể đã đủ; kết nối dữ liệu và quyền riêng tư |

### 2.2. Problem Card #1 — Gom yêu cầu và deadline

**Problem một câu:** Mỗi đầu tuần, sinh viên học nhiều môn phải dò LMS, Discord và file hướng dẫn để tự tạo danh sách bài tập; thông tin phân tán khiến việc tổng hợp chậm và có nguy cơ bỏ sót yêu cầu.

**Actor:** Sinh viên đang học từ 4 môn trở lên và nhận thông tin qua nhiều kênh.

**Thời điểm / bối cảnh:** Đầu tuần và trước mỗi hạn nộp.

**Current workflow:**

1. Mở từng lớp trên LMS.
2. Kiểm tra các kênh Discord liên quan.
3. Mở file hướng dẫn/rubric được đính kèm.
4. Chép tên bài, deadline, deliverable vào danh sách cá nhân.
5. Đối chiếu lại khi gần hạn.

**Bottleneck:** Bước 2–4: phải đọc, phân biệt thông báo quan trọng và nối thông tin rời rạc; ước lượng 20–30 phút/tuần.

**Impact:** Mất thời gian lặp lại; deadline hoặc yêu cầu file có thể bị bỏ sót; nhóm phải hỏi lại nhau.

**Success metric:** Trong pilot hai tuần, giảm median thời gian tổng hợp từ baseline đo được xuống ít nhất 50%; recall deadline/deliverable đạt 100% so với kiểm tra thủ công; mọi mục đều có link nguồn.

**Non-AI alternative:** Một bảng checklist chung, quy ước một kênh thông báo và đồng bộ lịch. Đây là phương án ưu tiên nếu nhà trường/nhóm kiểm soát được nguồn.

**AI hypothesis:** Sau khi người dùng cung cấp nội dung hoặc kết nối nguồn được phép, AI trích xuất yêu cầu chưa có cấu trúc thành draft; người dùng xác nhận trước khi đưa vào lịch.

**Quick gut:**

- [ ] No AI / process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

#### Draft workflow trước/sau

```text
CURRENT STATE — 6 bước, ước lượng 20–30 phút/tuần
[1. Mở LMS: ~5']
→ [2. Đọc Discord: ~5']
→ [3. Mở rubric/file: ~3']
→ [4. Nhận diện + nối deadline/deliverable: ~8–12']  <-- bottleneck
→ [5. Chép vào task list: ~3']
→ [6. Đối chiếu lại: ~2']

FUTURE STATE — 5 bước, mục tiêu giảm ≥50% sau khi đo baseline
[1. Lấy due date có cấu trúc: Rule]
→ [2. Sinh viên chọn/paste nguồn được phép]
→ [3. AI draft field + link nguồn]
→ [4. Sinh viên mở nguồn, sửa và xác nhận]  <-- human boundary
→ [5. Rule ghi task/lịch đã duyệt]

Fallback: thiếu nguồn hoặc độ tin cậy thấp → đánh dấu “cần kiểm tra”;
không tự tạo lịch và quay về checklist thủ công.
```

**Thay đổi chính:** Giảm công đọc và chép thủ công; không bỏ bước xác nhận vì deadline sai có hậu quả cao.

### 2.3. Problem Card #2 — Kiểm tra bài nộp theo rubric

**Problem một câu:** Trước khi nộp, sinh viên phải đối chiếu thủ công bài làm với rubric dài nên dễ bỏ sót deliverable hoặc tiêu chí bắt buộc.

**Actor:** Sinh viên chuẩn bị nộp bài có rubric/checklist nhiều mục.

**Thời điểm / bối cảnh:** 30–60 phút cuối trước hạn nộp.

**Current workflow:**

1. Đọc toàn bộ rubric và xác định các mục bắt buộc.
2. Mở các file sẽ nộp.
3. Dò từng tiêu chí trong bài và ghi nhớ/ghi chú phần còn thiếu.
4. Sửa nội dung hoặc cấu trúc file.
5. Đọc rubric và kiểm tra lại lần cuối.

**Bottleneck:** Ánh xạ câu chữ trong rubric với vị trí bằng chứng trong bài; ước lượng 20 phút/lần.

**Impact:** Nộp thiếu mục, sửa sát giờ, mất điểm vì lỗi hình thức thay vì nội dung.

**Success metric:** Giảm thời gian kiểm tra ít nhất 40%; 100% mục bắt buộc có trạng thái và vị trí bằng chứng; không tăng false negative khi giảng viên/người học kiểm lại.

**Non-AI alternative:** Chuyển rubric thành checklist cố định và yêu cầu người học tự tick.

**AI hypothesis:** AI tạo bảng “tiêu chí — bằng chứng — trạng thái — câu hỏi cần kiểm tra”; không tự chấm điểm cuối.

**Quick gut:**

- [ ] No AI / process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

#### Draft workflow trước/sau

```text
CURRENT STATE — 5 bước, ước lượng khoảng 20 phút/lần
[1. Đọc rubric: ~4']
→ [2. Mở các file: ~2']
→ [3. Ánh xạ tiêu chí với bằng chứng: ~8']  <-- bottleneck
→ [4. Sửa bài: thời gian phụ thuộc lỗi]
→ [5. Dò lại: ~6']

FUTURE STATE — 5 bước, mục tiêu giảm thời gian kiểm tra ≥40%
[1. Rule chuyển rubric thành checklist]
→ [2. AI đề xuất bằng chứng/trạng thái cho từng tiêu chí]
→ [3. Sinh viên mở đúng vị trí và xác nhận]  <-- human boundary
→ [4. Sinh viên sửa mục thiếu]
→ [5. Rule kiểm checklist bắt buộc trước khi nộp]

Fallback:
- AI không tìm thấy ≠ bài chắc chắn thiếu; đánh dấu “chưa xác định”.
- AI trích sai → bỏ gợi ý và kiểm theo checklist thủ công.
- AI không chấm điểm cuối hoặc tự sửa nội dung thay sinh viên.
```

**Thay đổi chính:** AI hỗ trợ tìm vị trí bằng chứng, nhưng sinh viên vẫn chịu trách nhiệm xác nhận bài đã đáp ứng tiêu chí.

### 2.4. Problem Card #3 — Tìm quyết định cũ trong Discord

**Problem một câu:** Thành viên nhóm mất thời gian tìm lại quyết định, file hoặc lời giải thích đã trôi trong nhiều kênh Discord.

**Actor:** Thành viên nhóm học tập/dự án dùng Discord làm kênh trao đổi.

**Thời điểm / bối cảnh:** Khi bắt đầu một task hoặc cần kiểm tra quyết định cũ.

**Current workflow:**

1. Nhớ lại một vài từ khóa liên quan.
2. Chọn server và kênh có khả năng chứa thông tin.
3. Search theo từ khóa hoặc bộ lọc.
4. Mở nhiều kết quả và đọc lại thread.
5. Xác định quyết định/file đúng hoặc hỏi lại nhóm nếu không tìm thấy.

**Bottleneck:** Từ khóa trong trí nhớ không trùng câu chữ của tin nhắn; ước lượng 5–15 phút/lần.

**Impact:** Gián đoạn công việc, hỏi lặp lại, có thể làm theo quyết định đã lỗi thời.

**Success metric:** Median time-to-source dưới 2 phút; câu trả lời phải kèm link tin nhắn; tỷ lệ tìm đúng nguồn ≥90% trên bộ 20 câu hỏi kiểm thử.

**Non-AI alternative:** Dùng bộ lọc `from:`, `in:`, `has:` của Discord và duy trì kênh `#decisions`.

**AI hypothesis:** Semantic search/reranking trên các kênh được cho phép, chỉ tóm tắt khi có trích dẫn nguồn.

**Quick gut:**

- [ ] No AI / process fix
- [ ] Rule
- [x] Workflow
- [ ] Agent
- [ ] Chưa biết

#### Draft workflow trước/sau

```text
CURRENT STATE — 5 bước, ước lượng 5–15 phút/lần
[1. Nhớ từ khóa]
→ [2. Chọn server/kênh]
→ [3. Search theo keyword/filter]
→ [4. Mở và đọc nhiều thread]  <-- bottleneck
→ [5. Dùng thông tin hoặc hỏi lại]

FUTURE STATE — 5 bước, mục tiêu median time-to-source <2 phút
[1. Người dùng nhập câu hỏi]
→ [2. Rule giới hạn server/kênh được phép]
→ [3. Semantic search/reranking]
→ [4. Hiển thị đoạn liên quan + link; chỉ tóm tắt khi có nguồn]
→ [5. Người dùng mở thread và quyết định]  <-- human boundary

Fallback:
- Không có nguồn đủ mạnh → trả “chưa tìm thấy”, không suy đoán.
- Kết quả mâu thuẫn → hiển thị cả hai nguồn và yêu cầu người dùng xác minh.
- Workflow lỗi → dùng Discord Search với `from:`, `in:`, `has:`.
```

**Thay đổi chính:** Giảm số kết quả phải đọc, nhưng câu trả lời không thay thế tin nhắn gốc.

### 2.5. Card ưu tiên để pitch

**Card chọn:** Gom yêu cầu và deadline bài tập từ nhiều nguồn.

**Vì sao:** Bài toán xảy ra đều đặn, có rủi ro bỏ sót rõ, workflow before/after vẽ được và cho phép so sánh process fix, Rule, Workflow và Agent.

**Câu hỏi muốn nhóm challenge:** “Nếu chỉ thống nhất một bảng deadline chung và một kênh thông báo thì đã giải quyết được phần lớn vấn đề chưa; phần nào thực sự cần AI?”

**Pitch ngắn:**

> Sinh viên học nhiều môn phải dò LMS, Discord và rubric để tự gom deadline và deliverable. Bước nghẽn là nhận diện rồi nối thông tin rời rạc, hiện được ước lượng 20–30 phút mỗi tuần nhưng chưa có time log. Tôi đề xuất kiểm chứng một Workflow nhỏ: Rule lấy dữ liệu có cấu trúc, AI tạo draft từ phần phi cấu trúc, sinh viên mở nguồn và xác nhận trước khi ghi lịch. Thành công chỉ được tính khi giảm ít nhất 50% thời gian mà vẫn đạt recall deadline/deliverable 100%.

### 2.6. Đối chiếu người dùng, failure point và ranh giới người–máy

| Card | Người dùng đã rõ? | Failure point chính | Human boundary |
|---|---|---|---|
| #1 Gom deadline | Có: sinh viên học từ 4 môn, nhận yêu cầu qua nhiều kênh | Trích sai ngày, ghép nhầm bài hoặc dùng nguồn cũ | Sinh viên mở link và xác nhận từng item trước khi ghi lịch |
| #2 Kiểm rubric | Có: sinh viên sắp nộp bài có rubric nhiều mục | AI không tìm thấy bằng chứng dù bài có, hoặc diễn giải sai tiêu chí | Sinh viên kiểm từng tiêu chí; AI không tự chấm điểm cuối |
| #3 Search Discord | Có: thành viên nhóm dùng Discord để lưu trao đổi | Trả kết quả không đúng ngữ cảnh hoặc quyết định đã lỗi thời | Người dùng mở thread gốc và quyết định có sử dụng hay không |

### 2.7. Tự kiểm Phase 2

- [x] Chọn Top 3 từ danh sách scan.
- [x] Mỗi card có Problem một câu, Actor và bối cảnh.
- [x] Mỗi card có current workflow gồm 3–7 bước.
- [x] Mỗi card có Bottleneck, Impact và Success metric.
- [x] Mỗi card có Non-AI alternative, AI hypothesis và Quick gut.
- [x] Mỗi card có draft workflow trước/sau, human boundary và fallback.
- [x] Đã chọn một card ưu tiên, viết pitch ngắn và có câu hỏi để nhóm phản biện.

### 2.8. Ghi chú sử dụng AI

AI được dùng để phản biện tính đo được của metric và chỉ ra rằng “AI không tìm thấy” không đồng nghĩa “bài không có yêu cầu”. Tôi giữ human confirmation, link nguồn và fallback thủ công; không chọn Agent tự động nộp hay tự gửi thông báo.
