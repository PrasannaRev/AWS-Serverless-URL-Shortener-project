# AWS-Serverless-URL-Shortener-project
This is a simple URL shortening service built using AWS Lambda, API Gateway, DynamoDB, and S3 for static website hosting. The deployment is automated using Terraform.

## Features
- Shorten long URLs into shorter, shareable links
- Store shortened URLs in DynamoDB
- Retrieve and redirect using API Gateway and Lambda
- Deploy infrastructure with Terraform
## Architecture
- Lambda: Handles URL shortening and retrieval.
- DynamoDB: Stores mapping between short and long URLs.
- API Gateway: Exposes endpoints for shortening and redirecting URLs.
- S3 & CloudFront: Hosts a static front-end (if applicable).
- Terraform: Automates infrastructure deployment.
## Prerequisites
- AWS CLI configured with necessary permissions
- Terraform installed
- IAM permissions to manage Lambda, API Gateway, DynamoDB, and S3

## Conclusion
This serverless URL shortener provides an efficient way to shorten and manage URLs using AWS services.
