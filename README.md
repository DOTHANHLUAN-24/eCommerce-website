# Website Thương Mại Điện Tử Sử Dụng Blazor & ASP.NET Core 8.0

## 1. Giới thiệu chung

Website thương mại điện tử là hệ thống cho phép người dùng **xem sản phẩm, đặt hàng và thanh toán trực tuyến**.  
Hệ thống được xây dựng theo kiến trúc **Client – Server**, trong đó:

- **Blazor** đảm nhiệm phần giao diện người dùng (Frontend)
- **ASP.NET Core 8.0 Web API** đảm nhiệm xử lý nghiệp vụ và dữ liệu (Backend)

Mục tiêu:
- Tách biệt frontend và backend
- Dễ bảo trì, mở rộng
- Phù hợp với các hệ thống web hiện đại

---

## 2. Công nghệ sử dụng

### 2.1 Frontend – Blazor

- Blazor WebAssembly
- .NET 8.0
- Razor Components
- HttpClient để gọi API
- Bootstrap / CSS

### 2.2 Backend – ASP.NET Core 8.0 Web API

- ASP.NET Core 8.0
- Entity Framework Core
- SQL Server
- RESTful API
- JWT Authentication

---

## 3. Kiến trúc hệ thống

Blazor WebAssembly  
↓ HTTP (JSON)  
ASP.NET Core 8.0 Web API  
↓  
Database

---

## 4. Chức năng hệ thống

### Khách hàng
- Xem, tìm kiếm sản phẩm
- Giỏ hàng
- Đặt hàng
- Đăng nhập / đăng ký

### Quản trị viên
- Quản lý sản phẩm
- Quản lý danh mục
- Quản lý đơn hàng
- Quản lý người dùng

---

## 5. API chính

- GET /api/products
- GET /api/products/{id}
- POST /api/orders
- POST /api/auth/login

---

## 6. Bảo mật

- JWT Token
- Authorize Attribute
- LocalStorage phía Blazor

---

## 7. Kết luận

Hệ thống Blazor kết hợp ASP.NET Core 8.0 Web API là giải pháp hiện đại, phù hợp cho học tập và triển khai thực tế.
