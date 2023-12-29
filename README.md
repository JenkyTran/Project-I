Xin chào, đây là kho lưu trữ bài tập lớn của Project I 
quanlythuchinhatro/
 │
 ├── src/main/java/com/example/cnpm/quanlythuchinhatro
 │   ├── config
 │   │   ├── SecurityConfig.java (Cấu hình bảo mật, ví dụ: cấu hình JWT, WebSecurity)
 │   │
 │   ├── controller
 │   │   ├── AuthController.java (Xử lý đăng nhập, đăng xuất, đăng ký)
 │   │   ├── UserController.java (Xử lý các yêu cầu liên quan đến người dùng)
 │   │
 │   ├── dto
 │   │   ├── LoginDto.java (Chứa thông tin đăng nhập)
 │   │   ├── RegisterDto.java (Chứa thông tin đăng ký)
 │   │   ├── UserDto.java (Chứa thông tin người dùng để trả về)
 │   │
 │   ├── filter
 │   │   ├── JwtRequestFilter.java (Bộ lọc JWT để xác thực các yêu cầu)
 │   │
 │   ├── model
 │   │   ├── User.java (Định nghĩa đối tượng người dùng)
 │   │   ├── Role.java (Định nghĩa vai trò người dùng)
 │   │
 │   ├── repository
 │   │   ├── UserRepository.java (Giao tiếp với cơ sở dữ liệu cho người dùng)
 │   │   ├── RoleRepository.java (Giao tiếp với cơ sở dữ liệu cho vai trò)
 │   │
 │   ├── service
 │   │   ├── UserService.java (Xử lý logic nghiệp vụ liên quan đến người dùng)
 │   │
 │   └── QuanLyThuChiNhaTroApplication.java (Lớp chính để chạy ứng dụng)
 │
 ├── src/main/resources/
 │   ├── application.properties (hoặc application.yml: Cấu hình ứng dụng)
 │   ├── static/ (Nếu có file tĩnh, ví dụ như HTML, CSS, JS)
 │   └── templates/ (Nếu sử dụng thymeleaf hoặc template engine khác)
 │
 ├── .gitignore (Định nghĩa các file và thư mục được git bỏ qua)
 ├── mvnw và mvnw.cmd (Wrapper cho Maven, giúp không cần cài đặt Maven)
 ├── README.md (Thông tin mô tả dự án)
 └── pom.xml (File cấu hình Maven cho dự án)
