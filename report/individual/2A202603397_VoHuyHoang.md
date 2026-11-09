# Báo cáo cá nhân — 2A202603397_VoHuyHoang

## 1. Thông tin học viên

- Họ tên: Võ Huy Hoàng
- MSSV: 2A202603397
- Email trường: 26ai.hoangvh4@vinuni.edu.vn
- Tên nhóm: NhomHTHT
- Link repo nhóm: https://github.com/hoanganhchimxanh/K5-L3A-Day02-NhomHTHT-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi làm Labs, tôi muốn file AI-Logs.md sẽ tự động cập nhật để tôi không phải tự viết tay | LabCoach | Mất 15-20p ở Lab1 để check lại câu hỏi cho AI|
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận bài Lab, tôi muốn các thông tin instruction được tổng hợp sẵn để không phải đi tìm các file Markdown cần thiết | Team | Trong chính bài Lab này tôi đã tốn ~10p để tìm thấy các file requirement và docs |
| 3 | Lặp lại | Khi thực hiện dự án Build Phase, tôi muốn Daily Stand up sẽ tự cập nhật các phần Task tôi đã thực hiện ngày hôm đó để không cần phải nhớ lại để viết | Team, Cá nhân | Sáng nay tôi mấy ~5p để viết Daily Standup |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi lên plan cho một chuyến đi, tôi muốn lịch trình được xếp sẵn theo vị trí địa lý để 2 điểm đếm gần nhất sẽ không các nhau quá xa | Nhóm, Cá nhân | Cuối tuần vừa rồi tôi và nhóm lên kế hoạch đi chơi nhưng chưa có planning trước nên quãng đường di chuyển rất dài |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi đi học về, tôi muốn có sẵn guideline để nấu món ăn từ những nguyên liệu tôi sẵn có để không phải suy nghĩ xem nấu món gì | Gia đình, Cá nhân | Đi học về lúc 6h tối, tôi mất >1h để quyết định nấu và nấu xong bữa cơm |
| 6 | Lặp lại | Khi mua sắm/chi tiền xong, tôi muốn thông tin về mục đích chi tiền sẽ được gửi tự động lên app thống kê để không phải điền manual | Cá nhân | Có đôi lúc tôi quên điền thông tin vào app quản lý chi tiêu |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi xong 1 buổi học, tôi muốn các kiến thức và bài ôn tập được tổng hợp và tạo tự động để dễ dàng ôn tập kiến thức | Cá nhân | Sau 2 ngày học đầu tiên, tôi phải đi research kiến thức để ôn tập lại, mất khoảng 4h ngày cuối tuần |
| 8 | Tốn thời gian | Khi hoàn thành 1 bài Lab, tôi muốn bài làm của mình được kiểm tra tự động với file Requirement và Rubric để có thể phát hiện lỗi và sửa sớm | Cá nhân | Tôi mất khoảng 1h để check lại file Rubric và sửa lại bài ở MiniLab 2|

**Nếu có dùng AI để gợi ý thêm:** 

- Tôi dùng AI để gợi ý thêm ý 7 và 8

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tự động kiểm tra bài Lab với Requirement và Rubric (#8) | Tốn thời gian, có baseline thật | Chưa xác định AI có thể kiểm tra chính xác đến mức nào và liệu kết quả đánh giá có khớp với LabCoach hay không. |
| 2 | Tự động tổng hợp kiến thức và tạo tài liệu ôn tập sau buổi học (#7) | Tốn thời gian, nhiều người gặp | Kiến thức AI tổng hợp có thể quá rộng hoặc quá ít |
| 3 | Tự động điền file AI-Logs.md (#1) | Tốn thời gian, nhiều người gặp | AI có thể điền quá chi tiết làm file quá dài |

### Problem Card #8

| Trường | Nội dung |
|---|---|
| Job Story | Khi hoàn thành 1 bài Lab, tôi muốn bài làm của mình được kiểm tra tự động với file Requirement và Rubric để có thể phát hiện lỗi và sửa sớm |
| Actor | Student, Học viên AI thực chiến |
| Thời điểm / bối cảnh | Sau khi hoàn thành bài Lab và trước khi submit bài làm. Người học cần kiểm tra xem bài làm đã đáp ứng đầy đủ các yêu cầu và tiêu chí đánh giá hay chưa. |
| Quy trình hiện tại | 1. Hoàn thành bài Lab theo hướng dẫn.  2. Mở các file Requirement và Documentation để xem lại yêu cầu. 3. Đọc file Rubric để hiểu các tiêu chí chấm điểm. 4. Đối chiếu từng yêu cầu với kết quả bài làm. 5. Phát hiện những phần còn thiếu hoặc chưa đúng. 6. Chỉnh sửa bài làm và kiểm tra lại trước khi nộp.|
| Bottleneck | Bước 2–4: Phải đọc nhiều tài liệu và đối chiếu thủ công giữa bài làm, Requirement và Rubric. Khoảng 1 giờ để kiểm tra Rubric và chỉnh sửa lại bài làm.|
| Impact | Tốn nhiều thời gian review thủ công, dễ bỏ sót yêu cầu quan trọng, có thể nộp bài chưa hoàn chỉnh hoặc không đạt một số tiêu chí trong Rubric. |
| Success metric | Thời gian kiểm tra bài: 60 phút → dưới 15 phút. Tỷ lệ phát hiện các lỗi/requirements bị thiếu trước khi submit: hướng tới trên 90% trên tập test được xác minh thủ công. Có báo cáo trạng thái cho từng tiêu chí: đạt / chưa đạt / cần kiểm tra. |
| Phương án không dùng AI | Xây dựng checklist hoặc form checklist dựa trên Requirement và Rubric. Người học tự đánh dấu từng tiêu chí sau khi kiểm tra bài làm. |
| Giả thuyết về AI | AI có thể đọc và phân tích các file Requirement, Documentation, Rubric cùng với bài làm của người học. Sau đó, AI tự động đối chiếu từng tiêu chí, xác định nội dung còn thiếu, phát hiện những điểm chưa phù hợp và đưa ra gợi ý chỉnh sửa cụ thể. Kết quả được trình bày dưới dạng báo cáo checklist kèm bằng chứng từ bài làm. |
| Cảm nhận nhanh | Agent |

Quy trình nháp hiện tại:

```text
[Hoàn thành bài Lab]
          |
          v
[Mở file Requirement / Documentation]
          |
          v
[Đọc file Rubric]
          |
          v
[Đối chiếu thủ công bài làm với từng tiêu chí]
          |
          v
[Phát hiện lỗi hoặc yêu cầu còn thiếu]
          |
          v
[Chỉnh sửa bài làm]
          |
          v
[Kiểm tra lại toàn bộ]
          |
          v
[Submit bài Lab]
```

### Problem Card #7

| Trường | Nội dung |
|---|---|
| Job Story | Khi xong 1 buổi học, tôi muốn các kiến thức và bài ôn tập được tổng hợp và tạo tự động để dễ dàng ôn tập kiến thức |
| Actor | Learner |
| Thời điểm / bối cảnh | Sau mỗi buổi học hoặc cuối ngày học. Người học cần hệ thống hóa kiến thức vừa tiếp thu để ghi nhớ lâu hơn và chuẩn bị cho các buổi học tiếp theo. |
| Quy trình hiện tại | 1. Tham gia buổi học và tiếp nhận kiến thức từ giảng viên. 2. Ghi chú hoặc lưu lại các tài liệu được cung cấp. 3. Sau buổi học, tìm kiếm thêm tài liệu để hiểu rõ những nội dung chưa nắm vững. 4. Đọc lại tài liệu và tổng hợp các kiến thức quan trọng. 5. Tự tạo câu hỏi hoặc bài tập để kiểm tra mức độ hiểu bài. 6. Ôn tập lại kiến thức vào cuối tuần. |
| Bottleneck | Bước 3–5: Phải tự tìm kiếm, đọc và tổng hợp thông tin từ nhiều nguồn, sau đó tự xây dựng nội dung ôn tập. |
| Impact | Tốn nhiều thời gian cho việc tìm kiếm và tổng hợp thay vì tập trung vào thực hành. Kiến thức có thể bị quên nếu không được ôn tập thường xuyên. Người học cũng có thể bỏ sót những nội dung quan trọng hoặc không biết mình đang yếu ở phần kiến thức nào. |
| Success metric | Thời gian tổng hợp và chuẩn bị tài liệu ôn tập: 4 giờ → dưới 30 phút. Tự động tạo bản tóm tắt kiến thức và bộ câu hỏi sau mỗi buổi học. Nội dung được tạo phải bám sát tài liệu gốc, hướng tới độ chính xác trên 90% qua kiểm tra thủ công.|
| Phương án không dùng AI | Sử dụng template ghi chú cố định như Notion hoặc Markdown để lưu lại kiến thức sau mỗi buổi học. Chuẩn bị sẵn checklist các chủ đề cần ôn tập và sử dụng flashcard hoặc câu hỏi trắc nghiệm được tạo thủ công. |
| Giả thuyết về AI | AI có thể đọc slide, tài liệu Markdown, ghi chú hoặc transcript của buổi học để tự động tổng hợp kiến thức quan trọng. Từ nội dung đó, AI tạo mindmap, flashcards, câu hỏi trắc nghiệm và bài tập thực hành theo từng chủ đề. AI cũng có thể phân loại nội dung theo mức độ khó và đề xuất những kiến thức cần ưu tiên ôn tập. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[Bắt đầu buổi học]
        |
        v
[Tiếp nhận kiến thức từ giảng viên]
        |
        v
[Ghi chú và lưu tài liệu]
        |
        v
[Kết thúc buổi học]
        |
        v
[Tìm kiếm thêm tài liệu trên Internet]
        |
        v
[Đọc và tổng hợp kiến thức]
        |
        v
[Tự tạo câu hỏi và bài tập ôn tập]
        |
        v
[Ôn tập lại vào cuối tuần]
```

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm Labs, tôi muốn file AI-Logs.md sẽ tự động cập nhật để tôi không phải tự viết tay |
| Actor | Learner, LabCoach |
| Thời điểm / bối cảnh | Trong và sau quá trình thực hiện mỗi bài Lab, đặc biệt khi sử dụng AI để hỗ trợ giải quyết các yêu cầu, viết code, phân tích hoặc tìm kiếm thông tin. |
| Quy trình hiện tại | 1. Đọc yêu cầu của bài Lab. 2. Sử dụng AI để hỏi đáp, giải thích hoặc hỗ trợ thực hiện các task. 3. Kiểm tra và đánh giá câu trả lời của AI. 4. Ghi nhớ những lần tương tác với AI. 5. Cuối buổi, mở file AI-Logs.md. 6. Viết lại các yêu cầu đã gửi, kết quả AI trả về, những lỗi AI mắc phải và cách bản thân kiểm chứng hoặc chỉnh sửa. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4–6: Phải nhớ lại các tương tác trước đó, chọn lọc thông tin quan trọng và trình bày lại theo đúng cấu trúc Markdown (~15-20p để check lại và điền). |
| Impact | Tốn thời gian ghi chép thủ công, dễ quên các lần tương tác hoặc bỏ sót những lỗi AI đã mắc phải. AI Logs có thể không đầy đủ, làm giảm khả năng đánh giá hiệu quả sử dụng AI và rút kinh nghiệm sau mỗi bài Lab. |
| Success metric | Thời gian cập nhật AI Logs: 15–20 phút → dưới 5 phút. Tỷ lệ ghi nhận các tương tác AI quan trọng: hướng tới trên 90% qua đối chiếu thủ công. File AI-Logs.md được cập nhật đúng cấu trúc Markdown và không mất dữ liệu cũ. |
| Phương án không dùng AI | Sử dụng template Markdown cố định để ghi lại từng lần tương tác. Có thể viết script hoặc browser extension để lưu prompt và response vào file log, sau đó người dùng tự phân loại và bổ sung phần đánh giá. |
| Giả thuyết về AI | AI có thể thu thập lịch sử tương tác, tự động phân loại theo từng giai đoạn Lab và tổng hợp thành các mục trong AI-Logs.md, bao gồm yêu cầu gửi cho AI, kết quả nhận được, vấn đề phát sinh, mức độ tin cậy và cách người học kiểm chứng hoặc chỉnh sửa. Người học chỉ cần review và xác nhận nội dung trước khi lưu. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[Bắt đầu làm Lab]
        |
        v
[Đọc Lab Requirements]
        |
        v
[Sử dụng AI hỗ trợ thực hiện Lab]
        |
        v
[Kiểm tra kết quả AI trả về]
        |
        v
[Tiếp tục thực hiện các task]
        |
        v
[Kết thúc Lab]
        |
        v
[Nhớ lại/Xem lại lịch sử các lần tương tác với AI]
        |
        v
[Viết thủ công vào AI-Logs.md]
        |
        v
[Kiểm tra và hoàn thiện AI Logs]
```

### Card muốn pitch nhất

- Card số: #8 - Tự động kiểm tra bài Lab với Requirement và Rubric
- Vì sao: Đây là vấn đề tôi đã trực tiếp gặp khi thực hiện MiniLab 2. Tôi mất khoảng 1 giờ để kiểm tra Rubric và chỉnh sửa bài làm. Giải pháp có thể giúp tiết kiệm thời gian, phát hiện những yêu cầu còn thiếu và giảm nguy cơ nộp bài chưa hoàn chỉnh. Ngoài ra, bài toán có đầu vào và đầu ra rõ ràng, có thể kết hợp Rule-based và AI để xây dựng MVP và đo lường hiệu quả thực tế.
- Câu hỏi muốn nhóm phản biện:
    1. Liệu AI có thể đánh giá chính xác mức độ đáp ứng của bài làm so với Requirement và Rubric không? 
    2. Nên sử dụng AI hoàn toàn hay kết hợp AI với Rule-based để đảm bảo kết quả đáng tin cậy?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| AI có thể đưa ra giải pháp quá rộng, chưa xác định rõ phạm vi MVP | Đồng ý | Giới hạn MVP vào việc đọc Requirement, đối chiếu Rubric và tạo báo cáo lỗi. |
| Success metric chưa có cơ sở kiểm chứng | Đồng ý | Bổ sung baseline 60 phút và target dưới 15 phút; xác định cần thử nghiệm để kiểm chứng. |
| AI có thể tự suy diễn thông tin khi tài liệu không đầy đủ | Đồng ý | Yêu cầu AI trích dẫn bằng chứng từ bài làm và đánh dấu Needs Review khi chưa đủ căn cứ. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch problem #8 #7 #1 | #8 và #7 được vào Shortlist, #7 được chọn |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | 1. Nếu sử dụng AI để giải thích đề bài, làm sao đảm bảo AI không diễn giải sai yêu cầu gốc? 2. AI sẽ xử lý thế nào nếu phần việc không phù hợp với thành viên được giao/thành viên không đủ khả năng handle task đấy? 3. Vấn đề nằm ở việc thiếu tài xế, thời gian chờ hay việc phải liên tục theo dõi ứng dụng? 4. Nếu AI cảnh báo sai rằng đơn hàng sẽ giao trễ, điều đó có gây ảnh hưởng đến kế hoạch sản xuất hoặc khách hàng không? 5. Làm sao đảm bảo AI không bỏ sót công việc hoặc báo cáo sai tiến độ của thành viên? 6. Nếu video không có transcript hoặc nội dung được trình bày bằng hình ảnh/code, giải pháp có tìm kiếm chính xác được không? |
| Nhận phản biện | Câu hỏi tôi nhận được: | **1.** AI chấm sai thì ai chịu trách nhiệm? Với những requirement và rubric chung chung thì liệu AI có hiểu nhầm không? **2.** Log tự điền thì có đáng tin không? Lấy lịch sử dùng AI từ đâu (mỗi công cụ một kiểu)? **3** Công sức bỏ ra có đáng không? Khóa này còn vài tuần là hết. Nếu build giải pháp của card bạn thì mất bao lâu? Build xong còn bao nhiêu buổi lab để dùng? Thời gian tiết kiệm được (phút/lần × số lần còn lại × số người dùng) có nhiều hơn thời gian build + sửa lỗi không? So với làm checklist (gần như không tốn thời gian build) thì sao? **Tôi đã sửa:** Clear lại các constrant và thread xử lý của AI |
| Gom cluster | Tổng hợp cluster | Gom nhóm các đề tài |
| Chọn candidate problem | Chọn shortlist 5 candidate | 2 Candidate được vào shortlist, 1 candidate được chọn làm Problem chính |
| Quy trình nhóm | Viết tài liệu Markdown | Fill toàn bộ Markdown cho phần task nhóm |
| Problem Statement | Viết problem statement v0 + v1 | Tổng hợp các thay đổi sau các bước thống kê và chốt lại Problem Statement v1 |
| Quyết định | Nêu ý kiến và chốt quyết định cuối cùng | Chốt quyết định cuối cùng  |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý problem 7 + 8 | Gợi ý cho tôi ý tưởng hợp lý | Một vài ý tưởng từ AI hơi mơ hồ và không khớp với thực tế bản thân tôi | Thêm problem 7 và 8 |
| CP2 Problem Card | Vẽ quy trình khi có AI cho các problem | Gợi ý workflow hợp lý khi áp dụng AI | Một số bước không hợp lý ở thực tế | Sửa lại cho hợp lý các workflow |
| CP5–6 Problem Statement | Tổng hợp thông tin workflow, gợi ý có nên thay đổi phần nào của problem statement không | Đưa ra gợi ý hợp lý | Câu trả lời quá dài | Rút ngắn câu trả lời cho phù hợp |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**  
Một số problem khá nhiều người cùng bị ảnh hưởng (như review bài lab trước khi nộp hay đọc hiểu đề bài lab)
Một số idea ban đầu của tôi hơi mơ hồ

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**  
Nhóm không bị solution-first

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**  
Tôi thay đổi một vài ràng buộc của Problem #1 - Điền file AI-Logs.md vì sau khi nhận phản biện, tôi nhận ra việc AI đôi khi sẽ ghi lịch sử chat quá dài và không focus vào nội dung chính.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**  


**6.5. Điều khó nhất khi viết Problem Statement là gì?**  
Điều khó nhất khi viết Problem Statement có lẽ là tính toán Success Metrics do nếu không có các số liệu cụ thể thì rất khó đoán được Success Metrics là bao nhiêu

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**  
Trong lúc thực hiện team đã không hiểu nhau ở một số phần dẫn đến việc hoàn thành bài Lab tốn thời gian hơn, tôi muốn team trao đổi nhiều hơn

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Problem: Sau các buổi học, việc tổng hợp lại kiến thức và bài ôn tập rất khó và mất thời gian, tôi muốn hệ thống AI có thể tổng hợp lại nội dung học để có thể dễ dàng ôn tập khi về nhà.  
Quy trình: 1. Sau buổi học, tổng hợp kiến thức trên lớp -> 2. Tìm kiếm tài liệu bên ngoài -> 3. Tổng hợp kiến thức -> 4. Ghi chép lại và nghĩ câu hỏi ôn tập -> 5. Ôn tập lại
Boundary: Confirm kiến thức tổng hợp là chắc chắn đúng, cần HITL
Mức can thiệp AI: Workflow
Quyết định: Go

---

## 7. Tài liệu tham khảo

-
