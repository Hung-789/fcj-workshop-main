---
title: "Worklog Tuần 6"
date: 2026-06-09
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
Mục tiêu tuần 6

- Nghiên cứu Amazon Bedrock và các tính năng AI Agent của dịch vụ này.
- Thiết kế kiến trúc Action Group cho AI Agent.
- Phát triển công cụ Lambda đầu tiên để truy xuất các chỉ số mạng.

Các công việc cần triển khai trong tuần này


| Thứ     | Công việc                                                                                                | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                                                                                                                                           |
| ------- | -------------------------------------------------------------------------------------------------------- | ------------ | --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Thứ Ba  | - Nghiên cứu Amazon Bedrock, các Foundation Models, Agents, Action Groups và Guardrails.                 | 09/06/2026   | 09/06/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html)   |
| Thứ Tư  | - So sánh các foundation models có sẵn và đánh giá tính phù hợp cho phân tích bảo mật mạng.              | 10/06/2026   | 10/06/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/models-supported.html](https://docs.aws.amazon.com/bedrock/latest/userguide/models-supported.html) |
| Thứ Năm | - Thiết kế 4 Action Groups: `getNetworkMetrics`, `checkTrafficAnomaly`, `sendAlert` và `blockIPAddress`. | 11/06/2026   | 11/06/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/agents.html](https://docs.aws.amazon.com/bedrock/latest/userguide/agents.html)                     |
| Thứ Sáu | - Phát triển hàm Lambda `getNetworkMetrics` để truy xuất thống kê lưu lượng đã xử lý từ Amazon DynamoDB. | 12/06/2026   | 12/06/2026      | [https://docs.aws.amazon.com/lambda/latest/dg/welcome.html](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)                                   |
| Thứ Bảy | - Tạo Amazon Bedrock Agent đầu tiên, gắn Action Group và thực hiện kiểm thử ban đầu trong Agent Builder. | 13/06/2026   | 13/06/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/agents.html](https://docs.aws.amazon.com/bedrock/latest/userguide/agents.html)                     |




Kết quả đạt được tuần 6

- Tạo thành công Amazon Bedrock Agent đầu tiên.
- Triển khai thành công công cụ Lambda `getNetworkMetrics`.
- Kết nối thành công Bedrock Agent với Action Group đầu tiên.
- Hoàn thành kiến trúc AI Agent ban đầu bao gồm 4 Action Groups.
- Xác minh thành công khả năng Agent truy xuất các chỉ số thống kê mạng từ Amazon DynamoDB.

