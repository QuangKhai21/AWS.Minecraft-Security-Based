---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Triển khai website tĩnh trên Amazon S3.
* Hiểu cách quản lý quyền truy cập, Public Access Block, Object Permission và Website Routing.
* Tối ưu tốc độ truy cập website thông qua Amazon CloudFront.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Tìm hiểu Static Website Hosting trên Amazon S3.<br>- Nghiên cứu Public Access Block, Bucket Policy và Object Permission.<br>- Tìm hiểu cơ chế hoạt động của S3 Website Endpoint. | 15/06/2026 | 15/06/2026 | https://docs.aws.amazon.com/s3/ |
| 3 | - Tạo S3 Bucket phục vụ Static Website Hosting.<br>- Upload mã nguồn website.<br>- Cấu hình Website Endpoint và kiểm tra khả năng truy cập. | 16/06/2026 | 16/06/2026 | https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html |
| 4 | - Cấu hình Public Access và Bucket Policy an toàn.<br>- Kiểm tra quyền truy cập website.<br>- Đánh giá các thiết lập bảo mật của Bucket. | 17/06/2026 | 17/06/2026 | https://docs.aws.amazon.com/AmazonS3/latest/userguide/bucket-policies.html |
| 5 | - Tạo CloudFront Distribution.<br>- Thiết lập S3 Bucket làm Origin.<br>- Cấu hình Cache Behavior, Default Root Object và kiểm tra tốc độ truy cập. | 18/06/2026 | 18/06/2026 | https://docs.aws.amazon.com/cloudfront/ |
| 6 | - Bật Versioning cho S3 Bucket.<br>- Tìm hiểu S3 Cross-Region Replication.<br>- Ghi chú quy trình sao lưu và dọn dẹp tài nguyên. | 19/06/2026 | 19/06/2026 | https://docs.aws.amazon.com/AmazonS3/latest/userguide/Versioning.html |
| 7 | - Tổng kết kiến thức về S3 và CloudFront.<br>- Hoàn thiện checklist triển khai Static Website.<br>- Chuẩn bị kế hoạch học tập cho tuần tiếp theo. | 20/06/2026 | 20/06/2026 | https://aws.amazon.com/s3/ |

### Kết quả đạt được tuần 9:

* Triển khai thành công website tĩnh trên Amazon S3.
* Hiểu rõ sự khác biệt giữa Public Access Block, Bucket Policy và Object Permission.
* Cấu hình CloudFront kết hợp với S3 Origin để cải thiện tốc độ truy cập.
* Bật Versioning và tìm hiểu cơ chế Replication để tăng độ bền dữ liệu.
* Hoàn thiện quy trình quản lý, sao lưu và dọn dẹp S3 Bucket.