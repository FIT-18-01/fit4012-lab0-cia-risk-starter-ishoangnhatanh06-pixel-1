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
Nếu là quản trị viên hệ thống, tôi sẽ ưu tiên xử lý vấn đề C trước tiên vì việc lộ danh sách điểm là vi phạm nghiêm trọng tính bảo mật và quyền riêng tư của sinh viên, gây hậu quả pháp lý khó lường. Sau đó, tôi sẽ giải quyết vấn đề B để ngăn chặn các sai sót về dữ liệu gốc, bảo vệ tính toàn vẹn và uy tín của hệ thống giáo dục. Cuối cùng mới là vấn đề A vì sự cố đăng nhập thuộc về tính sẵn sàng, thường có thể khắc phục tạm thời bằng các biện pháp kỹ thuật dự phòng nhanh chóng. Song song đó, tôi sẽ nâng cao hệ thống giám sát và thắt chặt phân quyền truy cập để phát hiện sớm các hành vi bất thường từ người dùng. Việc xây dựng quy trình vận hành rõ ràng và đào tạo đội ngũ là bước then chốt để đảm bảo hệ thống luôn hoạt động an toàn, chính xác và ổn định lâu dài.

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-A-B-I-C-C}

