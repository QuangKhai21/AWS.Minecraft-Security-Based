---
title: "Week 7 Worklog"
date: 2026-06-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Week 7 Objectives

* Understand the role of IAM Roles for EC2 and why they are safer than long-term access keys.
* Practice creating Instance Profiles, attaching IAM Roles to EC2, and using Temporary Credentials.
* Access AWS resources from EC2 without storing permanent credentials in applications.

### Tasks for This Week

| Day | Tasks | Start Date | Finish Date | Reference |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ----------- | -------------------------------- |
| Monday | - Learn about the risks of long-term Access Keys.<br>- Compare IAM User Access Keys and EC2 IAM Roles.<br>- Understand the benefits of Temporary Credentials. | 01/06/2026 | 01/06/2026 | https://docs.aws.amazon.com/IAM/latest/UserGuide/security-creds.html |
| Tuesday | - Create an IAM Role for EC2.<br>- Attach Amazon S3 access permissions.<br>- Review Trust Policy and Permission Policy configurations. | 02/06/2026 | 02/06/2026 | https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/iam-roles-for-amazon-ec2.html |
| Wednesday | - Attach an IAM Role to an EC2 Instance.<br>- Check Temporary Credentials through Instance Metadata Service.<br>- Verify EC2 permission access. | 03/06/2026 | 03/06/2026 | https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instancedata-data-retrieval.html |
| Thursday | - Access Amazon S3 from EC2 using IAM Role.<br>- Test read/write operations.<br>- Remove hardcoded credentials from application code. | 04/06/2026 | 04/06/2026 | https://docs.aws.amazon.com/sdkref/latest/guide/access.html |
| Friday | - Review and clean unused IAM Roles.<br>- Audit Instance Profiles.<br>- Summarize IAM Role security best practices. | 05/06/2026 | 05/06/2026 | https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html |
| Saturday | - Summarize IAM Role and EC2 concepts.<br>- Complete the credential security checklist.<br>- Prepare the learning plan for Week 8. | 06/06/2026 | 06/06/2026 | https://skillbuilder.aws/ |

### Week 7 Achievements

* Clearly understood why IAM Roles are preferred over long-term Access Keys.
* Successfully created and attached IAM Roles to EC2 instances.
* Accessed AWS resources from EC2 without storing credentials in application code.
* Verified Temporary Credentials through Instance Metadata.
* Learned IAM Role management best practices for EC2 environments.