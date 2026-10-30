# AI Log

## 2026-10-30 - Sửa lỗi giao diện và ảnh

- **Yêu cầu:** Khắc phục lỗi giao diện; ảnh trên trang không hiển thị đúng.
- **Nguyên nhân:** Hai trang HTML tham chiếu CSS bằng đường dẫn tuyệt đối trên ổ `D:`, không tồn tại trong môi trường hiện tại. Vì CSS không tải, ảnh không được giới hạn kích thước theo giao diện.
- **Thay đổi:** Đổi đường dẫn CSS trong `index.html` và `ket-qua.html` thành đường dẫn tương đối `css/style.css`.
- **Kiểm tra:** Mở lại cả hai trang trong trình duyệt; xác nhận CSS được tải, ảnh đại diện và ảnh dự án hiển thị. Kiểm tra trang chính ở chiều rộng 390 px và xác nhận không tràn ngang.
