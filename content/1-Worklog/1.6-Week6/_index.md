---
title: "Week 6 Worklog"
date: 2026-06-09
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
Week 6 Objectives

- Research Amazon Bedrock and its AI Agent capabilities.
- Design the Action Group architecture for the AI Agent.
- Develop the first Lambda tool for retrieving network statistics.


| Day       | Task                                                                                                                 | Start Date | Completion Date | Reference Material                                                                                                                                       |
| --------- | -------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tuesday   | - Studied Amazon Bedrock, Foundation Models, Agents, Action Groups, and Guardrails.                                  | 09/06/2026 | 09/06/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html)   |
| Wednesday | - Compared available foundation models and evaluated their suitability for network security analysis.                | 10/06/2026 | 10/06/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/models-supported.html](https://docs.aws.amazon.com/bedrock/latest/userguide/models-supported.html) |
| Thursday  | - Designed four Action Groups: `getNetworkMetrics`, `checkTrafficAnomaly`, `sendAlert`, and `blockIPAddress`.        | 11/06/2026 | 11/06/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/agents.html](https://docs.aws.amazon.com/bedrock/latest/userguide/agents.html)                     |
| Friday    | - Developed the `getNetworkMetrics` Lambda function to retrieve processed traffic statistics from Amazon DynamoDB.   | 12/06/2026 | 12/06/2026      | [https://docs.aws.amazon.com/lambda/latest/dg/welcome.html](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)                                   |
| Saturday  | - Created the first Amazon Bedrock Agent, attached the Action Group, and performed initial testing in Agent Builder. | 13/06/2026 | 13/06/2026      | [https://docs.aws.amazon.com/bedrock/latest/userguide/agents.html](https://docs.aws.amazon.com/bedrock/latest/userguide/agents.html)                     |




Week 6 Achievements

- Successfully created the first Amazon Bedrock Agent.
- Implemented the `getNetworkMetrics` Lambda tool.
- Successfully connected the Bedrock Agent with the first Action Group.
- Completed the initial AI Agent architecture featuring four Action Groups.
- Verified that the Agent can successfully retrieve network statistics from Amazon DynamoDB.

