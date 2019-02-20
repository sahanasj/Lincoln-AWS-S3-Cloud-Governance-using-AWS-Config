# AWS Cloud S3 Governance using AWS Config Feature

Its an Customer related project to ensure the security of AWS S3 buckets in real time

Task is to automate the creation of S3 bucket with all bucket standards and security standards based on the request comes from ServiceNow form.

Monitor the AWS S3 Buckets for any kind of Violation happens - Rectifies the issue and Notifies the Admin/User regarding the Violation via Email.

* UseCase 1: Get alerts when an S3 bucket is made public in AWS account

* UseCase 2: Get alerts when an S3 bucket Version is disabled/suspended in AWS account

# Steps to setup and configure the workflow on AWS Environment as below:
1.	Enable AWS Config to monitor Amazon S3 bucket ACLs and policies for compliance violations.
2.	Create an IAM Role and Policy that grants a Lambda function permissions to read S3 bucket policies and send alerts through SNS.
3.	Create and configure a CloudWatch Events rule that triggers the Lambda function when AWS Config detects an S3 bucket ACL or policy violation.
4.	Create a Lambda function that uses the IAM role to review S3 bucket ACLs and policies, correct the ACLs, and notify your team of out-of-compliance policies.
5.	Verify the monitoring solution.


