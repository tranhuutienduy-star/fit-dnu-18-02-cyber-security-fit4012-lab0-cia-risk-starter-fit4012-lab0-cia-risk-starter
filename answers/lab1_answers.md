# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Trần Hữu Tiến Duy

**MSSV:** 1871020191

**Lớp/Nhóm:** CNTT 18-02

---

## 1. Assets
Asset 1: Dữ liệu điểm của sinh viên  
Asset 2: Tài khoản đăng nhập (giảng viên, sinh viên)  
Asset 3: Hệ thống máy chủ lưu trữ dữ liệu  

## 2. Mapping CIA
Sự cố A -> Availability  
Sự cố B -> Integrity  
Sự cố C -> Confidentiality  

## 3. Phân tích sự cố B
Threat: Người dùng trái phép (hacker hoặc nội bộ) chỉnh sửa điểm  
Vulnerability: Hệ thống không có kiểm soát quyền truy cập hoặc không ghi log thay đổi  
Mitigation: Áp dụng phân quyền (RBAC) và ghi log/audit mọi thay đổi dữ liệu  

## 4. Reflection
Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý sự cố B trước. Vì đây là vấn đề liên quan đến tính toàn vẹn dữ liệu (Integrity), ảnh hưởng trực tiếp đến kết quả học tập của sinh viên và uy tín của hệ thống. Nếu dữ liệu bị thay đổi sai lệch, hậu quả sẽ nghiêm trọng hơn so với việc hệ thống tạm thời không truy cập được. Sau đó, em sẽ xử lý sự cố C để đảm bảo bảo mật dữ liệu và cuối cùng là cải thiện hệ thống để tránh lỗi Availability như sự cố A.

## 5. Bonus Flag
FIT4012{A-A-B-I-C-C}
