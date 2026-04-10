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
Nếu là quản trị viên hệ thống, tôi sẽ ưu tiên xử lý sự cố B trước tiên
Vì sự cố B liên quan trực tiếp đến tính toàn vẹn (Integrity) của dữ liệu điểm số.
Việc thay đổi trái phép điểm số có thể dẫn đến hậu quả nghiêm trọng như mất niềm tin vào hệ thống.
Ngoài ra, nó có thể ảnh hưởng trực tiếp đến quyền lợi và tương lai của sinh viên trong quá trình học tập
So với tính khả dụng hay tính bảo mật, tính toàn vẹn thường được ưu tiên cao hơn trong giáo dục.
Điều này giúp đảm bảo sự công bằng và chính xác tuyệt đối cho toàn bộ hệ thống điểm số.
Việc xây dựng quy trình vận hành rõ ràng là bước then chốt để đảm bảo hệ thống luôn ổn định lâu dài.


## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-A-B-I-C-C}

