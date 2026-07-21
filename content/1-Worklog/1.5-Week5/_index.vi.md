---
title: "Worklog Tuần 5"
date: 2026-06-02
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
Mục tiêu tuần 5

- Ổn định pipeline thu thập dữ liệu từ đầu đến cuối.
- Cấu hình IAM role và policy phù hợp.
- Tinh chỉnh memory và timeout của Lambda theo kết quả test.

Các công việc cần triển khai trong tuần này


| Thứ     | Công việc                                                                     | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu               |
| ------- | ----------------------------------------------------------------------------- | ------------ | --------------- | ---------------------------- |
| Thứ Ba  | - Test toàn pipeline: EC2 → Flow Logs → S3 → Lambda → DynamoDB.               | 02/06/2026   | 02/06/2026      | AWS Documentation            |
| Thứ Tư  | - Tạo IAM role và policy cho `preprocess-logs` với quyền tối thiểu cần thiết. | 03/06/2026   | 03/06/2026      | AWS IAM Documentation        |
| Thứ Năm | - Sửa lỗi thiếu quyền, timeout và cấu hình sai tài nguyên.                    | 04/06/2026   | 04/06/2026      | AWS CloudWatch Documentation |
| Thứ Sáu | - Chỉnh memory và timeout Lambda; test lại hiệu năng.                         | 05/06/2026   | 05/06/2026      | AWS Lambda Documentation     |
| Thứ Bảy | - Viết hướng dẫn xử lý các lỗi triển khai hay gặp.                            | 06/06/2026   | 06/06/2026      | Tài liệu dự án               |



Kết quả đạt được tuần 5

- Pipeline thu thập chạy ổn từ lưu lượng EC2 đến DynamoDB.
- IAM role và policy đã cấu hình cho Lambda.
- Lambda chạy nhanh hơn sau khi chỉnh memory/timeout.
- Xử lý xong các lỗi quyền và cấu hình chính trong quá trình test.
- Có tài liệu troubleshooting cho bảo trì sau này.

