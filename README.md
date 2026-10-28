# Ứng Dụng Chấm Công Nhân Viên (Mobile App Flutter)

Hệ thống Quản trị & Chấm công Doanh nghiệp Đa nền tảng (Mobile App Flutter).  
- Họ tên sinh viên: **Trần Minh Khôi**  
- MSSV: **2380601106**  
- Lớp: **23DTHC3 - CNTT - HUTECH**  
- **Repository Backend (C# .NET 9)**: [https://github.com/tranminhkhoi291205/appCC.git](https://github.com/tranminhkhoi291205/appCC.git)

---

## 1. Danh Sách API Chính Thức & Dự Phòng

Ứng dụng hỗ trợ kết nối đa kênh linh hoạt, đảm bảo luôn luôn hoạt động trong mọi môi trường (qua Internet, mạng Wi-Fi LAN nội bộ hoặc máy ảo Android):

| Kênh kết nối | Mục đích | Base URL API | Swagger Documentation |
|---|---|---|---|
| **Conveyor Cloud (Internet)** | Chấm bài & truy cập từ xa qua mạng 4G/Internet | `https://smallgreycar40.conveyor.cloud/api/` | [Xem Swagger](https://smallgreycar40.conveyor.cloud/swagger/) |
| **Wi-Fi LAN (Dự phòng khuyên dùng khi Demo)** | Điện thoại & Laptop kết nối cùng 1 Wi-Fi, không lo mất mạng | `http://192.168.1.3:5145/api/` | `http://192.168.1.3:5145/swagger/` |
| **Android Emulator (Giả lập)** | Chạy máy ảo Android Studio trên cùng máy tính | `http://10.0.2.2:5145/api/` | `http://10.0.2.2:5145/swagger/` |
| **Localhost** | Chạy kiểm thử trên máy tính Windows | `http://localhost:5145/api/` | `http://localhost:5145/swagger/` |

> [!TIP]
> **Đổi API tức thì trên màn hình Đăng nhập:** Tại góc trên bên phải màn hình Đăng nhập của ứng dụng, nhấn vào biểu tượng **⚙️ (Bánh răng cài đặt)** để chọn nhanh giữa các kênh kết nối trên mà không cần phải cài đặt lại app.

Cấu hình mặc định trong file `.env`:
```env
BASE_URL=https://smallgreycar40.conveyor.cloud/api/
```

---

## 2. Tài khoản mẫu đăng nhập
- **Admin**: `admin` / `Admin@123` *(Chuyển hướng vào Trang Quản trị Doanh nghiệp)*
- **Quản lý**: `quanly01` / `QuanLy@123` *(Quản lý ca, duyệt phép)*
- **Nhân viên**: `nhanvien01` / `NhanVien@123` *(Vào Dashboard Chấm công cá nhân & Bảng lương dự kiến)*
- **Khách hàng**: `khachhang01` / `KhachHang@123` *(Vào Trang Thẻ khách / Đối tác)*

*(Tại màn hình Đăng nhập có các nút 1 chạm để điền nhanh các tài khoản trên)*

---

## 3. Cách chạy ứng dụng Flutter
1. Cài đặt thư viện:
   ```bash
   flutter pub get
   ```
2. Chạy ứng dụng trên thiết bị Android / Emulator / Windows:
   ```bash
   flutter run
   ```
