---
title: "Worklog Tuần 8"
date: 2026-06-23
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---
Mục tiêu tuần 8

- Hoàn tất agent với khả năng chặn IP tự động.
- Tích hợp đủ bốn Action Group vào agent.
- Kiểm thử chu trình phát hiện và ứng phó mối đe dọa tự động từ đầu đến cuối.

Các công việc cần triển khai trong tuần này


| Thứ     | Công việc                                                                             | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                                                                                                                                   |
| ------- | ------------------------------------------------------------------------------------- | ------------ | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Thứ Ba  | - Học cách cập nhật Security Group và NACL lúc runtime bằng boto3.                    | 23/06/2026   | 23/06/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html) |
| Thứ Tư  | - Triển khai Lambda `blockIPAddress` ở chế độ dry-run (`REAL_BLOCK_ENABLED = false`). | 24/06/2026   | 24/06/2026      | [https://docs.aws.amazon.com/lambda/](https://docs.aws.amazon.com/lambda/)                                                                       |
| Thứ Năm | - Đăng ký Action Group `blockIPAddress` — cả bốn group đã được kết nối với agent.     | 25/06/2026   | 25/06/2026      | [https://docs.aws.amazon.com/bedrock/](https://docs.aws.amazon.com/bedrock/)                                                                     |
| Thứ Sáu | - Chạy mô phỏng tấn công; xác minh agent chọn đúng công cụ cho từng kịch bản bảo mật. | 26/06/2026   | 26/06/2026      | [https://docs.aws.amazon.com/bedrock/](https://docs.aws.amazon.com/bedrock/)                                                                     |
| Thứ Bảy | - Debug và tinh chỉnh luồng khi agent gọi nhiều Action Group liên tiếp.               | 27/06/2026   | 27/06/2026      | [https://docs.aws.amazon.com/bedrock/](https://docs.aws.amazon.com/bedrock/)                                                                     |




Kết quả đạt được tuần 8

- Lambda `blockIPAddress` đã triển khai và hoạt động ở chế độ dry-run.
- Toàn bộ Action Group đã được kết nối với Bedrock Agent.
- Trong các sự cố mô phỏng, agent gọi đúng công cụ cần thiết.
- Lần đầu hoàn thành luồng phát hiện → phân tích → cảnh báo → chặn IP.
- Các lần gọi agent nhiều bước liên tiếp ổn định hơn sau khi khắc lỗi.

