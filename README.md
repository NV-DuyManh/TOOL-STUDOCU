#  Studocu Helper

Một tiện ích mở rộng nhẹ dành cho trình duyệt, giúp tối ưu hóa trải nghiệm đọc và lưu trữ tài liệu trên Studocu.

> **Trạng thái:** v1.0

## 📖 Giới thiệu

Công cụ này được phát triển để giải quyết các vấn đề hiển thị gây cản trở khi xem tài liệu học tập. Thay vì phải thao tác thủ công phức tạp, extension cung cấp giải pháp "một click" để làm sạch giao diện và xuất tài liệu ra định dạng in ấn chuẩn.

## ✨ Tính năng chính

### 1. Bypass Blur & Remove Watermark 
Đây là tính năng cốt lõi giúp hiển thị nội dung nguyên bản của tài liệu:
- **Xóa lớp phủ mờ (Unblur):** Loại bỏ các layer che khuất nội dung, giúp văn bản hiển thị rõ nét 100%.
- **Xóa Watermark:** Tự động ẩn các logo chìm, text quảng cáo hoặc các popup gây rối mắt đè lên nội dung.
- **Tối ưu hiển thị:** Giữ lại định dạng gốc (font chữ, bố cục) để người dùng có trải nghiệm đọc tốt nhất.

### 2. PDF Export 
Tính năng hỗ trợ lưu tài liệu về máy để in ấn hoặc đọc offline:
- **Render tự động:** Tự động cuộn và tải toàn bộ các trang tài liệu trước khi xuất.
- **Chuẩn khổ giấy A4:** Tự động căn chỉnh lề và kích thước trang phù hợp với máy in thông dụng.
- **Fix lỗi hiển thị:** Đã xử lý triệt để lỗi xuất hiện "vạch đen" (black line artifact) ở cuối trang thường gặp khi lưu trang web thành PDF.

---

## 🛠 Hướng dẫn cài đặt

Do đây là công cụ phát triển cá nhân (chưa đưa lên Store), bạn cần cài đặt thủ công qua chế độ Developer:

1. **Tải mã nguồn:** Tải file `.zip` của dự án về và giải nén (hoặc clone repository này).
2. **Mở trình quản lý tiện ích:** Truy cập đường dẫn `chrome://extensions/` trên trình duyệt (Chrome, Edge, Cốc Cốc...).
3. **Bật Developer Mode:** Gạt công tắc **"Developer mode"** ở góc trên bên phải màn hình.
4. **Tải tiện ích:** Nhấn nút **"Load unpacked"** và chọn thư mục chứa mã nguồn vừa giải nén.
dụng
## Cách sử dụng

1. Truy cập vào tài liệu Studocu cần xem.
2. Nếu bị chặn watermark và mờ thì bắt buộc mở extension và chọn Bypass mờ và watermark để công đoạn tiếp theo thành công
3. Cuộn chuột xuống cuối trang để đảm bảo toàn bộ nội dung đã được tải.
4. Mở Extension và nhấn nút **"Tạo File PDF"**.
5. Chờ vài giây để tool xử lý, sau đó hộp thoại lưu PDF sẽ tự động hiện ra.

---

Video Testing:

https://github.com/user-attachments/assets/0f98de3a-cdbb-464d-8209-b9953b0721ee

## ⚠️ Lưu ý (Disclaimer)
Công cụ này được tạo ra với mục đích hỗ trợ học tập và nghiên cứu cá nhân. Vui lòng sử dụng có trách nhiệm và tôn trọng bản quyền của tài liệu gốc.




