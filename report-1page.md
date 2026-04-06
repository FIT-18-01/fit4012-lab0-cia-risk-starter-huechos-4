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
- Tài khoản đăng nhập của giảng viên và sinh viên

**CIA mapping:**
- Sự cố A -> Availability (A)
- Sự cố B -> Integrity (I)
- Sự cố C -> Confidentiality (C)

**Phân tích sự cố B:**
- Threat: Kẻ tấn công (hoặc người dùng nội bộ) cố ý thay đổi điểm số của sinh viên.
- Vulnerability: Hệ thống không kiểm soát tốt quyền truy cập hoặc không ghi lại lịch sử chỉnh sửa điểm.
- Mitigation: Áp dụng phân quyền chặt chẽ, bổ sung chức năng log lịch sử thay đổi điểm và xác thực hai lớp cho tài khoản giảng viên.

### 4. Kết luận ngắn
Bài lab giúp em hiểu rõ hơn về các khái niệm cơ bản trong an toàn thông tin như bộ ba CIA, threat, vulnerability và mitigation. Em nhận ra việc xác định đúng tài sản và phân tích đúng sự cố theo CIA là rất quan trọng để bảo vệ hệ thống. Phần khó nhất là phân tích chi tiết threat, vulnerability và đề xuất mitigation phù hợp cho từng tình huống thực tế. Khi phân tích một sự cố, cần chú ý xem xét cả nguyên nhân, hậu quả và các biện pháp phòng ngừa để đảm bảo hệ thống an toàn toàn diện.
