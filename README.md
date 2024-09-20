# Hình giao diện

## Onboarding

![Onboarding](image/onboarding.png)
![Onboarding](image/onboarding1.png)
![Onboarding](image/onboarding2.png)
![Onboarding](image/onboarding3.png)
![Onboarding](image/onboarding4.png)
![Onboarding](image/onboarding5.png)

## Sign up, Login and Reset Password 

![Lg](image/lg.png)
![Lg](image/lg1.png)
![Lg](image/lg2.png)
![Lg](image/lg3.png)
![Lg](image/lg4.png)
![Lg](image/lg5.png)
![Lg](image/lg6.png)
![Lg](image/lg7.png)

## Dashboard

![Db](image/db.png)
![Db](image/db1.png)
![Db](image/db2.png)
![Db](image/db3.png)
![Db](image/db4.png)
![Db](image/db5.png)

## Workout Tracker

![Wt](image/wt.png)
![Wt](image/wt1.png)
![Wt](image/wt2.png)
![Wt](image/wt3.png)
![Wt](image/wt4.png)
![Wt](image/wt5.png)

## Meal Planner

![Mp](image/mp.png)
![Mp](image/mp1.png)
![Mp](image/mp2.png)
![Mp](image/mp3.png)

## Sleep Tracker

![St](image/st.png)
![St](image/st1.png)
![St](image/st2.png)

## Progress Tracker

![Pt](image/pt.png)
![Pt](image/pt1.png)
![Pt](image/pt2.png)
![Pt](image/pt3.png)
![Pt](image/pt4.png)


# Mô tả Usecase

## Tổng quan usecase

![Usecase](image/Usecase.png)

### UC1. Đăng ký

| **Thuộc Tính**       | **Chi Tiết**                                                                                                      |
|----------------------|-------------------------------------------------------------------------------------------------------------------|
| **Use Case ID**       | UC_01                                                                                                             |
| **Name**              | Đăng ký                                                                                                           |
| **Goal**              | Cho phép người dùng đăng ký tài khoản để thực hiện đầy đủ chức năng trong ứng dụng.                               |
| **Actor(s)**          | Visitor                                                                                                           |
| **Pre-Condition(s)**  | N/A                                                                                                               |
| **Post-Condition(s)** | Nếu đăng ký thành công, dữ liệu tài khoản được thêm vào cơ sở dữ liệu.                                             |
| **Main Flow**         |  1. Tại trang chủ, Actors chọn biểu tượng tài khoản. <br> 2. Ứng dụng chuyển sang “Thông tin cá nhân”. <br> 3. Actors nhấn vào nút “Đăng nhập”. <br> 4. Ứng dụng chuyển hướng đến trang đăng nhập, tại đây Actors chọn vào “Đăng ký”. <br> 5. Ứng dụng chuyển sang trang đăng ký, bao gồm nút "Đăng nhập" và các trường thông tin trống bao gồm: Tên, Họ, Email, Mật Khẩu và Checkbox Chính sách bảo mật và Điều khoản sử dụng. <br> 6. Actors nhập các trường thông tin và nhấn tích vào ô Checkbox. <br> 7. Actors nhấn vào nút “Đăng ký”. <br> 8. Hệ thống kiểm tra thông tin Actors nhập. <br> 9. Ứng dụng chuyển đến trang điền thông tin cá nhân của Actors với các trường thông tin trống bao gồm: Giới tính, Sinh nhật, Cân nặng, Chiều cao. <br> 10. Actors nhập các trường thông tin. <br> 11. Actors nhấn nút “Xác nhận”. <br> 12. Hệ thống kiểm tra thông tin. <br> 13. Ứng dụng chuyển đến trang đăng ký thành công. <br> 14. Actors nhấn vào nút “Trở về trang chủ”. <br> 15. Ứng dụng chuyển hướng Actors đến trang chủ. |                                                              
| **Alternative Flow**  | 5.1. Actors nhấn vào “Đăng nhập” → UC_02 (A) (Đăng nhập).                                                       |
| **Exception Flow**    |  8.1. Một trong các trường thông tin bị bỏ trống thì hiển thị thông báo yêu cầu Actors nhập đầy đủ thông tin → Quay lại bước 5. <br> 8.2. Một trong các trường thông tin không đúng định dạng thì hiển thị thông báo yêu cầu nhập lại → Quay lại bước 5. <br> 8.3. Email đã tồn tại trong hệ thống thì hiển thị thông báo yêu cầu thay đổi email → Quay lại bước 4. <br> 12.1. Một trong các trường thông tin bị bỏ trống thì hiển thị thông báo yêu cầu Actors nhập đầy đủ thông tin → Quay lại bước 9. <br> 12.2. Một trong các trường thông tin không yêu cầu thì hiển thị thông báo yêu cầu nhập lại → Quay lại bước 9. |

