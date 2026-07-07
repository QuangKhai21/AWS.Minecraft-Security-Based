---
title: "Worklog Tuần 6"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Nắm vững vòng đời của EC2, EBS và AMI.
* Thực hành triển khai EC2 Linux và Windows, đồng thời xử lý các tình huống phục hồi quyền truy cập.
* Hiểu các chính sách IAM giúp kiểm soát việc sử dụng và tối ưu chi phí EC2.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Tìm hiểu các loại EC2 Instance Type.<br>- Nghiên cứu Amazon EBS và các loại Volume phổ biến.<br>- So sánh loại Volume phù hợp với từng nhu cầu sử dụng. | 25/05/2026 | 25/05/2026 | https://docs.aws.amazon.com/ec2/ |
| 3 | - Khởi tạo EC2 Linux.<br>- Khởi tạo EC2 Windows.<br>- So sánh các tùy chọn Bootstrap và User Data khi triển khai Instance. | 26/05/2026 | 26/05/2026 | https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/LaunchingAndUsingInstances.html |
| 4 | - Thực hành thay đổi Instance Type.<br>- Tạo EBS Snapshot.<br>- Tạo Custom AMI để sao lưu và tái sử dụng môi trường. | 27/05/2026 | 27/05/2026 | https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html |
| 5 | - Thực hành khôi phục quyền truy cập trên Linux và Windows.<br>- Cấu hình phương án khôi phục kết nối RDP.<br>- Tìm hiểu EBS Archive và lưu trữ dài hạn. | 28/05/2026 | 28/05/2026 | https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ |
| 6 | - Triển khai môi trường LAMP trên Amazon Linux.<br>- Triển khai ứng dụng Node.js trên EC2.<br>- Kiểm tra các chính sách IAM kiểm soát chi phí EC2. | 29/05/2026 | 29/05/2026 | https://docs.aws.amazon.com/ec2/latest/developerguide/ |
| 7 | - Tổng kết kiến thức về EC2, EBS và AMI.<br>- Hoàn thiện checklist quản lý Instance.<br>- Chuẩn bị kế hoạch học tập cho tuần tiếp theo. | 30/05/2026 | 30/05/2026 | https://docs.aws.amazon.com/ec2/ |

### Kết quả đạt được tuần 6:

* Quản lý thành công EC2 Linux và Windows trên AWS.
* Thực hiện được các thao tác tạo Snapshot, AMI và tái sử dụng môi trường đã cấu hình.
* Thực hành thay đổi Instance Type và xử lý các tình huống mất quyền truy cập.
* Triển khai thành công ứng dụng web trên môi trường Linux.
* Hiểu cách sử dụng IAM Policy để giới hạn Instance Family, Instance Type và EBS nhằm kiểm soát chi phí.