---
title: "Week 7 Worklog"
date: 2026-06-16
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
Week 7 Objectives

- Develop the network anomaly detection logic.
- Implement the alert notification system using Amazon SNS.
- Integrate additional Action Groups into the Amazon Bedrock Agent.

Tasks to be carried out this week


| Day       | Task                                                                                                                              | Start Date | Completion Date | Reference Material                                                                                                                   |
| --------- | --------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Tuesday   | - Designed the anomaly detection logic, including traffic thresholds, internal IP whitelist, and attack classification rules.     | 16/06/2026 | 16/06/2026      | Internal design notes                                                                                                                |
| Wednesday | - AImplemented an alert deduplication mechanism to prevent duplicate notifications within a specified time window.                | 17/06/2026 | 17/06/2026      | Internal design notes                                                                                                                |
| Thursday  | - Added escalation logic to increase the risk level when repeated attacks are detected from the same source IP.                   | 18/06/2026 | 18/06/2026      | Internal design notes                                                                                                                |
| Friday    | - Developed the `sendAlert` Lambda function using Amazon SNS and verified email notification delivery.                            | 19/06/2026 | 19/06/2026      | [Amazon SNS Developer Guide](https://docs.aws.amazon.com/sns/latest/dg/welcome.html)                                                 |
| Saturday  | - Attached the `checkTrafficAnomaly` and `sendAlert` Action Groups to the Amazon Bedrock Agent and performed integration testing. | 20/06/2026 | 20/06/2026      | [Use action groups to define actions for your agent](https://docs.aws.amazon.com/bedrock/latest/userguide/agents-action-create.html) |




Week 7 Achievements

- Successfully implemented the network anomaly detection logic.
- Added whitelist, deduplication, and risk escalation mechanisms.
- Developed the `sendAlert` Lambda function.
- Successfully delivered security alerts via Amazon SNS email notifications.
- Integrated three Action Groups into the Amazon Bedrock Agent and verified end-to-end operation.

