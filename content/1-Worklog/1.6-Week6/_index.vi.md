---
title: "Tuần 6 - Giám sát hệ thống CloudWatch & Tự động hóa CloudFormation"
date: 2026-07-06
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
url: "/vi/1-worklog/1.6-week6/"
---

### Chủ đề tuần

Monitor bằng CloudWatch + Cấu hình Infrastructure as Code (IaC)

### Mục tiêu tuần

* Tự thiết lập các cảnh báo tự động khi server quá tải.
* Viết code triển khai hạ tầng (CloudFormation) thay vì thao tác tay bằng chuột.

### Lịch làm việc

| Ngày | Thứ | Mô tả công việc | Lab / Dự án |
| :--- | :--- | :--- | :--- |
| 06/07/2026 | Thứ 2 | Cài đặt CloudWatch Agent để theo dõi log và metrics chi tiết từ EC2. | [Module: CloudWatch](https://cloudjourney.awsstudygroup.com/) |
| 07/07/2026 | Thứ 3 | Tạo custom dashboard giám sát trên CloudWatch. Thiết lập SNS gửi email khi CPU > 80%. | [Lab 11 - Monitor Alerts](https://cloudjourney.awsstudygroup.com/) |
| 08/07/2026 | Thứ 4 | Tìm hiểu tự động hóa hạ tầng bằng CloudFormation. Đọc hiểu syntax YAML. | [Module: IaC](https://cloudjourney.awsstudygroup.com/) |
| 09/07/2026 | Thứ 5 | Triển khai thử 1 stack tạo VPC và Security Group hoàn toàn bằng code CloudFormation. | [Lab 12 - CloudFormation](https://cloudjourney.awsstudygroup.com/) |
| 10/07/2026 | Thứ 6 | Verify tài nguyên được tạo từ Stack. Đánh giá quá trình học tập tuần 6. | Báo cáo tiến độ |

### Kết quả mong đợi

* Bảng điều khiển CloudWatch hiển thị trực quan các thông số hệ thống.
* Chạy thành công template IaC, khởi tạo tự động toàn bộ block mạng cơ bản.

### Tài liệu tham khảo Tuần 6

* [Lab 11 & 12 - Management and IaC](https://cloudjourney.awsstudygroup.com/)