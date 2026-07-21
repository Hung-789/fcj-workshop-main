---
title: "Week 3 Worklog"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---
### Week 3 Objectives:

- Deploy a network traffic collection mechanism using VPC Flow Logs.
- Set up Amazon S3 as a secure raw log storage layer (Data Lake).

### Tasks to be carried out this week:


| Day       | Task                                                                                                                           | Start Date | Completion Date | Reference Material                                                                                                                                                                                                             |
| --------- | ------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Monday    | - Study how VPC Flow Logs operate, including record format and aggregation interval.                                           | 18/05/2026 | 18/05/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html)                                                                                             |
| Tuesday   | - Create and configure S3 bucket `netmon-infra-flowlogs`; enable default server-side encryption (SSE).                         | 19/05/2026 | 19/05/2026      | [https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)                                                                                       |
| Wednesday | - Configure VPC Flow Logs to capture all traffic (`ALL`: ACCEPT + REJECT), with S3 as the destination and a 1-minute interval. | 20/05/2026 | 20/05/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs-s3.html](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs-s3.html)                                                                                       |
| Thursday  | - Verify that actual log files appear in S3; cross-check record structure against AWS documentation.                           | 21/05/2026 | 21/05/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/flow-log-records.html](https://docs.aws.amazon.com/vpc/latest/userguide/flow-log-records.html)                                                                               |
| Friday    | - Consolidate the network layer design; complete foundational documentation for the data processing pipeline build phase.      | 22/05/2026 | 22/05/2026      | [https://docs.aws.amazon.com/whitepapers/latest/aws-vpc-connectivity-options/aws-vpc-connectivity-options.html](https://docs.aws.amazon.com/whitepapers/latest/aws-vpc-connectivity-options/aws-vpc-connectivity-options.html) |


## Week 3 Achievements

- The system automatically exports and successfully writes VPC Flow Log records to the S3 Data Lake.
- At-rest encryption is enabled for the S3 bucket.
- Network design documentation is complete; ready to proceed to Lambda-based data processing in the following weeks.

