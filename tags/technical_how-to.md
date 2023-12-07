# technical_how-to

## New articles

| [How Dream11 built a multi-tenant user authentication service on Amazon EKS](https://aws.amazon.com/blogs/gametech/5359-2/) |
|:----------|
| *Created: 16 NOV 2023 by Chetan Dharma, Sanket Raut* | 
| This blog was co-authored by Qamar Ali Shaikh, AVP – Infrastructure & Platform Engineering, Dream11 and Arvind Sharma, Engineering Manager – Developer Platform , Dream11. With over 190+ million users, Dream11 is one of the world’s largest fantasy sports platform offering fantasy cricket, football, kabaddi, basketball, hockey, volleyball, handball, rugby, American football and baseball. Dream11 […] | 
|  | 

| [Build a multi-tenant chatbot with RAG using Amazon Bedrock and Amazon EKS](https://aws.amazon.com/blogs/containers/build-a-multi-tenant-chatbot-with-rag-using-amazon-bedrock-and-amazon-eks/) |
|:----------|
| *Created: 18 OCT 2023 by Farooq Ashraf, Jared Dean, Ravi Yadav* | 
| Introduction With the availability of Generative AI models, many customers are exploring ways to build chatbot applications that can cater to a wide range of their end-customers, with each instance of chatbot specializing on a specific tenant’s contextual information, and run such multi-tenant applications at scale with a cost-efficient infrastructure familiar to their development teams. […] | 
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

| [Secure data at rest on Amazon RDS Custom for Oracle with TDE – Part 2: Multi-tenant environments](https://aws.amazon.com/blogs/database/secure-data-at-rest-on-amazon-rds-custom-for-oracle-with-tde-part-2-multi-tenant-environments/) |
|:----------|
| *Created: 23 AUG 2023 by Prasad Matkar, Domenico di Salvia* | 
| In Part 1 of this series, we discussed implementing Oracle Transparent Database Encryption (TDE) in Amazon Relational Database Service (Amazon RDS) Custom for Oracle with the local auto-login option in a database with the multi-tenant option disabled. In this post, we focus on outlining the implementation steps of TDE in an Oracle database with the […] | 
|  | 

## Older posts
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

| [Design considerations for Amazon EMR on EKS in a multi-tenant Amazon EKS environment](https://aws.amazon.com/blogs/big-data/design-considerations-for-amazon-emr-on-eks-in-a-multi-tenant-amazon-eks-environment/) |
|:----------|
| *Created: 21 SEP 2022 by Lotfi Mouhib, Ajeeb Peter* | 
| Many AWS customers use Amazon Elastic Kubernetes Service (Amazon EKS) in order to take advantage of Kubernetes without the burden of managing the Kubernetes control plane. With Kubernetes, you can centrally manage your workloads and offer administrators a multi-tenant environment where they can create, update, scale, and secure workloads using a single API. Kubernetes also […] | 
|  | 

| [Configure Hadoop YARN CapacityScheduler on Amazon EMR on Amazon EC2 for multi-tenant heterogeneous workloads](https://aws.amazon.com/blogs/big-data/configure-hadoop-yarn-capacityscheduler-on-amazon-emr-on-amazon-ec2-for-multi-tenant-heterogeneous-workloads/) |
|:----------|
| *Created: 16 AUG 2022 by Suvojit Dasgupta, Bharat Gamini* | 
| Apache Hadoop YARN (Yet Another Resource Negotiator) is a cluster resource manager responsible for assigning computational resources (CPU, memory, I/O), and scheduling and monitoring jobs submitted to a Hadoop cluster. This generic framework allows for effective management of cluster resources for distributed data processing frameworks, such as Apache Spark, Apache MapReduce, and Apache Hive. When […] | 
|  | 

| [How Multi-Tenancy with AWS Transfer Family is a Cost-Effective Solution](https://aws.amazon.com/blogs/apn/how-multi-tenancy-with-aws-transfer-family-is-a-cost-effective-solution/) |
|:----------|
| *Created: 20 JUL 2022 by Ben Bridts* | 
| AWS Transfer Family provides SFTP, FTPS, and/or FTP access to Amazon S3 or Amazon Amazon EFS. It does that by providing a secure, highly available, and scalable server endpoint. You pay for the time this endpoint is enabled, and for data transfer (upload and download). Learn how this makes a multi-tenant setup where an endpoint is shared between different users (or applications), a more cost-efficient solution than having dedicated endpoints. | 
|  | 

| [How KoreroPlatforms (Powered by DiGiSPICE) built a multi-tenant SaaS architecture for their enterprise customers using AWS Organizations](https://aws.amazon.com/blogs/mt/how-digispice-built-a-multi-tenant-saas-architecture-for-their-enterprise-customers-using-aws-organizations/) |
|:----------|
| *Created: 19 JUL 2022 by Neha Garg* | 
| DiGiSPICE is known to its customers as a thriving, innovation-led organization with extensive experience in running telecom services in India (Spice Telecom). They help enterprises in their digital transformation journey by harnessing the power of mobile and using technology to improve the connected customer experience. With the above mission, DiGiSPICE has built a communications platform […] | 
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

| [Managing the account lifecycle in account-per-tenant SaaS environments on AWS](https://aws.amazon.com/blogs/mt/managing-the-account-lifecycle-in-account-per-tenant-saas-environments-on-aws/) |
|:----------|
| *Created: 24 SEP 2021 by Keith P* | 
| Software as a service (SaaS) companies have many options when they implement multi-tenancy in their applications. The AWS SaaS Factory Program provides recommendations for different deployment patterns depending on factors such as cost, compliance, and end-customer requirements. You might find that silo methods like VPC-per-tenant are not sufficient. Your application might be in a highly […] | 
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

| [Isolating SaaS Tenants with Dynamically Generated IAM Policies](https://aws.amazon.com/blogs/apn/isolating-saas-tenants-with-dynamically-generated-iam-policies/) |
|:----------|
| *Created: 21 SEP 2020 by Bill Tarr* | 
| Many SaaS organizations leverage AWS Identity and Access Management (IAM) to define a series of policies and roles that can be used to ensure tenants are not allowed to cross tenant boundaries when accessing resources. To make this work, you have to create separate policies for each tenant which can create an explosion of tenant policies that push the account limits of IAM. Learn how dynamic policy generation creates a more scalable and manageable isolation experience. | 
|  | 

