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
- Dữ liệu điểm số của sinh viên
- Thông tin xác thực người dùng

**CIA mapping:**
- Sự cố A -> A (Availability)
- Sự cố B -> I (Integrity)
- Sự cố C -> C (Confidentiality)

**Phân tích sự cố B:**
- Threat: Thay đổi trái phép dữ liệu điểm số
- Vulnerability: Kiểm soát truy cập không đủ mạnh
- Mitigation: Triển khai RBAC và ghi nhật ký kiểm tra 

### 4. Kết luận ngắn
Từ bài lab này, tôi học được cách áp dụng bộ ba CIA để phân tích các sự cố bảo mật trong hệ thống thông tin. Phần khó nhất là phân biệt rõ ràng giữa threat và vulnerability, vì chúng thường liên quan mật thiết. Khi phân tích một sự cố an toàn thông tin, cần chú ý đến tác động thực tế đối với người dùng và ưu tiên xử lý dựa trên mức độ nghiêm trọng, đồng thời luôn ghi lại nhật ký để theo dõi và cải thiện.
