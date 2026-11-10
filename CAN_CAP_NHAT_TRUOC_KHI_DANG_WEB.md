# Thông tin chuyển đổi website sang người phụ trách mới

Đã cập nhật toàn bộ thông tin liên hệ từ phiên bản gốc trong website này:

- **Người phụ trách:** Đỗ Quốc Hậu
- **Hotline / Zalo:** 0922396033
- **Gọi điện:** `tel:0922396033`
- **Zalo:** `https://zalo.me/0922396033` (chỉ hoạt động nếu số này đã đăng ký Zalo)

## Quan trọng: việc còn cần tự xác nhận

1. **Biểu mẫu khách hàng / Google Sheets:** URL Google Apps Script của người vận hành cũ đã được gỡ để tránh gửi dữ liệu khách đến tài khoản lạ. Form sẽ thông báo chưa kết nối và dẫn người dùng sang Hotline/Zalo. Để kích hoạt, tạo Google Sheet và Apps Script **thuộc tài khoản Google của Đỗ Quốc Hậu** theo `docs/HUONG_DAN_GOOGLE_SHEETS.md`, sau đó dán URL web app vào hằng số `GOOGLE_SHEET_WEBAPP_URL` trong `index.html`. Chỉ khi đó mới bắt đầu thu nhận dữ liệu từ form.
2. **Email:** đã loại địa chỉ `admin@50kuser.com` khỏi trang công khai vì không được xác nhận là email của Đỗ Quốc Hậu. Nếu có email riêng, bổ sung vào trang chủ và các trang chính sách.
3. **Địa chỉ:** đã bỏ địa chỉ văn phòng cũ tại Tân Bình. Chỉ thêm địa chỉ mới nếu là địa chỉ có thật và được phép công khai.
4. **Tên miền / SEO:** đã gỡ canonical, URL Open Graph, URL hình Open Graph và sitemap trỏ về GitHub của người khác. Khi có tên miền chính thức, bổ sung lại canonical, `og:url`, `og:image`, Twitter image và tạo sitemap.xml từ tên miền mới; cập nhật `robots.txt` nếu cần.
5. **Tài khoản ngân hàng / hóa đơn:** phiên bản gốc không có số tài khoản cụ thể, nhưng có nội dung về địa điểm thu tiền và hóa đơn VAT. Đã sửa thành hướng dẫn liên hệ trực tiếp để xác minh, không tự nhận người phụ trách có tư cách xuất hóa đơn hoặc sở hữu tài khoản công ty.
6. **Liên kết đơn vị khác:** các liên kết quảng bá ngoài website tới `500kuser.com` và `faceseo.vn` đã thay bằng nút Hotline/Zalo hoặc liên kết nội bộ để không chuyển khách sang website chưa xác nhận quyền quản lý. Tên thương hiệu **500KUSER** và nội dung dịch vụ được giữ nguyên, vì chưa có yêu cầu đổi tên thương hiệu.
7. **Nội dung cam kết/chính sách:** cần người vận hành rà soát tính đúng đắn của cam kết dịch vụ, hoàn tiền, bảo hành, bảo mật và việc tuân thủ chính sách của Google trước khi xuất bản. Việc sửa thông tin liên hệ không xác nhận tính pháp lý của các cam kết.
8. **Triển khai:** đây là bản mã nguồn ZIP đã được sửa, **không** tự cập nhật website đang chạy trên mạng.

Có thể mở `index.html` để kiểm tra bản giao diện cục bộ. Các trang chính sách nằm trong thư mục `pages`.
