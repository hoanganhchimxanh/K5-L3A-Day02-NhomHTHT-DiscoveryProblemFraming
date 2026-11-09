# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: NhomHTHT
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Tự động tổng hợp kiến thức trọng tâm và tạo bộ câu hỏi ôn tập từ tài liệu sau buổi học (slide, ghi chú, transcript)
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
| A — Báo cáo / tổng hợp | Báo cáo tuần, recap họp, báo cáo tiến độ lab | Gom thông tin nhiều nguồn rồi viết lại cho người khác đọc |
| B — Tìm kiếm | Tìm quyết định cũ trong Slack, tìm tài liệu trên LMS, FAQ lab | Tìm đúng thông tin trong nhiều nguồn rời rạc |
| C — Review | Review PRD, kiểm Problem Statement, review bài tập | Đọc bản nháp và chỉ ra thiếu sót |
| D — Theo dõi việc | Theo dõi action item, nhắc deadline | Sau cuộc họp nhiều việc bị rơi |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian chuẩn bị tài liệu ôn tập từ 4 giờ xuống dưới 45 phút và tăng tỷ lệ sinh viên tự ôn tập kiến thức ngay trong tuần
├── Opportunity A: Tài liệu sau buổi học nằm rải rác ở nhiều định dạng (slide PDF 40–50 trang, video ghi âm 2 tiếng, note cá nhân), tốn nhiều thời gian đọc lại từ đầu
├── Opportunity B: Việc tự lọc ý chính và tự soạn câu hỏi ôn tập thủ công rất tốn sức (3–4 tiếng/tuần), khiến người học ngại và trì hoãn đến sát kỳ thi mới ôn dồn
└── Opportunity C: Người học không tự đánh giá được mình đã hiểu đúng trọng tâm bài giảng hay chưa, dễ bỏ sót kiến thức cốt lõi hoặc hiểu sai định lý
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ~~*Xây dựng ứng dụng gia sư ảo AI trò chuyện 24/7*~~ (Solution $\rightarrow$ gạch bỏ)
- ~~*Hệ thống tự động tóm tắt bài giảng bằng podcast audio*~~ (Solution $\rightarrow$ gạch bỏ)
- ~~*Plugin tự động giải bài tập và làm quiz hộ sinh viên*~~ (Solution vi phạm liêm chính $\rightarrow$ gạch bỏ)

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Tự động kiểm tra bài Lab với Requirement và Rubric | 5 | 3 | 3 | 5 | 4 | 4 | 3 | **27** |
| **Tự động tổng hợp kiến thức và tạo tài liệu ôn tập sau buổi học** | 5 | 4 | 5 | 4 | 4 | 5 | 5 | **32** |
| Đọc hiểu yêu cầu đề bài lab | 5 | 4 | 4 | 4 | 4 | 3 | 5 | **29** |
| Đặt xe máy cho rẻ nhưng không ai nhận, phải trả thêm hoặc đổi xe | 5 | 4 | 5 | 3 | 2 | 2 | 3 | **24** |
| Đặt xe và canh app chờ tài xế nhận | 5 | 4 | 5 | 3 | 2 | 2 | 3 | **24** |

**Candidate được chọn:**
**Tự động tổng hợp kiến thức và tạo tài liệu ôn tập sau buổi học** (Candidate #2 của Võ Huy Hoàng).

**Vì sao chọn:**
1. **Đạt điểm cao nhất (32 điểm)** trên bảng đánh giá 7 tiêu chí khách quan của cả nhóm.
2. **Nhu cầu có thật, tần suất lặp lại cao:** Diễn ra sau mỗi buổi học trong suốt kỳ học (không chỉ giới hạn ở các buổi lab), ảnh hưởng đến toàn bộ sinh viên.
3. **Domain quen thuộc 100%:** Cả 4 thành viên đều là sinh viên, trực tiếp trải qua nỗi đau ngợp tài liệu và thiếu công cụ ôn tập phản xạ, dễ dàng phỏng vấn và kiểm chứng ngay tại lớp.
4. **Baseline đo lường rõ ràng:** Hiện tại sinh viên mất 3–4 tiếng đọc lại tài liệu để ôn tập; target giảm xuống dưới 45 phút mà vẫn nắm được 85%+ khái niệm cốt lõi.
5. **Rất rõ nét khi so sánh 4 mức can thiệp:** No AI (dùng template Cornell Note/Notion), Rule (script tách text và outline từ slide), Workflow (AI trích xuất khái niệm và tạo quiz), Agent (tự tìm tài liệu mở rộng và chấm điểm tự luận).

**Vì sao loại các candidate còn lại:**
- *Tự động kiểm tra bài Lab với Requirement và Rubric (27 điểm):* Cấu trúc bài lab và rubric thay đổi liên tục theo từng buổi, AI khó nắm bắt được tiêu chí chấm linh hoạt của LabCoach, nguy cơ rủi ro cao nếu AI chấm sai.
- *Đọc hiểu yêu cầu đề bài lab (29 điểm):* Chỉ diễn ra ở đầu buổi học, khó đo lường chính xác ranh giới giữa việc "hiểu đúng đề" với "đọc tóm tắt qua loa".
- *Các bài toán đặt xe xưởng sản xuất (24 điểm):* Không khả thi để kiểm chứng trong thời gian 4 tiếng của buổi lab; không thể can thiệp vào hệ thống và thuật toán điều xe của bên thứ ba (Grab/Ahamove).

**Xử lý bất đồng (nếu có):**
Ban đầu có sự phân vân giữa đề tài kiểm tra bài lab và tổng hợp tài liệu ôn tập. Sau khi chấm điểm chi tiết, nhóm nhận thấy đề tài tài liệu ôn tập có impact rộng hơn, thị trường đã có nhiều công cụ mẫu (NotebookLM, Quizlet) để research học hỏi kiến trúc, và dễ phỏng vấn người thật trong lớp hơn. Cả nhóm đồng thuận 100% chọn candidate này.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Sinh viên sau buổi học thực sự muốn ôn lại kiến thức bằng tóm tắt và câu hỏi trắc nghiệm/flashcard thay vì chỉ đọc lại slide. | Value | 5 | 2 | ✅ |
| 2 | Bước tốn thời gian nhất là đọc lại toàn bộ slide/recording để lọc ý chính và tự soạn câu hỏi, không phải việc học thuộc. | Value | 5 | 2 | ✅ |
| 3 | Người học tin tưởng và sẵn sàng dùng câu hỏi/tóm tắt do AI tạo ra nếu có dẫn nguồn (citation) rõ ràng về trang slide gốc. | Usability / Value | 4 | 2 | ✅ |
| 4 | Slide bài giảng (PDF) và transcript đủ cấu trúc để mô hình AI trích xuất đúng khái niệm cốt lõi mà không bịa đặt (hallucination). | Feasibility | 4 | 3 | — |
| 5 | Nhà trường / giảng viên cho phép đưa tài liệu bài giảng nội bộ vào các công cụ AI để xử lý. | Viability | 4 | 2 | Kiểm tra sau lab |

Giả định nhóm kiểm chứng trong buổi này: **Giả định #1, #2 và #3** (thuộc nhóm quan trọng cao nhưng ít bằng chứng thực tế).

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn trực tiếp 3 sinh viên ở nhóm khác (theo nguyên tắc **The Mom Test**: chỉ hỏi về hành vi đã xảy ra trong quá khứ, không hỏi giả định tương lai) kết hợp làm micro poll 8 bạn trong lớp.

**Interview snapshot 1:**

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên năm 3 ngành Khoa học dữ liệu / AI |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Mỗi lần học xong 2 tiếng trên lớp về là mình cất luôn slide, bảo cuối tuần đọc lại nhưng đến tận tuần thi mới lôi ra đọc trong hoảng loạn."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Tuần trước, chuẩn bị kiểm tra giữa kỳ môn Machine Learning, mở 6 bộ slide hơn 250 trang đọc trong 2 đêm, không kịp làm bài tập thực hành. |
| Hiện đang xử lý bằng cách nào (workaround)? | Mượn vở tóm tắt của bạn học chăm nhất hoặc lên mạng search đề thi trắc nghiệm các khóa trước. |
| Mất bao lâu, bao lần? | 4–5 tiếng trước mỗi kỳ thi; ngày thường = 0 phút (do lười và ngại đọc lại file dài). |
| Insight / opportunity rút ra | Sinh viên không thiếu tài liệu, sinh viên thiếu một công cụ "đóng gói kiến thức" nhỏ gọn ngay sau buổi học để giảm rào cản tâm lý khi bắt đầu ôn tập. |

**Interview snapshot 2:**

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên năm 2 ngành Kỹ thuật phần mềm |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Nếu tài liệu tóm tắt mà không chỉ rõ trang nào trong slide thì mình không dám tin, vì sợ AI tự chế công thức."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Đọc slide môn Xác suất thống kê, thử paste vào ChatGPT để tóm tắt nhưng ChatGPT giải thích sai ký hiệu toán học so với quy ước của thầy trên lớp. |
| Hiện đang xử lý bằng cách nào (workaround)? | Tự gõ ghi chú vào Notion, chụp màn hình công thức từ slide dán vào. |
| Mất bao lâu, bao lần? | Mất 60–90 phút cho mỗi bài giảng nếu chăm chỉ làm; thường bỏ cuộc sau 2–3 tuần đầu. |
| Insight / opportunity rút ra | Tính năng dẫn nguồn (Citation) trực tiếp về trang slide gốc là điều kiện tiên quyết để người học tin tưởng và sử dụng. |

**Interview snapshot 3:**

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Học viên lớp AI thực chiến (lớp khác cùng khóa) |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Mình chỉ cần bộ 5–10 câu hỏi trắc nghiệm test nhanh sau mỗi bài xem mình hổng chỗ nào, không cần bài văn tóm tắt dài dòng."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Tối qua, học xong buổi lab, muốn biết mình có nắm được bản chất của bài học không nhưng không có bộ câu hỏi tự kiểm tra. |
| Hiện đang xử lý bằng cách nào (workaround)? | Nhắn tin hỏi bạn cùng nhóm xem có hiểu giống mình không, trao đổi qua Discord. |
| Mất bao lâu, bao lần? | 25–30 phút trao đổi qua lại nhưng không có đáp án chuẩn. |
| Insight / opportunity rút ra | Đầu ra giá trị nhất không phải là bài tóm tắt dài (summary text), mà là bộ câu hỏi tự kiểm tra phản xạ (Active Recall Quiz) kèm giải thích đúng/sai. |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn sâu (The Mom Test) | 3 | 3/3 đều thừa nhận ngại đọc lại slide dài và thường dồn đến trước thi; 2/3 muốn có câu hỏi trắc nghiệm/flashcard ôn nhanh ngay sau buổi học. | 1 bạn nói thích tự viết tay flashcard vì tự viết mới nhớ được, tóm tắt của AI đọc xong cũng nhanh quên; 1 bạn chỉ tin tài liệu nếu có trích dẫn đúng trang slide của giảng viên. |
| Micro poll trong lớp | 8 | 6/8 cho biết mất trên 2 tiếng mỗi tuần nếu muốn tự tổng hợp tài liệu học; 7/8 muốn có quiz tự kiểm tra sau buổi học. | 2/8 nói họ chỉ cần xem lại code mẫu thực hành trên GitHub chứ không quan tâm đến lý thuyết bài giảng. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
1. **Thu hẹp phạm vi đầu ra (Scoping down):** Từ mục tiêu ban đầu là *"Tự động tạo toàn bộ tài liệu học tập tổng hợp thay thế việc đọc slide"* thu hẹp thành *"Trích xuất 5–7 khái niệm cốt lõi và tự động sinh 5–10 câu hỏi trắc nghiệm/flashcard có dẫn nguồn trang slide để người học tự kiểm tra nhanh trong 15 phút sau buổi học"*.
2. **Bổ sung yêu cầu bắt buộc về Citation (Dẫn nguồn):** Mọi câu hỏi và định nghĩa tóm tắt đều phải trỏ đúng số trang slide hoặc đoạn ghi chú gốc để người học tự đối chiếu khi nghi ngờ, giải quyết triệt để rủi ro mất niềm tin vào AI.
3. **Tôn trọng phương án No AI:** Bổ sung phương án dùng template câu hỏi ôn tập (Cornell Notes) cho những sinh viên thích tự ghi chép để ghi nhớ sâu.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Google NotebookLM** | https://notebooklm.google.com/ | Bước 2–4: Tải slide PDF lên, AI tự động tóm tắt, tạo Study Guide, FAQ và Audio Overview | Độ chính xác cao, bám sát tài liệu nguồn (grounded in source), luôn kèm trích dẫn số trang (citation) | Không có tính năng tạo bộ câu hỏi trắc nghiệm tương tác lặp lại ngắt quãng (Spaced Repetition), không xuất được sang Anki/Quizlet | **Học hỏi cơ chế trích dẫn nguồn (grounding)**: Không để AI tự do chém gió, mà bắt buộc phải trích nguồn từ tài liệu gốc. |
| **Quizlet Magic Notes / Q-Chat** | https://quizlet.com/features/magic-notes | Bước 3–5: Upload tài liệu/note, tự động tạo flashcards, câu hỏi trắc nghiệm và chế độ kiểm tra | Có sẵn hệ sinh thái luyện tập phản xạ (Flashcard, Spaced repetition, Quiz game) | Bản miễn phí bị giới hạn lượt dùng; tóm tắt các tài liệu kỹ thuật/code toán còn nông và hay nhầm công thức; phải trả phí gói Plus | **Học hỏi định dạng đầu ra**: Đầu ra tốt nhất cho ôn tập là Flashcard (thuật ngữ - giải thích) và Quiz trắc nghiệm 4 lựa chọn, thay vì văn bản dài. |
| **Otter.ai** | https://otter.ai/ | Bước 1–2: Ghi âm, chuyển giọng nói thành văn bản (transcript) và tạo tóm tắt cuộc họp/bài giảng | Xử lý file âm thanh/video bài giảng tốt, tự phân tách người nói và trích xuất bullet points | Chỉ dừng lại ở việc tóm tắt nội dung hội thoại, không có tư duy sư phạm (không tạo câu hỏi trắc nghiệm, không đánh giá độ hiểu bài) | **Nhận định ranh giới**: Không nên cố xử lý file âm thanh thô (nặng, tốn tài nguyên), mà nên bắt đầu từ tài liệu dạng chữ (slide PDF, export transcript) để tối ưu chi phí và độ chính xác. |

**Kết luận research:**
Thị trường đã có nhiều sản phẩm giải quyết từng mảnh ghép: NotebookLM làm rất tốt khâu tóm tắt có trích dẫn từ PDF, Quizlet làm rất tốt khâu tạo thẻ ôn tập. Vì vậy, **nhóm không cần và không nên tự xây dựng một mô hình AI từ đầu**. Thay vào đó, kiến trúc hợp lý nhất là một **Workflow**:
`Tài liệu buổi học (Slide PDF / Note) → AI trích xuất key concepts & sinh Quiz kèm trích dẫn nguồn → Sinh viên làm bài test & xem lại trang slide tương ứng`.

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
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

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
