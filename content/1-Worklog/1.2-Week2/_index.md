---
title: "Week 2 Worklog"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---
Week 2 Objectives

- Draft the initial network architecture for the monitoring platform.
- Provision the VPC and target EC2 instance that will be observed.

Tasks to be carried out this week:


| Day       | Task                                                                                                | Start Date | Completion Date | Reference Material                                                                                                                                   |
| --------- | --------------------------------------------------------------------------------------------------- | ---------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tuesday   | - Design network diagram: VPC with a public subnet hosting the target EC2.                          | 12/05/2026 | 12/05/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html) |
| Wednesday | - Deploy VPC `netmon-infra-vpc` (10.0.0.0/16), a public subnet, and an Internet Gateway.            | 13/05/2026 | 13/05/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html)               |
| Thursday  | - Spin up the target EC2 and configure the baseline Security Group.                                 | 14/05/2026 | 14/05/2026      | [https://docs.aws.amazon.com/ec2/](https://docs.aws.amazon.com/ec2/)                                                                                 |
| Friday    | - Restrict SSH to the admin IP; deliberately expose HTTP and test ports to generate sample traffic. | 15/05/2026 | 15/05/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/security-groups.html](https://docs.aws.amazon.com/vpc/latest/userguide/security-groups.html)       |
| Saturday  | - Verify connectivity; run Nmap to confirm inbound traffic reaches the instance.                    | 16/05/2026 | 16/05/2026      | [https://nmap.org/book/man.html](https://nmap.org/book/man.html)                                                                                     |




Week 2 Achievements

- VPC, public subnet, route table, IGW, and target EC2 are fully deployed.
- Security Group restricts SSH access to the administrator IP only.
- Outbound Internet works; EC2 responds correctly under the configured rules.
- Network foundation is prepared for enabling VPC Flow Logs next week.
- Initial AWS network infrastructure for the monitoring system is complete.

