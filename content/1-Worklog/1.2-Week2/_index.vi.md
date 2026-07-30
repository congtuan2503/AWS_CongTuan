---
title: "Tuần 2 - Cấu hình mạng VPC & Khởi tạo máy chủ EC2"
date: 2026-06-08
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
url: "/vi/1-worklog/1.2-week2/"
---

### Chủ đề tuần

Triển khai hạ tầng mạng ảo VPC + Khởi chạy máy chủ ảo EC2

### Mục tiêu tuần

* Tự tay xây dựng được một mạng lưới VPC hoàn chỉnh với các kết nối Internet.
* Cấu hình và SSH thành công vào máy chủ EC2, cài đặt web server cơ bản.

### Lịch làm việc

| Ngày | Thứ | Mô tả công việc | Lab / Dự án |
| :--- | :--- | :--- | :--- |
| 08/06/2026 | Thứ 2 | Tìm hiểu kiến trúc mạng ảo Amazon VPC. Tính toán và chia IP CIDR. | [Module: Amazon VPC](https://cloudjourney.awsstudygroup.com/) |
| 09/06/2026 | Thứ 3 | Thực hành phân chia Public và Private Subnet. Gắn Internet Gateway cho Public Subnet. | [Lab 03 - VPC Configuration](https://cloudjourney.awsstudygroup.com/) |
| 10/06/2026 | Thứ 4 | Nghiên cứu dịch vụ tính toán Amazon EC2 và các loại AMI. | [Module: Amazon EC2](https://cloudjourney.awsstudygroup.com/) |
| 11/06/2026 | Thứ 5 | Khởi tạo máy chủ Ubuntu trên EC2. Cấu hình Security Group mở port 22 và 80. | [Lab 04 - Launch EC2](https://cloudjourney.awsstudygroup.com/) |
| 12/06/2026 | Thứ 6 | SSH vào server cài đặt Nginx/Apache. Kiểm tra truy cập web và tổng kết tuần 2. | Báo cáo tiến độ |

### Kết quả mong đợi

* Mạng VPC hoạt động trơn tru, định tuyến luồng traffic rõ ràng.
* EC2 instance được khởi chạy thành công, host được một trang HTML cơ bản.

### Tài liệu tham khảo Tuần 2

* [Lab 03 - Basic networking with Amazon VPC](https://cloudjourney.awsstudygroup.com/)
* [Lab 04 - Introduction to Amazon EC2](https://cloudjourney.awsstudygroup.com/)