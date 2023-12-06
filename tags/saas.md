# saas

## New articles

| [Build a multi-tenant chatbot with RAG using Amazon Bedrock and Amazon EKS](https://aws.amazon.com/blogs/containers/build-a-multi-tenant-chatbot-with-rag-using-amazon-bedrock-and-amazon-eks/) |
|:----------|
| *Created: 18 OCT 2023 by Farooq Ashraf, Jared Dean, Ravi Yadav* | 
| Introduction With the availability of Generative AI models, many customers are exploring ways to build chatbot applications that can cater to a wide range of their end-customers, with each instance of chatbot specializing on a specific tenant’s contextual information, and run such multi-tenant applications at scale with a cost-efficient infrastructure familiar to their development teams. […] | 
|  | 

| [Tenant Onboarding Best Practices in SaaS with the AWS Well-Architected SaaS Lens](https://aws.amazon.com/blogs/apn/tenant-onboarding-best-practices-in-saas-with-the-aws-well-architected-saas-lens/) |
|:----------|
| *Created: 26 SEP 2023 by Dhammika Sriyananda* | 
| Uncover architectural best practices related to the recommendations in the AWS Well-Architected SaaS Lens framework for providing a frictionless tenant onboarding experience for a SaaS solution. The technology, tools, and realities of your SaaS environment will influence the specifics of your onboarding experience. With an efficient, automated onboarding mechanism, your solution will be able to provide a robust, repeatable onboarding flow that will benefit both customers (tenants) and your SaaS business. | 
|  | 

| [Using AWS AppConfig to Manage Multi-Tenant SaaS Configurations](https://aws.amazon.com/blogs/mt/using-aws-appconfig-to-manage-multi-tenant-saas-configurations/) |
|:----------|
| *Created: 25 SEP 2023 by Ran Isenberg (AWS Serverless Hero), Alex Pulver, Bill Tarr* | 
| As a Software as a Service (SaaS) provider, you can benefit from a SaaS operating model in a number of ways. One of the most impactful benefits you can realize is improvements to your operational efficiency, and one of the fundamental techniques you can leverage is to maintain a single software version for all your […] | 
|  | 

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

| [Storing Multi-Tenant SaaS Data with Amazon OpenSearch Service](https://aws.amazon.com/blogs/apn/storing-multi-tenant-saas-data-with-amazon-opensearch-service/) |
|:----------|
| *Created: 13 SEP 2022 by Madhukar Thumma, Ujwal Bukka* | 
| Amazon OpenSearch Service is frequently used by SaaS providers to address a broad range of use cases. The use of Amazon OpenSearch Service in a multi-tenant environment, however, introduces a collection of new considerations that will influence how you partition, isolate, deploy, and manage your solution. Explore the strategies and patterns that are used to address these common issues, and look at the specific models used to represent and isolate each tenant’s data with Amazon OpenSearch Service constructs. | 
|  | 

| [Partitioning and Isolating Multi-Tenant SaaS Data with Amazon S3](https://aws.amazon.com/blogs/apn/partitioning-and-isolating-multi-tenant-saas-data-with-amazon-s3/) |
|:----------|
| *Created: 14 JUN 2022 by Kevin Hakanson, Tod Golding* | 
| Many SaaS applications store multi-tenant data with Amazon S3. Learn about the various strategies that can be applied when partitioning tenant data with S3, and explore the considerations that may influence how and when you apply these mechanisms in your own solution. See how this influences tenant isolation and the accessibility of S3 objects, and dive deep on tenant activity and cost tracking, lifecycle management for objects, and additional bucket security configurations. | 
|  | 

| [Implementing a Multi-Tenant MLaaS Build Environment with Amazon SageMaker Pipelines](https://aws.amazon.com/blogs/apn/implementing-a-multi-tenant-mlaas-build-environment-with-amazon-sagemaker-pipelines/) |
|:----------|
| *Created: 10 MAR 2022 by Mehran Najafi, Michael Pelts* | 
| Organizations hosting customer-specific machine learning models on AWS have unique isolation and performance requirements and require a solution that provides a scalable, high-performance, and feature-rich ML platform. Learn how Amazon SageMaker Pipelines helps you to pre-process data, build, train, tune, and register ML models in SaaS applications. We’ll focus on best practices for building tenant-specific ML models with particular focus on tenant isolation and cost attribution. | 
|  | 

| [Performance Efficiency in AWS Multi-Tenant SaaS Environments](https://aws.amazon.com/blogs/apn/performance-efficiency-in-aws-multi-tenant-saas-environments/) |
|:----------|
| *Created: 26 OCT 2021 by Humberto Somensi* | 
| Maximizing performance is a key area of focus for all architects. Achieving optimal performance, however, can be challenging in SaaS environments where multi-tenant workloads can make it difficult to efficiently profile and scale your environment. This post dives deep into the challenges, opportunities, and best practices of efficiently managing performance in multi-tenant SaaS environments on AWS. We’ll review these topics through the lens of an example multi-tenant search application. | 
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

| [Capturing and Visualizing Multi-Tenant Metrics Inside a SaaS Application on AWS](https://aws.amazon.com/blogs/apn/capturing-and-visualizing-multi-tenant-metrics-inside-a-saas-application-on-aws/) |
|:----------|
| *Created: 22 JAN 2021 by Anubhav Sharma, Tod Golding* | 
| As a SaaS provider, it’s essential to have a clear picture of how tenants are exercising your system. Being able to model the functional and operational profile of tenants and tenant tiers is critical to evolving the business and technical strategies of a SaaS organization. Learn about the role metrics play within a SaaS-based application, and dive deep into a solution that provides all of the infrastructure that will support the ingestion, aggregation, and analysis of SaaS metric data. | 
|  | 

| [Using Amazon SQS in a Multi-Tenant SaaS Solution](https://aws.amazon.com/blogs/apn/using-amazon-sqs-in-a-multi-tenant-saas-solution/) |
|:----------|
| *Created: 09 OCT 2020 by Raju Patel* | 
| Modern applications often rely on queuing for service integrations, batch processing, or as part of workflow orchestration. Queues are key to adding scale and resiliency to your environment. This is especially true in software-as-a-service (SaaS) environments. Explore some of the common scenarios used when building SaaS solutions with Amazon Simple Queue Service (SQS), and learn how data isolation, scalability, and compliance requirements might influence the queuing model you select. | 
|  | 

| [Explore SaaS Tenant Isolation Strategies in New SaaS Whitepaper](https://aws.amazon.com/blogs/apn/explore-saas-tenant-isolation-strategies-in-new-saas-whitepaper/) |
|:----------|
| *Created: 25 SEP 2020 by Tod Golding* | 
| Tenant isolation is fundamental to the design and development of SaaS systems, enabling providers to reassure customers their resources cannot be accessed by other tenants. While the importance of isolation is well understood, the strategies for realizing a robust isolation model vary significantly. Learn how our new SaaS Tenant Isolation Strategies whitepaper assembles a collection of best practices and considerations that often shape your approach to implementing isolation in a SaaS environment. | 
|  | 

| [Isolating SaaS Tenants with Dynamically Generated IAM Policies](https://aws.amazon.com/blogs/apn/isolating-saas-tenants-with-dynamically-generated-iam-policies/) |
|:----------|
| *Created: 21 SEP 2020 by Bill Tarr* | 
| Many SaaS organizations leverage AWS Identity and Access Management (IAM) to define a series of policies and roles that can be used to ensure tenants are not allowed to cross tenant boundaries when accessing resources. To make this work, you have to create separate policies for each tenant which can create an explosion of tenant policies that push the account limits of IAM. Learn how dynamic policy generation creates a more scalable and manageable isolation experience. | 
|  | 

| [Partitioning Pooled Multi-Tenant SaaS Data with Amazon DynamoDB](https://aws.amazon.com/blogs/apn/partitioning-pooled-multi-tenant-saas-data-with-amazon-dynamodb/) |
|:----------|
| *Created: 10 AUG 2020 by Anubhav Sharma, Tod Golding* | 
| As you design, develop, and build SaaS solutions on AWS, you must think about how you want to partition the data that belongs to each of your customers (tenants). In this post, experts from AWS SaaS Factory focus on what it means to implement the pooled model with Amazon DynamoDB. We’ll outline basic strategies to partition and isolate data by tenant, and illustrate common techniques you can use to avoid the “hot” partition problem that’s often associated with partitioning tenant data in a pooled model. | 
|  | 

| [Calculating Tenant Costs in SaaS Environments](https://aws.amazon.com/blogs/apn/calculating-tenant-costs-in-saas-environments/) |
|:----------|
| *Created: 25 AUG 2017 by Tod Golding* | 
| In traditional single-tenant environments, calculating and aggregating infrastructure costs is a pretty straightforward exercise. Typically, each application or customer has its own collection of dedicated resources and tallying the costs is simply a matter of categorizing and summing those costs. However, in multi-tenant SaaS environments, this becomes a much more challenging problem. With SaaS, tenants often share some or all of a system’s infrastructure resources. | 
|  | 

