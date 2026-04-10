# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Dữ liệu điểm của sinh viên
- Tài khoản đăng nhập của giảng viên và sinh viên
- Hệ thống máy chủ và ứng dụng quản lý điểm

  

**CIA mapping:**
- Sự cố A -> Availability (A)
- Sự cố B -> Integrity (I)
- Sự cố C -> Confidentiality (C)

**Phân tích sự cố B:**
- Threat: Người dùng trái phép chỉnh sửa dữ liệu điểm
- Vulnerability: Hệ thống thiếu kiểm soát quyền truy cập hoặc không có cơ chế ghi log
- Mitigation: Áp dụng phân quyền người dùng rõ ràng và ghi log/audit mọi thay đổi dữ liệu

### 4. Kết luận ngắn
(4-6 dòng: em học được gì từ bài lab này, phần nào khó nhất, điều gì cần chú ý khi phân tích một sự cố an toàn thông tin.)
Qua bài lab, em hiểu rõ hơn về mô hình CIA và cách áp dụng vào phân tích hệ thống thực tế.
Em cũng phân biệt được sự khác nhau giữa threat và vulnerability.
Phần khó nhất là xác định đúng loại sự cố thuộc CIA nào.
Khi phân tích an toàn thông tin, cần xem xét cả nguyên nhân và cách phòng tránh.
Bài lab giúp em làm quen với quy trình bảo mật và sử dụng GitHub trong học tập.
