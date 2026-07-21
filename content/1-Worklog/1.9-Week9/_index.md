---
title: "Week 9 Worklog"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---
Week 9 Objectives

- Secure the Bedrock Agent using Guardrails policies.
- Set up a CloudWatch Dashboard to monitor network traffic and overall system health.

Tasks to be carried out this week


| Day       | Task                                                                                            | Start Date | Completion Date | Reference Material                                                                                                                                                                     |
| --------- | ----------------------------------------------------------------------------------------------- | ---------- | --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tuesday   | - Guardrails: prompt injection filters, denied topics, content filters.                         | 30/06/2026 | 30/06/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html)                                           |
| Wednesday | - Deploy a Guardrail policy and link it to the Bedrock Agent.                                   | 01/07/2026 | 01/07/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html)                                           |
| Thursday  | - Run prompt-injection test cases; ensure valid requests continue to work normally.             | 02/07/2026 | 02/07/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html)                                           |
| Friday    | - Create a CloudWatch Dashboard covering traffic volume, anomaly patterns, and risk indicators. | 03/07/2026 | 03/07/2026      | [https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html) |
| Saturday  | - Add widgets for alert logs, blocked IP records, and Lambda execution metrics.                 | 04/07/2026 | 04/07/2026      | [https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html) |




Week 9 Achievements

- Guardrail policies are active on the Bedrock Agent.
- Malicious prompt injection is filtered out while legitimate queries remain unaffected.
- The CloudWatch Dashboard surfaces traffic trends, alert activity, and Lambda performance.
- A single centralized dashboard simplifies routine operational monitoring.

