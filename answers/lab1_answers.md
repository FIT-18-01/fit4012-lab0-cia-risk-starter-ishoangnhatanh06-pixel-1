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

Nếu là quản trị viên hệ thống, tôi sẽ ưu tiên xử lý vấn đề C (vi phạm tính bảo mật) trước tiên. Lý do là vì việc lộ danh sách điểm ảnh hưởng đến quyền riêng tư của tất cả sinh viên, có thể dẫn đến hậu quả nghiêm trọng như bị đe dọa hoặc phân biệt đối xử. Tiếp theo là vấn đề B (vi phạm tính toàn vẹn), vì việc thay đổi điểm số có thể làm mất niềm tin vào hệ thống và ảnh hưởng trực tiếp đến kết quả học tập của sinh viên. Cuối cùng là vấn đề A (vi phạm tính sẵn sàng), mặc dù quan trọng nhưng có thể khắc phục nhanh chóng hơn và ít gây thiệt hại lâu dài hơn. Việc ưu tiên này dựa trên mức độ tác động và rủi ro đối với người dùng và tổ chức.

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-A-B-I-C-C}

