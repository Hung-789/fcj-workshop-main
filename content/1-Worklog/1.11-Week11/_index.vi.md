---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
Mục tiêu tuần 11

- Tăng cường hệ thống trước buổi demo cuối.
- Thực hiện đánh giá Well-Architected và siết chặt IAM cùng xử lý lỗi.

Các công việc cần triển khai trong tuần này


| Thứ     | Công việc                                                                           | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                                                                                                                           |
| ------- | ----------------------------------------------------------------------------------- | ------------ | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Thứ Ba  | - Rà soát theo AWS Well-Architected Framework; ghi nhận các hạng mục cần khắc phục. | 14/07/2026   | 14/07/2026      | [https://docs.aws.amazon.com/wellarchitected/](https://docs.aws.amazon.com/wellarchitected/)                                             |
| Thứ Tư  | - Áp dụng IAM least-privilege cho từng Lambda; loại bỏ quyền không sử dụng.         | 15/07/2026   | 15/07/2026      | [https://docs.aws.amazon.com/IAM/latest/UserGuide/](https://docs.aws.amazon.com/IAM/latest/UserGuide/)                                   |
| Thứ Năm | - Cấu hình DLQ cho các Lambda quan trọng; xác nhận invocation lỗi được ghi lại.     | 16/07/2026   | 16/07/2026      | [https://docs.aws.amazon.com/lambda/latest/dg/invocation-async.html](https://docs.aws.amazon.com/lambda/latest/dg/invocation-async.html) |
| Thứ Sáu | - Chạy lại kiểm thử end-to-end sau chỉnh IAM; xác minh không còn lỗi truy cập.      | 17/07/2026   | 17/07/2026      | [https://docs.aws.amazon.com/lambda/](https://docs.aws.amazon.com/lambda/)                                                               |
| Thứ Bảy | - Cập nhật sơ đồ kiến trúc; chuẩn bị slide cho buổi trình bày cuối.                 | 18/07/2026   | 18/07/2026      | Tài liệu dự án                                                                                                                           |




Kết quả đạt được tuần 11

- Hoàn thành đánh giá hệ thống theo AWS Well-Architected Framework.
- Áp dụng thành công chính sách Least Privilege cho tất cả Lambda Function.
- Cấu hình Dead Letter Queue (DLQ) cho các thành phần quan trọng.
- Kiểm thử thành công hệ thống sau khi tối ưu bảo mật.
- Hoàn thiện sơ đồ kiến trúc và tài liệu phục vụ báo cáo cuối kỳ.

