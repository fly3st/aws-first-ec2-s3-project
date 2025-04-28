# AWS First Cloud Project: EC2 + S3 Setup

## Overview
This project demonstrates manual configuration of core AWS services, including:
- Launching and connecting to an EC2 instance.
- Creating an S3 bucket for object storage.
- Uploading and managing data in S3.

## Implementation Details
- Deployed an Amazon EC2 instance (Amazon Linux 2, t2.micro) within the AWS Free Tier.
- Configured SSH access using a generated key pair to ensure secure remote connection.
- Created a private S3 bucket scoped to a specific AWS region.
- Uploaded a sample file to validate storage functionality and bucket access controls.

## Screenshots
(Located inside the `/screenies` folder)
- EC2 Dashboard: Running Instance
- SSH Terminal Session: Connected to EC2
- S3 Bucket: Uploaded File Display

## Next Steps
- Automate EC2 and S3 resource provisioning using AWS CLI.
- Develop Infrastructure as Code deployments with Terraform.
- Implement monitoring and alerting with AWS CloudWatch.

---
