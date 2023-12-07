# intermediate_200

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

| [Using AWS AppConfig to Manage Multi-Tenant SaaS Configurations](https://aws.amazon.com/blogs/mt/using-aws-appconfig-to-manage-multi-tenant-saas-configurations/) |
|:----------|
| *Created: 25 SEP 2023 by Ran Isenberg (AWS Serverless Hero), Alex Pulver, Bill Tarr* | 
| As a Software as a Service (SaaS) provider, you can benefit from a SaaS operating model in a number of ways. One of the most impactful benefits you can realize is improvements to your operational efficiency, and one of the fundamental techniques you can leverage is to maintain a single software version for all your […] | 
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

| [Migrating Elasticsearch on Amazon EC2 to Modernized, Multi-Tenant Amazon OpenSearch Service Architecture](https://aws.amazon.com/blogs/apn/migrating-elasticsearch-on-amazon-ec2-to-modernized-multi-tenant-amazon-opensearch-service-architecture/) |
|:----------|
| *Created: 22 AUG 2022 by Benjamin Draper, Irshad Buchh* | 
| For a recent project, NTT DATA Services was asked to architect and design the migration of a customer’s backend search tool used by two of its applications. Both applications were leveraging Elasticsearch for data storage. Learn how NTT DATA used some of the DevOps pillars to implement migrations using an active migration strategy. The goal was to move from individual Elasticsearch instances on Amazon EC2 to a single multi-tenant hosted Elasticsearch solution per region—in this case, Amazon OpenSearch Service. | 
|  | 

| [How KoreroPlatforms (Powered by DiGiSPICE) built a multi-tenant SaaS architecture for their enterprise customers using AWS Organizations](https://aws.amazon.com/blogs/mt/how-digispice-built-a-multi-tenant-saas-architecture-for-their-enterprise-customers-using-aws-organizations/) |
|:----------|
| *Created: 19 JUL 2022 by Neha Garg* | 
| DiGiSPICE is known to its customers as a thriving, innovation-led organization with extensive experience in running telecom services in India (Spice Telecom). They help enterprises in their digital transformation journey by harnessing the power of mobile and using technology to improve the connected customer experience. With the above mission, DiGiSPICE has built a communications platform […] | 
|  | 

| [Manage Multi-Tenant Remote Access with Cisco Secure Firewall Cloud Native on Amazon EKS](https://aws.amazon.com/blogs/apn/manage-multi-tenant-remote-access-with-cisco-secure-firewall-cloud-native-on-amazon-eks/) |
|:----------|
| *Created: 13 JUN 2022 by Muffadal Quettawala, Anubhav Swami* | 
| Cisco Secure Firewall Cloud Native (SFCN) is a lightweight network firewall in a cloud-native form factor. Offering granular control and massive throughput potential, SFCN enables security at the speed of business. It offers an easy way to deploy scalable remote access VPN architecture as its primary use case. The solution utilizes Amazon Amazon EKS and other cloud-native services including Amazon ElastiCache for Redis and Amazon Amazon EFS. | 
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

| [Dynamic Request Routing in Multi-tenant Systems with Amazon CloudFront](https://aws.amazon.com/blogs/architecture/dynamic-request-routing-in-multi-tenant-systems-with-amazon-cloudfront/) |
|:----------|
| *Created: 19 APR 2021 by Manuel Pata, Achraf Souk, André Matos* | 
| In this blog post, we will share how OutSystems designed a globally distributed serverless request routing service for their multi-tenant architecture. This will provide you ways to benefit from a managed solution that’s scalable and requires a low operational effort. Namely, we explain how to select the origin serving an HTTP/S request using Lambda@Edge, including […] | 
|  | 

| [Capturing and Visualizing Multi-Tenant Metrics Inside a SaaS Application on AWS](https://aws.amazon.com/blogs/apn/capturing-and-visualizing-multi-tenant-metrics-inside-a-saas-application-on-aws/) |
|:----------|
| *Created: 22 JAN 2021 by Anubhav Sharma, Tod Golding* | 
| As a SaaS provider, it’s essential to have a clear picture of how tenants are exercising your system. Being able to model the functional and operational profile of tenants and tenant tiers is critical to evolving the business and technical strategies of a SaaS organization. Learn about the role metrics play within a SaaS-based application, and dive deep into a solution that provides all of the infrastructure that will support the ingestion, aggregation, and analysis of SaaS metric data. | 
|  | 

| [Managing Multi-Tenancy in Digital Banking with AWS Control Tower](https://aws.amazon.com/blogs/apn/managing-multi-tenancy-in-digital-banking-with-aws-control-tower/) |
|:----------|
| *Created: 10 AUG 2020 by Amol Pathak, Viraj Nadkarni* | 
| Cost conscious credit unions looking to provide digital banking services need logical isolation from other tenants. Larger credit unions, on the other hand, require physical as well as logical isolation from other tenants. Persistent Systems Digital Credit Union Solution helps a credit union go live in a short time frame with digital banking offerings such as digital loans or digital deposits. The solution uses fine-grained microservices, deployed on Amazon EKS and provided as secure API’s using Amazon API Gateway. | 
|  | 

| [Multi-Tenant Storage with Amazon DynamoDB](https://aws.amazon.com/blogs/apn/multi-tenant-storage-with-amazon-dynamodb/) |
|:----------|
| *Created: 28 JAN 2016 by Tod Golding* | 
| Editor’s note: For the latest information, visit the DynamoDB website. By Tod Golding, Partner Solutions Architect at AWS If you’re designing a true multi-tenant software as a service (SaaS) solution, you’re likely to devote a significant amount of time to selecting a strategy for effectively partitioning your system’s tenant data. On Amazon Web Services (AWS), your partitioning […] | 
|  | 

