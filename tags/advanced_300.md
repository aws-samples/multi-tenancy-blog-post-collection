# advanced_300

## New articles

| [Tracing Tenant Activity for Multi-Account SaaS with AWS Distro for Open Telemetry](https://aws.amazon.com/blogs/apn/tracing-cross-account-tenant-activities-for-saas-solutions-with-aws-distro-for-open-telemetry/) |
|:----------|
| *Created: 08 SEP 2023 by Peter Yang, Tomo Sakatoku* | 
| In this post, delve into the process of detecting tenant activities within microservices spanning multiple AWS accounts. We provide insights into instrumenting AWS Lambda functions to include tenant information in tracing using ADOT and demonstrated how to establish a service map across several AWS accounts using Amazon CloudWatch. By leveraging AWS observability technology, SaaS providers can enhance operational efficiency and redirect their attention towards their desired development goals. | 
|  | 

| [Data Ingestion in a Multi-Tenant SaaS Environment Using AWS Services](https://aws.amazon.com/blogs/apn/data-ingestion-in-a-multi-tenant-saas-environment-using-aws-services/) |
|:----------|
| *Created: 30 AUG 2023 by Peter Yang, Ranjith Raman* | 
| AWS experts break down how you can build a multi-tenant data ingestion and processing engine using AWS services. We examine each component of this data pipeline and examine some of the key considerations that can influence how you approach designing a SaaS multi-tenant data ingestion process. We also explore how multi-tenant streaming data can be ingested, transformed, and stored using AWS services while ensuring there are constructs built in to the pipeline to ensure secure processing of the data. | 
|  | 

## Older posts
| [Multitenant best practices for Amazon RDS Custom for Oracle](https://aws.amazon.com/blogs/database/multitenant-best-practices-for-amazon-rds-custom-for-oracle/) |
|:----------|
| *Created: 18 APR 2023 by Arnab Saha, Vishal Patil* | 
| Amazon Relational Database Service (Amazon RDS) Custom for Oracle is a managed database service for legacy, custom, and packaged applications that require access to the underlying operating system and database environment. Amazon RDS Custom now supports the Oracle Multitenant option on Oracle Database version 19c using Enterprise Edition. With this release, an RDS Custom for […] | 
|  | 

| [Managed database backup and recovery in a multi-tenant SaaS application](https://aws.amazon.com/blogs/database/managed-database-backup-and-recovery-in-a-multi-tenant-saas-application/) |
|:----------|
| *Created: 07 DEC 2022 by Dave Roberts* | 
| Exporting data or restoring to an earlier point in time are core capabilities that customers look for in a software as a service (SaaS) product. Database backup and recovery is vital to business continuity and regulatory compliance. You should understand how your multi-tenant data partitioning model will affect the backup and restore capabilities of your […] | 
|  | 

| [Multi-Tenant Customer Routing for Amazon RDS and Amazon Redshift with Heimdall Data](https://aws.amazon.com/blogs/apn/multi-tenant-customer-routing-for-amazon-rds-and-amazon-redshift-with-heimdall-data/) |
|:----------|
| *Created: 07 NOV 2022 by Erik Brandsberg, Antony Prasad Thevaraj* | 
| Learn how the Heimdall Database Proxy can be configured to provide customer query routing for Amazon RDS for Postgres, although any SQL database type including Amazon Redshift can be supported. This provides a single Heimdall Proxy endpoint to access data for multiple customers from multiple databases, transparently. Heimdall Data provides functionality needed to support many complex database environments, and solves many of the challenges in scaling database access. | 
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

| [How Multi-Tenancy with AWS Transfer Family is a Cost-Effective Solution](https://aws.amazon.com/blogs/apn/how-multi-tenancy-with-aws-transfer-family-is-a-cost-effective-solution/) |
|:----------|
| *Created: 20 JUL 2022 by Ben Bridts* | 
| AWS Transfer Family provides SFTP, FTPS, and/or FTP access to Amazon S3 or Amazon Amazon EFS. It does that by providing a secure, highly available, and scalable server endpoint. You pay for the time this endpoint is enabled, and for data transfer (upload and download). Learn how this makes a multi-tenant setup where an endpoint is shared between different users (or applications), a more cost-efficient solution than having dedicated endpoints. | 
|  | 

| [Partitioning and Isolating Multi-Tenant SaaS Data with Amazon S3](https://aws.amazon.com/blogs/apn/partitioning-and-isolating-multi-tenant-saas-data-with-amazon-s3/) |
|:----------|
| *Created: 14 JUN 2022 by Kevin Hakanson, Tod Golding* | 
| Many SaaS applications store multi-tenant data with Amazon S3. Learn about the various strategies that can be applied when partitioning tenant data with S3, and explore the considerations that may influence how and when you apply these mechanisms in your own solution. See how this influences tenant isolation and the accessibility of S3 objects, and dive deep on tenant activity and cost tracking, lifecycle management for objects, and additional bucket security configurations. | 
|  | 

| [Throttling a tiered, multi-tenant REST API at scale using API Gateway: Part 2](https://aws.amazon.com/blogs/architecture/throttling-a-tiered-multi-tenant-rest-api-at-scale-using-api-gateway-part-2/) |
|:----------|
| *Created: 09 MAY 2022 by Nick Choi* | 
| In Part 1 of this blog series, we demonstrated why tiering and throttling become necessary at scale for multi-tenant REST APIs, and explored tiering strategy and throttling with Amazon API Gateway. In this post, Part 2, we will examine tenant isolation strategies at scale with API Gateway and extend the sample code from Part 1. […] | 
|  | 

| [Throttling a tiered, multi-tenant REST API at scale using API Gateway: Part 1](https://aws.amazon.com/blogs/architecture/throttling-a-tiered-multi-tenant-rest-api-at-scale-using-api-gateway-part-1/) |
|:----------|
| *Created: 06 MAY 2022 by Nick Choi* | 
| Many software-as-a-service (SaaS) providers adopt throttling as a common technique to protect a distributed system from spikes of inbound traffic that might compromise reliability, reduce throughput, or increase operational cost. Multi-tenant SaaS systems have an additional concern of fairness; excessive traffic from one tenant needs to be selectively throttled without impacting the experience of other […] | 
|  | 

| [Implementing a Multi-Tenant MLaaS Build Environment with Amazon SageMaker Pipelines](https://aws.amazon.com/blogs/apn/implementing-a-multi-tenant-mlaas-build-environment-with-amazon-sagemaker-pipelines/) |
|:----------|
| *Created: 10 MAR 2022 by Mehran Najafi, Michael Pelts* | 
| Organizations hosting customer-specific machine learning models on AWS have unique isolation and performance requirements and require a solution that provides a scalable, high-performance, and feature-rich ML platform. Learn how Amazon SageMaker Pipelines helps you to pre-process data, build, train, tune, and register ML models in SaaS applications. We’ll focus on best practices for building tenant-specific ML models with particular focus on tenant isolation and cost attribution. | 
|  | 

| [Migrate On-Premises Multi-Tenant Systems to Amazon Elastic Kubernetes Service](https://aws.amazon.com/blogs/mt/migrate-on-premises-multi-tenant-systems-to-amazon-elastic-kubernetes-service/) |
|:----------|
| *Created: 03 MAR 2022 by Scott Wainner* | 
| Managing the deployment of containers in a multi-tenant environment presents a number of new challenges for many of my customers. Some organizations have explored building and managing their own Kubernetes container orchestration environment, but the management challenges lead them to evaluate Amazon Elastic Kubernetes Service (Amazon EKS). Particularly, Independent Software Vendors (ISVs) are using a […] | 
|  | 

| [Using ELB Access Logs and AWS Application Cost Profiler to track tenant cost of shared AWS Infrastructure](https://aws.amazon.com/blogs/mt/elb-access-logs-and-aws-application-cost-profiler-track-tenant-cost-of-shared-aws-infrastructure/) |
|:----------|
| *Created: 04 JAN 2022 by Ryan Peterson, Galen Dunkleberger* | 
| In our previous post on AWS Application Cost Profiler (ACP), we demonstrated how application owners instrument a serverless application with tenant metadata in a contextual format using AWS X-Ray. This tenant metadata is necessary for ACP to generate a granular cost breakdown of shared AWS resources used by multi-tenant applications. These granular cost insights let […] | 
|  | 

| [Performance Efficiency in AWS Multi-Tenant SaaS Environments](https://aws.amazon.com/blogs/apn/performance-efficiency-in-aws-multi-tenant-saas-environments/) |
|:----------|
| *Created: 26 OCT 2021 by Humberto Somensi* | 
| Maximizing performance is a key area of focus for all architects. Achieving optimal performance, however, can be challenging in SaaS environments where multi-tenant workloads can make it difficult to efficiently profile and scale your environment. This post dives deep into the challenges, opportunities, and best practices of efficiently managing performance in multi-tenant SaaS environments on AWS. We’ll review these topics through the lens of an example multi-tenant search application. | 
|  | 

| [Using AWS X-Ray and AWS Application Cost Profiler to track tenant cost of shared AWS Infrastructure](https://aws.amazon.com/blogs/mt/using-aws-x-ray-and-aws-application-cost-profiler-to-track-tenant-cost-of-shared-aws-infrastructure/) |
|:----------|
| *Created: 30 SEP 2021 by Ryan Peterson, Venkata Kampana* | 
| In our last blog post, we introduced AWS Application Cost Profiler (ACP), where we discussed this new service that allows customers, running multi-tenant applications, to receive granular cost breakdowns of shared AWS resources across their tenants. AWS Application Cost Profiler provides customers, especially SaaS ISVs, with a standard mechanism to correlate and report their infrastructure […] | 
|  | 

| [Managing the account lifecycle in account-per-tenant SaaS environments on AWS](https://aws.amazon.com/blogs/mt/managing-the-account-lifecycle-in-account-per-tenant-saas-environments-on-aws/) |
|:----------|
| *Created: 24 SEP 2021 by Keith P* | 
| Software as a service (SaaS) companies have many options when they implement multi-tenancy in their applications. The AWS SaaS Factory Program provides recommendations for different deployment patterns depending on factors such as cost, compliance, and end-customer requirements. You might find that silo methods like VPC-per-tenant are not sufficient. Your application might be in a highly […] | 
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

| [Storing Multi-Tenant SaaS Data in a Serverless Environment with Amazon Keyspaces](https://aws.amazon.com/blogs/apn/storing-multi-tenant-saas-data-in-a-serverless-environment-with-amazon-keyspaces/) |
|:----------|
| *Created: 25 JAN 2021 by Tod Golding, Muhammad Sadigain Tahir* | 
| With Amazon Keyspaces, AWS has enabled SaaS providers to run their Apache Cassandra workloads using a fully managed, serverless offering. This option allows you to leverage the strengths of Cassandra while getting all of the scale, cost, reliability, and operational efficiency that comes with a managed model. Learn how Amazon Keyspaces can be used to store data in a multi-tenant architecture and review common models for partitioning each tenant’s data. | 
|  | 

| [Building a cross-account CI/CD pipeline for single-tenant SaaS solutions](https://aws.amazon.com/blogs/devops/cross-account-ci-cd-pipeline-single-tenant-saas/) |
|:----------|
| *Created: 17 OCT 2020 by Rafael Ramos* | 
| This post describes how to automate the deployment process of a single-tenant SaaS solution to deliver software quickly, securely, and less error-prone for each existing tenant. To achieve a higher level of environment segregation across the tenants, I demonstrate all the steps to build and configure a CI/CD pipeline using AWS CodeCommit, AWS CodePipeline, AWS CodeBuild, and AWS CloudFormation. For each new version, the pipeline automatically deploys the same application version on the multiple tenant AWS accounts. | 
|  | 

| [Using Amazon SQS in a Multi-Tenant SaaS Solution](https://aws.amazon.com/blogs/apn/using-amazon-sqs-in-a-multi-tenant-saas-solution/) |
|:----------|
| *Created: 09 OCT 2020 by Raju Patel* | 
| Modern applications often rely on queuing for service integrations, batch processing, or as part of workflow orchestration. Queues are key to adding scale and resiliency to your environment. This is especially true in software-as-a-service (SaaS) environments. Explore some of the common scenarios used when building SaaS solutions with Amazon Simple Queue Service (SQS), and learn how data isolation, scalability, and compliance requirements might influence the queuing model you select. | 
|  | 

| [Partitioning Pooled Multi-Tenant SaaS Data with Amazon DynamoDB](https://aws.amazon.com/blogs/apn/partitioning-pooled-multi-tenant-saas-data-with-amazon-dynamodb/) |
|:----------|
| *Created: 10 AUG 2020 by Anubhav Sharma, Tod Golding* | 
| As you design, develop, and build SaaS solutions on AWS, you must think about how you want to partition the data that belongs to each of your customers (tenants). In this post, experts from AWS SaaS Factory focus on what it means to implement the pooled model with Amazon DynamoDB. We’ll outline basic strategies to partition and isolate data by tenant, and illustrate common techniques you can use to avoid the “hot” partition problem that’s often associated with partitioning tenant data in a pooled model. | 
|  | 

| [In-Depth Strategies for Building a Scalable, Multi-Tenant SaaS Solution with Amazon Redshift](https://aws.amazon.com/blogs/apn/in-depth-strategies-for-building-a-scalable-multi-tenant-saas-solution-with-amazon-redshift/) |
|:----------|
| *Created: 27 MAR 2020 by Anubhav Sharma* | 
| Software-as-a-Service (SaaS) presents developers and architects with a unique set of challenges. One essential decision you’ll have to make is how to partition data for each tenant of your system. Learn how to harness Amazon Redshift to build a scalable, multi-tenant SaaS solution on AWS. This post explores trategies that are commonly used to partition and isolate tenant data in a SaaS environment, and how to apply them in Amazon Redshift. | 
|  | 

