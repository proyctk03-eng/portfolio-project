# Mini Project: "Tân trang" trang Giới thiệu bản thân

Dự án nâng cấp toàn diện giao diện trang cá nhân "About Me" thông qua sức mạnh của CSS thuần (External CSS), biến tài liệu HTML có cấu trúc thành một portfolio cá nhân chuyên nghiệp và ấn tượng theo chuẩn CodeGym.

---

## Các yêu cầu đã hoàn thành
1. **Thiết lập và Bố cục chung**:
   - Sử dụng phương pháp External CSS (`style.css`) tách biệt hoàn toàn mã giao diện khỏi HTML.
   - Thẻ `body` áp dụng nền xám nhẹ `#f0f2f5`, font chữ `Segoe UI / Arial`.
   - Lớp `.container` giới hạn chiều rộng 900px, căn giữa với `margin: 30px auto`, nền trắng `#ffffff`, padding 40px và hiệu ứng bóng đổ `box-shadow` mềm mại.
2. **Khu vực Đầu trang (`<header>`)**:
   - Căn giữa toàn bộ nội dung với `text-align: center`.
   - Ảnh đại diện tròn hoàn hảo (`border-radius: 50%`) kèm viền màu nhấn và hiệu ứng phóng to nhẹ khi hover.
   - Tên cá nhân `<h1>` có kích thước lớn và màu sắc sang trọng `#2c3e50`.
3. **Khu vực Nội dung (`<section>`)**:
   - Tiêu đề `<h2>` màu xanh đậm kèm đường gạch chân trang trí `border-bottom: 2px solid #3498db`.
   - Thẻ `<p>` có khoảng cách dòng `line-height: 1.8` và căn lề đều hai bên (`text-align: justify`).
   - Thẻ `<strong>` sử dụng màu đỏ cam `#e74c3c` nổi bật các từ khóa trọng tâm.
4. **Khu vực Liên kết & Footer**:
   - Bộ chọn `a` bỏ gạch chân mặc định (`text-decoration: none`), tạo dạng nút bo góc với hiệu ứng `:hover` đổi màu và nổi lên trên (`transform: translateY(-2px)`).
   - Thẻ `ul.social-links` loại bỏ hoàn toàn dấu chấm đầu dòng (`list-style-type: none`) và căn giữa các nút bấm.
5. **Tổ chức CSS**:
   - Tệp `style.css` được chia thành 4 khu vực rõ ràng kèm chú thích chi tiết (`/* ... */`).

---

## Cấu trúc thư mục dự án
```
mini-project-tan-trang-trang-gioi-thieu-ban-than/
├── index.html       # Trang Portfolio cá nhân hoàn thiện
├── style.css        # Tệp External CSS chuẩn hóa
├── README.md        # Hướng dẫn chi tiết
└── images/
    └── avatar.jpg   # Ảnh đại diện cá nhân
```
