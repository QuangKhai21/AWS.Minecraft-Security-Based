---
title: "Worklog Tuần 4"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Nắm vững các thành phần cơ bản của AWS IAM: User, Group, Role, Policy và Permissions Boundary.
* Thực hành phân quyền theo nguyên tắc Least Privilege.
* Tách biệt quyền của tài khoản Root và tài khoản sử dụng hằng ngày.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Ôn lại các thành phần của AWS IAM: User, Group, Role và Policy.<br>- So sánh Managed Policy và Inline Policy.<br>- Tìm hiểu Permissions Boundary. | 11/05/2026 | 11/05/2026 | https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html |
| 3 | - Tạo nhóm quản trị (Admin Group).<br>- Gán các Policy phù hợp cho nhóm.<br>- Tạo tài khoản quản trị và thêm vào nhóm. | 12/05/2026 | 12/05/2026 | https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users.html |
| 4 | - Đăng nhập bằng tài khoản quản trị.<br>- Kiểm tra quyền truy cập trên AWS Console và AWS CLI.<br>- Xác minh các quyền đã được cấp. | 13/05/2026 | 13/05/2026 | https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users_sign-in.html |
| 5 | - Tạo tài khoản vận hành.<br>- Thiết lập IAM Role và Policy cho phép Assume Role.<br>- Thực hành chuyển đổi Role giữa các tài khoản. | 14/05/2026 | 14/05/2026 | https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.html |
| 6 | - Kiểm tra các User không còn sử dụng.<br>- Rà soát quyền truy cập dư thừa.<br>- Xây dựng checklist quản lý và dọn dẹp IAM định kỳ. | 15/05/2026 | 15/05/2026 | https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html |
| 7 | - Tổng kết kiến thức về AWS IAM.<br>- Hoàn thiện checklist phân quyền theo nguyên tắc Least Privilege.<br>- Chuẩn bị kế hoạch học tập cho tuần tiếp theo. | 16/05/2026 | 16/05/2026 | https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/permissions-management.html |

### Kết quả đạt được tuần 4:

* Tạo thành công Group và User cho các vai trò quản trị và vận hành.
* Áp dụng nguyên tắc Least Privilege khi phân quyền.
* Thực hành sử dụng IAM Role và chuyển đổi Role giữa các tài khoản.
* Rà soát và loại bỏ các quyền truy cập không cần thiết.
* Hoàn thiện checklist quản trị AWS IAM.