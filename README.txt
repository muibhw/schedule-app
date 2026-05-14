# Phần mềm lập thời gian biểu kết hợp đọc ảnh

## Chức năng
- Thêm lịch thủ công.
- Đọc lịch từ hình ảnh bằng OCR.
- Dán lịch từ website khác.
- Nhập file CSV/ICS.
- Lưu thời gian biểu trong trình duyệt.
- Xuất CSV và ICS để nhập vào Google Calendar, Outlook, Apple Calendar.

## Cách chạy
1. Giải nén file zip.
2. Mở `index.html` bằng Chrome hoặc Edge.
3. Nếu dùng chức năng đọc ảnh, cần có Internet vì phần mềm dùng Tesseract.js từ CDN.

## Định dạng nhập tốt nhất
Tên việc | 2026-05-20 | 08:00 | 10:00 | Địa điểm

Ví dụ:
Học tiếng Anh | 2026-05-20 | 08:00 | 10:00 | Phòng A
Làm bài tập MIS | 2026-05-21 | 19:00 | 21:00 | Ở nhà

## Lưu ý
- Ảnh càng rõ, chữ càng thẳng thì OCR càng chính xác.
- Sau khi đọc ảnh, nên kiểm tra và sửa lại nội dung OCR trước khi chuyển thành lịch.
