# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: NhomHTHT
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Tự động tổng hợp kiến thức và tạo tài liệu ôn tập sau buổi học
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Võ Huy Hoàng | Tự động kiểm tra bài Lab với Requirement và Rubric | Student | | 1. AI chấm sai thì ai chịu trách nhiệm? Với những requirement và rubric chung chung thì liệu AI có hiểu nhầm không? (Hoàng Anh) |
| 2 | Võ Huy Hoàng | Tự động tổng hợp kiến thức và tạo tài liệu ôn tập sau buổi học | Student | | |
| 3 | Võ Huy Hoàng | Tự động điền file AI-Logs.md | Student, LabCoach | | 1. Log tự điền thì có đáng tin không? Lấy lịch sử dùng AI từ đâu (mỗi công cụ một kiểu)? (Hoàng Anh) |
| 4 | Nguyễn Hoàng Anh | Đọc hiểu yêu cầu đề bài lab | Học viên (cá nhân và trưởng nhóm) | | 1. Nếu sử dụng AI để giải thích đề bài, làm sao đảm bảo AI không diễn giải sai yêu cầu gốc? (Huy Hoàng) 2. Đề bài lab thường có nhiều ràng buộc ngầm và tiêu chí chấm điểm rất chi tiết (như SUBMISSION, RUBRIC). Nếu để AI tóm tắt, làm sao bạn chắc chắn AI không tóm tắt thiếu các quy định nhỏ khiến cả nhóm bị trừ điểm oan? (Ngọc Tuyên) 3. Việc đọc lâu là do đề bài khó hay do mình thiếu checklist đọc nhanh? Nếu chỉ cần 1 bảng câu hỏi cố định (Nộp file gì? Deadline lúc nào? Tiêu chí nào nhiều điểm nhất?) thì có cần đến AI không? (Ngọc Tuyên)|
| 5 | Nguyễn Hoàng Anh | Phân chia công việc cho thành viên nhóm | Trưởng nhóm | | 1. AI sẽ xử lý thế nào nếu phần việc không phù hợp với thành viên được giao/thành viên không đủ khả năng handle task đấy? (Huy Hoàng) 2. Làm sao đảm bảo công việc được phân chia đồng đều và không có thành viên bị quá tải? (Huy Hoàng) 3. Nút thắt làm mất 45 phút thực chất là lúc 'nghĩ ra đầu việc', hay là lúc 'thương lượng ai nhận phần khó'? AI có giải quyết được tâm lý đùn đẩy phần khó của thành viên không? (Ngọc Tuyên) 4. AI không biết được tuần này ai bận thi, ai giỏi phần nào và thời gian rảnh của từng người. Liệu AI phân chia có thực tế hơn việc 4 người bật mic nói chuyện 5 phút không? (Ngọc Tuyên) |
| 6 | Nguyễn Hoàng Anh | Kiểm tra tiến độ commit của thành viên theo branch | Trưởng nhóm | | 1. Nỗi đau ở đây là do 'GitHub khó theo dõi', hay do 'thành viên không chịu commit đúng hạn'? Nếu thành viên không chịu làm bài thì dù có tool báo cáo tự động, bạn vẫn phải đi nhắn tin giục từng người bằng tay? (Ngọc Tuyên) 2. GitHub đã có sẵn tab Network Graph, và chỉ cần 1 Webhook/GitHub Action bắn thông báo về Discord/Telegram mỗi khi có commit mới là xong. Việc này chỉ cần Rule cơ bản, tại sao lại cần đến AI ở đây? (Ngọc Tuyên) |
| 7 | Nguyễn Trung Anh | Đặt xe và canh app chờ tài xế nhận | Quản lý kế hoạch sản xuất ở xưởng gia công nhỏ, người duy nhất lo cả sản xuất lẫn giao hàng | | 1. Vấn đề nằm ở việc thiếu tài xế, thời gian chờ hay việc phải liên tục theo dõi ứng dụng? (Huy Hoàng) |
| 8 | Nguyễn Trung Anh | Theo dõi hàng trên đường, lo giao trễ | Quản lý kế hoạch sản xuất; khách nhận hàng | | 1. Nếu AI cảnh báo sai rằng đơn hàng sẽ giao trễ, điều đó có gây ảnh hưởng đến kế hoạch sản xuất hoặc khách hàng không? (Huy Hoàng) |
| 9 | Nguyễn Trung Anh | Đặt xe máy cho rẻ nhưng không ai nhận, phải trả thêm hoặc đổi xe | Quản lý kế hoạch sản xuất; xưởng nằm ở khu ít đơn nên tài xế xe máy tụ ở chỗ khác | | |
| 10 | Dương Ngọc Tuyên | Đối chiếu quy cách bài lab trước khi nộp | Sinh viên đang làm bài lab môn học | | |
| 11 | Dương Ngọc Tuyên | Báo cáo tiến độ tuần cho nhóm đồ án | Thành viên phụ trách tổng hợp báo cáo tuần của nhóm đồ án | | 1. Làm sao đảm bảo AI không bỏ sót công việc hoặc báo cáo sai tiến độ của thành viên? (Huy Hoàng) |
| 12 | Dương Ngọc Tuyên | Dò tìm bài tập mẫu trong video bài giảng | Sinh viên tự học, tự ôn tập bài tập lớn | | 1. Nếu video không có transcript hoặc nội dung được trình bày bằng hình ảnh/code, giải pháp có tìm kiếm chính xác được không? (Huy Hoàng) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Báo cáo / tổng hợp |  Tổng hợp kiến thức và tạo tài liệu ôn tập, Điền file AI-Logs.md, Đọc hiểu yêu cầu đề bài lab, Báo cáo tiến độ tuần | Gom và tổng hợp thông tin viết báo cáo |
| B — Tìm kiếm | Đặt xe và canh app chờ tài xế nhận, Theo dõi hàng trên đường, Đặt xe máy cho rẻ nhưng không ai nhận | Tìm đúng thông tin |
| C — Review | Kiểm tra bài Lab với Requirement và Rubric, Đối chiếu quy cách bài lab | Đọc source, so sánh và chỉ ra sai sót |
| D — Theo dõi việc | Phân chia công việc, Kiểm tra tiến độ commit, Dò tìm bài tập mẫu | Tổng hợp thông tin từ Git |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
Outcome: Giảm thời gian mỗi thành viên mất cho việc gom, tìm, kiểm và theo dõi thông tin lặp lại mỗi tuần, để dành thời gian cho phần việc chính

 ├── Opportunity A (cluster A): Mất nhiều thời gian gom thông tin từ nhiều nguồn
 │                              rồi viết lại thành báo cáo cho người khác đọc
 │
 ├── Opportunity B (cluster B): Khó tìm đúng thông tin (quyết định cũ, tài liệu, câu trả lời)
 │                              vì nó nằm rải rác ở nhiều nơi
 │
 ├── Opportunity C (cluster C): Bản nháp có thiếu sót mà người viết không tự thấy,
 │                              người review phải đọc kỹ mới chỉ ra được
 │
 └── Opportunity D (cluster D): Sau cuộc họp, nhiều việc cần làm bị quên hoặc rơi mất
                                vì không ai theo dõi đến cùng
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:
```text
.Bot tóm tắt họp / tự động viết báo cáo tuần (cluster A): Pain thật là “mất thời gian gom và viết lại”.

.Chatbot hỏi đáp FAQ lab / tìm kiếm thông minh trên Slack, LMS (cluster B): Pain thật là “thông tin rải rác, khó tìm”.

.AI review PRD / tự chấm Problem Statement (cluster C): Pain thật là “thiếu sót không tự phát hiện được”.

.Nhắc deadline tự động / dashboard theo dõi action item (cluster D): Pain thật là “việc bị rơi sau họp”.
```

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Tự động kiểm tra bài Lab với Requirement và Rubric | 5 | 3 | 3 | 5 | 4 | 4 | 3 | **27** |
| Tự động tổng hợp kiến thức và tạo tài liệu ôn tập sau buổi học | 5 | 4 | 5 | 4 | 4 | 5 | 5 | **32** |
| Đọc hiểu yêu cầu đề bài lab | 5 | 4 | 4 | 4 | 4 | 3 | 5 | **29** |
| Đặt xe máy cho rẻ nhưng không ai nhận, phải trả thêm hoặc đổi xe | 5 | 4 | 5 | 3 | 2 | 2 | 3 | **24** |
| Đặt xe và canh app chờ tài xế nhận | 5 | 4 | 5 | 3 | 2 | 2 | 3 | **24** |

**Candidate được chọn:** Tự động kiểm tra bài Lab với Requirement và Rubric

**Vì sao chọn:** Phù hợp với domain của nhóm và cũng là Pain của tất cả các thành viên

**Vì sao loại các candidate còn lại:** Đề tài số 4 + 5 không phù hợp domain, đề tài số 1 AI có thể sai sót dẫn đến thiếu thông tin và đề tài 3 có thể không cần dùng đến AI

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Learner |
| **Quy trình** | 1. Tham gia buổi học và tiếp nhận kiến thức từ giảng viên. 2. Ghi chú hoặc lưu lại các tài liệu được cung cấp. 3. Sau buổi học, tìm kiếm thêm tài liệu để hiểu rõ những nội dung chưa nắm vững. 4. Đọc lại tài liệu và tổng hợp các kiến thức quan trọng. 5. Tự tạo câu hỏi hoặc bài tập để kiểm tra mức độ hiểu bài. 6. Ôn tập lại kiến thức vào cuối tuần. |
| **Bottleneck** | Bước 3–5: Phải tự tìm kiếm, đọc và tổng hợp thông tin từ nhiều nguồn, sau đó tự xây dựng nội dung ôn tập. |
| **Impact** | Tốn nhiều thời gian cho việc tìm kiếm và tổng hợp thay vì tập trung vào thực hành. Kiến thức có thể bị quên nếu không được ôn tập thường xuyên. Người học cũng có thể bỏ sót những nội dung quan trọng hoặc không biết mình đang yếu ở phần kiến thức nào. |
| **Success Metric** | Thời gian tổng hợp và chuẩn bị tài liệu ôn tập: 4 giờ → dưới 30 phút. Tự động tạo bản tóm tắt kiến thức và bộ câu hỏi sau mỗi buổi học. Nội dung được tạo phải bám sát tài liệu gốc, hướng tới độ chính xác trên 90% qua kiểm tra thủ công. |
| **Boundary** | **AI không được:** 1. Tự ý bổ sung kiến thức không có trong tài liệu nguồn mà không đánh dấu rõ ràng. 2. Tạo thông tin, công thức, ví dụ hoặc đáp án không có căn cứ. **Con người cần kiểm tra (HITL):** 1. Đối chiếu bản tóm tắt với tài liệu gốc để phát hiện thông tin sai lệch hoặc bị bỏ sót. 2. Kiểm tra tính chính xác và mức độ phù hợp của câu hỏi, bài tập và đáp án được tạo ra. |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- Nhóm đồng ý

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
