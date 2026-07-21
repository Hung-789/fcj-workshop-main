---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---
Mục tiêu tuần 9

- Tăng cường bảo mật cho AI Agent bằng Amazon Bedrock Guardrails.
- Xây dựng CloudWatch Dashboard để theo dõi các chỉ số và trạng thái của hệ thống giám sát mạng.

Các công việc cần triển khai trong tuần này


| Thứ     | Công việc                                                                           | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                                                                                                                                                                         |
| ------- | ----------------------------------------------------------------------------------- | ------------ | --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Thứ Ba  | - Guardrails: lọc prompt injection, denied topics, content filter.                  | 30/06/2026   | 30/06/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html)                                           |
| Thứ Tư  | - Triển khai Guardrail và liên kết với Bedrock Agent.                               | 01/07/2026   | 01/07/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html)                                           |
| Thứ Năm | - Chạy kịch bản prompt injection; đảm bảo request hợp lệ vẫn hoạt động bình thường. | 02/07/2026   | 02/07/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html)                                           |
| Thứ Sáu | - Tạo CloudWatch Dashboard theo dõi lưu lượng, mẫu bất thường và chỉ số rủi ro.     | 03/07/2026   | 03/07/2026      | [https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html) |
| Thứ Bảy | - Bổ sung widget lịch sử cảnh báo, danh sách IP bị chặn và metric thực thi Lambda.  | 04/07/2026   | 04/07/2026      | [https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html) |




Kết quả đạt được tuần 9

- Cấu hình thành công Amazon Bedrock Guardrails cho AI Agent.
- Kiểm thử thành công cơ chế chống Prompt Injection mà vẫn đảm bảo các yêu cầu hợp lệ được xử lý chính xác.
- Xây dựng hoàn chỉnh CloudWatch Dashboard để theo dõi lưu lượng mạng, cảnh báo bảo mật và hiệu suất Lambda.
- Nâng cao khả năng giám sát và quản lý hệ thống thông qua Dashboard tập trung.

