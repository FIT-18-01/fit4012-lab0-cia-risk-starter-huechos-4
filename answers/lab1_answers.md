# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Nguyễn Việt Hoàng

**MSSV:** 1871020253

**Lớp/Nhóm:** CNTT 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Dữ liệu điểm số của sinh viên
- Asset 2: Tài khoản đăng nhập của giảng viên và sinh viên
- Asset 3 (nếu có): Hệ thống máy chủ lưu trữ dữ liệu điểm

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Availability (A)
- Sự cố B -> Integrity (I)
- Sự cố C -> Confidentiality (C)

---

## 3. Phân tích sự cố B
- Threat: Kẻ tấn công (hoặc người dùng nội bộ) cố ý thay đổi điểm số của sinh viên.
- Vulnerability: Hệ thống không kiểm soát tốt quyền truy cập hoặc không ghi lại lịch sử chỉnh sửa điểm.
- Mitigation: Áp dụng phân quyền chặt chẽ, bổ sung chức năng log lịch sử thay đổi điểm và xác thực hai lớp cho tài khoản giảng viên.

---

## 4. Reflection
Nếu là quản trị viên hệ thống, em sẽ ưu tiên xử lý vấn đề về tính toàn vẹn dữ liệu (Integrity) trước, cụ thể là sự cố điểm bị thay đổi (sự cố B). Bởi vì khi điểm số bị thay đổi sai lệch, quyền lợi của sinh viên bị ảnh hưởng trực tiếp và có thể gây ra hậu quả nghiêm trọng về mặt học tập, tâm lý. Ngoài ra, việc mất toàn vẹn dữ liệu còn làm giảm uy tín của hệ thống và nhà trường. Sau đó, em sẽ tiếp tục xử lý các vấn đề về bảo mật thông tin (Confidentiality) và đảm bảo hệ thống luôn sẵn sàng phục vụ (Availability). Việc ưu tiên này giúp bảo vệ quyền lợi người dùng và duy trì niềm tin vào hệ thống.

---

## 5. Bonus (khuyến khích)
Flag: FIT4012{A-A-B-I-C-C}
