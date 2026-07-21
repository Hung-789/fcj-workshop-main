---
title: "Week 8 Worklog"
date: 2026-06-23
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---
Week 8 Objectives

- Complete the Bedrock Agent by adding automated IP blocking.
- Integrate all four Action Groups into the agent.
- Validate the end-to-end automated threat detection and response cycle.

Tasks to be carried out this week


| Day       | Task                                                                                                 | Start Date | Completion Date | Reference Material                                                                                                                               |
| --------- | ---------------------------------------------------------------------------------------------------- | ---------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Tuesday   | - Learn to update Security Groups and NACLs at runtime with boto3.                                   | 23/06/2026 | 23/06/2026      | [https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html) |
| Wednesday | - Implement the `blockIPAddress` Lambda in dry-run mode (`REAL_BLOCK_ENABLED = false`).              | 24/06/2026 | 24/06/2026      | [https://docs.aws.amazon.com/lambda/](https://docs.aws.amazon.com/lambda/)                                                                       |
| Thursday  | - Register the `blockIPAddress` Action Group — all four groups are now connected to the agent.       | 25/06/2026 | 25/06/2026      | [https://docs.aws.amazon.com/bedrock/](https://docs.aws.amazon.com/bedrock/)                                                                     |
| Friday    | - Run attack simulations; verify the agent selects the appropriate tools for each security scenario. | 26/06/2026 | 26/06/2026      | [https://docs.aws.amazon.com/bedrock/](https://docs.aws.amazon.com/bedrock/)                                                                     |
| Saturday  | - Debug and tune the flow when the agent chains multiple Action Groups.                              | 27/06/2026 | 27/06/2026      | [https://docs.aws.amazon.com/bedrock/](https://docs.aws.amazon.com/bedrock/)                                                                     |




Week 8 Achievements

- The `blockIPAddress` Lambda is deployed and operating in dry-run mode.
- Every Action Group is connected to the Bedrock Agent.
- During simulated incidents, the agent invokes the correct tools.
- End-to-end detect → analyze → alert → block workflow succeeded for the first time.
- Chained multi-step agent calls run more reliably following bug fixes.

