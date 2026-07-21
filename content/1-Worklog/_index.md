---
title: "Worklog"
date: 2026-05-05
weight: 1
chapter: false
pre: " <b> 1. </b> "
---


This worklog tracks progress across **12 weeks** (~3 months) on an **AI Agent–driven Network Security Monitoring System on AWS**, from initial architecture through deployment and security reinforcement. VPC Flow Logs are ingested into S3, transformed via Lambda and DynamoDB, and handled by a Bedrock Agent that autonomously identifies, investigates, and responds to network threats.

**Week 1:** [Company onboarding, project scope, and AWS fundamentals](1.1-week1/)

**Week 2:** [Network architecture; provisioning VPC, Security Groups, and target EC2](1.2-week2/)

**Week 3:** [Enabling VPC Flow Logs and persisting raw logs in S3](1.3-week3/)

**Week 4:** [Event-driven pipeline: S3 triggers → Lambda → DynamoDB](1.4-week4/)

**Week 5:** [Pipeline hardening and baseline IAM configuration](1.5-week5/)

**Week 6:** [Bedrock Agent exploration and Action Group architecture](1.6-week6/)

**Week 7:** [Anomaly-detection Lambdas and alert notifications](1.7-week7/)

**Week 8:** [Automated IP-blocking Lambda and all four Action Groups](1.8-week8/)

**Week 9:** [Agent Guardrails setup and CloudWatch Dashboard](1.9-week9/)

**Week 10:** [Full-stack attack simulation and validation](1.10-week10/)

**Week 11:** [AWS Well-Architected review and remediation](1.11-week11/)

**Week 12:** [Data protection enhancements and final report delivery](1.12-week12/)
