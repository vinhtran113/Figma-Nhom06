# Mô tả Usecase

## UC1. Đăng ký

| **Use Case ID**       | UC_01                                                                                                             |
|----------------------|-------------------------------------------------------------------------------------------------------------------|
| **Name**              | Đăng ký                                                                                                           |
| **Goal**              | Cho phép người dùng đăng ký tài khoản để thực hiện đầy đủ chức năng trong ứng dụng.                               |
| **Actor(s)**          | Visitor                                                                                                           |
| **Pre-Condition(s)**  | N/A                                                                                                               |
| **Post-Condition(s)** | Nếu đăng ký thành công, dữ liệu tài khoản được thêm vào cơ sở dữ liệu.                                             |
| **Main Flow**         |  1. Tại trang chủ, Actors chọn biểu tượng tài khoản. <br> 2. Ứng dụng chuyển sang “Thông tin cá nhân”. <br> 3. Actors nhấn vào nút “Đăng nhập”. <br> 4. Ứng dụng chuyển hướng đến trang đăng nhập, tại đây Actors chọn vào “Đăng ký”. <br> 5. Ứng dụng chuyển sang trang đăng ký, bao gồm nút "Đăng nhập" và các trường thông tin trống bao gồm: Tên, Họ, Email, Mật Khẩu và Checkbox Chính sách bảo mật và Điều khoản sử dụng. <br> 6. Actors nhập các trường thông tin và nhấn tích vào ô Checkbox. <br> 7. Actors nhấn vào nút “Đăng ký”. <br> 8. Hệ thống kiểm tra thông tin Actors nhập. <br> 9. Ứng dụng chuyển đến trang điền thông tin cá nhân của Actors với các trường thông tin trống bao gồm: Giới tính, Sinh nhật, Cân nặng, Chiều cao. <br> 10. Actors nhập các trường thông tin. <br> 11. Actors nhấn nút “Xác nhận”. <br> 12. Hệ thống kiểm tra thông tin. <br> 13. Ứng dụng chuyển đến trang đăng ký thành công. <br> 14. Actors nhấn vào nút “Trở về trang chủ”. <br> 15. Ứng dụng chuyển hướng Actors đến trang chủ. |                                                              
| **Alternative Flow**  | 5.1. Actors nhấn vào “Đăng nhập” → UC_02 (A) (Đăng nhập).                                                       |
| **Exception Flow**    |  8.1. Một trong các trường thông tin bị bỏ trống thì hiển thị thông báo yêu cầu Actors nhập đầy đủ thông tin → Quay lại bước 5. <br> 8.2. Một trong các trường thông tin không đúng định dạng thì hiển thị thông báo yêu cầu nhập lại → Quay lại bước 5. <br> 8.3. Email đã tồn tại trong hệ thống thì hiển thị thông báo yêu cầu thay đổi email → Quay lại bước 4. <br> 12.1. Một trong các trường thông tin bị bỏ trống thì hiển thị thông báo yêu cầu Actors nhập đầy đủ thông tin → Quay lại bước 9. <br> 12.2. Một trong các trường thông tin không yêu cầu thì hiển thị thông báo yêu cầu nhập lại → Quay lại bước 9. |

