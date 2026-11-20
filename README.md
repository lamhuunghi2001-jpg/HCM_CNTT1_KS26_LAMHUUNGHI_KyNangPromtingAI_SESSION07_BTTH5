# Bài tập: Xây dựng Prompt chấm bài viết bằng AI

Đề tài: "Vai trò của AI trong hoạt động học tập của sinh viên đại học"

## 1. Prompt thiết lập vai trò người chấm

```text
Bạn là giảng viên đại học có kinh nghiệm chấm bài luận ngắn. Nhiệm vụ của bạn là chấm bài viết của sinh viên theo đúng Rubric bên dưới, khách quan và nhất quán.

Đề bài sinh viên: "Vai trò của AI trong hoạt động học tập của sinh viên đại học", khoảng 300 từ.

Rubric (không được đổi trọng số): Đúng chủ đề 2 điểm; Nội dung và lập luận 3 điểm; Ví dụ minh họa 2 điểm; Cấu trúc bài viết 1,5 điểm; Ngữ pháp và diễn đạt 1,5 điểm. Tổng 10 điểm.

Quy tắc bắt buộc:
- Mỗi điểm số phải kèm ít nhất một minh chứng trích nguyên văn từ bài viết, đặt trong ngoặc kép.
- Không chấm theo cảm tính. Nếu trừ điểm, nêu rõ lý do trừ.
- Không cho điểm cao chỉ vì bài dài. Đánh giá chất lượng lập luận, không đánh giá số lượng từ.
- Điểm từng tiêu chí không vượt mức tối đa, bước chấm 0,25.
- Mỗi lỗi phải chỉ rõ vị trí và đề xuất cách sửa cụ thể.

Quy trình: đọc kỹ bài viết, chấm từng tiêu chí, xác định điểm mạnh và điểm yếu, đề xuất cải thiện, cộng tổng điểm.

Định dạng đầu ra:
1. Điểm từng tiêu chí (điểm / tối đa), kèm minh chứng và lý do.
2. Điểm mạnh.
3. Điểm yếu, kèm lỗi cụ thể và cách sửa.
4. Đề xuất cải thiện tổng thể.
5. Tổng điểm /10.

Bài viết cần chấm: [dán bài viết vào đây]
```

## 2. Rubric

| Tiêu chí | Điểm tối đa | Mô tả mức cao nhất |
|---|---|---|
| Đúng chủ đề | 2 | Bám sát vai trò của AI trong học tập đại học, không lạc đề |
| Nội dung và lập luận | 3 | Có luận điểm rõ, phân tích được cả lợi ích và rủi ro, lập luận chặt chẽ |
| Ví dụ minh họa | 2 | Ví dụ cụ thể, thực tế, gắn với từng luận điểm |
| Cấu trúc bài viết | 1,5 | Có mở bài, thân bài, kết bài, các đoạn liên kết mạch lạc |
| Ngữ pháp và diễn đạt | 1,5 | Ít lỗi, câu rõ nghĩa, từ ngữ đa dạng, không lặp |
| Tổng | 10 | |

## 3. Bài viết mẫu (khoảng 300 từ)

Trong những năm gần đây, trí tuệ nhân tạo (AI) đã trở thành một phần quen thuộc trong cuộc sống của sinh viên đại học. Theo tôi, AI giữ vai trò như một người trợ giảng luôn sẵn sàng, nhưng chỉ phát huy giá trị khi sinh viên biết sử dụng đúng cách.

Trước hết, AI giúp sinh viên tiết kiệm thời gian và tiếp cận kiến thức nhanh hơn. Chẳng hạn, khi gặp một đoạn code Python báo lỗi, sinh viên có thể nhờ ChatGPT giải thích nguyên nhân và gợi ý hướng sửa, thay vì mất hàng giờ tìm kiếm trên mạng. Tương tự, các công cụ như Google Translate hay Grammarly giúp sinh viên đọc tài liệu tiếng Anh và chỉnh sửa bài viết dễ dàng hơn.

Bên cạnh đó, AI còn hỗ trợ học tập cá nhân hóa. Sinh viên có thể yêu cầu AI tạo câu hỏi ôn tập, tóm tắt bài giảng hoặc giải thích một khái niệm khó theo nhiều cách khác nhau cho đến khi hiểu. Điều này đặc biệt hữu ích với sinh viên năm nhất còn bỡ ngỡ với phương pháp học ở đại học.

Tuy nhiên, việc lạm dụng AI cũng mang lại nhiều rủi ro. Nếu chỉ sao chép câu trả lời mà không suy nghĩ, sinh viên sẽ dần mất khả năng tư duy độc lập và có thể vi phạm quy định về liêm chính học thuật. Ngoài ra, AI đôi khi đưa ra thông tin sai nhưng nghe rất thuyết phục, nên sinh viên cần kiểm chứng lại với giáo trình hoặc giảng viên.

Tóm lại, AI là công cụ hỗ trợ đắc lực chứ không thể thay thế việc học thật sự. Sinh viên nên dùng AI để hiểu bài sâu hơn, đồng thời giữ thói quen tự suy nghĩ và kiểm tra thông tin. Có như vậy, AI mới thật sự góp phần nâng cao chất lượng học tập.

## 4. Kết quả AI chấm điểm

Đúng chủ đề: 2/2. Bài mở đầu bằng "AI đã trở thành một phần quen thuộc trong cuộc sống của sinh viên đại học" và xuyên suốt bám vào vai trò của AI trong học tập, không lạc đề.

Nội dung và lập luận: 2,5/3. Bài có luận điểm trung tâm ("AI giữ vai trò như một người trợ giảng") và phân tích đủ ba hướng: tiết kiệm thời gian, cá nhân hóa, rủi ro. Trừ 0,5 vì phần rủi ro chưa phân tích sâu, chưa nói rõ hậu quả với kết quả học tập.

Ví dụ minh họa: 1,5/2. Phần lợi ích có ví dụ cụ thể ("đoạn code Python báo lỗi", "Grammarly"). Trừ 0,5 vì phần rủi ro chỉ nêu chung chung ("sao chép câu trả lời"), thiếu tình huống thực tế.

Cấu trúc bài viết: 1,25/1,5. Có mở, thân, kết rõ, có từ nối ("Trước hết", "Bên cạnh đó", "Tuy nhiên", "Tóm lại"). Trừ 0,25 vì phần kết lặp lại ý đã nói, chưa thêm khuyến nghị mới.

Ngữ pháp và diễn đạt: 1,25/1,5. Câu đúng ngữ pháp, dễ hiểu. Trừ 0,25 vì lặp từ ("thật sự" xuất hiện hai lần, "AI" lặp dày) và cụm "mang lại nhiều rủi ro" còn chung chung.

Điểm mạnh: bám đề, bố cục rõ, có ví dụ gần gũi với sinh viên, cân bằng giữa lợi ích và rủi ro.

Điểm yếu: phần rủi ro thiếu chiều sâu và ví dụ, phần kết lặp ý, còn lặp từ.

Tổng điểm: 2 + 2,5 + 1,5 + 1,25 + 1,25 = 8,5/10.

## 5. Nhận xét và đề xuất cải thiện

Về lập luận, nên thêm một câu nêu hậu quả cụ thể của việc lạm dụng AI, ví dụ sinh viên nộp bài giống nhau hoặc không giải thích được bài của chính mình khi bị hỏi.

Về ví dụ, thay "sao chép câu trả lời" bằng một tình huống cụ thể như "nhờ AI viết trọn bài tiểu luận rồi nộp mà không đọc lại".

Về kết bài, thay câu cuối bằng một lời khuyên mới, chẳng hạn "sinh viên nên ghi rõ phần nào dùng AI hỗ trợ".

Về diễn đạt, thay "thật sự" thứ hai bằng "thực sự" hoặc bỏ đi, và dùng "công cụ này", "trợ lý ảo" để bớt lặp "AI".

## 6. Bảng đối chiếu tiêu chí, điểm số và minh chứng

| Tiêu chí | Điểm | Minh chứng từ bài viết | Lỗi / cách sửa |
|---|---|---|---|
| Đúng chủ đề | 2/2 | "AI đã trở thành một phần quen thuộc trong cuộc sống của sinh viên đại học" | Không có lỗi |
| Nội dung và lập luận | 2,5/3 | "AI giữ vai trò như một người trợ giảng luôn sẵn sàng" | Phân tích rủi ro còn mỏng: thêm hậu quả cụ thể |
| Ví dụ minh họa | 1,5/2 | "đoạn code Python báo lỗi", "Grammarly" | Ví dụ rủi ro chung chung: thêm tình huống thực tế |
| Cấu trúc bài viết | 1,25/1,5 | "Trước hết", "Bên cạnh đó", "Tuy nhiên", "Tóm lại" | Kết bài lặp ý: thêm khuyến nghị mới |
| Ngữ pháp và diễn đạt | 1,25/1,5 | "mới thật sự góp phần", "việc học thật sự" | Lặp "thật sự", lặp "AI": thay từ đồng nghĩa |
| Tổng | 8,5/10 | | |
