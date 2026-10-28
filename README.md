# Ứng Dụng Chấm Công Nhân Viên (Mobile App Flutter)

Hệ thống Quản trị & Chấm công Doanh nghiệp Đa nền tảng (Mobile App Flutter).  
- Họ tên sinh viên: **Trần Minh Khôi**  
- MSSV: **2380601106**  
- Lớp: **23DTHC3 - CNTT - HUTECH**  
- **Repository Backend (C# .NET 9)**: [https://github.com/tranminhkhoi291205/TranMinhKhoi.git](https://github.com/tranminhkhoi291205/TranMinhKhoi.git)

---

## 1. API Chính Thức

| Kênh kết nối | Base URL API | Swagger Documentation |
|---|---|---|
| **Conveyor Cloud (Internet)** | `https://smallgreycar40.conveyor.cloud/api/` | [Xem Swagger](https://smallgreycar40.conveyor.cloud/swagger/) |

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
