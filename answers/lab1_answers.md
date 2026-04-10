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
Nếu là quản trị viên hệ thống, tôi sẽ ưu tiên xử lý vấn đề C trước tiên vì khi danh sách điểm bị lộ, đó là sự cố vi phạm tính bảo mật và quyền riêng tư của toàn bộ sinh viên, dễ dẫn đến mất uy tín và hậu quả pháp lý cho trường. Sau đó, tôi sẽ xử lý vấn đề B vì thay đổi điểm số là sự cố vi phạm tính toàn vẹn, trực tiếp làm mất niềm tin và công bằng trong hệ thống đánh giá học tập. Cuối cùng mới là vấn đề A vì sự cố về đăng nhập ảnh hưởng tính sẵn sàng, thường có thể khắc phục nhanh hơn bằng kiểm soát tải và dự phòng truy cập. Tôi cũng sẽ tăng cường giám sát, đào tạo nhân sự và xây dựng quy trình vận hành rõ ràng để ngăn chặn tái diễn.

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-A-B-I-C-C}

