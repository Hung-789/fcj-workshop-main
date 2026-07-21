---
title: "Week 5 Worklog"
date: 2026-06-02
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
Week 5 Objectives

- Make the ingestion pipeline reliable end to end.
- Set up IAM roles with the right permissions.
- Tune Lambda memory and timeout based on test runs.

Tasks to be carried out this week


| Day       | Task                                                                            | Start Date | Completion Date | Reference Material                                                                                                                                                       |
| --------- | ------------------------------------------------------------------------------- | ---------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Tuesday   | - Run full pipeline test: EC2 → Flow Logs → S3 → Lambda → DynamoDB.             | 02/06/2026 | 02/06/2026      | [https://docs.aws.amazon.com/](https://docs.aws.amazon.com/)                                                                                                             |
| Wednesday | - Create IAM roles and policies for `preprocess-logs` with least access needed. | 03/06/2026 | 03/06/2026      | [https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)                                 |
| Thursday  | - Fix permission errors, timeouts, and misconfigured resources.                 | 04/06/2026 | 04/06/2026      | [https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html) |
| Friday    | - Adjust Lambda memory and timeout; re-test performance.                        | 05/06/2026 | 05/06/2026      | [https://docs.aws.amazon.com/lambda/latest/dg/configuration-memory.html](https://docs.aws.amazon.com/lambda/latest/dg/configuration-memory.html)                         |
| Saturday  | - Write a short troubleshooting guide for common deploy issues.                 | 06/06/2026 | 06/06/2026      | [https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)                   |




Week 5 Achievements

- Ingestion pipeline runs reliably from EC2 traffic to DynamoDB.
- IAM roles and policies are in place for the Lambda functions.
- Lambda runs faster after memory/timeout tuning.
- Fixed the main permission and config issues that showed up in testing.
- Troubleshooting notes documented for later maintenance.

