---
title: "Worklog Tuần 10"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Triển khai và quản lý dịch vụ cơ sở dữ liệu Amazon RDS trên AWS.
* Thiết kế kết nối database an toàn thông qua VPC, Security Group và DB Subnet Group.
* Thực hành backup, restore và quản lý vòng đời của Database Instance.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Tìm hiểu Amazon RDS: Database Engine, Instance Class và Storage.<br>- Nghiên cứu DB Subnet Group và mô hình High Availability.<br>- Tìm hiểu các phương án tối ưu tài nguyên database. | 22/06/2026 | 22/06/2026 | https://docs.aws.amazon.com/rds/ |
| 3 | - Thiết lập VPC và Security Group cho RDS.<br>- Tạo DB Subnet Group.<br>- Cấu hình giới hạn truy cập database theo nguyên tắc bảo mật. | 23/06/2026 | 23/06/2026 | https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_VPC.WorkingWithRDSInstanceinaVPC.html |
| 4 | - Khởi tạo Amazon RDS Instance.<br>- Cấu hình Parameter Group và Backup Retention.<br>- Kiểm tra kết nối từ EC2 đến RDS. | 24/06/2026 | 24/06/2026 | https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_CreateDBInstance.html |
| 5 | - Triển khai ứng dụng kết nối với RDS.<br>- Cấu hình thông tin kết nối database.<br>- Kiểm tra thao tác đọc và ghi dữ liệu. | 25/06/2026 | 25/06/2026 | https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_CommonTasks.Connect.html |
| 6 | - Thực hành tạo Database Backup và Restore.<br>- Kiểm tra Snapshot của RDS.<br>- Ghi chú quy trình dọn dẹp Database Instance và tài nguyên liên quan. | 26/06/2026 | 26/06/2026 | https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_WorkingWithAutomatedBackups.html |
| 7 | - Tổng kết kiến thức về Amazon RDS.<br>- Hoàn thiện checklist triển khai database trên AWS.<br>- Đánh giá toàn bộ nội dung đã thực hiện trong chương trình. | 27/06/2026 | 27/06/2026 | https://aws.amazon.com/rds/ |

### Kết quả đạt được tuần 10:

* Triển khai thành công Amazon RDS trong môi trường VPC riêng biệt.
* Thiết kế kết nối database an toàn thông qua DB Subnet Group và Security Group.
* Kết nối ứng dụng với RDS và thực hiện thành công các thao tác đọc/ghi dữ liệu.
* Thực hành backup, restore và quản lý Snapshot của database.
* Hiểu quy trình quản lý vòng đời và dọn dẹp tài nguyên RDS.
* Hoàn thiện kiến thức nền tảng về triển khai hệ thống database trên AWS.