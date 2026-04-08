# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Đào Văn Minh

**MSSV:** 1871020390

**Lớp/Nhóm:** CNTT18-02

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

Asset 1: Bảng điểm sinh viên
Asset 2: Tài khoản giảng viên
Asset 3: Cơ sở dữ liệu hệ thống

## 2. Mapping CIA
Ghép từng sự cố với CIA.

Sự cố A → Availability (không đăng nhập được hệ thống)
Sự cố B → Integrity (điểm bị sửa từ 8.0 → 5.0)
Sự cố C → Confidentiality (lộ thông tin sinh viên)

## 3. Phân tích sự cố B
-Threat:
Người dùng trái phép hoặc giảng viên sửa điểm sai quyền
-Vulnerability:
Mật khẩu yếu
Phân quyền chưa rõ ràng
Không có log theo dõi thay đổi điểm
-Mitigation:
Áp dụng MFA (xác thực nhiều lớp)
Phân quyền rõ ràng (role-based)
Ghi log tất cả thay đổi điểm
Yêu cầu xác nhận/phê duyệt khi sửa điểm
## 4. Reflection
Nếu là quản trị viên, em sẽ ưu tiên xử lý vấn đề liên quan đến Integrity trước, cụ thể là việc sửa điểm sai. Vì điểm số ảnh hưởng trực tiếp đến kết quả học tập và quyền lợi của sinh viên nên nếu bị thay đổi sẽ gây hậu quả nghiêm trọng. Sau đó, em sẽ cải thiện hệ thống xác thực và phân quyền để ngăn chặn truy cập trái phép. Đồng thời, đảm bảo hệ thống luôn hoạt động ổn định để tránh gián đoạn (Availability). Cuối cùng, tăng cường bảo mật dữ liệu để tránh rò rỉ thông tin cá nhân. Việc kết hợp các biện pháp này giúp hệ thống an toàn và đáng tin cậy hơn.

## 5. Bonus Flag
A = Availability → A
B = Integrity → I
C = Confidentiality → C

