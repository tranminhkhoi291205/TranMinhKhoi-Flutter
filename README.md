# Ứng Dụng Chấm Công Nhân Viên - Flutter Mobile App

Ứng dụng di động chấm công thông minh dành cho nhân viên và quản lý, xây dựng bằng Flutter.

## API Backend kết nối
- **Swagger Documentation**: [https://smallgreycar40.conveyor.cloud/swagger/](https://smallgreycar40.conveyor.cloud/swagger/)
- **Conveyor API URL**: `https://smallgreycar40.conveyor.cloud/api/`

## Tính năng chính
- Đăng nhập bảo mật 2 bước (Username/Password + OTP gửi về Email).
- Chấm công Check-in / Check-out linh hoạt bằng định vị GPS hoặc quét mã QR.
- Tự động kiểm tra khoảng cách đến cơ quan / phòng ban và phát hiện giả lập vị trí.
- Quản lý đơn nghỉ phép: Tạo đơn xin nghỉ phép, theo dõi tiến độ duyệt.
- Thống kê lịch sử chấm công, bảng công cá nhân.
- Hỗ trợ đổi cấu hình API trực tiếp ngay trên giao diện ứng dụng.

## Hướng dẫn chạy
1. Cài đặt các gói phụ thuộc:
   ```bash
   flutter pub get
   ```
2. Chạy ứng dụng trên máy ảo hoặc thiết bị thực tế:
   ```bash
   flutter run
   ```
