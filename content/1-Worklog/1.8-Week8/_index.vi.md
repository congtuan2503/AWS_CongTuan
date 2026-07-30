---
title: "Tuần 8 - Thực thi triển khai AWS & Tự động hóa Deploy"
date: 2026-07-20
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
url: "/vi/1-worklog/1.8-week8/"
---

### Chủ đề tuần

Build hạ tầng AWS thực tế + Thiết lập luồng CI/CD

### Mục tiêu tuần

* Triển khai toàn bộ resources lên AWS dựa trên bản vẽ đã chốt.
* Cấu hình pipeline tự động đẩy code từ Github lên server.

### Lịch làm việc

| Ngày | Thứ | Mô tả công việc | Lab / Dự án |
| :--- | :--- | :--- | :--- |
| 20/07/2026 | Thứ 2 | Thực thi cài đặt môi trường mạng (VPC, Subnets, Route tables, NAT/IGW). | Dự án cuối khóa |
| 21/07/2026 | Thứ 3 | Build môi trường Backend. Chạy EC2 hoặc Lambda tùy yêu cầu dự án. | Dự án cuối khóa |
| 22/07/2026 | Thứ 4 | Khởi tạo RDS/DynamoDB. Kết nối Backend với Database. Test query data. | Dự án cuối khóa |
| 23/07/2026 | Thứ 5 | Host Frontend trên S3/CloudFront. Xây dựng pipeline tự động deploy (CI/CD). | Dự án cuối khóa |
| 24/07/2026 | Thứ 6 | Báo cáo tiến độ code và deploy dự án. Đảm bảo toàn bộ luồng chính hoạt động. | Báo cáo tiến độ |

### Kết quả mong đợi

* Hạ tầng chạy thực tế trên AWS đúng với bản thiết kế.
* Code mỗi khi push lên nhánh main sẽ tự động được build và deploy lên AWS.

### Tài liệu tham khảo Tuần 8

* [AWS CodePipeline Documentation](https://aws.amazon.com/codepipeline/)