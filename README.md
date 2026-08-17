# OUTPUT CONTRACT — BẮT BUỘC TẠO FILE DOCX

Sau khi đọc file hướng dẫn này và dữ liệu được người dùng cung cấp trong message hiện tại, hãy thực hiện toàn bộ công việc từ đầu đến cuối.

## Hành động bắt buộc

1. Đọc toàn bộ dữ liệu `Tuần / Bài học / Nội dung tích hợp` từ message của người dùng.
2. Parse dữ liệu theo đúng các quy tắc trong tài liệu này.
3. Tự tạo trực tiếp một **file Microsoft Word `.docx` thực tế**.
4. Điền toàn bộ dữ liệu vào bảng trong file Word.
5. Áp dụng đầy đủ border, header, column width, A4 layout và các định dạng đã quy định.
6. Lưu file `.docx` hoàn chỉnh.
7. Kiểm tra file sau khi tạo để đảm bảo file hợp lệ và có thể mở bằng Microsoft Word.
8. Trả file `.docx` đã tạo trực tiếp cho người dùng dưới dạng **file attachment / download link / nút tải file** mà môi trường hiện tại hỗ trợ.

## QUAN TRỌNG

**Không chỉ mô tả cách tạo file.**

**Không yêu cầu người dùng tự tạo file.**

**Không yêu cầu người dùng copy code rồi chạy.**

**Không trả Python code thay cho file.**

**Không trả XML thay cho file.**

**Không trả HTML thay cho file.**

**Không trả Markdown table thay cho file.**

**Không xuất nội dung bảng dưới dạng text thay cho file.**

**Không tạo file `.md` mới làm kết quả.**

Kết quả cuối cùng bắt buộc phải là:

`*.docx`

Người dùng phải có thể **click trực tiếp vào file/link/nút tải xuống** để tải file Word đã hoàn chỉnh.

Nếu môi trường có công cụ tạo file, xử lý tài liệu, Python, DOCX hoặc filesystem, hãy **tự sử dụng công cụ phù hợp** để tạo file thay vì hướng dẫn người dùng cách thực hiện.

Không hỏi lại người dùng nếu dữ liệu hiện tại đã đủ để xác định:

- Tuần
- Tên bài học
- Nội dung tích hợp

Sau khi file được tạo thành công, phản hồi ngắn gọn, ví dụ:

> Đã tạo xong file Word. Bạn có thể tải xuống tại đây:

Sau đó cung cấp trực tiếp file `.docx` để người dùng tải.

---

# NGUỒN DỮ LIỆU THỰC TẾ

Dữ liệu cần xử lý **KHÔNG nằm trong file Markdown này**.

Hãy lấy toàn bộ dữ liệu thực tế từ **message mà người dùng gửi kèm với file này**.

Nếu message chứa dữ liệu Tuần/Bài học/Nội dung tích hợp, hãy **bắt đầu tạo DOCX ngay lập tức**.
