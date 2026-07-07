---
title: "Worklog Tuần 7"
date: 2026-06-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Hiểu vai trò của IAM Role đối với EC2 và lý do sử dụng Role an toàn hơn Access Key cố định.
* Thực hành tạo Instance Profile, gắn IAM Role vào EC2 và sử dụng Temporary Credentials.
* Truy cập tài nguyên AWS từ EC2 mà không lưu trữ Credential trực tiếp trong ứng dụng.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Tìm hiểu rủi ro khi sử dụng Access Key dài hạn.<br>- So sánh IAM User Access Key và IAM Role dành cho EC2.<br>- Tìm hiểu lợi ích của Temporary Credentials. | 01/06/2026 | 01/06/2026 | https://docs.aws.amazon.com/IAM/latest/UserGuide/security-creds.html |
| 3 | - Tạo IAM Role cho EC2.<br>- Gắn quyền truy cập Amazon S3.<br>- Kiểm tra Trust Policy và Permission Policy của Role. | 02/06/2026 | 02/06/2026 | https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/iam-roles-for-amazon-ec2.html |
| 4 | - Gắn IAM Role vào EC2 Instance.<br>- Kiểm tra Temporary Credentials thông qua Instance Metadata Service.<br>- Xác minh quyền truy cập của Instance. | 03/06/2026 | 03/06/2026 | https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instancedata-data-retrieval.html |
| 5 | - Thực hiện truy cập Amazon S3 từ EC2 thông qua IAM Role.<br>- Kiểm tra thao tác đọc/ghi dữ liệu.<br>- Xóa bỏ Credential cố định khỏi mã nguồn ứng dụng. | 04/06/2026 | 04/06/2026 | https://docs.aws.amazon.com/sdkref/latest/guide/access.html |
| 6 | - Kiểm tra và dọn dẹp IAM Role không sử dụng.<br>- Rà soát Instance Profile.<br>- Tổng hợp các Best Practices khi sử dụng IAM Role. | 05/06/2026 | 05/06/2026 | https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html |
| 7 | - Tổng kết kiến thức về IAM Role và EC2.<br>- Hoàn thiện checklist bảo mật Credential.<br>- Chuẩn bị kế hoạch học tập cho tuần tiếp theo. | 06/06/2026 | 06/06/2026 | https://skillbuilder.aws/ |

### Kết quả đạt được tuần 7:

* Hiểu rõ lý do nên sử dụng IAM Role thay vì Access Key dài hạn.
* Tạo và gắn IAM Role vào EC2 thành công.
* Truy cập tài nguyên AWS từ EC2 mà không cần lưu Credential trong mã nguồn.
* Kiểm tra được Temporary Credential thông qua Instance Metadata.
* Nắm được các Best Practices khi quản lý IAM Role cho EC2.