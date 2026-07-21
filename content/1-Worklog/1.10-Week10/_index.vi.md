---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
## Mục tiêu tuần 10

- Thực hiện mô phỏng tấn công trên toàn bộ nền tảng.
- Đánh giá phản ứng của agent với port scan, brute force và lưu lượng bất thường.

## Các công việc cần triển khai trong tuần này


| Thứ     | Công việc                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                                                                                                                     |
| ------- | ------------------------------------------------------------------------------------------ | ------------ | --------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| Thứ Ba  | - Chạy port scan bằng Nmap; xác nhận agent phát hiện hoạt động đáng ngờ.                   | 07/07/2026   | 07/07/2026      | [https://nmap.org/book/](https://nmap.org/book/)                                                                                   |
| Thứ Tư  | - Mô phỏng tấn công SSH brute force; kiểm tra logic phát hiện và gửi cảnh báo.             | 08/07/2026   | 08/07/2026      | [https://owasp.org/www-community/attacks/Brute_force_attack](https://owasp.org/www-community/attacks/Brute_force_attack)           |
| Thứ Năm | - Tạo mẫu lưu lượng bất thường; kiểm thử chấm điểm rủi ro và luồng leo thang.              | 09/07/2026   | 09/07/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html) |
| Thứ Sáu | - Thu thập minh chứng: thông báo SNS, CloudWatch Logs, bản ghi DynamoDB và phản hồi agent. | 10/07/2026   | 10/07/2026      | [https://docs.aws.amazon.com/](https://docs.aws.amazon.com/)                                                                       |
| Thứ Bảy | - Phân tích kết quả kiểm thử, ghi nhận điểm còn thiếu và cập nhật tài liệu dự án.          | 11/07/2026   | 11/07/2026      | Tài liệu dự án                                                                                                                     |




## Kết quả đạt được tuần 10

- Nền tảng end-to-end đã được kiểm chứng với kịch bản tấn công gần thực tế.
- Port scan, SSH brute force và lưu lượng bất thường đều được phát hiện chính xác.
- Cảnh báo kích hoạt ổn định; agent đưa ra quyết định hợp lý.
- Đã thu thập minh chứng và soạn báo cáo đánh giá.

