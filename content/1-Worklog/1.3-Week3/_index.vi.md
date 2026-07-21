---
title: "Worklog Tuần 3"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---
### Mục tiêu tuần 3:

- Triển khai cơ chế thu thập lưu lượng mạng sử dụng VPC Flow Logs.
- Thiết lập Amazon S3 làm lớp lưu trữ log thô (Data Lake) an toàn.

### Các công việc cần triển khai trong tuần này:


| Thứ     | Công việc                                                                                                                  | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                                                                                                                                                                                                                 |
| ------- | -------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Thứ Hai | - Nghiên cứu cơ chế vận hành, định dạng bản ghi và chu kỳ aggregation của VPC Flow Logs.                                   | 18/05/2026   | 18/05/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html)                                                                                             |
| Thứ Ba  | - Tạo và cấu hình S3 Bucket (`netmon-infra-flowlogs`), kích hoạt mã hóa phía máy chủ (SSE) mặc định.                       | 19/05/2026   | 19/05/2026      | [https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)                                                                                       |
| Thứ Tư  | - Thiết lập VPC Flow Logs ghi lại toàn bộ lưu lượng (`ALL`: ACCEPT + REJECT), trỏ đích về S3 với chu kỳ 1 phút.            | 20/05/2026   | 20/05/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs-s3.html](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs-s3.html)                                                                                       |
| Thứ Năm | - Kiểm chứng sự xuất hiện của các file log thực tế trên S3, đối chiếu cấu trúc bản ghi với tiêu chuẩn tài liệu AWS.        | 21/05/2026   | 21/05/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/flow-log-records.html](https://docs.aws.amazon.com/vpc/latest/userguide/flow-log-records.html)                                                                               |
| Thứ Sáu | - Tổng hợp thiết kế tầng mạng (Network Layer), hoàn thiện tài liệu nền tảng cho giai đoạn xây dựng pipeline xử lý dữ liệu. | 22/05/2026   | 22/05/2026      | [https://docs.aws.amazon.com/whitepapers/latest/aws-vpc-connectivity-options/aws-vpc-connectivity-options.html](https://docs.aws.amazon.com/whitepapers/latest/aws-vpc-connectivity-options/aws-vpc-connectivity-options.html) |




### Kết quả đạt được tuần 3:

- Hệ thống đã tự động xuất và ghi thành công các bản ghi VPC Flow Logs vào S3 Data Lake.
- Đảm bảo tính bảo mật dữ liệu tại chỗ (at-rest encryption) cho S3 bucket.
- Hoàn thành hồ sơ tài liệu thiết kế mạng, sẵn sàng kết nối sang bước lập trình Lambda xử lý dữ liệu ở các tuần tiếp theo.

