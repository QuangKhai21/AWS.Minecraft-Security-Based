---
title: "Worklog Tuần 5"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Xây dựng môi trường mạng AWS hoàn chỉnh với Amazon VPC.
* Hiểu cách hoạt động của Subnet, Route Table, Internet Gateway, NAT Gateway, Security Group và Network ACL.
* Thực hành kiểm tra kết nối và giám sát hạ tầng mạng trên AWS.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Ôn tập kiến thức về Amazon VPC, Subnet, Route Table, Internet Gateway và NAT Gateway.<br>- Tìm hiểu Security Group và Network ACL.<br>- So sánh chức năng của Security Group và NACL. | 18/05/2026 | 18/05/2026 | https://docs.aws.amazon.com/vpc/latest/userguide/ |
| 3 | - Tạo Amazon VPC.<br>- Tạo Public Subnet và Private Subnet.<br>- Gắn Internet Gateway vào VPC. | 19/05/2026 | 19/05/2026 | https://docs.aws.amazon.com/vpc/latest/userguide/create-vpc.html |
| 4 | - Cấu hình Route Table cho Public và Private Subnet.<br>- Tạo NAT Gateway.<br>- Kiểm tra kết nối Internet từ Private Subnet. | 20/05/2026 | 20/05/2026 | https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html |
| 5 | - Tạo Security Group và Network ACL.<br>- Bật VPC Flow Logs.<br>- Sử dụng Reachability Analyzer để kiểm tra đường đi mạng. | 21/05/2026 | 21/05/2026 | https://docs.aws.amazon.com/vpc/latest/userguide/vpc-security-groups.html |
| 6 | - Khởi tạo EC2 trong VPC.<br>- Kết nối EC2 bằng AWS Systems Manager Session Manager.<br>- Theo dõi CloudWatch Metrics và tạo Alarm cơ bản. | 22/05/2026 | 22/05/2026 | https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager.html |
| 7 | - Tổng kết kiến thức về Amazon VPC.<br>- Hoàn thiện sơ đồ mạng và checklist cấu hình VPC.<br>- Chuẩn bị kế hoạch học tập cho tuần tiếp theo. | 23/05/2026 | 23/05/2026 | https://aws.amazon.com/vpc/ |

### Kết quả đạt được tuần 5:

* Xây dựng thành công VPC với Public Subnet và Private Subnet.
* Cấu hình đúng Route Table, NAT Gateway, Security Group và Network ACL.
* Kiểm tra đường đi mạng bằng Reachability Analyzer.
* Kết nối EC2 thông qua Session Manager mà không cần SSH.
* Thiết lập CloudWatch để giám sát cơ bản tài nguyên mạng.