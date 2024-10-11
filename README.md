# E-commerce Pet Project

## Mục đích dự án

Dự án này được phát triển với mục đích học hỏi và phát triển kỹ năng trong việc xây dựng các hệ thống e-commerce. Thông qua dự án này, tôi muốn nắm vững các khía cạnh như xây dựng API, quản lý cơ sở dữ liệu, làm việc với backend và frontend, cùng với việc hiểu rõ các use case thực tế trong một hệ thống thương mại điện tử.

### Các kỹ năng học hỏi:

- Xây dựng kiến trúc hệ thống backend.
- Phát triển API RESTful.
- Quản lý dữ liệu trong cơ sở dữ liệu quan hệ.
- Tích hợp giữa frontend và backend.
- Tìm hiểu về quy trình xử lý thanh toán, giao hàng, và quản lý đơn hàng.
- Phát triển hệ thống người dùng, đăng ký, đăng nhập và quản lý tài khoản.

## Các Use Case Chính

### 1. Customer -> Tìm kiếm sản phẩm
- **Mô tả**: Khách hàng có thể tìm kiếm sản phẩm bằng cách nhập từ khóa liên quan vào thanh tìm kiếm. Hệ thống sẽ trả về danh sách các sản phẩm phù hợp với từ khóa đã nhập.
- **Mục tiêu**: Giúp khách hàng nhanh chóng tìm thấy sản phẩm họ cần.

### 2. Customer -> Xem chi tiết sản phẩm
- **Mô tả**: Khách hàng có thể nhấp vào một sản phẩm cụ thể để xem thông tin chi tiết bao gồm mô tả, giá, hình ảnh, và đánh giá từ người dùng khác.
- **Mục tiêu**: Cung cấp thông tin đầy đủ về sản phẩm giúp khách hàng đưa ra quyết định mua hàng.

### 3. Customer -> Thêm sản phẩm vào giỏ hàng
- **Mô tả**: Khách hàng có thể chọn một sản phẩm và thêm nó vào giỏ hàng của mình để mua sau.
- **Mục tiêu**: Hỗ trợ khách hàng lưu lại các sản phẩm yêu thích để chuẩn bị thanh toán.

### 4. Customer -> Thanh toán đơn hàng
- **Mô tả**: Khách hàng sẽ hoàn tất việc mua hàng bằng cách thanh toán các sản phẩm trong giỏ hàng của mình. Hệ thống sẽ xử lý thông tin giao hàng và thanh toán qua các phương thức khác nhau (thẻ tín dụng, ví điện tử...).
- **Mục tiêu**: Hoàn tất quá trình mua hàng của khách hàng.

### 5. Customer -> Đăng ký tài khoản
- **Mô tả**: Khách hàng có thể đăng ký tài khoản mới bằng cách cung cấp thông tin cá nhân như email, mật khẩu, và địa chỉ.
- **Mục tiêu**: Tạo tài khoản để theo dõi đơn hàng và nhận thông tin khuyến mãi.

### 6. Customer -> Đăng nhập tài khoản
- **Mô tả**: Khách hàng có thể đăng nhập vào tài khoản đã đăng ký để xem lịch sử mua hàng, theo dõi đơn hàng, và cập nhật thông tin cá nhân.
- **Mục tiêu**: Quản lý tài khoản và thông tin cá nhân.

### 7. Customer -> Theo dõi đơn hàng
- **Mô tả**: Khách hàng có thể theo dõi trạng thái đơn hàng của mình (đã đặt hàng, đang giao, đã giao).
- **Mục tiêu**: Giúp khách hàng nắm rõ tình trạng của đơn hàng sau khi mua.

### 8. Customer -> Viết đánh giá sản phẩm
- **Mô tả**: Sau khi mua sản phẩm, khách hàng có thể để lại đánh giá về sản phẩm đó, bao gồm số sao và nhận xét chi tiết.
- **Mục tiêu**: Cung cấp trải nghiệm thực tế cho các khách hàng khác và cải thiện uy tín sản phẩm.

### 9. Admin -> Quản lý sản phẩm
- **Mô tả**: Admin có thể thêm mới, chỉnh sửa hoặc xóa sản phẩm khỏi hệ thống.
- **Mục tiêu**: Đảm bảo hệ thống luôn cập nhật với các sản phẩm mới và thông tin sản phẩm chính xác.

### 10. Admin -> Quản lý đơn hàng
- **Mô tả**: Admin có thể theo dõi và quản lý các đơn hàng, bao gồm xử lý các yêu cầu, kiểm tra thanh toán và cập nhật trạng thái giao hàng.
- **Mục tiêu**: Đảm bảo quy trình xử lý đơn hàng diễn ra suôn sẻ.

### 11. Admin -> Quản lý khách hàng
- **Mô tả**: Admin có thể xem và quản lý thông tin tài khoản của khách hàng, bao gồm khóa tài khoản hoặc hỗ trợ các vấn đề liên quan đến tài khoản.
- **Mục tiêu**: Đảm bảo trải nghiệm tốt nhất cho khách hàng và duy trì hệ thống an toàn.

### 12. Admin -> Tạo mã khuyến mãi
- **Mô tả**: Admin có thể tạo và quản lý mã khuyến mãi cho khách hàng.
- **Mục tiêu**: Thúc đẩy doanh số thông qua các chương trình khuyến mãi.

### 13. Supplier -> Cập nhật tồn kho sản phẩm
- **Mô tả**: Nhà cung cấp có thể cập nhật số lượng tồn kho sản phẩm sau mỗi đợt nhập hàng.
- **Mục tiêu**: Đảm bảo dữ liệu tồn kho chính xác cho quá trình mua bán.

### 14. Delivery Partner -> Cập nhật trạng thái giao hàng
- **Mô tả**: Đối tác giao hàng có thể cập nhật trạng thái đơn hàng từ lúc lấy hàng đến khi giao hàng cho khách.
- **Mục tiêu**: Đảm bảo khách hàng và hệ thống đều nắm rõ tình trạng giao hàng.
