 Cloud Security Project – Scout Suite AWS Audit

 Project Overview
This project demonstrates how I used Scout Suite, an open-source multi-cloud security auditing tool, to assess the security posture of an AWS environment.

Scout Suite generates a detailed HTML report highlighting risks across IAM, S3, EC2, VPC, CloudTrail and KMS

Tools Used
-Scout Suite (Security auditing)
-AWS CLI (Authentication)
 -Python venv (Virtual environment)
- GitHub (Portfolio hosting)

 How to Run
1. Install Scout Suite:
pip install scoutsuite

2 .Run the audit:
scout aws --report-dir scoutsuite-report

3. The report will be generated at:
scoutsuite-report/aws-default.html
