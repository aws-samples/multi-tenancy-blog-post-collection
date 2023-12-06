# thought_leadership

## New articles

| [How Sela Builds Low-Latency Serverless Control Planes for Hybrid-Tenant Developer Platforms](https://aws.amazon.com/blogs/apn/how-sela-builds-low-latency-serverless-control-planes-for-hybrid-tenant-developer-platforms/) |
|:----------|
| *Created: 27 OCT 2023 by Yehuda Cohen, Puneet Kalra, Laurell McCaffrey* | 
| Explore the hybrid-tenant architecture Sela designed and implemented for Dittofi’s hosting platform. We’ll focus on the underlying architecture of the Dittofi hosting platform where tenant workloads run, as well as the architecture for the hybrid-tenant control plane that enables the provisioning, de-provisioning, and updating of tenants. We’ll pay special attention to the user experience during the development of no-code applications and the measures Sela put in place to enable near-real-time code generation. | 
|  | 

| [Tenant Onboarding Best Practices in SaaS with the AWS Well-Architected SaaS Lens](https://aws.amazon.com/blogs/apn/tenant-onboarding-best-practices-in-saas-with-the-aws-well-architected-saas-lens/) |
|:----------|
| *Created: 26 SEP 2023 by Dhammika Sriyananda* | 
| Uncover architectural best practices related to the recommendations in the AWS Well-Architected SaaS Lens framework for providing a frictionless tenant onboarding experience for a SaaS solution. The technology, tools, and realities of your SaaS environment will influence the specifics of your onboarding experience. With an efficient, automated onboarding mechanism, your solution will be able to provide a robust, repeatable onboarding flow that will benefit both customers (tenants) and your SaaS business. | 
|  | 

| [Data Ingestion in a Multi-Tenant SaaS Environment Using AWS Services](https://aws.amazon.com/blogs/apn/data-ingestion-in-a-multi-tenant-saas-environment-using-aws-services/) |
|:----------|
| *Created: 30 AUG 2023 by Peter Yang, Ranjith Raman* | 
| AWS experts break down how you can build a multi-tenant data ingestion and processing engine using AWS services. We examine each component of this data pipeline and examine some of the key considerations that can influence how you approach designing a SaaS multi-tenant data ingestion process. We also explore how multi-tenant streaming data can be ingested, transformed, and stored using AWS services while ensuring there are constructs built in to the pipeline to ensure secure processing of the data. | 
|  | 

## Older posts
| [Optimizing Cost Per Tenant Visibility in SaaS Solutions](https://aws.amazon.com/blogs/apn/optimizing-cost-per-tenant-visibility-in-saas-solutions/) |
|:----------|
| *Created: 17 MAR 2023 by Ujwal Bukka* | 
| One of the top challenges in operating a software-as-a-service (SaaS) solution is measuring the resource consumption of individual tenants in order to understand their usage patterns, attribute costs, and more. The dynamic nature of SaaS environment and shifting needs makes it even more challenging. Explore how you can use the tenant resource consumption data you gathered to optimize your SaaS architecture, to improve operational footprint of SaaS environment and to drive business decisions. | 
|  | 

| [How CyberArk Built a Tenant Management Service for its SaaS Offering](https://aws.amazon.com/blogs/apn/how-cyberark-built-tenant-management-service-for-its-saas-offering/) |
|:----------|
| *Created: 23 FEB 2023 by Ran Isenberg, Yossi Lagstein* | 
| A tenant management service manages the tenant’s provisioning and lifecycle, and tenant management is usually one of the first services SaaS providers build for their SaaS control plane, as the tenant onboarding experience must be simple and fast. Learn how CyberArk built a serverless, simple, and scalable tenant management service. Its primary responsibility is adding new tenants and provisioning multiple CyberArk products to the tenants according to the customer’s subscription. | 
|  | 

| [Multi-Tenant Customer Routing for Amazon RDS and Amazon Redshift with Heimdall Data](https://aws.amazon.com/blogs/apn/multi-tenant-customer-routing-for-amazon-rds-and-amazon-redshift-with-heimdall-data/) |
|:----------|
| *Created: 07 NOV 2022 by Erik Brandsberg, Antony Prasad Thevaraj* | 
| Learn how the Heimdall Database Proxy can be configured to provide customer query routing for Amazon RDS for Postgres, although any SQL database type including Amazon Redshift can be supported. This provides a single Heimdall Proxy endpoint to access data for multiple customers from multiple databases, transparently. Heimdall Data provides functionality needed to support many complex database environments, and solves many of the challenges in scaling database access. | 
|  | 

| [Simplifying Tenant Cost Allocation in a SaaS Solution on AWS with CloudZero](https://aws.amazon.com/blogs/apn/simplifying-tenant-cost-allocation-in-a-saas-solution-on-aws-with-cloudzero/) |
|:----------|
| *Created: 05 OCT 2022 by Kevin Mueller, Bill Tarr, Ujwal Bukka* | 
| The Cost Optimization Pillar of the SaaS Lens for the AWS Well-Architected Framework emphasizes the need for expenditure awareness by measuring tenant consumption and correlating it to tenant costs. This can prove challenging in SaaS solutions, where resources are shared across tenants. Learn how to leverage CloudZero to gain visibility into tenant consumption, and how you can gain insights into tenant cost using CloudZero’s Enhanced Unit Cost Analytics. | 
|  | 

| [Enabling Tiering and Throttling in a Multi-Tenant Amazon EKS SaaS Solution Using Amazon API Gateway](https://aws.amazon.com/blogs/apn/enabling-tiering-and-throttling-in-a-multi-tenant-amazon-eks-saas-solution-using-amazon-api-gateway/) |
|:----------|
| *Created: 26 SEP 2022 by Ranjith Raman, Peter Yang* | 
| Every SaaS architecture must introduce mechanisms and policies that prevent noisy neighbor conditions. Getting these policies right is essential to building a robust SaaS solution that delivers a consistent experience to customers. This post looks at the different strategies that can be used to introduce the throttles (transaction rate) and quotas (transaction volume) that manage each tenant’s activity, exploring the various AWS services that can be used to bring these concepts to life. | 
|  | 

| [Managing MSP Costs with VMware Cloud Director Service Multi-Tenancy](https://aws.amazon.com/blogs/apn/managing-msp-costs-with-vmware-cloud-director-service-multi-tenancy/) |
|:----------|
| *Created: 21 SEP 2022 by Adrian Begg, Steve Lord, Kiran Reid* | 
| VMware Cloud on AWS allows customers to migrate their workloads faster without having to refactor or change any application code or logic. Many MSPs have built highly successful businesses on VMware Cloud Director-powered clouds running in their own data centers. These MSPs have earned trust with their customers over many years as trusted advisors and partners. Explore some of the challenges MSPs face and how using multi tenancy with VMware Cloud Director Service can help address them. | 
|  | 

| [Storing Multi-Tenant SaaS Data with Amazon OpenSearch Service](https://aws.amazon.com/blogs/apn/storing-multi-tenant-saas-data-with-amazon-opensearch-service/) |
|:----------|
| *Created: 13 SEP 2022 by Madhukar Thumma, Ujwal Bukka* | 
| Amazon OpenSearch Service is frequently used by SaaS providers to address a broad range of use cases. The use of Amazon OpenSearch Service in a multi-tenant environment, however, introduces a collection of new considerations that will influence how you partition, isolate, deploy, and manage your solution. Explore the strategies and patterns that are used to address these common issues, and look at the specific models used to represent and isolate each tenant’s data with Amazon OpenSearch Service constructs. | 
|  | 

| [Designing a Multi-Tenant SFTP Server with AWS Transfer Family](https://aws.amazon.com/blogs/apn/designing-a-multi-tenant-sftp-server-with-aws-transfer-family/) |
|:----------|
| *Created: 23 AUG 2022 by Hiroto Sakuraya* | 
| Data security is a particularly important topic for multi-tenant SaaS applications that handle customers’ sensitive data. How to securely segregate tenant data and how to provide data access to customers will vary depending on the SaaS solution’s architecture and its requirements. This post explores how SaaS vendors can build secure, scalable, and cost-effective data exchange mechanisms using SFTP (SSH File Transfer Protocol) with AWS managed services like AWS Transfer Family. | 
|  | 

| [Migrating Elasticsearch on Amazon EC2 to Modernized, Multi-Tenant Amazon OpenSearch Service Architecture](https://aws.amazon.com/blogs/apn/migrating-elasticsearch-on-amazon-ec2-to-modernized-multi-tenant-amazon-opensearch-service-architecture/) |
|:----------|
| *Created: 22 AUG 2022 by Benjamin Draper, Irshad Buchh* | 
| For a recent project, NTT DATA Services was asked to architect and design the migration of a customer’s backend search tool used by two of its applications. Both applications were leveraging Elasticsearch for data storage. Learn how NTT DATA used some of the DevOps pillars to implement migrations using an active migration strategy. The goal was to move from individual Elasticsearch instances on Amazon EC2 to a single multi-tenant hosted Elasticsearch solution per region—in this case, Amazon OpenSearch Service. | 
|  | 

| [Partitioning and Isolating Multi-Tenant SaaS Data with Amazon S3](https://aws.amazon.com/blogs/apn/partitioning-and-isolating-multi-tenant-saas-data-with-amazon-s3/) |
|:----------|
| *Created: 14 JUN 2022 by Kevin Hakanson, Tod Golding* | 
| Many SaaS applications store multi-tenant data with Amazon S3. Learn about the various strategies that can be applied when partitioning tenant data with S3, and explore the considerations that may influence how and when you apply these mechanisms in your own solution. See how this influences tenant isolation and the accessibility of S3 objects, and dive deep on tenant activity and cost tracking, lifecycle management for objects, and additional bucket security configurations. | 
|  | 

| [Manage Multi-Tenant Remote Access with Cisco Secure Firewall Cloud Native on Amazon EKS](https://aws.amazon.com/blogs/apn/manage-multi-tenant-remote-access-with-cisco-secure-firewall-cloud-native-on-amazon-eks/) |
|:----------|
| *Created: 13 JUN 2022 by Muffadal Quettawala, Anubhav Swami* | 
| Cisco Secure Firewall Cloud Native (SFCN) is a lightweight network firewall in a cloud-native form factor. Offering granular control and massive throughput potential, SFCN enables security at the speed of business. It offers an easy way to deploy scalable remote access VPN architecture as its primary use case. The solution utilizes Amazon Amazon EKS and other cloud-native services including Amazon ElastiCache for Redis and Amazon Amazon EFS. | 
|  | 

| [Implementing a Multi-Tenant MLaaS Build Environment with Amazon SageMaker Pipelines](https://aws.amazon.com/blogs/apn/implementing-a-multi-tenant-mlaas-build-environment-with-amazon-sagemaker-pipelines/) |
|:----------|
| *Created: 10 MAR 2022 by Mehran Najafi, Michael Pelts* | 
| Organizations hosting customer-specific machine learning models on AWS have unique isolation and performance requirements and require a solution that provides a scalable, high-performance, and feature-rich ML platform. Learn how Amazon SageMaker Pipelines helps you to pre-process data, build, train, tune, and register ML models in SaaS applications. We’ll focus on best practices for building tenant-specific ML models with particular focus on tenant isolation and cost attribution. | 
|  | 

| [How Pegasystems Manages Multi-Tenant WebSocket Rate Limiting Issues with Amazon API Gateway](https://aws.amazon.com/blogs/apn/how-pegasystems-manages-multi-tenant-websocket-rate-limiting-issues-with-amazon-api-gateway/) |
|:----------|
| *Created: 17 JAN 2022 by Steven Warwick, Josue Lima* | 
| The Pega Digital Messaging Service allows customer service applications to receive and send messages in a simplified, consistent format over digital channels such as Apple Messages for Business, Facebook, SMS, WhatsApp, Twitter, and web chat. This post explores how Pegasystems built a solution to enable the Pega Digital Messaging service to manage inbound multi-tenant WebSocket connection and message rates using Amazon API Gateway, AWS Lambda, SQS, and Amazon DynamoDB. | 
|  | 

| [Implementing SaaS Tenant Isolation Using Amazon SageMaker Endpoints and IAM](https://aws.amazon.com/blogs/apn/implementing-saas-tenant-isolation-using-amazon-sagemaker-endpoints-and-iam/) |
|:----------|
| *Created: 15 NOV 2021 by Michael Pelts, Joshua Fox* | 
| As multi-tenant SaaS providers look to leverage machine learning services, they must consider how they’ll protect the data that flows in and out of these services from different tenants. Learn how tenant isolation of machine learning services can be achieved using AWS IAM, and how the integration between IAM, Amazon SageMaker, and many other AWS services provide developers with a rich set of mechanisms that can be applied to realize tenant isolation goals. | 
|  | 

| [Building a Multi-Tenant SaaS Solution Using AWS Serverless Services](https://aws.amazon.com/blogs/apn/building-a-multi-tenant-saas-solution-using-aws-serverless-services/) |
|:----------|
| *Created: 26 AUG 2021 by Anubhav Sharma, Ujwal Bukka* | 
| The move to a SaaS delivery model is accompanied by a desire to maximize cost and operational efficiency. This can be especially challenging in a multi-tenant environment where the activity of tenants can be difficult to predict. In this post, AWS experts look into a reference solution that provides an end-to-end view of a functional multi-tenant serverless SaaS environment. The goal is to explore the architecture and design considerations that went into creating this reference solution. | 
|  | 

| [Building a Multi-Tenant SaaS Solution Using Amazon EKS](https://aws.amazon.com/blogs/apn/building-a-multi-tenant-saas-solution-using-amazon-eks/) |
|:----------|
| *Created: 04 MAR 2021 by Toby Buckley, Ranjith Raman* | 
| As more organizations make the move to a SaaS delivery model, many are choosing Amazon EKS as the target for their solutions. The programming model, cost efficiency, security, deployment, and operational attributes of Amazon EKS represent a compelling model for SaaS providers. Walk through the key architectural elements of a sample architecture, and learn how to isolate tenants within an EKS cluster, automate tenant onboarding, manage tenant identities, and support routing of tenant workloads. | 
|  | 

| [Explore SaaS Tenant Isolation Strategies in New SaaS Whitepaper](https://aws.amazon.com/blogs/apn/explore-saas-tenant-isolation-strategies-in-new-saas-whitepaper/) |
|:----------|
| *Created: 25 SEP 2020 by Tod Golding* | 
| Tenant isolation is fundamental to the design and development of SaaS systems, enabling providers to reassure customers their resources cannot be accessed by other tenants. While the importance of isolation is well understood, the strategies for realizing a robust isolation model vary significantly. Learn how our new SaaS Tenant Isolation Strategies whitepaper assembles a collection of best practices and considerations that often shape your approach to implementing isolation in a SaaS environment. | 
|  | 

