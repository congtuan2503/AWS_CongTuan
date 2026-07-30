---
title: "Week 8 - AWS Deployment Execution & Deploy Automation"
date: 2026-07-20
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
url: "/en/1-worklog/1.8-week8/"
---

### Weekly Topic

Building physical AWS infrastructure + Setting up CI/CD pipeline

### Weekly Objectives

* Deploy all resources on AWS based on the finalized diagram.
* Configure automated pipeline to push code from GitHub to the server.

### Work Schedule

| Date | Day | Task Description | Lab / Project |
| :--- | :--- | :--- | :--- |
| 20/07/2026 | Monday | Execute network environment installation (VPC, Subnets, Route tables, NAT/IGW). | Final Project |
| 21/07/2026 | Tuesday | Build the Backend environment. Run EC2 or Lambda depending on project requirements. | Final Project |
| 22/07/2026 | Wednesday | Initialize RDS/DynamoDB. Connect Backend to Database. Test data queries. | Final Project |
| 23/07/2026 | Thursday | Host Frontend on S3/CloudFront. Build automated deployment pipeline (CI/CD). | Final Project |
| 24/07/2026 | Friday | Report on code progress and project deployment. Ensure main flows are operational. | Progress Report |

### Expected Outcomes

* Infrastructure runs physically on AWS matching the design.
* Code automatically builds and deploys to AWS upon push to the main branch.

### Week 8 References

* [AWS CodePipeline Documentation](https://aws.amazon.com/codepipeline/)