# AI Log

## 2026-10-30 - Sửa lỗi giao diện và ảnh

- **Yêu cầu:** Khắc phục lỗi giao diện; ảnh trên trang không hiển thị đúng.
- **Nguyên nhân:** Hai trang HTML tham chiếu CSS bằng đường dẫn tuyệt đối trên ổ `D:`, không tồn tại trong môi trường hiện tại. Vì CSS không tải, ảnh không được giới hạn kích thước theo giao diện.
- **Thay đổi:** Đổi đường dẫn CSS trong `index.html` và `ket-qua.html` thành đường dẫn tương đối `css/style.css`.
- **Kiểm tra:** Mở lại cả hai trang trong trình duyệt; xác nhận CSS được tải, ảnh đại diện và ảnh dự án hiển thị. Kiểm tra trang chính ở chiều rộng 390 px và xác nhận không tràn ngang.

## 2026-11-05 - Chuẩn bị repository cho Buổi 7

- **Yêu cầu:** Kiểm tra trạng thái, đặt tag `v7`, rà soát tên và đường dẫn, đồng thời chuẩn bị cấu trúc tài liệu và minh chứng.
- **Thay đổi:** Cập nhật `README.md`; thêm `CHANGELOG.md` và `docs/evidence-index.md`; chuẩn bị `docs/evidence/`.
- **Kiểm tra:** Xác nhận các tệp và liên kết tài liệu tồn tại. Tag `v7` trỏ tới commit hiện tại; các thay đổi tài liệu vẫn chưa commit.
- **Ghi chú:** Chưa có mẫu Phụ lục trong workspace, nên các tệp mới dùng khung chung với chỗ trống để điền sau.

## 2026-11-06 - Cập nhật thông tin portfolio và tài liệu hướng dẫn

- **Yêu cầu:** Nâng cấp mô tả portfolio để phù hợp với nội dung thực tế: giới thiệu bản thân, 3 dự án học tập, mục tiêu tuyển dụng thực tập và các bước mở demo.
- **Thay đổi:**
  - Chỉnh sửa `README.md` để mô tả rõ mục tiêu portfolio và thêm phần demo + hướng dẫn mở trang web.
  - Cập nhật `CHANGELOG.md` với phiên bản `V8 - 4/11/2026`, ghi rõ thay đổi, nội dung mới và trạng thái chưa kiểm tra trên iPhone.
  - Dùng đường dẫn tương đối và chuẩn hóa tài liệu để dễ dùng hơn khi triển khai hoặc chia sẻ.
- **Kiểm tra:**
  - Xác nhận nội dung đã được lưu vào repo.
  - Kiểm tra trạng thái Git và đẩy các thay đổi lên GitHub thành công.
- **Ghi chú:** Các thay đổi này tập trung vào tài liệu và trình bày portfolio, không làm thay đổi logic hoặc cấu trúc chính của giao diện.
