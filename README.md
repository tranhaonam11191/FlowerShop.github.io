# FlowerWeb

Landing page bán hoa tĩnh, không dùng PHP và không cần cài đặt thư viện.

## Sử dụng

Mở trực tiếp `index.html` bằng trình duyệt. Có thể triển khai toàn bộ thư mục lên GitHub Pages, Netlify hoặc bất kỳ static hosting nào.

Nội dung website nằm trong `data/flowers.js`. Chỉnh thông tin cửa hàng ở `site`; thêm danh mục trong `tabs`; mỗi bài viết/sản phẩm gồm `id`, `title`, `price`, `thumbnail` và `content`.

## Công cụ quản lý nội dung

Mở `tools/editor.html` bằng Chrome hoặc Edge. Tool cho phép chỉnh thông tin cửa hàng, thay ảnh, thêm/xóa menu và thêm/xóa bài viết. Nhấn **Lưu flowers.js** rồi chọn tệp `data/flowers.js`; nếu trình duyệt không hỗ trợ ghi trực tiếp, tool sẽ tải một tệp mới để thay thế thủ công.

### Kết nối Google Form

Trong phần **Thông tin cửa hàng** của tool, nhập URL Google Form và mã hai trường nhận tiêu đề, giá. Mã trường có dạng `entry.123456789` và có thể lấy từ đường dẫn **Nhận đường liên kết được điền sẵn** của Google Forms. Nút **Đặt hoa** sẽ mở form trong tab mới và truyền dữ liệu của sản phẩm vào hai trường này.

Mỗi bài viết có thêm trường **Link Zalo** và **Link Facebook**. Liên kết được hiển thị ở cuối bài viết khi có giá trị; trường để trống sẽ không xuất hiện trên website.
