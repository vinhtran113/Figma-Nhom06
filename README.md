# Mô tả Usecase

## UC1. Đăng ký

| **Thuộc Tính**       | **Chi Tiết**                                                                                                      |
|----------------------|-------------------------------------------------------------------------------------------------------------------|
| **Use Case ID**       | UC_01                                                                                                             |
| **Name**              | Đăng ký                                                                                                           |
| **Goal**              | Cho phép người dùng đăng ký tài khoản để thực hiện đầy đủ chức năng trong ứng dụng.                               |
| **Actor(s)**          | Visitor                                                                                                           |
| **Pre-Condition(s)**  | N/A                                                                                                               |
| **Post-Condition(s)** | Nếu đăng ký thành công, dữ liệu tài khoản được thêm vào cơ sở dữ liệu.                                             |
| **Main Flow**         | Người dùng nhập thông tin đăng ký và nhấn "Đăng ký".                                                              |
| **Alternative Flow**  | Nếu người dùng nhấn "Đăng nhập" sẽ chuyển hướng đến Use Case "Đăng nhập".                                         |
| **Exception Flow**    | Nếu thông tin không hợp lệ (thiếu hoặc sai định dạng), hệ thống yêu cầu nhập lại thông tin.                       |
| **Post Success**      | Sau khi đăng ký thành công, người dùng được chuyển về trang chủ.                                                  |
