# Group Report — Day 02

## 1. Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|---:|---|---|---|
| 1 | Nguyễn Đức Anh | 2A202601063 | Đề xuất candidate, phân tích workflow, research |
| 2 |  | — |  |
| 3 |  | — |  |

> Bản này hoàn thiện phần phân tích từ dữ liệu hiện có. Nhật ký phát biểu, tên thành viên và validation với người thật phải được nhóm bổ sung sau buổi làm việc; báo cáo không bịa phỏng vấn hay đồng thuận nhóm.

## 2. Phase 3 — Nhật ký Group Convergence

### 2.1. Vị trí trong Double Diamond

Nhóm đang ở phần **Define của Diamond 1 — tìm đúng vấn đề**:

```text
DISCOVER — cá nhân scan rộng
→ DEFINE — pitch → cluster → shortlist → chọn một candidate
→ CHƯA sang Diamond 2 — chưa chọn hay triển khai solution
```

Mục tiêu của phase này chỉ là chọn một candidate đáng đào sâu. Các nhận định về Rule, Workflow hoặc Agent ở đây chỉ dùng để kiểm tra candidate có phân tích được hay không, chưa phải quyết định giải pháp.

### 2.2. Nguyên tắc hội tụ

1. Nghe hết các candidate trước khi chấm.
2. Không chọn theo độ “ngầu” của solution hoặc vì candidate có chữ AI.
3. Chấm điểm chỉ để làm lộ khác biệt trong lập luận, không thay thế đồng thuận.
4. Nếu hai bài bằng điểm, ưu tiên bài có actor và bottleneck rõ hơn; sau đó xét evidence, phạm vi lab và khả năng kiểm chứng.
5. Lời pitch, câu hỏi challenge và quyết định cuối phải do học viên tự thực hiện. Báo cáo chỉ lưu lại nội dung sau thảo luận.

### 2.3. Nhật ký pitch candidates

| # | Người đưa ra | Candidate problem | Actor | Current bottleneck | Workflow sau thay đổi gì? | Câu hỏi cần challenge |
|---:|---|---|---|---|---|---|
| 1 | Nguyễn Đức Anh | Gom yêu cầu và deadline từ LMS, Discord và rubric | Sinh viên học từ 4 môn, nhận yêu cầu qua nhiều kênh | Phải tự nhận diện rồi nối deadline, deliverable và cách nộp từ nội dung rời rạc | Giảm việc đọc/chép thủ công; sinh viên vẫn xác nhận nguồn trước khi ghi task | Checklist + một kênh thông báo có giải quyết đủ pain không? |
| 2 | Nguyễn Đức Anh | Kiểm tra bài nộp theo rubric | Sinh viên sắp nộp bài có rubric nhiều mục | Ánh xạ từng tiêu chí với vị trí bằng chứng trong bài | Chuyển rubric thành checklist và đưa người học tới vị trí cần xác nhận | Đo “không bỏ sót” thế nào và ai tạo đáp án chuẩn? |
| 3 | Nguyễn Đức Anh | Tìm quyết định cũ trong Discord | Thành viên nhóm học tập/dự án dùng Discord | Search theo từ khóa trả nhiều kết quả; phải đọc lại nhiều thread | Thu hẹp số kết quả và luôn dẫn về tin nhắn gốc | Discord Search và kênh `#decisions` đã đủ chưa? |

**Ghi chú về dữ liệu nhóm:** Repo hiện chỉ có Top 3 của Nguyễn Đức Anh. Tên thành viên và candidate của các bạn khác chưa được cung cấp, nên bảng không tạo thêm người hoặc lời pitch giả. Nếu nhóm có thêm candidate, cần chèn vào bảng này trước khi nộp bản nhóm chính thức.

### 2.4. Gom trùng / cluster

| Cluster | Candidates included | Pattern chung | Điểm khác biệt quan trọng |
|---|---|---|---|
| A — Biến yêu cầu học tập thành hành động | Gom deadline; kiểm rubric | Sinh viên phải đọc nguồn rồi chuyển thành checklist/task có thể kiểm tra | Gom deadline xảy ra xuyên nhiều nguồn; kiểm rubric tập trung vào một bài và một bộ tiêu chí |
| B — Truy hồi tri thức nhóm | Tìm quyết định Discord | Thành viên phải tìm lại thông tin cũ trước khi tiếp tục công việc | Phụ thuộc lịch sử chat, quyền truy cập và độ mới của quyết định |

**Kết luận cluster:** Không gộp cả ba thành “trợ lý học tập” vì actor, trigger và success metric sẽ quá rộng. Mỗi candidate vẫn được giữ độc lập khi shortlist.

### 2.5. Shortlist

| Candidate | Actor rõ? | Bottleneck cụ thể? | Impact đo được? | Vẽ before/after được? | Phù hợp lab? | Kết luận shortlist |
|---|---|---|---|---|---|---|
| Gom yêu cầu/deadline | Có: sinh viên học nhiều môn | Có: nhận diện và nối field từ nhiều nguồn | Có thể đo thời gian, recall và tỷ lệ item có nguồn | Có, current flow gồm thu thập–đọc–chép–đối chiếu | Có, nếu giới hạn một sinh viên và một số nguồn | Giữ |
| Kiểm rubric | Có: sinh viên chuẩn bị nộp bài | Có: ánh xạ tiêu chí với bằng chứng | Có thể đo thời gian, false negative và coverage | Có, current flow gồm đọc–dò–sửa–kiểm lại | Rất phù hợp với file tĩnh | Giữ |
| Search Discord | Khá rõ: thành viên nhóm | Có: keyword không khớp và phải đọc nhiều thread | Có thể đo time-to-source và tỷ lệ tìm đúng | Có | Khó hơn vì permission và dữ liệu chat | Giữ để so sánh, nhưng ưu tiên thấp hơn |

### 2.6. Chấm nhanh để làm rõ trade-off

Thang điểm: `1 = rất yếu/chưa rõ`, `5 = rất mạnh/rõ`. Đây là điểm sơ bộ trên artifact hiện có, không được trình bày như kết quả bỏ phiếu của các thành viên chưa cung cấp dữ liệu.

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Gom yêu cầu/deadline | 5 | 5 | 2 | 5 | 4 | 5 | 5 | **31/35** |
| Kiểm rubric | 5 | 5 | 2 | 4 | 5 | 5 | 5 | **31/35** |
| Search Discord | 4 | 4 | 3 | 4 | 3 | 4 | 4 | **26/35** |

### 2.7. Xử lý trường hợp bằng điểm và disagreement

Hai candidate đầu cùng đạt 31 điểm, vì vậy không dùng tổng điểm để quyết định. Trade-off được làm rõ như sau:

| Tiêu chí tie-break | Gom deadline | Kiểm rubric |
|---|---|---|
| Tần suất | Xảy ra đầu tuần và trước hạn của nhiều môn | Xảy ra ở giai đoạn cuối của từng bài |
| Số nguồn/handoff | LMS, Discord, file hướng dẫn, task list/lịch | Rubric và các file bài nộp |
| Bottleneck | Đọc, nối và chép field từ nhiều nguồn | Ánh xạ tiêu chí với bằng chứng |
| Metric chính | Thời gian + recall deadline/deliverable | Thời gian + coverage/false negative |
| Giá trị cho deep-dive workflow | Thể hiện rõ nhiều handoff và source of truth | Pilot đơn giản hơn nhưng workflow hẹp hơn |
| Rủi ro scope | Có thể rộng nếu kết nối toàn bộ hệ thống | Dễ giới hạn bằng file tĩnh |

**Cách xử lý disagreement:** Mỗi bên phải nêu một bằng chứng ủng hộ và một rủi ro phản bác candidate mình thích. Nếu vẫn chưa thống nhất, nhóm chọn candidate có workflow được ít nhất một thành viên mô tả từ trải nghiệm trực tiếp và có thể validation trong Phase 4. Không dùng vote ngay từ đầu.

### 2.8. Candidate được chọn để deep-dive

```text
Gom yêu cầu và deadline bài tập từ LMS, Discord và rubric.
```

**Lý do chọn:**

- Actor và trigger rõ: sinh viên học nhiều môn, kiểm tra đầu tuần và trước hạn nộp.
- Bottleneck nằm ở một bước cụ thể: nhận diện rồi nối deadline, deliverable và cách nộp.
- Có thể đo bằng thời gian tổng hợp, recall và tỷ lệ item có nguồn.
- Workflow có nhiều nguồn và handoff đủ rõ để deep-dive nhưng vẫn có thể thu hẹp thành một pilot.
- Candidate cho phép nhóm kiểm tra nghiêm túc liệu process fix hoặc Rule đã đủ hay chưa.

**Lý do không chọn các candidate còn lại:**

- **Kiểm bài theo rubric:** Đây là candidate tốt và dễ pilot, nhưng workflow hẹp hơn. Nhóm giữ làm phương án dự phòng nếu candidate được chọn không vượt qua validation.
- **Tìm quyết định trong Discord:** Có pain và metric tương đối rõ, nhưng Discord Search đã giải một phần; permission, privacy và phạm vi lịch sử chat làm bài khó kiểm chứng trong thời gian lab.

**Mức đồng thuận hiện tại:** Candidate trên là lựa chọn làm việc được suy ra từ artifact hiện có. Chỉ đổi nhãn thành “nhóm đồng thuận” sau khi các thành viên xác nhận trong buổi thảo luận; báo cáo không bịa phiếu hoặc phát biểu.

### 2.9. Boundary của Phase 3

Ở cuối Phase 3, nhóm mới có **candidate problem**, chưa có Problem Statement hoàn chỉnh và chưa quyết định dùng AI. Những việc còn phải làm trước quyết định cuối:

```text
Validation pain
→ research giải pháp đã có
→ vẽ workflow chi tiết
→ đo baseline/đặt metric
→ viết Problem Statement v0/v1
→ so sánh No AI / Rule / Workflow / Agent
→ Go / Not Yet / No-Go
```

### 2.10. Tự kiểm Phase 3

- [x] Candidates được trình bày theo problem, actor, bottleneck và thay đổi workflow.
- [x] Các ý gần nhau đã được cluster nhưng không gộp thành một bài quá rộng.
- [x] Shortlist dựa trên actor, bottleneck, metric, before/after và phạm vi lab.
- [x] Ma trận điểm được dùng để làm rõ trade-off, không thay thế đồng thuận.
- [x] Có candidate được chọn và lý do loại hai candidate còn lại.
- [x] Có cách xử lý trường hợp bằng điểm/disagreement.
- [x] Chưa viết Problem Statement hoặc chọn solution trong Phase 3.

## 3. Phase 4 — Quick Validation và Research giải pháp

### 3.1. Mục tiêu và nguyên tắc evidence

Phase này kiểm tra candidate trước khi viết Problem Statement. Nhóm tách thông tin thành bốn mức:

| Mức | Ý nghĩa | Cách dùng trong bài |
|---|---|---|
| **Đã quan sát** | Có một tình huống hoặc workflow cá nhân đã trải qua | Dùng làm tín hiệu ban đầu, chưa khái quát cho nhiều sinh viên |
| **Đã đo** | Có log, số mẫu và cách đo có thể kiểm tra lại | Có thể dùng làm baseline nếu phương pháp phù hợp |
| **Được nguồn chính thức xác nhận** | Claim về tính năng/cách hoạt động khớp tài liệu của nhà cung cấp | Dùng trong research solution |
| **Giả định còn mở** | Chưa có dữ liệu hoặc chỉ là ước lượng | Không viết như fact; đưa vào assumption register |

Không có interview, survey hoặc time log thì ghi `0`, không tự tạo người trả lời hoặc số liệu. Mọi target là điều kiện kiểm chứng tương lai, không phải kết quả đã đạt.

### 3.2. Candidate cần kiểm chứng

```text
Sinh viên học nhiều môn phải gom deadline, deliverable và cách nộp từ LMS,
Discord và rubric/file hướng dẫn. Việc nhận diện và nối thông tin rời rạc
có thể tốn thời gian và gây bỏ sót yêu cầu.
```

Candidate này chứa ba giả thuyết khác nhau cần kiểm tra riêng:

1. Thông tin của cùng một bài thực sự phân tán qua nhiều nguồn.
2. Bước đau nhất là diễn giải/nối thông tin, không chỉ là thiếu kỷ luật ghi lịch.
3. Pain đủ thường xuyên và đủ lớn để solution mới tốt hơn checklist hoặc lịch hiện có.

### 3.3. Validation notes hiện có

| Nguồn evidence | Số người / số mẫu | Điều được xác nhận | Tín hiệu phản bác / giới hạn | Trạng thái |
|---|---:|---|---|---|
| Quan sát workflow cá nhân | 1 người | Có bối cảnh phải kiểm LMS, Discord và file hướng dẫn; có bước chép lại thành task | Một người không đại diện cho nhóm người dùng; ký ức thời gian có thể sai | Quan sát định tính |
| Ước lượng hồi tưởng | 1 ước lượng | Thời gian được cảm nhận khoảng 20–30 phút/tuần | Chưa có timestamp hoặc time log; không dùng làm baseline chính thức | Giả định định lượng |
| Interview có cấu trúc | 0 | Chưa có | Chưa biết người khác có cùng workflow hay pain không | Chưa thực hiện |
| Survey / poll | 0 | Chưa có | Chưa biết tần suất và mức độ phổ biến | Chưa thực hiện |
| Time log | 0 tuần | Chưa có | Chưa biết median, độ dao động và bước tốn thời gian nhất | Chưa thực hiện |
| Log lỗi/bỏ sót | 0 mẫu | Chưa có | Chưa chứng minh đã bỏ sót deadline/deliverable với tần suất đáng kể | Chưa thực hiện |

**Kết luận validation hiện tại:** Pain **có tín hiệu tồn tại** trong một workflow cá nhân, nhưng chưa đủ bằng chứng để nói pain phổ biến, baseline là 20–30 phút hoặc AI là cần thiết.

### 3.4. Kế hoạch quick validation khả thi trong 30 phút

#### Quick interview — tối thiểu 3 sinh viên

Chỉ hỏi về lần gần nhất, tránh câu dẫn dắt kiểu “bạn có muốn AI không?”:

1. Lần gần nhất bạn tổng hợp bài cần làm cho một tuần là khi nào?
2. Bạn đã mở những nguồn nào, theo thứ tự nào?
3. Bước nào khiến bạn dừng lâu nhất hoặc phải quay lại?
4. Bạn có bỏ sót hoặc hỏi lại yêu cầu nào không? Điều gì đã xảy ra?
5. Bạn đang dùng lịch, checklist hay cách workaround nào?
6. Nếu chỉ được thay đổi một phần của workflow, bạn muốn thay đổi phần nào?

#### Time log — một tuần

| Field cần ghi | Ví dụ định dạng, không phải dữ liệu thật |
|---|---|
| Thời điểm bắt đầu/kết thúc | `08:05–08:23` |
| Số môn / số bài | `4 môn / 6 bài` |
| Số nguồn đã mở | LMS, Discord, PDF |
| Thời gian theo bước | Thu thập, diễn giải, chép, kiểm lại |
| Số item phải hỏi lại | Số nguyên |
| Số item phát hiện muộn | Số nguyên |

#### Tiêu chí đọc kết quả

- **Xác nhận mạnh:** ít nhất 2/3 người mô tả cùng pattern nhiều nguồn và bước diễn giải/nối thông tin là bottleneck.
- **Phản bác mạnh:** phần lớn thời gian nằm ở việc trì hoãn hoặc thiếu thói quen cập nhật; lịch/checklist giải quyết đủ.
- **Thu hẹp problem:** pain chỉ xuất hiện ở bài nhóm hoặc chỉ ở nguồn Discord.
- **Dừng candidate:** không có lỗi bỏ sót, tổng thời gian nhỏ và người dùng không coi đây là việc đáng thay đổi.

### 3.5. Research giải pháp và pattern đã có

| Nguồn / tool / pattern | Nguồn đã kiểm tra | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Điều nhóm học được |
|---|---|---|---|---|---|
| Google Classroom Calendar | [Classroom Help — View due dates and events](https://support.google.com/edu/classroom/answer/6272985) | Hiển thị classwork có due date trên Classroom/Google Calendar | Nguồn có cấu trúc, ít mơ hồ, không cần AI | Chỉ hiện item đã được gán due date; không tự gom yêu cầu nằm trong Discord hoặc file rời | Rule/lịch chính thức phải là baseline trước mọi solution AI |
| Discord Search | [Discord Support — How to Use Search](https://support.discord.com/hc/en-us/articles/115000468588-How-to-Use-Search-on-Discord) | Tìm message/file và thu hẹp theo người gửi, kênh, ngày, loại nội dung | Có sẵn; cho phép nhảy về message gốc | Search nằm trong server/DM hiện tại; vẫn phụ thuộc từ khóa và việc người dùng đọc đúng ngữ cảnh | Đào tạo dùng filter và giữ link nguồn có thể giải một phần pain không cần AI |
| Notion Enterprise Search | [Notion Help — Enterprise Search](https://www.notion.com/help/enterprise-search) | Search workspace và connected apps; câu trả lời từ nguồn nội bộ có citation | Pattern tốt cho search đa nguồn, chọn scope và truy nguồn | Chỉ có ở Business/Enterprise; cần connector/permission; không phải source of truth cho deadline | Nếu thử AI, phải cho người dùng biết nguồn nào được đọc và luôn cho đường quay về nguồn |
| PAIR — User Needs + Defining Success | [PAIR Guidebook — User Needs](https://pair.withgoogle.com/chapter/user-needs/) | Kiểm tra giao điểm giữa nhu cầu người dùng và điểm mạnh AI | Buộc xác định giá trị người dùng trước model/feature | Không thay thế interview hoặc measurement thật | Metric phải đo kết quả người dùng, không chỉ độ “thông minh” của output |
| PAIR — Explainability + Trust | [PAIR Guidebook — Explainability + Trust](https://pair.withgoogle.com/guidebook-v2/chapter/explainability-trust/) | Hướng dẫn hiệu chỉnh mức tin cậy, nói rõ data source và giới hạn | Phù hợp với rủi ro deadline sai và over-trust | Citation không bảo đảm nội dung đúng; người dùng vẫn cần phán đoán | Mỗi item phải chỉ nguồn, scope dữ liệu và trường hợp cần kiểm tra thủ công |
| PAIR — Errors + Graceful Failure | [PAIR Guidebook — Errors + Graceful Failure](https://pair.withgoogle.com/chapter/errors-failing/) | Thiết kế đường đi tiếp khi AI hoặc context sai | Chuyển failure thành hành vi có thể dự đoán và phục hồi | Cần định nghĩa loại lỗi và mức hậu quả cụ thể | Không có nguồn/xung đột thì abstain và quay về checklist; không tự đoán deadline |

### 3.6. Điều research đã làm thay đổi

| Trước research | Sau research | Lý do thay đổi |
|---|---|---|
| “Tổng hợp deadline từ nhiều nguồn” | “Hỗ trợ trích xuất phần chưa có cấu trúc; giữ lịch chính thức làm source of truth khi có” | Google Classroom đã giải tốt due date có cấu trúc |
| Đo chủ yếu bằng thời gian | Thêm recall deadline/deliverable, precision theo field và 100% item có source | Nhanh nhưng bỏ sót deadline là thất bại không chấp nhận được |
| Có thể kết nối tự động tất cả nguồn | Pilot chỉ dùng nguồn người dùng chủ động chọn/paste | Permission và contextual surprise có thể làm mất niềm tin |
| AI trả một câu trả lời hoàn chỉnh | AI tạo draft có citation, gắn cờ thiếu/xung đột và cho phép sửa | PAIR nhấn mạnh trust calibration, feedback/control và graceful failure |
| Có xu hướng xem nhiều nguồn là lý do cần Agent | Giữ đường đi tuyến tính, chưa cần Agent | Existing search/connectors cho thấy bài chính là scope, source và review, không phải tự lập kế hoạch |

### 3.7. Assumption register

| ID | Giả định còn mở | Mức rủi ro nếu sai | Cách kiểm chứng | Tiêu chí ra quyết định |
|---|---|---|---|---|
| A1 | Ít nhất một nhóm sinh viên phải kiểm 3 nguồn trở lên cho cùng một tuần học | Cao | Interview 3 người + chụp/ghi danh sách nguồn không chứa dữ liệu nhạy cảm | ≥2/3 người có pattern tương tự |
| A2 | Diễn giải/nối field là bước tốn thời gian nhất | Cao | Time log theo từng bước | Median của bước này lớn nhất |
| A3 | Có lỗi bỏ sót hoặc phát hiện muộn đủ đáng quan tâm | Cao | Log hai tuần + hỏi về lần gần nhất | Có incident thật hoặc người dùng đánh giá hậu quả đáng tránh |
| A4 | Checklist/lịch hiện tại chưa giải quyết đủ | Cao | Cho người dùng thử baseline Rule-only trước | Workflow mới phải vượt baseline về thời gian mà không giảm recall |
| A5 | Có thể tạo gold set nhất quán cho deadline, deliverable, cách nộp | Trung bình | Hai người độc lập gắn nhãn 20 mẫu rồi so disagreement | Field bắt buộc có định nghĩa và đạt đồng thuận thủ công |
| A6 | Người dùng sẵn sàng paste/chọn nguồn và review từng item | Trung bình | Test prototype giấy với 3 người | Người dùng hoàn tất review và hiểu trách nhiệm xác nhận |
| A7 | Citation giúp người dùng kiểm tra thay vì over-trust | Trung bình | Quan sát task-based test | Người dùng mở nguồn ở case xung đột/không chắc |
| A8 | Dữ liệu học tập có thể xử lý trong phạm vi permission cho phép | Cao | Data inventory và consent check | Không cần lấy dữ liệu ngoài quyền của người thử |

### 3.8. Evidence đủ chắc và điều chưa được phép khẳng định

**Có thể khẳng định:**

- Current workflow cá nhân có nhiều nguồn và bước chép lại.
- Google Classroom có lịch cho classwork được gán due date.
- Discord có search/filter và cho phép mở message gốc.
- Notion Enterprise Search là một pattern đa nguồn có citation và scope/connector.
- PAIR khuyến nghị xác định nhu cầu người dùng, nói rõ nguồn dữ liệu, hiệu chỉnh trust và thiết kế đường phục hồi khi AI sai.

**Chưa được phép khẳng định:**

- “Sinh viên nói chung mất 20–30 phút mỗi tuần.”
- “Đa số sinh viên thường xuyên bỏ sót deadline.”
- “AI sẽ giảm ít nhất 50% thời gian.”
- “Citation sẽ loại bỏ hallucination.”
- “Workflow có AI chắc chắn tốt hơn checklist hoặc lịch.”

### 3.9. Kết luận Phase 4

Research làm candidate hẹp và an toàn hơn, nhưng validation người dùng vẫn thiếu. Vì vậy nhóm có thể tiếp tục vẽ workflow và viết Problem Statement với nhãn giả định rõ ràng, nhưng chưa đủ evidence để quyết định `Go`.

### 3.10. Tự kiểm Phase 4

- [x] Có validation notes và trạng thái từng loại evidence.
- [x] Không bịa interview, survey, log hoặc số liệu.
- [x] Có kế hoạch validation và tiêu chí xác nhận/phản bác.
- [x] Có ít nhất ba giải pháp/pattern và link nguồn chính thức.
- [x] Research chỉ ra phần tool hiện có đã giải và khoảng trống còn lại.
- [x] Research làm thay đổi problem, metric và boundary.
- [x] Có danh sách giả định còn mở, rủi ro và cách kiểm chứng.
- [x] Phân biệt rõ claim có thể nói và claim chưa được phép nói.

## 4. Phase 5 — Workflow và Problem Statement v0

**Sơ đồ Mermaid riêng:** [02-group-problem-statement-workflow.md](02-group-problem-statement-workflow.md)

### 4.1. Current workflow chi tiết

```text
CURRENT STATE — 6 bước; baseline thời gian chưa đo

[1. Sinh viên kiểm LMS của từng môn]
    output: danh sách item có cấu trúc
        ↓ handoff trong trí nhớ/tab trình duyệt
[2. Sinh viên đọc thông báo Discord liên quan]
    output: thông tin bổ sung/đính chính
        ↓ handoff trong trí nhớ hoặc note tạm
[3. Sinh viên mở rubric/file/link đính kèm]
    output: deliverable, format, cách nộp
        ↓
[4. Sinh viên diễn giải + nối thông tin thành một record]  <-- BOTTLENECK
    output: môn, task, deadline, deliverable, cách nộp, nguồn
        ↓
[5. Sinh viên chép record vào task list/lịch]
    output: danh sách việc cá nhân
        ↓
[6. Sinh viên mở lại nguồn và đối chiếu trước hạn]
    output: item đã xác nhận để thực hiện/nộp
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Handoff | Failure point |
|---:|---|---|---|---|---|---|
| 1 | Sinh viên | Các lớp trên LMS | Item có cấu trúc: tên bài, due date nếu được gán | Đầu tuần; thời gian chưa đo | Sang bước 2 qua tab/note/trí nhớ | Bỏ sót một lớp hoặc item không có due date |
| 2 | Sinh viên | Kênh Discord, announcement/thread | Thông tin bổ sung hoặc thay đổi | Đầu tuần và khi có thông báo; chưa đo | Sang bước 3 qua note tạm/trí nhớ | Tin nhắn trôi, đọc thiếu context hoặc dùng thông báo cũ |
| 3 | Sinh viên | PDF, Markdown, link, rubric | Deliverable, format, cách nộp | Mỗi bài; chưa đo | Sang bước 4 bằng nội dung đang mở | File nhiều phiên bản, yêu cầu nằm rải rác |
| 4 | Sinh viên | Output từ bước 1–3 | Một record thống nhất cho từng bài | Ước lượng 10–15 phút/tuần; cần time log | Sang bước 5 bằng record tự tổng hợp | **Bottleneck:** nối nhầm môn/bài, bỏ field hoặc chọn sai nguồn khi xung đột |
| 5 | Sinh viên | Record đã diễn giải | Task/lịch cá nhân | Ước lượng 5–10 phút/tuần; cần time log | Sang bước 6 qua task app/lịch | Chép sai ngày hoặc thiếu deliverable/source |
| 6 | Sinh viên | Task/lịch và các nguồn gốc | Item đã xác nhận | Trước hạn; chưa đo | Người học dùng item để làm/nộp bài | Không kiểm lại hoặc phát hiện lỗi quá muộn |

**Bottleneck chính:** Bước 4 — diễn giải và nối thông tin của cùng một bài thành record có cấu trúc. Bước này được chọn vì yêu cầu người học giữ ngữ cảnh từ nhiều nguồn, phân biệt nguồn mới/cũ và tránh bỏ field. Thời gian 10–15 phút mới là ước lượng hồi tưởng, chưa phải baseline.

**Handoff yếu nhất:** Bước 3 → 4 → 5. Thông tin chuyển từ nhiều tab/file sang trí nhớ, rồi được chép thủ công vào task list; không có schema hoặc source link bắt buộc.

### 4.2. Future workflow

```text
FUTURE STATE — 6 bước; Rule + AI hỗ trợ + người xác nhận

[1. RULE: lấy item có cấu trúc từ nguồn/lịch chính thức]
    output: record nháp + source
        ↓
[2. NGƯỜI: chọn/paste Discord và rubric được phép sử dụng]
    output: tập nguồn có scope rõ
        ↓
[3. AI: trích xuất/ghép field vào record nháp]
    output: môn, task, deadline, deliverable, cách nộp, source
        ↓
[4. RULE: kiểm field bắt buộc, format ngày và xung đột nguồn]
    output: pass hoặc cờ “thiếu/xung đột/cần kiểm tra”
        ↓
[5. NGƯỜI: mở citation, sửa và xác nhận từng record]  <-- HUMAN BOUNDARY
    output: record đã duyệt
        ↓
[6. RULE: ghi record đã duyệt vào task list/lịch]
    output: task/lịch cá nhân

Fallback:
- Không có nguồn → không tạo fact; ghi “thiếu nguồn” và chuyển cho người kiểm.
- Hai nguồn xung đột → hiển thị cả hai; AI/Rule không tự chọn source of truth.
- AI không chạy hoặc output không dùng được → bỏ draft, dùng schema/checklist thủ công.
- Người dùng không xác nhận → không ghi task/lịch.
- Workflow không bao giờ tự nộp bài hoặc tự gửi thông báo ra ngoài.
```

| Bước | Chủ thể | Input | Output | Boundary / kiểm soát |
|---:|---|---|---|---|
| 1 | Rule | Item từ nguồn có cấu trúc | Record nháp có source | Không suy ra field không tồn tại |
| 2 | Sinh viên | Discord/rubric do mình có quyền truy cập | Tập nguồn được chọn | Người dùng kiểm soát scope và permission |
| 3 | AI | Tập nguồn + schema | Draft field có citation | Chỉ đề xuất; không ghi dữ liệu hoặc quyết định nguồn đúng |
| 4 | Rule | Draft field | Pass hoặc cờ lỗi | Rule kiểm format/required field, không hiểu thay người dùng |
| 5 | Sinh viên | Draft + citation + cờ lỗi | Record đã xác nhận | **Điểm chịu trách nhiệm cuối:** người dùng mở nguồn và sửa |
| 6 | Rule | Record đã xác nhận | Task/lịch | Chỉ chạy sau explicit confirmation |

### 4.3. Before/after impact

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Số bước | 6 | 6 | Đếm node chính; mục tiêu không phải giảm số bước mà giảm effort tại bước 4–5 |
| Tổng thời gian | **Baseline chưa đo**; ước lượng hồi tưởng 20–30 phút/tuần | Median giảm ≥50% so với baseline đo được | Time log theo bước, cùng scope nguồn, tối thiểu hai tuần trước/sau |
| Bước thủ công | 6/6 có thao tác người | 2/6 do người chủ động: chọn nguồn và review | Đếm actor trên workflow |
| Bước thủ công nặng | Đọc/diễn giải/nối/chép | Review record và xử lý ngoại lệ | Time log + quan sát task |
| Bottleneck chính | Bước 4: diễn giải và nối nguồn | Bước 5: review/xử lý xung đột | So thời gian median theo bước |
| Recall deadline/deliverable | Chưa đo | 100% trên gold set pilot | `TP / (TP + FN)` theo field bắt buộc |
| Precision theo field | Chưa đo | ≥95% | `TP / (TP + FP)` trên gold set |
| Traceability | Source link không bắt buộc | 100% record có ít nhất một source | Kiểm schema output |
| Rủi ro | Người dùng chép sót/sai | AI trích sai, ghép nhầm bài, dùng nguồn cũ, automation bias | Error log theo loại; task test xem người dùng có mở citation |

**Lưu ý về metric:** `20–30 phút` không phải baseline chính thức. Nếu time log cho thấy baseline thấp hoặc checklist/Rule-only đã đạt target, nhóm phải hạ scope hoặc dừng phần AI.

### 4.4. Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên đại học học từ 4 môn trở lên và tự quản lý yêu cầu bài tập nhận qua LMS, Discord và rubric/file hướng dẫn. Hiện actor này mới dựa trên một quan sát cá nhân, cần interview để xác nhận độ phổ biến. |
| **Workflow** | Đầu tuần và trước hạn nộp, sinh viên mở từng lớp trên LMS → đọc thông báo Discord → mở rubric/file → diễn giải và nối deadline, deliverable, format, cách nộp → chép vào task list/lịch → mở nguồn đối chiếu lại. |
| **Bottleneck** | **Bước 4:** biến thông tin từ nhiều nguồn thành một record thống nhất cho từng bài. Bước này dễ bỏ field, nối nhầm bài hoặc chọn nhầm thông báo cũ; thời gian 10–15 phút/tuần mới là ước lượng cần đo. |
| **Impact** | Workflow tạo công lặp lại và nguy cơ chép sai/bỏ sót yêu cầu hoặc phát hiện lỗi gần deadline. Mức độ và tần suất hậu quả chưa được validation ngoài quan sát cá nhân, nên chưa được khẳng định là pain phổ biến. |
| **Success Metric** | **Hiện trạng:** baseline thời gian, recall và precision chưa đo; 20–30 phút/tuần chỉ là ước lượng. **Mục tiêu pilot:** median thời gian giảm ≥50% so với baseline đo được, recall deadline/deliverable đạt 100%, precision theo field ≥95% và 100% record có source. **Cách đo:** time log cùng scope trước/sau và so output với gold set được gắn nhãn thủ công. |
| **Boundary** | Chỉ xử lý nguồn người dùng chủ động cấp hoặc có quyền truy cập. AI chỉ tạo draft có citation; Rule chỉ kiểm schema/format và ghi record đã duyệt. Sinh viên phải mở nguồn, giải quyết xung đột và xác nhận trước khi ghi lịch. Thiếu nguồn/xung đột/AI lỗi thì abstain và quay về checklist. Không tự chọn source of truth, tự gửi thông báo hoặc tự nộp bài. |

### 4.5. Tự phản biện Problem Statement v0

| Câu hỏi phản biện | Điểm còn yếu trong v0 | Nhóm cần làm gì tiếp |
|---|---|---|
| Actor có quá rộng không? | “Sinh viên học từ 4 môn” chưa được xác nhận là segment có pain cao nhất | Interview ít nhất 3 người; so người dùng một nguồn và nhiều nguồn |
| Workflow có thật ngoài một cá nhân không? | Mới có mô tả từ một workflow cá nhân | Yêu cầu người được hỏi kể lần gần nhất và vẽ lại flow của họ |
| Bottleneck có đúng là bước 4 không? | Chưa có time log theo bước | Đo thời gian thu thập, diễn giải, chép và kiểm lại riêng |
| Impact có đang phóng đại không? | Chưa có log incident bỏ sót | Ghi số item hỏi lại/phát hiện muộn trong hai tuần |
| Metric có đo được không? | Có công thức nhưng chưa có baseline/gold set | Tạo 20 mẫu đã ẩn dữ liệu và thống nhất schema/gold label |
| Boundary có đủ khi AI sai không? | Đã có abstain và human confirmation, nhưng source of truth giữa các kênh chưa được quy định | Pilot không tự quyết nguồn; hiển thị xung đột để người dùng xử lý |

### 4.6. Tự kiểm Phase 5

- [x] Current workflow có actor, input, output, thời gian/tần suất và handoff cho từng bước.
- [x] Bottleneck là một bước cụ thể và số liệu chưa đo được gắn nhãn ước lượng.
- [x] Future workflow phân biệt rõ Rule, AI và người thực hiện.
- [x] Có human boundary, abstain và fallback khi AI sai/không chạy.
- [x] Bảng before/after có số bước, thời gian, bước thủ công, bottleneck và risk mới.
- [x] Problem Statement v0 đủ Actor, Workflow, Bottleneck, Impact, Success Metric và Boundary.
- [x] Success Metric có hiện trạng, mục tiêu và cách đo.
- [x] Có danh sách câu hỏi phản biện; các lỗ hổng chưa được che bằng số liệu giả.

## 5. Phase 6 — Rule / Workflow / Agent và Decision

### 5.1. Đặt bài toán vào ma trận độ mơ hồ × độ phức tạp

| Trục | Đánh giá | Evidence / lập luận |
|---|---|---|
| Độ mơ hồ của input | Trung bình–cao | Yêu cầu có thể nằm trong câu tự nhiên, bảng, file hoặc thread; cùng một field có nhiều cách diễn đạt |
| Độ mơ hồ của output | Trung bình | Schema đầu ra cố định, nhưng việc ánh xạ câu chữ vào deadline/deliverable có thể có nhiều cách hiểu |
| Độ phức tạp workflow | Trung bình | Có sáu bước và ba nhóm nguồn, nhưng thứ tự xử lý gần như tuyến tính và biết trước |
| Nhu cầu tự quyết định bước tiếp theo | Thấp | Khi thiếu/xung đột, hệ thống chỉ cần gắn cờ và chuyển người dùng; không cần tự lập kế hoạch |
| Hậu quả khi sai | Trung bình–cao | Sai deadline hoặc ghép nhầm bài có thể khiến người dùng nộp muộn/sai; vì vậy phải có citation và confirmation |

**Ô của ma trận:**

```text
Độ mơ hồ trung bình–cao × độ phức tạp trung bình
→ Workflow có AI hỗ trợ một bước, không cần Agent.
```

Rule phù hợp với field đã có cấu trúc và validation cố định. AI chỉ đáng thử tại bước diễn giải nội dung phi cấu trúc. Vì workflow không yêu cầu hệ thống tự chọn mục tiêu hoặc tự đổi kế hoạch nên chưa có lý do nâng lên Agent.

### 5.2. Đi qua cây quyết định

```text
[Candidate problem]
      |
      v
Volume đủ lớn / lặp thường xuyên?
      |
      └── CHƯA BIẾT CHẮC
          → Không Go; cần interview + time log.
          → Vẫn có thể tiếp tục chọn cấp độ giả thuyết để thiết kế validation.

Input ổn định và toàn bộ logic viết được bằng if/else?
      |
      ├── CÓ với due date có cấu trúc
      |   → Dùng Rule.
      |
      └── KHÔNG với Discord/rubric phi cấu trúc
          → Xét AI cho riêng bước trích xuất.

Có nhiều nhánh, nhiều tool và state thay đổi đến mức hệ thống
phải tự lập kế hoạch hoặc tự quyết định hành động tiếp theo?
      |
      └── KHÔNG
          → Workflow có AI + Human Review.
          → DỪNG, không nâng lên Agent.
```

Mỗi nhánh `KHÔNG` đã tránh một mức phức tạp:

- Chưa chứng minh volume → tránh quyết định Go quá sớm.
- Không phải mọi input đều phi cấu trúc → tránh dùng AI cho dữ liệu Rule đã xử lý được.
- Không cần tự lập kế hoạch → tránh Agent và permission rộng.

### 5.3. So sánh ba mức trên cùng một bottleneck

**Bottleneck chung để so sánh:** Bước 4 của current workflow — diễn giải và nối deadline, deliverable, format, cách nộp từ nhiều nguồn thành một record.

| Tiêu chí | Rule / Script | Workflow có AI | Agent |
|---|---|---|---|
| Cách hoạt động | Parser/template cố định, mapping field, kiểm format ngày và required fields | Rule lấy/kiểm dữ liệu → AI draft field từ văn bản → người review → Rule ghi record | Tự đăng nhập/đọc nguồn, tự chọn bước, tự hỏi thêm, tự cập nhật lịch |
| Phần bottleneck giải được | Tốt với due date/field đã có cấu trúc | Xử lý được cả phần văn bản đa dạng nhưng vẫn giữ schema và review | Có thể bao phủ toàn workflow |
| Phần không giải được | Khó hiểu cách diễn đạt mới, ngữ cảnh và coreference | Không tự giải quyết source conflict; phụ thuộc chất lượng input/review | Vẫn có thể hiểu sai nhưng hành động với quyền lớn hơn |
| Data/permission | Thấp; nguồn cố định | Trung bình; người dùng chọn/paste nguồn trong scope | Cao; cần quyền nhiều hệ thống và quản lý credential |
| Khả năng audit | Cao, deterministic | Khá cao nếu lưu input, output, citation và correction | Thấp hơn do nhiều nhánh và hành động tự chủ |
| Human boundary | Người dùng xử lý case ngoài rule | Người dùng duyệt từng record trước khi ghi | Cần approval tại nhiều hành động quan trọng |
| Graceful failure | Báo field thiếu/format sai | Abstain, hiển thị xung đột, quay về checklist | Khó thiết kế đầy đủ vì state/tool có thể thay đổi |
| Chi phí/độ phức tạp | Thấp nhất | Trung bình | Cao nhất |
| Khi nào đủ | Nguồn chủ yếu có cấu trúc hoặc checklist giải được ≥ mục tiêu | Văn bản phi cấu trúc tạo pain thật và AI vượt baseline Rule-only | Chỉ khi cần tự lập kế hoạch nhiều bước và lợi ích vượt rủi ro quyền hạn |
| Mức đề xuất | Baseline và thành phần bắt buộc | **Chọn để kiểm chứng sau khi đủ evidence** | Không chọn |

### 5.4. Mức can thiệp được chọn

```text
Workflow có AI hỗ trợ một bước + Human Review.
```

**Vì sao chọn Workflow:**

- Workflow có đường đi cố định; input/output của từng bước đã biết.
- Rule giải phần có cấu trúc, AI chỉ xử lý phần ngôn ngữ khó viết hết bằng điều kiện.
- Sinh viên duyệt trước hành động có hậu quả; hệ thống có thể audit bằng citation và correction log.
- Có thể pilot bằng file tĩnh/paste thủ công, không cần tích hợp hoặc quyền rộng.

**Vì sao không chọn mức đơn giản hơn làm toàn bộ solution:**

- Process fix và Rule phải là baseline, không bị loại bỏ.
- Rule-only không xử lý ổn định các cách diễn đạt deliverable/cách nộp trong thread và rubric.
- Tuy nhiên, nếu validation cho thấy checklist + lịch đạt target, nhóm phải hạ xuống Rule; Workflow chưa được mặc định là tốt hơn.

**Vì sao không chọn Agent:**

- Không có nhu cầu tự lập kế hoạch hoặc tự đổi mục tiêu.
- Khi nguồn xung đột, hành vi đúng là dừng và hỏi người dùng, không phải tự ra quyết định.
- Agent đòi permission lớn hơn trong khi pain, baseline và value chưa được chứng minh.
- Tự ghi lịch hoặc gửi thông báo làm hậu quả của lỗi lớn hơn mà không tăng giá trị cần thiết cho bottleneck.

### 5.5. Ranh giới người–máy theo PAIR

| Tình huống | Máy được làm | Người phải làm | Phản hồi / graceful failure |
|---|---|---|---|
| Nguồn có cấu trúc | Rule đọc field và giữ source | Kiểm scope nguồn | Field thiếu thì đánh dấu, không suy đoán |
| Nguồn phi cấu trúc | AI đề xuất field và citation | Mở nguồn, sửa và xác nhận | Hiển thị “chưa xác định” thay vì tạo fact |
| Hai nguồn xung đột | Phát hiện và hiển thị cả hai | Chọn source of truth theo bối cảnh | Không tự ghi record |
| Output sai | Lưu correction nếu người dùng cho phép | Sửa hoặc bỏ draft | Cho phép quay về checklist thủ công |
| Record đã đúng | Rule chuẩn bị thao tác ghi | Xác nhận explicit | Chỉ ghi sau confirmation |
| Gửi/nộp bài | Không được thực hiện | Người dùng tự gửi/nộp | Ngoài boundary của solution |

Thiết kế này áp dụng ba nguyên tắc từ PAIR: nói rõ nguồn dữ liệu, hiệu chỉnh trust thay vì yêu cầu người dùng tin hoàn toàn, và luôn cung cấp đường phục hồi khi output sai.

### 5.6. Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên đại học học từ 4 môn trở lên và tự quản lý yêu cầu bài tập qua LMS, Discord và rubric/file. Segment và độ phổ biến của pain vẫn cần validation với ít nhất ba người. |
| **Workflow** | Sinh viên kiểm LMS → đọc Discord → mở rubric/file → diễn giải và nối field → chép task/lịch → kiểm lại trước hạn. Future workflow giữ đường đi tuyến tính: Rule lấy dữ liệu có cấu trúc → người dùng chọn nguồn → AI draft field có citation → Rule kiểm schema/xung đột → người dùng duyệt → Rule ghi record. |
| **Bottleneck** | Bước diễn giải và nối deadline, deliverable, format, cách nộp từ nhiều nguồn thành một record. Ước lượng 10–15 phút/tuần cho bước này chưa phải baseline đã đo. |
| **Impact** | Công lặp lại và nguy cơ chép sai, bỏ field hoặc phát hiện lỗi gần deadline. Hiện impact mới có tín hiệu từ một quan sát cá nhân; chưa được khái quát cho nhiều sinh viên. |
| **Success Metric** | **Baseline:** thời gian, recall và precision chưa đo; 20–30 phút/tuần chỉ là ước lượng. **Target:** median thời gian giảm ≥50% so với baseline đo được, recall deadline/deliverable 100%, precision theo field ≥95%, 100% record có source. **Đo:** time log cùng scope trước/sau và gold set tối thiểu 20 mẫu đã ẩn dữ liệu. |
| **Boundary** | Chỉ dùng nguồn người dùng chủ động cấp/có quyền truy cập. AI chỉ tạo draft có citation; không tự chọn source of truth, không tự ghi khi chưa duyệt, không tự gửi/nộp. Thiếu nguồn, xung đột hoặc lỗi thì abstain và quay về checklist. |
| **AI intervention point** | Sau khi nguồn có scope rõ được thu thập, trước bước người dùng tạo record/task. AI chỉ trích xuất phần phi cấu trúc; Rule xử lý dữ liệu có cấu trúc và validation. |
| **Mức chọn** | Workflow có AI hỗ trợ một bước + Human Review. Rule là baseline/thành phần của workflow; Agent không được chọn. |
| **Rủi ro & người thật kiểm tra** | Rủi ro: sai ngày, ghép nhầm môn/bài, bỏ field, dùng thông báo cũ, automation bias và lộ dữ liệu ngoài scope. Sinh viên review từng record và chịu trách nhiệm xác nhận; owner pilot quản lý gold set, error log và permission. |

### 5.7. Khác biệt giữa Problem Statement v0 và v1

| Thành phần | v0 | v1 |
|---|---|---|
| Workflow tương lai | Mới mô tả boundary tổng quát | Nêu rõ Rule → AI → Rule → Human Review → Rule |
| AI intervention | Chưa là field riêng | Chỉ tại bước trích xuất nội dung phi cấu trúc |
| Mức solution | Chưa chốt | Workflow; Rule là baseline, Agent bị loại |
| Rủi ro | Nêu xung đột và AI lỗi | Bổ sung sai ngày, ghép nhầm bài, nguồn cũ, automation bias, permission |
| Reviewer | Sinh viên xác nhận | Sinh viên review từng record; owner pilot quản lý evaluation |
| Evidence status | Có nhãn chưa validate | Giữ nguyên nhãn và gắn điều kiện trước Go |

### 5.8. Khung quyết định Go / Not Yet / No-Go

| Câu hỏi | Kết quả | Evidence / khoảng trống |
|---|---|---|
| Actor và current workflow đã đủ rõ để kiểm chứng? | **Yes** | Có actor, trigger, sáu bước và bottleneck cụ thể |
| Pain đã được xác nhận với nhiều người? | **Not Yet** | Mới có một quan sát cá nhân; interview = 0 |
| Baseline thời gian và lỗi đã đo? | **Not Yet** | Time log = 0 tuần; log bỏ sót = 0 mẫu |
| Có metric và cách đo? | **Yes** | Đã có time log design, recall, precision, traceability và gold-set plan |
| Có dữ liệu pilot hợp lệ? | **Not Yet** | Chưa có 20 mẫu ẩn dữ liệu và gold labels |
| Rule-only có được kiểm tra trước không? | **Not Yet** | Đã định nghĩa baseline nhưng chưa chạy comparison |
| AI sai có đường phục hồi? | **Yes, trên thiết kế** | Citation, abstain, human confirmation và fallback thủ công |
| Có owner/reviewer thật? | **Một phần** | Sinh viên là reviewer; nhóm chưa chốt owner pilot/evaluation |
| Agent có cần thiết? | **No** | Không cần tự lập kế hoạch hoặc quyền nhiều công cụ |

### 5.9. Quyết định cuối

```text
NOT YET
```

**Lý do dựa trên evidence:**

- Problem, workflow, bottleneck, target metric và boundary đã đủ rõ để thiết kế validation.
- Pain mới có tín hiệu từ một người; chưa biết có lặp ở nhóm người dùng mục tiêu.
- Baseline 20–30 phút và bottleneck 10–15 phút vẫn là ước lượng, chưa phải measurement.
- Chưa có gold set để kiểm recall/precision và chưa chứng minh Workflow vượt checklist + Rule-only.
- Go ngay sẽ tối ưu solution trước khi xác nhận pain và comparative value.

**Vì sao chưa phải No-Go:**

- Bottleneck có phần ngôn ngữ phi cấu trúc phù hợp để kiểm tra AI.
- Workflow có thể pilot ở scope nhỏ, không cần integration hoặc quyền rộng.
- Rủi ro có thể giới hạn bằng citation, abstain và review trước khi ghi.

### 5.10. Điều cần validate để chuyển từ Not Yet

| Gate | Việc cần làm | Điều kiện pass |
|---|---|---|
| G1 — User need | Interview tối thiểu 3 sinh viên về lần gần nhất | ≥2/3 người có pattern nhiều nguồn và coi bước diễn giải/nối là pain đáng xử lý |
| G2 — Baseline | Time log một–hai tuần theo từng bước | Có baseline đủ mẫu; bottleneck bước 4 được xác nhận hoặc PS được sửa |
| G3 — Incident | Ghi item hỏi lại, chép sai hoặc phát hiện muộn | Có hậu quả thật; nếu không có, hạ mức ưu tiên |
| G4 — Data | Tạo tối thiểu 20 mẫu đã ẩn dữ liệu và hai người gắn label | Schema/gold labels đủ nhất quán để evaluation |
| G5 — Non-AI baseline | Chạy checklist + Rule-only trên cùng task | Ghi được thời gian, recall, precision và usability |
| G6 — AI value | Chạy Workflow có AI trên cùng task | Recall 100%, precision ≥95%, 100% citation và median time giảm ≥50% so baseline |
| G7 — Human control | Task test conflict/missing-source | Người dùng nhận ra lỗi, mở source và không over-trust |
| G8 — Permission | Kiểm inventory và consent | Không cần nguồn ngoài quyền; có thể xóa dữ liệu pilot |

### 5.11. Pilot nhỏ nhất nếu các gate đạt

```text
Scope:
- 1 sinh viên
- 1 môn
- dữ liệu của 2 tuần
- input do người dùng paste/chọn thủ công
- output là bảng draft/CSV có citation
- chưa kết nối lịch thật
- không gửi thông báo, không nộp bài

So sánh:
A. Checklist thủ công
B. Rule-only
C. Workflow Rule + AI + Human Review

Thu thập:
thời gian theo bước, recall, precision, số lần mở citation,
số correction, loại lỗi và mức tin tưởng của người dùng.
```

**Rollback:** Nếu AI vi phạm deadline recall, thường xuyên ghép nhầm bài, người dùng phải viết lại phần lớn record hoặc không vượt Rule-only, dừng AI và dùng checklist + lịch/source chính thức.

### 5.12. Trách nhiệm quyết định

Phân tích trên đề xuất `Workflow` và quyết định `Not Yet` từ evidence hiện có. Quyết định chính thức vẫn phải do các thành viên nhóm xác nhận; báo cáo không coi lựa chọn do AI gợi ý là sự đồng thuận của nhóm.

### 5.13. Tự kiểm Phase 6

- [x] Bài toán được đặt vào ma trận độ mơ hồ × độ phức tạp.
- [x] Đã đi qua cây quyết định và ghi rõ các nhánh dừng tăng độ phức tạp.
- [x] Rule, Workflow và Agent được so sánh trên cùng bottleneck.
- [x] Chọn Workflow và giải thích vì sao Rule-only chưa chắc đủ.
- [x] Giải thích vì sao không chọn Agent.
- [x] Problem Statement v1 có AI intervention point, mức chọn, rủi ro và reviewer.
- [x] Quyết định `Not Yet` dựa trên evidence và assumption register.
- [x] Có validation gates, pilot nhỏ nhất và rollback.
- [x] Ranh giới người–máy phù hợp nguyên tắc PAIR.
