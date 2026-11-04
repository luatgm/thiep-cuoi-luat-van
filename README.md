# Website thiệp cưới Giáp Minh Luật & Đỗ Thị Vân

## Hai thiệp riêng
- `nha-trai.html`: thiệp mời nhà trai, lễ thành hôn 10:00 ngày 29/11/2026.
- `nha-gai.html`: thiệp mời nhà gái, lễ vu quy 07:00 ngày 29/11/2026.
- `index.html`: trang chọn thiệp nhà trai hoặc nhà gái.

## Cá nhân hóa tên khách mời
Mở một thiệp, kéo xuống phần "Tạo thiệp riêng cho khách mời", nhập tên và nhấn "Sao chép link thiệp cá nhân". Mỗi khách sẽ có URL riêng, ví dụ:
`nha-trai.html?to=Anh%20Nguyen%20Van%20A`
Bạn cũng có thể tự thêm `?to=Ten%20Khach` vào cuối đường link.

## Chạy thử
Mở `index.html` bằng trình duyệt. Google Fonts cần internet để tải kiểu chữ.

## Đưa lên GitHub Pages
1. Tạo repository mới, ví dụ `thiep-cuoi-luat-van`.
2. Tải toàn bộ nội dung ZIP lên repository, giữ nguyên cấu trúc thư mục.
3. Vào Settings → Pages → Deploy from a branch.
4. Chọn branch `main`, folder `/ (root)`, nhấn Save.
5. GitHub sẽ cấp link dạng `https://TEN-GITHUB.github.io/thiep-cuoi-luat-van/`.

## Lưu ý
- QR hai nhà được giữ trong `assets/qr-nha-trai.png` và `assets/qr-nha-gai.png`.
- Mã QR là ảnh người dùng cung cấp; hãy thử quét bằng điện thoại trước khi gửi khách.
- Chưa có ảnh cưới và website không sử dụng ảnh cô dâu chú rể.
- Các trang là hai thiệp riêng, không phải một trang tự động chọn theo địa chỉ khách.
