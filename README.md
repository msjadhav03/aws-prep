# AWS : Associate Certified Developer

<p>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Amazon_Web_Services_Logo.svg/512px-Amazon_Web_Services_Logo.svg.png?20170912170050" alt="AWS Logo" height="260">
</p>

# Contents

1. [Getting Started with AWS](#intro)
2. [IAM and AWS CLI](#iam)
3. [EC2 Fundamentals](#ec2)
4. [EC2 storage](#ec2storage)
5. [AWS Fundamentals: ELB + ASG](#elb)
6. [AWS Fundamentals: RDS + Aurora + ElasticCache](#rds)
7. [Route 53](#route53)
8. [VPC Fundamentals](#vpc)
9. [Amazon S3 Introduction](#s3)
10. [CloudFront](#cloudFront)
11. [ECS,ECR and Fargate - Docker in AWS](#ecs)
12. [AWS Elastic Beanstalk](#beanstalk)
13. [AWS CloudFormation](#cloudFormation)
14. [AWS Integration and Messaging: SQS, SNS and Kinesis](#messaging)
15. [AWS Monitoring and Audit: Cloud Watch, X-Ray and CloudTrail](#cloudWatch)
16. [AWS Serverless: Lambda](#Lambda)
17. [AWS Serverless: DynamoDB](#dynamoDB)
18. [AWS Serverless: API Gateway🚪️](#apiGateway🚪️)
19. [AWS CICD: CodeCommit, CodePipeline, CodeBuild, CodeDeploy](#cicd)
20. [AWS Serverless: SAM - Serverless Application Model](#serverless)
21. [Cloud Development Kit](#cdk)
22. [Cognito: Cognito User Pools, Cognito Identity Pools and Cognito Sync](#cognito)
23. [Other Serverless : Step Functions and AppSync](#appfunction)
24. [Advanced Identity](#advanceidentity)
25. [AWS Security and Encryption : KMS, Encryption SDK, SSM Parameter store, IAM and STS](#securityandencryption)
26. [AWS Other Services](#otherservices)
27. [AWS Final Cleanup](#cleanup)
28. [Preparing for the exam](#awscertified)

# Getting Started With AWS

- `What is AWS?`🤔️
  1. Cloud Computing Platform.
  2. Provides Cloud Service Like Computing, Storage 🗄️, Databases, Machine
     Learning, Analytics, Content delievery, IoT, Security🔐️ and many more.
  3. Access to utilize resources on a pay-as-you-go 💸️ basis.
  4. It is Know for its reliability, scalibility, and flexibility.
  5. It has global🌍️ network of data centers, allows to run their application
     close to their customers for low latency and high availability.
  - `Features` Scalability ⬆️, Reliability, Security💪️, Flexibility, Storage,
    Databases, analytics, Networking🌐️, Machine Learning, Serverless, Global
    Reach.

# IAM and AWS CLI

- `What is IAM?`🤔️
  1. IAM 👨‍💻️ stands for Access and Identity Management Service.
  2. Global Service.
  3. Provides tools to manage users, groups, roles, policies and permission for
     an AWS account.
  4. Provides Control over accessing resources.
  5. Implements best security💪️ measures.
  6. Support features like Multifactor Authentication 🔐️, Identity Federation,
     Security Token Access
  7. `roles` set of permissions, defines what actions are alloweded or denied on
     resources. Use Cases : Cross Account Access, Service to Service Access,
     Temporary Permissions, Federation, Least Privilefe Principle, Rotation of
     Credentials.
- `aws-cli`
  1. Command Line Tool👨‍💻️ to interact and manage AWS services from local
     terminal.
  2. Performs tasks like creating, configuring, and managing AWS resources.
  3. Cross Platform, Access AWS APIS, Support for MFA 🔐️, Scripting and
     Automation, Customization.
  4. Installing AWS CLI on ubuntu
  ```js
  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
  unzip awscliv2.zip
  sudo ./aws/install
  ```

# EC2 Fundamentals

# EC2 storage

# AWS Fundamentals: ELB + ASG

# AWS Fundamentals: RDS + Aurora + ElasticCache

# Route 53

# VPC Fundamentals

# Amazon S3 Introduction

# CloudFront

# ECS,ECR and Fargate - Docker in AWS

# AWS Elastic Beanstalk

# AWS CloudFormation

# AWS Integration and Messaging: SQS, SNS and Kinesis

# AWS Monitoring and Audit: Cloud Watch, X-Ray and CloudTrail

# AWS Serverless: Lambda

# AWS Serverless: DynamoDB

# AWS Serverless: API Gateway🚪️
- Amazon API Gateway🚪️ is an AWS service for creating, publishing, maintaining, monitoring, and securing 🛡️  REST, HTTP, and WebSocket APIs at any scale
-  Can create APIs that access AWS or other web services,
- client --> Method Request --> Lambda Proxy --> Lambda Function --> Integration Response --> Method Reponse --> Client
- API Type Supported
   1. REST API
   2. HTTP API : HTTP APIs enable you to create RESTful APIs with lower latency and lower cost than REST APIs.
   3. WebSocket API
- `Who uses API Gateway?`
API developers and app developers.
- REST APIs and HTTP APIs are both RESTful API products.
- Architecture 🔩️
`User ---> API Gateway🚪️ (API Gateway🚪️ Cache and API Gateway🚪️ Cloudwatch ) ---> Database/Other AWS Services/Lambda `
- ## Features
1. Support stateful and stateless API i.e. websocket, REST API
2. Flexiable authentication mechanism and IAM Policies , Amazon cognito pools.
3. CloudTrail logging and monitoring of API usage and API changes.
4. CloudWatch access logging and execution logging, including the ability to set alarms. 
5. Ability to use AWS CloudFormation templates to enable API creation.
6. Support for custom domain names.
7. AWS WAF is a web application firewall that helps protect web applications and APIs from attacks
8. You can use AWS X-Ray to trace and analyze user requests as they travel through your Amazon API Gateway🚪️ REST APIs to the underlying services.
- ## Getting Started With API Gateway🚪️
1. Create lambda function.
2. Now, create API Gateway🚪️, HTTP APIs.
3. Create routes inside API Gateway🚪️ and integrate corresponding Lambda function to the route.
4. To Delete All the Service 
   1. Go to Lambda service and delete Lamda function
   2. Go to Log Groups and delete log groups with delete options.
   3. Go to API Gateway🚪️ service and delete all the unwanted API Gateway🚪️s
   

# AWS CICD: CodeCommit, CodePipeline, CodeBuild, CodeDeploy

# AWS Serverless: SAM - Serverless Application Model

# Cloud Development Kit

# Cognito: Cognito User Pools, Cognito Identity Pools and Cognito Sync

# Other Serverless : Step Functions and AppSync

# Advanced Identity

# AWS Security and Encryption : KMS, Encryption SDK, SSM Parameter store, IAM and STS

# AWS Other Services

# AWS Final Cleanup

# Preparing for the exam
