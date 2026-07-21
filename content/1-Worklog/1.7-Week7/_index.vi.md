---
title: "Worklog Tuần 7"
date: 2026-06-16
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
Mục tiêu tuần 7

- Phát triển logic phát hiện bất thường mạng.
- Triển khai hệ thống thông báo cảnh báo sử dụng Amazon SNS.
- Tích hợp thêm các Action Groups vào Amazon Bedrock Agent.

Các công việc cần triển khai trong tuần này


| Thứ     | Công việc                                                                                                                             | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                                                                                                                       |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Thứ Ba  | - Thiết kế logic phát hiện bất thường, bao gồm ngưỡng lưu lượng, danh sách trắng IP nội bộ (whitelist) và quy tắc phân loại tấn công. | 16/06/2026   | 16/06/2026      | Tài liệu thiết kế nội bộ                                                                                                             |
| Thứ Tư  | - Triển khai cơ chế khử trùng lặp cảnh báo (alert deduplication) để tránh gửi thông báo trùng lặp trong khoảng thời gian nhất định.   | 17/06/2026   | 17/06/2026      | Tài liệu thiết kế nội bộ                                                                                                             |
| Thứ Năm | - Thêm logic leo thang mức độ rủi ro (risk escalation) khi phát hiện các cuộc tấn công lặp lại từ cùng một IP nguồn.                  | 18/06/2026   | 18/06/2026      | Tài liệu thiết kế nội bộ                                                                                                             |
| Thứ Sáu | - Phát triển hàm Lambda `sendAlert` sử dụng Amazon SNS và xác minh việc gửi thông báo qua email thành công.                           | 19/06/2026   | 19/06/2026      | [Amazon SNS Developer Guide](https://docs.aws.amazon.com/sns/latest/dg/welcome.html)                                                 |
| Thứ Bảy | - Gắn các Action Groups `checkTrafficAnomaly` và `sendAlert` vào Amazon Bedrock Agent và thực hiện kiểm thử tích hợp.                 | 20/06/2026   | 20/06/2026      | [Use action groups to define actions for your agent](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-action-create.html) |




Kết quả đạt được tuần 7

- Triển khai thành công logic phát hiện bất thường mạng.
- Bổ sung các cơ chế danh sách trắng (whitelist), khử trùng lặp (deduplication) và leo thang rủi ro (risk escalation).
- Phát triển thành công hàm Lambda `sendAlert`.
- Gửi thành công các cảnh báo bảo mật qua thông báo email của Amazon SNS.
- Tích hợp 3 Action Groups vào Amazon Bedrock Agent và xác minh hoạt động end-to-end thành công.

