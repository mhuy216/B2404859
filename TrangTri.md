# 🚗 Hệ Thống Quản Lý Và Cho Thuê Xe Trực Tuyến (Car Rental Management System)

[![PHP Version](https://img.shields.io/badge/PHP-%5E8.0-blue.svg)](https://php.net/)
[![MySQL](https://img.shields.io/badge/Database-MySQL-orange.svg)](https://www.mysql.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Đồ án môn học **Phát triển hệ thống web** (Mã HP: CT299). Hệ thống hỗ trợ khách hàng tìm kiếm, đặt xe trực tuyến và cung cấp các công cụ quản lý toàn diện cho Quản trị viên (Admin).

---

## 👥 Thành Viên Nhóm (Nhóm 6)

| STT | Họ và Tên | MSSV | Vai trò & Nhiệm vụ chính |
| :---: | :--- | :---: | :--- |
| 1 | Nguyen Minh Huy| B2404859 | Thiết kế CSDL, Lập trình Trang chủ, Đăng nhập/Đăng ký |
| 2 | Nguyen Trong Vy | B204890 | Phân tích hệ thống, Lập trình Phân hệ Khách hàng |
| 3 | Duong Thanh Tuan | B2404xxx | Xây dựng Sơ đồ Use Case, Lập trình Quản lý xe & Dịch vụ |
| 4 | Doan Huu Thien | B2404xxx | Đặc tả Use Case, Lập trình Quản lý đơn đặt xe & Thống kê |

---

## 📋 Mục Lục
1. [Giới thiệu đề tài](#-giới-thiệu-đề-tài)
2. [Tính năng chính của hệ thống](#-tính-năng-chính-của-hệ-thống)
3. [Công nghệ sử dụng](#-công-nghệ-sử-dụng)
4. [Cài đặt và Chạy chương trình](#-cài-đặt-và-chạy-chương-trình)
5. [Cấu trúc cơ sở dữ liệu](#-cấu-trúc-cơ-sở-dữ-liệu)

---

## 📖 1. Giới thiệu đề tài
Hệ thống được xây dựng nhằm đáp ứng nhu cầu thuê xe trực tuyến ngày càng phổ biến của các cửa hàng quy mô vừa và nhỏ. 
* **Đối với Khách hàng:** Dễ dàng tra cứu thông tin xe theo hãng, số chỗ, mức giá; xem lịch trình chi tiết, đặt xe nhanh chóng và lựa chọn các dịch vụ phụ trợ đi kèm.
* **Đối với Quản trị viên (Admin):** Cung cấp giao diện quản lý tập trung giúp kiểm soát kho xe, duyệt đơn thuê, quản lý thông tin khách hàng và xem báo cáo thống kê doanh thu trực quan.

---

## ⚙️ 2. Tính năng chính của hệ thống

### 👤 Phân hệ Khách hàng (Client)
* **Xác thực tài khoản:** Đăng ký tài khoản mới, đăng nhập, đổi mật khẩu và cập nhật thông tin cá nhân.
* **Tìm kiếm và Lọc xe:** Tìm kiếm xe theo từ khóa, lọc theo khoảng giá, dòng xe (4 chỗ, 7 chỗ) hoặc hãng xe.
* **Đặt xe & Thanh toán:** Chọn thời gian nhận/trả xe, tích hợp dịch vụ phụ trợ, bảo hiểm và chọn hình thức thanh toán (Tiền mặt hoặc Chuyển khoản QR).
* **Đánh giá dịch vụ:** Gửi phản hồi và chấm sao cho chuyến đi sau khi hoàn thành.

### 🛠️ Phân hệ Quản trị (Admin)
* **Quản lý phương tiện:** Thêm mới, chỉnh sửa thông tin, cập nhật hình ảnh và trạng thái xe (Sẵn sàng, Đang cho thuê, Bảo trì).
* **Quản lý dịch vụ phụ trợ:** Thêm, sửa, xóa các dịch vụ đi kèm (Ghế trẻ em, GPS, tài xế riêng,...).
* **Quản lý đơn thuê xe:** Duyệt đơn, cập nhật trạng thái đơn (Chờ duyệt, Đang giao xe, Đã hoàn tất, Đã hủy).
* **Quản lý người dùng:** Quản lý danh sách khách hàng thành viên và phân quyền hệ thống.
* **Báo cáo thống kê:** Thống kê doanh thu theo thời gian và tần suất dòng xe được thuê nhiều nhất.

---

## 💻 3. Công nghệ sử dụng
* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap / W3.CSS.
* **Backend:** PHP (Pure PHP / MVC tùy cấu trúc nhóm).
* **Database:** MySQL (Quản trị qua XAMPP / phpMyAdmin).
* **Công cụ hỗ trợ:** StarUML (Vẽ sơ đồ Use Case, ERD), Git / GitHub (Quản lý mã nguồn).

---

## 🚀 4. Cài đặt và Chạy chương trình

Yêu cầu máy tính đã cài đặt sẵn **XAMPP** (hoặc ứng dụng Server tương tự hỗ trợ Apache và MySQL).

1. **Clone repository về máy:**
   ```bash
   git clone [https://github.com/ten-tai-khoan/ten-repository.git](https://github.com/ten-tai-khoan/ten-repository.git)
