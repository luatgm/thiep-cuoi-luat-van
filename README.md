# Thiệp cưới Minh Luật & Đỗ Vân

- `index.html`: trang chọn thiệp nhà trai hoặc nhà gái.
- `nha-trai.html`: thiệp nhà trai riêng.
- `nha-gai.html`: thiệp nhà gái riêng.
- `tao-link.html`: công cụ riêng để gia đình tạo link có tên từng khách; không hiển thị trong nội dung thiệp.
- `assets/`: hai mã QR địa điểm.

Tên hiển thị trên thiệp đã chỉnh thành **Minh Luật & Đỗ Vân**. Phần tạo/sửa tên khách đã được bỏ khỏi thiệp gửi khách và chuyển sang trang riêng `tao-link.html`.

## Xuất bản GitHub Pages
Upload toàn bộ file và thư mục này vào thư mục gốc repository; vào Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.

Sau khi xuất bản:
- Trang chủ: `https://TEN-GITHUB.github.io/thiep-cuoi-luat-van/`
- Thiệp nhà trai: `.../nha-trai.html`
- Thiệp nhà gái: `.../nha-gai.html`
- Công cụ tạo link khách: `.../tao-link.html`

Mỗi link khách có tên riêng qua tham số `?to=Ten%20Khach`. QR là ảnh người dùng cung cấp; nên thử quét lại trước khi gửi khách.
