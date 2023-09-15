# AWS Database Domains:

#### 1: Workload-Specific Database Design 
#### 2: Deployment and Migration
#### 3: Management and Operations
#### 4: Monitoring and Troubleshooting
#### 5: Database Security
-   ---------------
## 1: Workload-Specific Database Design

### 1.1: Select appropriate database services for specific types of data and workloads.

-   Differentiate between ACID and BASE workloads.

-   Explain appropriate uses of types of databases (for example,
    relational, key-value, document, in-memory, graph, time series,
    ledger).

-   Identify use cases for persisted data compared with ephemeral data.

### 1.2: Determine strategies for disaster recovery and high availability.

-   Select Region and Availability Zone placement to optimize database
    performance.

-   Determine implications of Regions and Availability Zones on disaster
    recovery and high availability strategies.

-   Differentiate use cases for read replicas and Multi-AZ deployments.

### 1.3: Design database solutions for performance, compliance, and scalability.

-   Recommend serverless compared with instance-based database
    architecture.

-   Evaluate requirements for scaling read replicas.

-   Define database caching solutions.

-   Evaluate the implications of partitioning, sharding, and indexing.

-   Determine appropriate instance types and storage options.

-   Determine auto scaling capabilities for relational and NoSQL
    databases.

-   Determine the implications of Amazon DynamoDB adaptive capacity.

-   Determine data locality based on compliance requirements.

### 1.4: Compare the costs of database solutions.

-   Determine cost implications of DynamoDB capacity units, including
    on-demand capacity compared with provisioned capacity.

-   Determine costs associated with instance types and automatic
    scaling.

-   Design for costs, including high availability, backups,
    multi-Region, Multi-AZ, and storage type options.

-   Compare data access costs.

## 2: Deployment and Migration

### 2.1: Automate database solution deployments.

-   Evaluate application requirements to determine components to deploy.

-   Choose appropriate deployment tools and services (for example, AWS
    CloudFormation, AWS CLI).

### 2.2: Determine data preparation and migration strategies.

-   Determine the data migration method (for example, snapshots,
    replication, restore).

-   Evaluate database migration tools and services (for example, AWS
    Database Migration Service \[AWS DMS\], native database tools).

-   Prepare data sources and targets.

-   Determine schema conversion methods (for example, AWS Schema
    Conversion Tool \[AWS SCT\]).

-   Determine heterogeneous compared with homogeneous migration
    strategies.

### 2.3: Perform and validate data migration.

-   Design and script data migration.

-   Run data extraction and migration scripts.

-   Verify the successful load of data.

## 3: Management and Operations

### 3.1: Determine maintenance tasks and processes.

-   Account for the AWS shared responsibility model for database
    services.

-   Determine appropriate maintenance window strategies.

-   Differentiate between major and minor engine upgrades.

### 3.2: Determine backup and restore strategies.

-   Identify the need for automatic and manual backups and snapshots.

-   Differentiate backup and restore strategies (for example, full
    backup, point-in-time, encrypting backups cross-Region).

-   Define retention policies.

-   Correlate the backup and restore to recovery point objective (RPO)
    and recovery time objective (RTO) requirements.

### 3.3: Manage the operational environment of a database solution.

-   Orchestrate the refresh of lower environments.

-   Implement configuration changes (for example, in Amazon RDS option
    groups and parameter groups, or DynamoDB indexing changes).

-   Automate operational tasks.

-   Take action based on AWS Trusted Advisor reports.

## 4: Monitoring and Troubleshooting

### 4.1: Determine monitoring and alerting strategies.

-   Evaluate monitoring tools (for example, Amazon CloudWatch, Amazon
    RDS Performance Insights, database native).

-   Determine appropriate parameters and thresholds for alert
    conditions.

-   Use tools to notify users when thresholds are breached (for example,
    Amazon Simple Notification Service \[Amazon SNS\], Amazon Simple
    Queue Service \[Amazon SQS\], CloudWatch dashboards).

### 4.2: Troubleshoot and resolve common database issues.

-   Identify, evaluate, and respond to categories of failures (for
    example, troubleshoot connectivity; instance, storage, and
    partitioning issues).

-   Automate responses when possible.

### 4.3: Optimize database performance.

-   Troubleshoot database performance issues.

-   Identify appropriate AWS tools and services for database
    optimization.

-   Evaluate the configuration, schema design, queries, and
    infrastructure to improve performance.

## 5: Database Security

### 5.1: Encrypt data at rest and in transit.

-   Encrypt data in relational and NoSQL databases.

-   Apply SSL connectivity to databases.

-   Implement key management (for example, AWS Key Management Service
    \[AWS KMS\], AWS CloudHSM).

### 5.2: Evaluate auditing solutions.

-   Determine auditing strategies for structural and schema changes (for
    example, DDL).

-   Determine auditing strategies for data changes (for example, DML).

-   Determine auditing strategies for data access (for example,
    queries).

-   Determine auditing strategies for infrastructure changes (for
    example, AWS CloudTrail).

-   Enable the export of database logs to Amazon CloudWatch Logs.

### 5.3: Determine access control and authentication mechanisms.

-   Recommend authentication controls for users and roles (for example,
    IAM, native credentials, Active Directory).

-   Recommend authorization controls for users (for example, policies).

### 5.4: Recognize potential security vulnerabilities within database
solutions.

-   Determine security group rules and network ACLs for database access.

-   Identify relevant VPC configurations (for example, VPC endpoints,
    public subnets compared with private subnets, perimeter zone).

-   Determine appropriate storage methods for sensitive data.

## In-scope AWS services and features

#### Application Integration:

-   Amazon EventBridge

-   Amazon Simple Notification Service (Amazon SNS)

-   Amazon Simple Queue Service (Amazon SQS)

#### Cloud Financial Management:

-   AWS Budgets

-   AWS Cost Explorer

#### Compute:

-   AWS Auto Scaling

-   Amazon EC2

-   AWS Lambda

#### Containers:

-   Amazon Elastic Container Service (Amazon ECS)

-   Amazon Elastic Kubernetes Service (Amazon EKS)

#### Database:

-   Amazon Aurora

-   Amazon DocumentDB (with MongoDB compatibility)

-   Amazon DynamoDB

-   Amazon DynamoDB Accelerator (DAX)

-   Amazon ElastiCache

-   Amazon Keyspaces (for Apache Cassandra)

-   Amazon Neptune

-   Amazon Quantum Ledger Database (Amazon QLDB)

-   Amazon RDS

-   Amazon Redshift

-   Amazon Timestream

#### Management and Governance:

-   AWS CLI

-   AWS CloudFormation

-   AWS CloudTrail

-   Amazon CloudWatch

-   AWS Config

-   AWS Trusted Advisor

#### Migration and Transfer:

-   AWS Database Migration Service (AWS DMS)

-   AWS DataSync

-   AWS Schema Conversion Tool (AWS SCT)

-   AWS Snow Family

#### Networking and Content Delivery:

-   AWS Direct Connect

-   Elastic Load Balancing (ELB)

-   Amazon Route 53

-   Amazon VPC (and associated features)

#### Security, Identity, and Compliance:

-   AWS CloudHSM

-   AWS Directory Service

-   AWS Identity and Access Management (IAM)

-   AWS Key Management Service (AWS KMS)

-   AWS Secrets Manager

#### Storage:

-   Amazon Elastic Block Store (Amazon EBS)

-   Amazon S3

-   Amazon S3 Glacier
