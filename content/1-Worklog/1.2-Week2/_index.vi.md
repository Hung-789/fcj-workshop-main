---
title: "Worklog Tuần 2"
date: 2026-05-12
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---
### Mục tiêu tuần 2

- Thiết kế sơ bộ kiến trúc mạng cho nền tảng giám sát.
- Triển khai VPC và máy EC2 đích sẽ được theo dõi.

### Các công việc cần triển khai trong tuần này:


| Thứ     | Công việc                                                                             | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                                                                                                                                       |
| ------- | ------------------------------------------------------------------------------------- | ------------ | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Thứ Ba  | - Lập sơ đồ mạng: VPC kèm public subnet chứa EC2 đích.                                | 12/05/2026   | 12/05/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html) |
| Thứ Tư  | - Triển khai VPC `netmon-infra-vpc` (10.0.0.0/16), public subnet và Internet Gateway. | 13/05/2026   | 13/05/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html)               |
| Thứ Năm | - Khởi tạo EC2 và thiết lập Security Group cơ bản.                                    | 14/05/2026   | 14/05/2026      | [https://docs.aws.amazon.com/ec2/](https://docs.aws.amazon.com/ec2/)                                                                                 |
| Thứ Sáu | - Giới hạn SSH cho IP quản trị; cố ý mở HTTP và một số cổng thử để tạo lưu lượng mẫu. | 15/05/2026   | 15/05/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/security-groups.html](https://docs.aws.amazon.com/vpc/latest/userguide/security-groups.html)       |
| Thứ Bảy | - Xác minh kết nối; dùng Nmap kiểm tra EC2 nhận lưu lượng đến.                        | 16/05/2026   | 16/05/2026      | [https://nmap.org/book/man.html](https://nmap.org/book/man.html)                                                                                     |




### Kết quả đạt được tuần 2

- PC, public subnet, route table, IGW và EC2 đích đã triển khai đầy đủ.
- Security Group chỉ cho phép SSH từ IP quản trị.
- EC2 truy cập Internet bình thường và phản hồi đúng theo rule đã cấu hình.
- Tầng mạng đã sẵn sàng để bật VPC Flow Logs ở tuần tiếp theo.
- Hoàn thành hạ tầng mạng AWS ban đầu cho hệ thống giám sát.

