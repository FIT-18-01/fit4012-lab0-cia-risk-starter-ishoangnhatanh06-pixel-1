# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Hoàng Nhật Anh

**MSSV:** 1871020064

**Lớp/Nhóm:** CNTT 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Dữ liệu điểm số của sinh viên (Student grades data)
- Asset 2: Thông tin xác thực người dùng (User authentication credentials)
- Asset 3 (nếu có): Hệ thống máy chủ lưu trữ dữ liệu (Server infrastructure)

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> A (Availability)
- Sự cố B -> I (Integrity)
- Sự cố C -> C (Confidentiality)

---

## 3. Phân tích sự cố B
- Threat: Thay đổi trái phép dữ liệu điểm số (Unauthorized modification of grades)
- Vulnerability: Kiểm soát truy cập không đủ mạnh hoặc thiếu ghi nhật ký kiểm tra (Weak access controls or lack of audit logging)
- Mitigation: Triển khai kiểm soát truy cập dựa trên vai trò (RBAC) và kích hoạt ghi nhật ký kiểm tra (Implement role-based access control and enable audit logging)

---

## 4. Reflection
Viết 5-7 dòng.
Nếu là quản trị viên hệ thống, tôi sẽ ưu tiên xử lý vấn đề C trước tiên vì đây là sự cố vi phạm tính bảo mật và ảnh hưởng đến quyền riêng tư của tập thể sinh viên.
Tiếp đến tôi sẽ giải quyết vấn đề B vì việc thay đổi điểm số là vi phạm tính toàn vẹn và gây mất niềm tin vào hệ thống đánh giá.
Cuối cùng tôi mới xử lý vấn đề A vì sự cố không đăng nhập được là vi phạm tính sẵn sàng và thường có thể khắc phục nhanh hơn bằng biện pháp dự phòng.
Tôi cũng sẽ xây dựng quy trình giám sát chặt chẽ để phát hiện và truy vết sự cố kịp thời.
Bên cạnh đó, đào tạo nhân viên vận hành và tài liệu hóa quy trình là cần thiết để ngăn chặn tái diễn.
Việc ưu tiên này dựa trên mức độ tác động thực tế đến người dùng và rủi ro danh tiếng của nhà trường.

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-A-B-I-C-C}

