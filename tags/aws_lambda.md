# aws_lambda

## New articles

| [Using AWS AppConfig to Manage Multi-Tenant SaaS Configurations](https://aws.amazon.com/blogs/mt/using-aws-appconfig-to-manage-multi-tenant-saas-configurations/) |
|:----------|
| *Created: 25 SEP 2023 by Ran Isenberg (AWS Serverless Hero), Alex Pulver, Bill Tarr* | 
| As a Software as a Service (SaaS) provider, you can benefit from a SaaS operating model in a number of ways. One of the most impactful benefits you can realize is improvements to your operational efficiency, and one of the fundamental techniques you can leverage is to maintain a single software version for all your […] | 
|  | 

## Older posts
| [How SeatGeek uses AWS Serverless to control authorization, authentication, and rate-limiting in a multi-tenant SaaS application](https://aws.amazon.com/blogs/architecture/how-seatgeek-uses-aws-to-control-authorization-authentication-and-rate-limiting-in-a-multi-tenant-saas-application/) |
|:----------|
| *Created: 14 AUG 2023 by Umesh Kalaspurkar, Anderson Parra, Anton Aleksandrov, João Mikos, Samit Kumbhani* | 
| SeatGeek is a ticketing platform for web and mobile users, offering ticket purchase and reselling for sports games, concerts, and theatrical productions. In 2022, SeatGeek had an average of 47 million daily tickets available, and their mobile app was downloaded 33+ million times. Historically, SeatGeek used multiple identity and access tools internally. Applications were individually […] | 
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

| [Using ELB Access Logs and AWS Application Cost Profiler to track tenant cost of shared AWS Infrastructure](https://aws.amazon.com/blogs/mt/elb-access-logs-and-aws-application-cost-profiler-track-tenant-cost-of-shared-aws-infrastructure/) |
|:----------|
| *Created: 04 JAN 2022 by Ryan Peterson, Galen Dunkleberger* | 
| In our previous post on AWS Application Cost Profiler (ACP), we demonstrated how application owners instrument a serverless application with tenant metadata in a contextual format using AWS X-Ray. This tenant metadata is necessary for ACP to generate a granular cost breakdown of shared AWS resources used by multi-tenant applications. These granular cost insights let […] | 
|  | 

| [Implementing SaaS Tenant Isolation Using Amazon SageMaker Endpoints and IAM](https://aws.amazon.com/blogs/apn/implementing-saas-tenant-isolation-using-amazon-sagemaker-endpoints-and-iam/) |
|:----------|
| *Created: 15 NOV 2021 by Michael Pelts, Joshua Fox* | 
| As multi-tenant SaaS providers look to leverage machine learning services, they must consider how they’ll protect the data that flows in and out of these services from different tenants. Learn how tenant isolation of machine learning services can be achieved using AWS IAM, and how the integration between IAM, Amazon SageMaker, and many other AWS services provide developers with a rich set of mechanisms that can be applied to realize tenant isolation goals. | 
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

| [Dynamic Request Routing in Multi-tenant Systems with Amazon CloudFront](https://aws.amazon.com/blogs/architecture/dynamic-request-routing-in-multi-tenant-systems-with-amazon-cloudfront/) |
|:----------|
| *Created: 19 APR 2021 by Manuel Pata, Achraf Souk, André Matos* | 
| In this blog post, we will share how OutSystems designed a globally distributed serverless request routing service for their multi-tenant architecture. This will provide you ways to benefit from a managed solution that’s scalable and requires a low operational effort. Namely, we explain how to select the origin serving an HTTP/S request using Lambda@Edge, including […] | 
|  | 

| [Isolating SaaS Tenants with Dynamically Generated IAM Policies](https://aws.amazon.com/blogs/apn/isolating-saas-tenants-with-dynamically-generated-iam-policies/) |
|:----------|
| *Created: 21 SEP 2020 by Bill Tarr* | 
| Many SaaS organizations leverage AWS Identity and Access Management (IAM) to define a series of policies and roles that can be used to ensure tenants are not allowed to cross tenant boundaries when accessing resources. To make this work, you have to create separate policies for each tenant which can create an explosion of tenant policies that push the account limits of IAM. Learn how dynamic policy generation creates a more scalable and manageable isolation experience. | 
|  | 

