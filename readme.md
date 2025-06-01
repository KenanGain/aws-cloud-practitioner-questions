Link: https://g.co/gemini/share/625965c458d8

AWS Certified Cloud Practitioner–style exam, with questions distributed by domain according to the official exam weighting:

Domain 1: Cloud Concepts (17 questions, ~26%)

Domain 2: Security and Compliance (16 questions, ~25%)

Domain 3: Technology (21 questions, ~33%)

Domain 4: Billing and Pricing (11 questions, ~16%)

Each question is multiple-choice with four options (A–D). No answers are provided here—this is the complete question set.

Domain 1: Cloud Concepts (Questions 1–17)
(Cloud Concepts)
Which of the following best describes the “shared responsibility model” in AWS?
A. AWS is responsible for securing customer data, while customers manage physical hardware security.
B. AWS manages security “of” the cloud, and customers manage security “in” the cloud.
C. Customers are responsible for the physical infrastructure, and AWS manages application-layer security.
D. AWS and the customer share responsibility for both “of” and “in” the cloud based on resource tagging.

(Cloud Concepts)
Which AWS characteristic refers to “on-demand self-service,” allowing you to provision compute resources without human interaction?
A. Resource pooling
B. Rapid elasticity
C. On-demand self-service
D. Measured service

(Cloud Concepts)
What is the primary benefit of deploying applications across multiple Availability Zones (AZs)?
A. Lower data transfer costs between AZs
B. Increased fault tolerance and high availability
C. Automatic cross-Region data replication
D. Reduced latency to end users in a single AZ

(Cloud Concepts)
Which of these is NOT considered one of the five pillars of the AWS Well-Architected Framework?
A. Cost Optimization
B. Operational Excellence
C. Migration Readiness
D. Reliability

(Cloud Concepts)
A company needs to burst compute capacity for periodic traffic spikes. Which AWS concept allows automatic scaling up and down?
A. High availability
B. Elasticity
C. Disaster recovery
D. Data locality

(Cloud Concepts)
In the context of AWS, which term describes pooling computing resources to serve multiple customers using a multi-tenant model?
A. Elasticity
B. Resource pooling
C. On-premises integration
D. Dedicated hosting

(Cloud Concepts)
Which AWS global infrastructure component ensures low latency by caching content at edge locations?
A. AWS Regions
B. Availability Zones
C. Edge locations (Amazon CloudFront)
D. Direct Connect

(Cloud Concepts)
Which of the following scenarios best exemplifies a hybrid cloud deployment?
A. Running an EC2 instance in one AZ and replicating its data to another AZ.
B. Using AWS Lambda to process data from an S3 bucket.
C. Maintaining an on-premises data center for sensitive data and extending some workloads to AWS.
D. Deploying an application across multiple AWS Regions for disaster recovery.

(Cloud Concepts)
Which statement best describes “pay-as-you-go” pricing?
A. You commit to a one-year contract and pay upfront.
B. You pay a flat monthly fee regardless of usage.
C. You pay only for the resources you consume, with no long-term commitment.
D. You pay a fixed price per instance type, regardless of uptime.

(Cloud Concepts)
What is an AWS Marketplace?
A. A web interface to launch and manage EC2 instances.
B. A catalog of third-party software and services that run on AWS.
C. A global content delivery network of edge locations.
D. A billing dashboard for viewing AWS costs.

(Cloud Concepts)
Which best describes an AWS “Region”?
A. A single data center owned by AWS
B. A collection of data centers within a geographic area, isolated from other Regions
C. A service that automatically assigns IP addresses
D. A group of network routes in an on-premises network

(Cloud Concepts)
Which AWS service enables you to model and predict the total cost of running your environment before deployment?
A. AWS Cost Explorer
B. AWS Pricing Calculator
C. AWS Budgets
D. AWS Cost and Usage Reports

(Cloud Concepts)
How does AWS achieve fault tolerance in its core services?
A. By using a single, dedicated physical server per customer
B. Through replication of data and services across multiple Availability Zones
C. By disabling public access to all EC2 instances
D. By enforcing monthly scheduled downtime for maintenance

(Cloud Concepts)
Which of the following is an example of an Infrastructure as a Service (IaaS) offering?
A. Amazon RDS
B. AWS Lambda
C. Amazon EC2
D. AWS Elastic Beanstalk

(Cloud Concepts)
Which advantage does the AWS Cloud provide over a traditional data center?
A. Always lower latency for local users
B. On-premises only licensing is not required
C. Guaranteed zero data transfer fees
D. Total elimination of security management

(Cloud Concepts)
Which concept refers to “right-sizing” your AWS environment to ensure cost efficiency?
A. Overprovisioning
B. Reserved Instances
C. Cost Optimization
D. Elastic Load Balancing

(Cloud Concepts)
What is the primary benefit of AWS’s “pay-per-use” model in comparison to a traditional capital expenditure (CapEx) model?
A. Predictable fixed monthly costs
B. No need for any architectural planning
C. Minimal upfront investment and paying only for actual usage
D. Unlimited free tier usage without restrictions

Domain 2: Security and Compliance (Questions 18–33)
(Security & Compliance)
Which AWS service provides centralized logging of API calls and stores them in S3 (or CloudTrail Lake) for auditing purposes?
A. AWS CloudTrail
B. AWS Config
C. AWS GuardDuty
D. AWS CloudWatch

(Security & Compliance)
Which IAM feature lets you grant temporary, limited-privilege credentials to users or services?
A. IAM Groups
B. IAM Roles
C. IAM Access Keys
D. IAM Policies

(Security & Compliance)
You need to enforce multi-factor authentication (MFA) for all IAM users before they can perform any EC2 actions. Which policy condition should you use?
A. "Bool": { "aws:MultiFactorAuthPresent": "true" }
B. "StringEquals": { "aws:username": "*" }
C. "IpAddress": { "aws:SourceIp": "0.0.0.0/0" }
D. "DateGreaterThan": { "aws:CurrentTime": "2022-01-01T00:00:00Z" }

(Security & Compliance)
Which AWS service helps detect unauthorized or malicious activity within your AWS environment by analyzing VPC flow logs, DNS logs, and CloudTrail events?
A. AWS Inspector
B. AWS GuardDuty
C. AWS Macie
D. AWS WAF

(Security & Compliance)
To ensure all newly created EBS volumes are encrypted by default, which AWS feature should you enable?
A. EBS Snapshot Copying
B. KMS Key Policies
C. EBS Default Encryption
D. S3 Bucket Policies

(Security & Compliance)
Which AWS service can centrally manage encryption keys and integrate with multiple AWS services to encrypt data at rest?
A. AWS KMS (Key Management Service)
B. AWS Certificate Manager (ACM)
C. AWS Shield
D. AWS Security Hub

(Security & Compliance)
Your application stores sensitive customer PII data in S3. You want to detect unintentional public access. Which feature can automatically evaluate S3 bucket and object permissions for policy violations?
A. S3 Versioning
B. S3 Access Analyzer
C. S3 Transfer Acceleration
D. S3 Object Lock

(Security & Compliance)
Which AWS service provides a managed firewall to protect web applications from common exploits and vulnerabilities?
A. AWS Shield
B. AWS WAF (Web Application Firewall)
C. AWS Firewall Manager
D. AWS GuardDuty

(Security & Compliance)
Which IAM principal should you use when creating an EC2 instance that needs to access DynamoDB without embedding credentials?
A. IAM User
B. IAM Group
C. IAM Role attached to the EC2 instance profile
D. IAM Access Key

(Security & Compliance)
Which service can automatically analyze S3 data for sensitive content such as PII and generate security findings?
A. AWS Macie
B. AWS GuardDuty
C. Amazon Inspector
D. AWS Config

(Security & Compliance)
You want to create a policy that only allows users to delete objects in S3 if they have MFA enabled. Which condition key do you use in the policy?
A. "Bool": { "aws:SecureTransport": "true" }
B. "StringEquals": { "aws:MultiFactorAuthPresent": "true" }
C. "StringNotEquals": { "s3:VersionId": "null" }
D. "IpAddress": { "aws:SourceIp": "203.0.113.0/24" }

(Security & Compliance)
Which AWS service provides real-time protection against Distributed Denial of Service (DDoS) attacks?
A. AWS Shield Advanced
B. AWS IAM
C. AWS Config
D. AWS GuardDuty

(Security & Compliance)
A compliance requirement mandates that the root user’s access key be disabled. Which best practice aligns with this requirement?
A. Create an IAM user with the AdministratorAccess policy and delete the root access key permanently.
B. Leave the root user’s access key active and monitor with CloudTrail.
C. Utilize the root user for all administrative tasks and rotate the access key monthly.
D. Store root user’s access key in SSM Parameter Store as a secure string.

(Security & Compliance)
Which feature enables organization-wide governance and policy enforcement across multiple AWS accounts?
A. AWS Organizations with Service Control Policies (SCPs)
B. AWS IAM Access Analyzer
C. AWS Trusted Advisor
D. AWS Identity Center (formerly Single Sign-On)

(Security & Compliance)
You need to inspect incoming HTTP requests to your application for SQL injection and cross-site scripting (XSS) attacks. Which service should you configure?
A. AWS WAF
B. AWS Shield Standard
C. Amazon Inspector
D. Amazon GuardDuty

(Security & Compliance)
Which AWS service would you use to store encrypted and versioned secrets (API keys, passwords) for your applications?
A. AWS KMS
B. AWS Secrets Manager
C. AWS CloudHSM
D. Amazon S3

Domain 3: Technology (Questions 34–54)
(Technology)
Which AWS compute service lets you run containers without managing servers or clusters?
A. Amazon EC2
B. Amazon ECS on EC2
C. AWS Fargate
D. AWS Lambda

(Technology)
A developer wants to deploy a highly available, autoscaling web application without managing the underlying infrastructure. Which service should they choose?
A. Amazon EC2 with Auto Scaling Groups
B. AWS Elastic Beanstalk
C. Amazon Lightsail
D. Amazon EKS

(Technology)
Which service is designed for building and running serverless APIs with built-in authorization, request validation, and throttling?
A. AWS AppSync
B. Amazon API Gateway
C. Amazon CloudFront
D. AWS Elastic Load Balancer

(Technology)
Your company needs a relational database that automatically replicates six copies of data across three Availability Zones. Which service is this?
A. Amazon RDS for MySQL
B. Amazon Aurora
C. Amazon Redshift
D. Amazon DynamoDB

(Technology)
Which AWS service provides a petabyte-scale data warehouse optimized for analytical queries?
A. Amazon RDS for PostgreSQL
B. Amazon DynamoDB
C. Amazon Redshift
D. Amazon ElastiCache

(Technology)
A developer needs low-latency access to objects (e.g., images) stored in S3. Which AWS service speeds up content delivery by caching at edge locations?
A. AWS Global Accelerator
B. Amazon CloudFront
C. AWS Direct Connect
D. AWS Storage Gateway

(Technology)
Which storage option is most appropriate for a file system that needs to be shared by multiple EC2 instances?
A. Amazon S3
B. Amazon EBS
C. Amazon EFS
D. Amazon FSx for Windows File Server

(Technology)
Which service should you use for object lifecycle management (e.g., transition objects to Glacier after 30 days)?
A. Amazon S3 Lifecycle Policies
B. AWS Backup
C. Amazon EBS Snapshots
D. AWS Storage Gateway

(Technology)
Which compute option provides built-in support for running highly scalable containerized Elasticsearch clusters?
A. Amazon Elasticsearch Service (Amazon OpenSearch Service)
B. Amazon MQ
C. Amazon EMR
D. Amazon MSK

(Technology)
Your application needs a NoSQL database that can handle millions of requests per second with single-digit millisecond latency. Which service fits best?
A. Amazon RDS for MySQL
B. Amazon Aurora
C. Amazon DynamoDB
D. Amazon DocumentDB

(Technology)
Which AWS service provides a managed Kubernetes control plane?
A. Amazon ECS
B. Amazon EKS
C. AWS Fargate
D. AWS Batch

(Technology)
Which service is used to automate infrastructure provisioning by writing templates in JSON or YAML?
A. AWS Config
B. AWS CloudFormation
C. AWS Elastic Beanstalk
D. AWS OpsWorks

(Technology)
Which service collects and monitors operational metrics (CPU, memory, disk I/O) from EC2 instances and other AWS resources?
A. AWS CloudTrail
B. Amazon CloudWatch
C. AWS X-Ray
D. AWS Config

(Technology)
A team wants to run a serverless function written in Python that executes whenever a new object lands in a specific S3 bucket. Which combination is correct?
A. Amazon S3 Event Notifications → AWS Lambda
B. Amazon SNS → AWS Fargate
C. Amazon EventBridge → Amazon EC2 Auto Scaling
D. AWS Step Functions → AWS Batch

(Technology)
Which service helps you migrate on-premises VMware virtual machines to AWS with minimal downtime?
A. AWS DataSync
B. AWS Server Migration Service (SMS)
C. AWS Database Migration Service (DMS)
D. AWS Snowball

(Technology)
Which AWS service is designed for real-time streaming data ingestion and processing (e.g., clickstream analytics)?
A. Amazon Kinesis Data Streams
B. Amazon SQS
C. Amazon SNS
D. Amazon MQ

(Technology)
An application requires sub-millisecond latency at scale for caching database queries. Which solution should you choose?
A. Amazon ElastiCache (Redis)
B. Amazon RDS Proxy
C. Amazon DynamoDB Streams
D. Amazon S3 Transfer Acceleration

(Technology)
Which AWS service simplifies the process of decoupling microservices by providing a managed message queue?
A. Amazon SNS
B. Amazon SQS
C. Amazon MQ
D. AWS App Mesh

(Technology)
A developer wants to create a private link between their VPC and an S3 bucket so that traffic never traverses the internet. Which feature should they use?
A. VPC Peering
B. VPC Endpoint (Gateway Endpoint for S3)
C. AWS Direct Connect
D. AWS Transit Gateway

(Technology)
Which AWS service allows you to run and manage Kubernetes pods on serverless infrastructure (no nodes to manage)?
A. Amazon ECS
B. Amazon EKS on EC2
C. AWS Fargate
D. AWS Batch

(Technology)
Your company wants to deliver software patches and updates to thousands of EC2 instances in a controlled manner. Which service should you use to orchestrate patching?
A. AWS Systems Manager Patch Manager
B. AWS Config
C. AWS CloudTrail
D. AWS Backup

Domain 4: Billing and Pricing (Questions 55–65)
(Billing & Pricing)
Which pricing model allows you to reserve capacity for EC2 instances for one or three-year terms in exchange for a significant discount over On-Demand pricing?
A. Spot Instances
B. Reserved Instances
C. Savings Plans
D. Dedicated Hosts

(Billing & Pricing)
Which AWS feature enables you to view detailed line-item billing data and break down costs by service, region, usage type, and resource tags?
A. AWS Cost Explorer
B. AWS Simple Monthly Calculator
C. AWS Trusted Advisor
D. AWS Config

(Billing & Pricing)
Your company needs to enforce a hard limit on monthly AWS spending and trigger an alert if forecasted costs exceed the budget. Which service should you configure?
A. AWS Cost and Usage Reports (CUR)
B. AWS CloudWatch Alarms
C. AWS Budgets
D. AWS Cost Explorer

(Billing & Pricing)
Which statement about the AWS Free Tier is TRUE?
A. It automatically applies to all AWS accounts and never expires.
B. It provides 12 months of free usage for certain services, subject to usage limits.
C. It includes unlimited usage of all AWS services for the first year.
D. It is available only to enterprise support plan customers.

(Billing & Pricing)
Which purchasing option gives you the most flexibility to use EC2 capacity and apply discounts across instance families?
A. Reserved Instances (Standard RI)
B. Reserved Instances (Convertible RI)
C. On-Demand Instances
D. Spot Instances

(Billing & Pricing)
Which AWS tool can generate a detailed cost forecast for the next 6–12 months based on historical usage patterns?
A. AWS Cost Explorer Forecast
B. AWS Pricing Calculator
C. AWS CloudTrail
D. AWS Personal Health Dashboard

(Billing & Pricing)
A startup runs intermittent batch processing jobs that can tolerate interruptions. Which EC2 billing option will result in the lowest overall cost?
A. On-Demand Instances
B. Reserved Instances (Partial Upfront)
C. Spot Instances
D. Dedicated Instances

(Billing & Pricing)
Which of the following AWS services is NOT included in the Free Tier at any usage level?
A. Amazon DynamoDB (25 GB storage per month)
B. Amazon EC2 (750 hours per month t2.micro)
C. Amazon RDS (750 hours per month db.t2.micro Single-AZ)
D. Amazon S3 Glacier Deep Archive storage

(Billing & Pricing)
Which billing construct allows you to consolidate payment for multiple AWS accounts under a single paying account and apply volume-based discounts?
A. AWS Single Sign-On (SSO)
B. AWS Organizations with Consolidated Billing
C. AWS Identity Center
D. AWS Control Tower

(Billing & Pricing)
Which type of Savings Plan offers the greatest discount but requires you to commit to using a specific EC2 instance family within a region?
A. Compute Savings Plan
B. EC2 Instance Savings Plan (Instance-Family Savings Plan)
C. EBS Savings Plan
D. S3 Storage Savings Plan

(Billing & Pricing)
Your team wants to tag all resources with “CostCenter” so that in Cost Explorer you can filter and allocate costs. Which IAM action must you grant to allow developers to assign tags at resource creation?
A. iam:PassRole
B. ec2:CreateTags (or equivalent for the specific service)
C. s3:PutObject
D. cloudtrail:PutEventSelectors

