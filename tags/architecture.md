# architecture

## New articles

| [How Sela Builds Low-Latency Serverless Control Planes for Hybrid-Tenant Developer Platforms](https://aws.amazon.com/blogs/apn/how-sela-builds-low-latency-serverless-control-planes-for-hybrid-tenant-developer-platforms/) |
|:----------|
| *Created: 27 OCT 2023 by Yehuda Cohen, Puneet Kalra, Laurell McCaffrey* | 
| Explore the hybrid-tenant architecture Sela designed and implemented for Dittofi’s hosting platform. We’ll focus on the underlying architecture of the Dittofi hosting platform where tenant workloads run, as well as the architecture for the hybrid-tenant control plane that enables the provisioning, de-provisioning, and updating of tenants. We’ll pay special attention to the user experience during the development of no-code applications and the measures Sela put in place to enable near-real-time code generation. | 
|  | 

| [Data Ingestion in a Multi-Tenant SaaS Environment Using AWS Services](https://aws.amazon.com/blogs/apn/data-ingestion-in-a-multi-tenant-saas-environment-using-aws-services/) |
|:----------|
| *Created: 30 AUG 2023 by Peter Yang, Ranjith Raman* | 
| AWS experts break down how you can build a multi-tenant data ingestion and processing engine using AWS services. We examine each component of this data pipeline and examine some of the key considerations that can influence how you approach designing a SaaS multi-tenant data ingestion process. We also explore how multi-tenant streaming data can be ingested, transformed, and stored using AWS services while ensuring there are constructs built in to the pipeline to ensure secure processing of the data. | 
|  | 

## Older posts
| [How SeatGeek uses AWS Serverless to control authorization, authentication, and rate-limiting in a multi-tenant SaaS application](https://aws.amazon.com/blogs/architecture/how-seatgeek-uses-aws-to-control-authorization-authentication-and-rate-limiting-in-a-multi-tenant-saas-application/) |
|:----------|
| *Created: 14 AUG 2023 by Umesh Kalaspurkar, Anderson Parra, Anton Aleksandrov, João Mikos, Samit Kumbhani* | 
| SeatGeek is a ticketing platform for web and mobile users, offering ticket purchase and reselling for sports games, concerts, and theatrical productions. In 2022, SeatGeek had an average of 47 million daily tickets available, and their mobile app was downloaded 33+ million times. Historically, SeatGeek used multiple identity and access tools internally. Applications were individually […] | 
|  | 

| [AWS Cloud service considerations when modernizing account-per-tenant solutions](https://aws.amazon.com/blogs/architecture/aws-cloud-service-considerations-for-designing-multi-tenant-saas-solutions/) |
|:----------|
| *Created: 04 AUG 2023 by Dennis Greene, Ignacio Fuentes, Greg Pierce* | 
| An increasing number of software as a service (SaaS) providers are modernizing their architectures to utilize resources more efficiently and reduce operational costs. There are multiple strategies that can be used when refining your multi-tenant architecture. This blog will look at a specific scenario where SaaS providers move from an account-per-tenant to an Amazon Elastic […] | 
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

| [Dynamic Request Routing in Multi-tenant Systems with Amazon CloudFront](https://aws.amazon.com/blogs/architecture/dynamic-request-routing-in-multi-tenant-systems-with-amazon-cloudfront/) |
|:----------|
| *Created: 19 APR 2021 by Manuel Pata, Achraf Souk, André Matos* | 
| In this blog post, we will share how OutSystems designed a globally distributed serverless request routing service for their multi-tenant architecture. This will provide you ways to benefit from a managed solution that’s scalable and requires a low operational effort. Namely, we explain how to select the origin serving an HTTP/S request using Lambda@Edge, including […] | 
|  | 

