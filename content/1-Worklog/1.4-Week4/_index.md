---
title: "Week 4 Worklog"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---
Week 4 Objectives:

- Implement an automated data processing pipeline from S3 Data Lake via AWS Lambda to analyze raw logs and store metrics in Amazon DynamoDB.

Tasks to be carried out this week:


| Day       | Task                                                                                                                                       | Start Date | Completion Date | Reference Material                                                                                                                                                                                 |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Monday    | - Researched AWS Lambda and asynchronous trigger mechanisms from S3 Event Notifications.                                                   | 25/05/2026 | 25/05/2026      | [https://docs.aws.amazon.com/lambda/latest/dg/with-s3.html](https://docs.aws.amazon.com/lambda/latest/dg/with-s3.html)                                                                             |
| Tuesday   | - Explored Amazon DynamoDB architecture (Partition Key, Capacity Mode) and optimal NoSQL table design principles.                          | 26/05/2026 | 26/05/2026      | [https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.CoreComponents.html](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.CoreComponents.html) |
| Wednesday | - Designed and initialized the DynamoDB table `netmon-app-traffic-stats` with `sourceIp` as the Partition Key.                             | 27/05/2026 | 27/05/2026      | [https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-table-design.html](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-table-design.html)                     |
| Thursday  | - Developed the `preprocess-logs` Lambda function: parsing Flow Logs formatting and calculating traffic metrics by source IP using Python. | 28/05/2026 | 28/05/2026      | [https://docs.aws.amazon.com/lambda/latest/dg/python-handler.html](https://docs.aws.amazon.com/lambda/latest/dg/python-handler.html)                                                               |
| Friday    | Configured S3 Event Notifications to automatically trigger Lambda and conducted the first end-to-end pipeline test.                        | 29/05/2026 | 29/05/2026      | [https://docs.aws.amazon.com/AmazonS3/latest/userguide/EventNotifications.html](https://docs.aws.amazon.com/AmazonS3/latest/userguide/EventNotifications.html)                                     |




Week 4 Achievements:

- Successfully built the first functional version of the network log preprocessing Lambda function.
- Verified that the DynamoDB table successfully receives and stores structured data processed from S3 Flow Logs.

