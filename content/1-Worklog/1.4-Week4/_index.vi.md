---
title: "Tuần 4 - Xây dựng API Serverless với Lambda & API Gateway"
date: 2026-06-22
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
url: "/vi/1-worklog/1.4-week4/"
---

### Chủ đề tuần

Triển khai tính toán Serverless + Cấu hình Cổng API

### Mục tiêu tuần

* Tự tay viết và deploy các đoạn code xử lý sự kiện lên AWS Lambda.
* Xuất bản các API RESTful để tương tác với Lambda thông qua API Gateway.

### Lịch làm việc

| Ngày | Thứ | Mô tả công việc | Lab / Dự án |
| :--- | :--- | :--- | :--- |
| 22/06/2026 | Thứ 2 | Tìm hiểu mô hình điện toán Serverless trên AWS. Đọc tài liệu Lambda. | [Module: Serverless](https://cloudjourney.awsstudygroup.com/) |
| 23/06/2026 | Thứ 3 | Viết function xử lý dữ liệu đầu tiên với AWS Lambda (Node.js/Python). Test log trên CloudWatch. | [Lab 07 - Lambda Function](https://cloudjourney.awsstudygroup.com/) |
| 24/06/2026 | Thứ 4 | Học cách tạo RESTful API với API Gateway. Tạo các methods (GET, POST). | [Module: API Gateway](https://cloudjourney.awsstudygroup.com/) |
| 25/06/2026 | Thứ 5 | Test luồng kết nối từ API Gateway gọi đến Lambda. Dùng Postman để verify response. | [Lab 08 - Build API](https://cloudjourney.awsstudygroup.com/) |
| 26/06/2026 | Thứ 6 | Deploy API lên stage (dev/prod). Cập nhật worklog tuần 4. | Báo cáo tiến độ |

### Kết quả mong đợi

* Function Lambda chạy ổn định, trả về kết quả chính xác theo input.
* API endpoint public có thể gọi được từ bên ngoài và định tuyến đúng vào Lambda.

### Tài liệu tham khảo Tuần 4

* [Lab 07 & 08 - Serverless and API Management](https://cloudjourney.awsstudygroup.com/)