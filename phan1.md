Trong Spring Boot, rất nhiều cấu hình đã có sẵn dưới dạng:

Default Properties

Ví dụ mặc định:

Thuộc tính	Giá trị mặc định
Port	8080
Context Path	/
Logging	INFO
Embedded Server	Tomcat

Điều này giúp ứng dụng chạy được ngay mà gần như không cần cấu hình ban đầu

Spring Boot quản lý cấu hình mặc định như thế nào?

Spring Boot có cơ chế:

Auto Configuration
Externalized Configuration

Nó đọc cấu hình theo thứ tự ưu tiên từ:

application.properties
application.yml
Environment Variables
Command Line
Default Properties bên trong Spring Boot

Nếu bạn tự khai báo:

server.port=8081

thì giá trị này sẽ ghi đè mặc định 8080.

Tìm danh sách cấu hình ở đâu?

Bạn có thể xem toàn bộ danh sách tại:

Spring Boot Common Application Properties

Đây giống “bảng điều khiển trung tâm” của Spring Boot:

server
database
logging
security
mail
cache
multipart
jackson
thymeleaf
jpa

đều có thể cấu hình tại đây.