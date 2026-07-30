---
title: "Tuần 5 - Thao tác DynamoDB & Tăng tốc web với CloudFront"
date: 2026-06-29
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
url: "/vi/1-worklog/1.5-week5/"
---

### Chủ đề tuần

Sử dụng NoSQL DynamoDB + Phân phối nội dung CloudFront & Route 53

### Mục tiêu tuần

* Thiết kế và tương tác CRUD dữ liệu thực tế trên bảng DynamoDB.
* Gắn domain và thiết lập mạng CDN để tăng tốc độ truy cập web.

### Lịch làm việc

| Ngày | Thứ | Mô tả công việc | Lab / Dự án |
| :--- | :--- | :--- | :--- |
| 29/06/2026 | Thứ 2 | Nghiên cứu cơ sở dữ liệu phi quan hệ DynamoDB. Tạo table và định nghĩa Key. | [Module: DynamoDB](https://cloudjourney.awsstudygroup.com/) |
| 30/06/2026 | Thứ 3 | Thực hành thao tác CRUD dữ liệu trên DynamoDB bằng console và script. | [Lab 09 - DynamoDB CRUD](https://cloudjourney.awsstudygroup.com/) |
| 01/07/2026 | Thứ 4 | Tìm hiểu dịch vụ DNS của AWS (Route 53). Khởi tạo Hosted Zone. | [Module: Route 53](https://cloudjourney.awsstudygroup.com/) |
| 02/07/2026 | Thứ 5 | Cấu hình CDN với Amazon CloudFront để tăng tốc độ phân phối nội dung từ S3. | [Lab 10 - CloudFront Setup](https://cloudjourney.awsstudygroup.com/) |
| 03/07/2026 | Thứ 6 | Trỏ domain từ Route 53 sang CloudFront. Tóm tắt nội dung đã thực hành trong tuần. | Báo cáo tiến độ |

### Kết quả mong đợi

* Thao tác thuần thục việc thêm/sửa/xóa item trong DynamoDB.
* Web tĩnh tải nhanh hơn nhờ được cache tại các edge locations của CloudFront.

### Tài liệu tham khảo Tuần 5

* [Lab 09 - Amazon DynamoDB](https://cloudjourney.awsstudygroup.com/)
* [Lab 10 - Route 53 & CloudFront](https://cloudjourney.awsstudygroup.com/)