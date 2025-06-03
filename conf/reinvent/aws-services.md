# AWS Services <!-- omit in toc -->

- [Analytic](#analytic)
- [Application Integration](#application-integration)
- [AWS Cost management](#aws-cost-management)
- [Business Applications](#business-applications)
- [Compute](#compute)
  - [Instances (VM)](#instances-vm)
  - [Container](#container)
  - [Serverless](#serverless)
  - [Edge and hybrid](#edge-and-hybrid)
  - [Cost and capacity management](#cost-and-capacity-management)
- [Database](#database)
- [Developer Tools](#developer-tools)
- [End user Computing](#end-user-computing)
- [Front-end web \& Mobile](#front-end-web--mobile)
- [Game Development](#game-development)
- [Internet of Things.](#internet-of-things)
- [Management \& Governance](#management--governance)
- [Migration \& Transfer](#migration--transfer)
- [Networking \& Content Delivery](#networking--content-delivery)
  - [Network foundations](#network-foundations)
  - [Application networking](#application-networking)
  - [Edge networking](#edge-networking)
  - [Hybrid connectivity](#hybrid-connectivity)
  - [Network security](#network-security)
- [Security, Identity, \& Compliance](#security-identity--compliance)
- [Storage](#storage)

# Analytic

- Athena
- AWS CLean Rooms
- CloudSearch – Managed search service
- AWS Data Exchange – Easily find, subscribe to, and use third-party data.
- Data Pipeline – Orchestration for data-drive workflows.
- Amazon DataZone – Unlock data across organizational boundaries with built-in governance.
- EMR (Elastic MapReduce) – Managed Hadoop Framework
- Amazon FinSpace – Store, catalog, prepare, and analyze financial industry data.
- AWS Glue – serverless data integration service.
- AWS Glue DataBrew – Visual data preparation tool to clean and normalize data for analytic and machine learning.
- Kinesis – Work with Real-Time Streaming data.
- AWS Lake Formation – makes it easy to set up a secure data lake.
- MSK – Fully managed, highly available, and secure service for Apache Kafka.
- Amazon OpenSearch Service – Run open-source OpenSearch or ElasticSearch using managed Cluster or Serverless deployments.
- QuickSight – Fast, easy to use business analytics.
- Amazon Redshift – Fast, Simple, Cost-Effective Data Warehouse.

# Application Integration

- Amazon AppFlow – Integrates apps and automates data flows without code.
- Amazon EventBridge – Serverless service for building event-driven applications.
- Managed Apache AirFlow – Run Apache Airflow without provisioning or managing servers.
- Amazon MQ – Managed message broker service for Apache ActiveMQ and RabbitMQ.
- Simple Notification Service – managed message topics for Pub/Sub.
- Simple Queue Service – SQS Manage message Queues.
- Step Functions – Coordinate Distribute Application.
- SWF – Workflow service for coordination application components.

# AWS Cost management

- AWS Application Const Profiler – Cost per tenant and workload.
- AWS Billing Conductor – Simplifying your billing practice.
- AWS Budgets – Set custom budgets and receipt alerts.
- AWS Cost Explorer – visualize and Explorer your AWS Costs and Usage.
- AWS Marketplace Subscriptions – Digital catalog where you can find, buy, and deploy software.

# Business Applications

- Amazon Chime – a communications service that transforms online meetings.
- Amazon Chime SDK – Real-time communication for your application.
- Amazon connect – contact center that enables engagement at any scale.
- Amazon HoneyCode – Build mobile and web apps without programming.
- Amazon Pinpoint – Engage Users via Email, SMS, Push & Analytics.
- Amazon Simple Email Service – Email Sending and Receive Service.
- AWS Supply Chain – Supply Chain management application to manage your supply chain systems.
- AWS Wickr – Secure Communication with end-to-end encryption.
- Amazon WorkDocs – Secure Enterprise Storage and Sharing service.
- Amazon WorkMail – Secure Email and Calendaring Service.

# Compute

## Instances (VM)

- AWS Elastic Beanstalk
- Amazon EC2
- Amazon EC2 Spot
- Amazon EC2 Autoscaling
- Amazon Lightsail
- AWS Batch
- AWS Parallel Computing Service

## Container

- Amazon ECS
- Amazon ECS Anywhere
- Amazon ECR
- Amazon EKS
- Amazon EKS Anywhere, Fully managed Kubernetes service
- AWS Fargate
- AWS App Runner

## Serverless

- AWS Lambda

## Edge and hybrid

- AWS Outposts
- AWS Snow family - Collect and process data in rugged or disconnected edge environments
- AWS Wavelength -Deliver ultra-low latency application for 5G devices
- VMware Cloud on AWS - Preferred service for all vSphere workloads to rapidly extend and migrate to the cloud
- AWS Local Zones - Run latency sensitive applications closer to end-users

## Cost and capacity management

- AWS Savings Plan
- AWS Compute Optimizer
- EC2 Image Builder
- ELB

# Database

| type        | examples                                                                                       | services                                |
| ----------- | ---------------------------------------------------------------------------------------------- | --------------------------------------- |
| relational  | Traditional app, ERP, CRM, ecommerce                                                           | Aurora, RDS, Redshift                   |
|             | GenAI (chatbots with RAG, similarity search, recommendation systems, and more)                 |                                         |
| key-value   | high-traffic webapp, ecommerce systems, gaming app                                             | DynamoDB                                |
|             | GenAI (similarity search using DynamoDB zero-ETL integration with Amazon OpenSearch Service)   |                                         |
| in-memory   | Caching, session management, gaming leaderboards, geospatial applications                      | ElasticCache, MemoryDB                  |
|             | GenAI (chatbots with RAG, semantic caching, recommendation systems, fraud detection, and more) |                                         |
| Document    | Content management, catalogs, user profiles                                                    | DocumentDB (with MongoDB compatibility) |
|             | GenAI (chatbots with RAG, similarity search, recommendation systems, and more)                 |                                         |
| Graph       | Fraud detection, social networking, recommendation engines                                     | Neptune                                 |
|             | GenAI (GraphRAG, enhanced fraud detection, discovery of new answers, and more)                 |                                         |
| Wide column | High-scale industrial apps for equipment maintenance, fleet management, and route optimization | Keyspaces                               |
| Time series | Internet of Things (IoT) applications, DevOps, industrial telemetry                            | Timestream                              |


# Developer Tools

- AWS AppConfig – use feature flags, operational flags, and other runtime configuration to make chages quickly and safely on production.
- Application Composer – Visually design and build serverless applications quickly.
- Cloud9 – IDE for Writing, Running, and Debugging code.
- CloudShell – Browser based shell with AWS CLI access from the AWS Management Console.
- CodeArtifact – Secure, scalable, and cost-effective artifact management for software developer.
- CodeBuild – Build and Test Code.
- Amazon CodeCatalyst – Integrated DevOps service.
- CodeCommit – Store code in Private git Repositories.
- CodeDeploy – Automate Code Deployments.
- CodePipeline – Release software using Continuous Delivery.
- CodeStart – Quickly develop, build, and deploy applications.
- Amazon CodeWhisperer – Build applications faster with the ML-powered coding companion.
- AWS FIS – Improve resiliency and performance with controlled experiments.
- X-Ray – Analyze and Debug your applications.

# End user Computing

- AppStream 2.0 – Stream desktop applications securely to any web browser
- WorkSpaces – Desktop in the cloud.
- WorkSpaces Web – Cloud-native secure web access.


# Front-end web & Mobile

- AWS Amplify – complete platform-frameworks & tools and app services for developing, building, testing, and running mobile and web apps.
- AWS AppSync – realtime data sync using GraphQL for mobile and web Apps. Online or Offline.
- Device Farm – Test Android, iOSm and web apps on real devices in the cloud.
- Amazon Location Service – Securely and easily add location data to applications.

# Game Development

- Amazon GameLift – Deploy and Scale Session-base multiplayer games.
- Amazon GameSparks – build, optimize, and scale customizable game features.

# Internet of Things.

- FreeRTOS – an IoT operating system for microcontrollers.
- IoT 1-Click – Trigger AWS Lambda functions from simple devices.
- IoT Core – connect devices to the cloud.
- IoT Device defender – Secure your fleet of connected IoT devices.
- IoT Device Management – Securely manage Fleet as small as One Device, or as Broad as Millions of Devices.
- IoT Events – Detect and respond to events from IoT sensors and Industrial IoT equipment.
- AWS IoT FleetWise – Easily collect, organize, and transfer vehicle data to the cloud at scale.
- IoT Greengrass – Deploy and run code on your devices.
- IoT RoboRunner – optimize robotics automations.
- IoT SiteWise – data driven decisions in Industrial operations.
- IoT TwinMake – Easily create digital twins of real-world systems to optimize operations.

# Management & Governance

- AWS Auto Scaling – Enables you to quickly scale your entire application on AWS.
- AWS Chatbot – ChatOps for AWS.
- CloudFormation – Create and Manage Resources with templates.
- CloudTrail – Track user activity and API Usage.
- CloudWatch – Monitor Resources and Applications.
- WS Compute Optimizer. – Recommend optimal AWS Compute resource for your workloads.
- Config – Track resource Inventory and Changes.
- Control Tower – The easiest way to set up and govern a secure, compliant multi-account environment.
- Amazon Grafana – Fully managed Grafana service for interactive data visualizations and dashboarding.
- Incident Manager – Automated incident response plans in AWS Systems manager.
- Launch Wizard – Guided deployment for Enterprise application and complex workloads.
- AWS License Manager – Set rules to manage, discover, and report third-party license usage proactively.
- OpsWork – Configuration management with Chef and Puppet.
- AWS Organizations – Central governance and management across AWS accounts.
- Amazon Prometheus – A fully managed Prometheus-compatible monitoring service.
- AWS Proton – Manage your infrastructure so developers can focus on coding.
- AWS Resilience Hub – Provides a central place to define, validate, and track the resiliency of application on AWS.
- AWS Resource Explorer – Easily search for and discover relevant resources across AWS.
- Resource Groups & Tag Editor – lets you Search and group AWS Resources.
- Service Catalog – Create, Share, Organize, and Govern your curated infrastructure as Code (IaC) templates.
- System Manager – Central place to view and manage AWS resources.
- AWS Telco network builder – Automate the deployment and management of telecom networks on AWS.
- Trusted Advisor – Optimize performance and security.
- AWS User Notifications – Configure and view notifications from AWS Services.
- AWS Well-Architected Tool – learn best practices, measure, and improve your workloads.
- AWS health Dashboard.

# Migration & Transfer

- Application Discovery Service – Discover on-premises application inventory and dependencies.
- AWS Application Migration Service (MGN) – automates lift-and-shift migration.
- Database Migration Service – Managed Database Migration Service
- DataSync – simplifies, automates, and accelerates moving data.
- AWS Mainframe Modernization –
- AWS Migration Hub – Simplify and accelerate the migration of data centers to AWS.
- AWS Snow Family -Large Scale Data Transport
- AWS Transfer Family – Fully managed support for SFTP, FTPS and FTP.

# Networking & Content Delivery

## Network foundations

- AWS VPC
- AWS Transit Gateway
- AWS PrivateLink

## Application networking

- AWS VPC Lattice
- AWS AppMesh
- AWS API Gateway
- AWS Cloud Map
- Elastic Load Balancing

## Edge networking

- AWS CloudFront
- AWS Route53
- AWS Global Accelerator – Improve your applications availability and performance using the AWS Global Network.

## Hybrid connectivity

- AWS Direct Connect - Estabilish a private, dedicated AWS connection to your data center, office or colocation environment
- AWS Site-to-Site VPN - create an encrypted network connection to your Amazon VPCs or AWS Transit Gateways
- AWS Client VPN - Connect your remote workforce to AWS or on-premises with a VPN
- AWS Cloud WAN - Easily build, manage, and monitor global WAN

## Network security

- AWS Shield - Safeguard AWS applications against DDoS attacks
- AWS WAF - Protect your webapp from common web exploits
- AWS Network Firewall - Deploy network security across your Amazon VPCs
- AWS Firewall Manager - Centrally configure and manage firewall rules

# Security, Identity, & Compliance

- AWS Artifact – Security compliance reports and agreements
- AWS Audit Manager – Continuously assess controls for risk and compliance
- Certificate Manager – Provision, Manage, and deploy SSL/TLS Certificates
- CloudHSM – managed hardware security Modules in the Cloud
- Cognito – Cunsumer Identity Management and AWS Credentials for Federated Indentities.
- Detective - Investigage and analyze potential security issues.
- Directory Service – Host and manage Active Directory.
- AWS Firewall Manager – Central Management of Firewall rules
- GuardDuty – Intelligent Threat Detection to Protect your AWS Account and Workloads.
- IAM – Manage access to AWS resources.
- IAM Identity Center (Successor to AWS Single Sign-On) – Manage workforce user access to multiple AWS accounts and cloud applications.
- Amazon Inspector – Continual vulnerability management at scale.
- Key management Service – Securely Generate and Manage AWS Encryption keys.
- Amazon Macie – classifies and secures your business-critical content.
- AWS Private Certificate Authority – Manage private certificate authority service.
- Resource Access Manager – Share AWS resources with other accounts or AWS Organizations.
- Security Manager – Easily rotate, manage, and retrieve secrets throughout their lifecycle.
- Security Hub – AWS Security and compliance center.
- Security Lake – Automatically centralize all your security data with a few clicks.
- AWS Signer – Ensuring trust and integrity of your code.
- AWS Verified Permissions – manage, analyze, and enforce permissions across your applications.
- WAF & Shield – Protects against DDoS Attack and Malicious Web Traffic.

# Storage

- AWS Backup – Centrally manages and automates backups across AWS Services
- EFS – Managed File Storage for EC2
- AWS Elastic Disaster Recovery – Scalable, cost-effective application recovery to AWS.
- FSx – Fully managed third-party file systems optimized for variety of workloads.
- S3 – Scalable Storage in the cloud.
- S3 Glacier – Archive Storage in the Cloud
- Storage Gateway – Hybrid Storage Integration.
