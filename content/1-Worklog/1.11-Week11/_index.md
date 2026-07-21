---
title: "Week 11 Worklog"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
Week 11 Objectives

- Strengthen the system ahead of the final demonstration.
- Conduct a Well-Architected assessment and tighten IAM policies and error handling.

Tasks to be carried out this week


| Day       | Task                                                                                       | Start Date | Completion Date | Reference Material                                                                                                                       |
| --------- | ------------------------------------------------------------------------------------------ | ---------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Tuesday   | - Review against the AWS Well-Architected Framework; document items requiring remediation. | 14/07/2026 | 14/07/2026      | [https://docs.aws.amazon.com/wellarchitected/](https://docs.aws.amazon.com/wellarchitected/)                                             |
| Wednesday | - Enforce least-privilege IAM on each Lambda; remove unused permissions.                   | 15/07/2026 | 15/07/2026      | [https://docs.aws.amazon.com/IAM/latest/UserGuide/](https://docs.aws.amazon.com/IAM/latest/UserGuide/)                                   |
| Thursday  | - Configure DLQs on critical Lambdas; confirm failed invocations are recorded.             | 16/07/2026 | 16/07/2026      | [https://docs.aws.amazon.com/lambda/latest/dg/invocation-async.html](https://docs.aws.amazon.com/lambda/latest/dg/invocation-async.html) |
| Friday    | - Re-execute end-to-end tests post-IAM changes; verify no access errors remain.            | 17/07/2026 | 17/07/2026      | [https://docs.aws.amazon.com/lambda/](https://docs.aws.amazon.com/lambda/)                                                               |
| Saturday  | - Refresh the architecture diagram; prepare slides for the final presentation.             | 18/07/2026 | 18/07/2026      | Project Documentation                                                                                                                    |




Week 11 Achievements

- Well-Architected assessment completed with a prioritized remediation list.
- Every Lambda now operates under least-privilege IAM policies.
- Dead-letter queues configured on critical functions.
- System remains stable following the security hardening pass.
- Architecture diagram and presentation deck are prepared.

