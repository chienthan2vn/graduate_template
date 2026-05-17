# Thiệp Mời Lễ Tốt Nghiệp Thạc Sĩ - Lương Đức Thuận 🎓

Trang web thiệp mời trực tuyến (Landing Page) sang trọng, hiện đại và phản hồi tốt (responsive) được tùy chỉnh đặc biệt để gửi lời mời tham dự lễ tốt nghiệp của Lương Đức Thuận tại **Học viện Công nghệ Bưu chính Viễn thông (PTIT)**.

Dự án được phát triển và tối ưu hóa dựa trên mẫu template thiệp mời gốc, lược bỏ các phần không cần thiết và Việt hóa hoàn toàn 100% với kiểu chữ viết tay nghệ thuật tinh tế.

---

## ✨ Tính Năng Nổi Bật

- ⏱️ **Đồng hồ đếm ngược:** Đếm ngược thời gian chính xác theo thời gian thực đến thời điểm khai mạc buổi lễ tốt nghiệp (09:00 ngày 23/05/2026). Các nhãn được Việt hóa hoàn toàn (*Ngày, Giờ, Phút, Giây*).
- 📅 **Thêm vào Google Calendar:** Tích hợp nút tạo nhanh sự kiện lịch Google Calendar với đầy đủ thông tin mô tả buổi lễ và vị trí được lập trình sẵn.
- 📍 **Bản đồ chỉ đường (Google Maps):** Nhúng bản đồ tương tác của PTIT và nút dẫn đường chi tiết bằng Google Maps.
- ✍️ **Font chữ viết tay nghệ thuật:** Sử dụng Google Fonts (`Great Vibes` và `Dancing Script`) hỗ trợ hoàn chỉnh bảng mã Tiếng Việt, loại bỏ hoàn toàn lỗi hiển thị ký tự đặc trưng.
- 📱 **Hỗ trợ đa thiết bị:** Giao diện tối ưu hiển thị mượt mà trên cả thiết bị di động (Mobile) lẫn máy tính (Desktop).

---

## 📂 Cấu Trúc Mã Nguồn

- **`index.html`**: File giao diện chính, chứa nội dung thiệp mời, thư chào mừng, bản đồ nhúng và thông tin thời gian.
- **`css/`**:
  - `menikah.css`: CSS tùy chỉnh phong cách giao diện, màu sắc hồng pastel quý phái, và liên kết font chữ Việt hóa.
  - `jquery.countdown.css`: CSS định dạng cho đồng hồ đếm ngược.
- **`js/`**:
  - `jquery.coundown.js`: Logic đếm ngược đã được sửa đổi và Việt hóa toàn diện các nhãn mặc định.
  - `menikah.js`: Các hiệu ứng chuyển động trượt mượt mà (smooth scrolling) và hiệu ứng ẩn/hiện menu trên di động.
- **`image/`**:
  - `bg.jpg`: Hình nền chính của banner phần đầu buổi lễ.
  - `divider-flowers-leaves.png`: Hoa văn trang trí chân trang đã được tối ưu kích thước thanh lịch.
  - `favicon.png`: Biểu tượng favicon nhỏ gọn hiển thị trên tab trình duyệt.

---

## 🚀 Cách Chạy Dự Án

Dự án là một trang web tĩnh (static website), do đó bạn không cần cài đặt môi trường phức tạp:
1. Tải toàn bộ mã nguồn về máy.
2. Click đúp chuột trực tiếp vào file `index.html` để mở thiệp mời trên bất kỳ trình duyệt nào (Chrome, Safari, Edge, Firefox, v.v.).

---

## 🎨 Cấu HÌnh Hình Nền Tùy Chỉnh

Nếu bạn muốn cập nhật hình ảnh cá nhân cho thiệp:
- **Hình nền Banner chính (`.hero`):** Lưu ảnh mới của bạn vào thư mục `image/bg.jpg` hoặc sửa đường dẫn trong [css/menikah.css](css/menikah.css) tại class `.hero`:
  ```css
  background: linear-gradient(rgba(153, 110, 109, 0.65), rgba(153, 110, 109, 0.65)), rgba(0, 0, 0, 0.55) url("../image/bg.jpg") no-repeat;
  ```
- **Hoa văn trang trí chân trang (`.section-light`):** Ảnh nằm tại `image/divider-flowers-leaves.png`, kích thước hiển thị được cấu hình tối ưu ở cuối file [css/menikah.css](css/menikah.css).
