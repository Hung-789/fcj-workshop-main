---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---
Mục tiêu tuần 4:

- Xây dựng pipeline xử lý dữ liệu: S3 Event đến Lambda đến DynamoDB.

Các công việc cần triển khai trong tuần này:


| Thứ     | Công việc                                                                                                                             | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                                                                                                                                                                                     |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Thứ Hai | - Nghiên cứu AWS Lambda và cơ chế kích hoạt bất đồng bộ (asynchronous trigger) từ S3 Event Notification.                              | 25/05/2026   | 25/05/2026      | [https://docs.aws.amazon.com/lambda/latest/dg/with-s3.html](https://docs.aws.amazon.com/lambda/latest/dg/with-s3.html)                                                                             |
| Thứ Ba  | - Tìm hiểu kiến trúc Amazon DynamoDB (Partition Key, Capacity Mode) và nguyên tắc thiết kế bảng NoSQL tối ưu.                         | 26/05/2026   | 26/05/2026      | [https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.CoreComponents.html](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.CoreComponents.html) |
| Thứ Tư  | - Thiết kế và khởi tạo bảng DynamoDB `netmon-app-traffic-stats` với Partition Key là `sourceIp`.                                      | 27/05/2026   | 27/05/2026      | [https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-table-design.html](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-table-design.html)                     |
| Thứ Năm | - Phát triển hàm Lambda `preprocess-logs`: xử lý parse định dạng Flow Logs, tính toán các chỉ số lưu lượng theo IP nguồn bằng Python. | 28/05/2026   | 28/05/2026      | [https://docs.aws.amazon.com/lambda/latest/dg/python-handler.html](https://docs.aws.amazon.com/lambda/latest/dg/python-handler.html)                                                               |
| Thứ Sáu | - Cấu hình S3 Event Notification để trigger Lambda tự động, tiến hành kiểm thử toàn bộ đường ống dữ liệu (pipeline) lần đầu tiên.     | 29/05/2026   | 29/05/2026      | [https://docs.aws.amazon.com/AmazonS3/latest/userguide/EventNotifications.html](https://docs.aws.amazon.com/AmazonS3/latest/userguide/EventNotifications.html)                                     |




Kết quả đạt được tuần 4:

- Xây dựng thành công phiên bản đầu tiên của hàm Lambda tiền xử lý log mạng.
- Kiểm chứng bảng DynamoDB nhận và lưu trữ chính xác cấu trúc dữ liệu đẩy lên từ S3 Flow Logs.

