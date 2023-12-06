# amazon_dynamodb

## New articles

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

| [Using AWS X-Ray and AWS Application Cost Profiler to track tenant cost of shared AWS Infrastructure](https://aws.amazon.com/blogs/mt/using-aws-x-ray-and-aws-application-cost-profiler-to-track-tenant-cost-of-shared-aws-infrastructure/) |
|:----------|
| *Created: 30 SEP 2021 by Ryan Peterson, Venkata Kampana* | 
| In our last blog post, we introduced AWS Application Cost Profiler (ACP), where we discussed this new service that allows customers, running multi-tenant applications, to receive granular cost breakdowns of shared AWS resources across their tenants. AWS Application Cost Profiler provides customers, especially SaaS ISVs, with a standard mechanism to correlate and report their infrastructure […] | 
|  | 

| [Dynamic Request Routing in Multi-tenant Systems with Amazon CloudFront](https://aws.amazon.com/blogs/architecture/dynamic-request-routing-in-multi-tenant-systems-with-amazon-cloudfront/) |
|:----------|
| *Created: 19 APR 2021 by Manuel Pata, Achraf Souk, André Matos* | 
| In this blog post, we will share how OutSystems designed a globally distributed serverless request routing service for their multi-tenant architecture. This will provide you ways to benefit from a managed solution that’s scalable and requires a low operational effort. Namely, we explain how to select the origin serving an HTTP/S request using Lambda@Edge, including […] | 
|  | 

| [Partitioning Pooled Multi-Tenant SaaS Data with Amazon DynamoDB](https://aws.amazon.com/blogs/apn/partitioning-pooled-multi-tenant-saas-data-with-amazon-dynamodb/) |
|:----------|
| *Created: 10 AUG 2020 by Anubhav Sharma, Tod Golding* | 
| As you design, develop, and build SaaS solutions on AWS, you must think about how you want to partition the data that belongs to each of your customers (tenants). In this post, experts from AWS SaaS Factory focus on what it means to implement the pooled model with Amazon DynamoDB. We’ll outline basic strategies to partition and isolate data by tenant, and illustrate common techniques you can use to avoid the “hot” partition problem that’s often associated with partitioning tenant data in a pooled model. | 
|  | 

| [Multi-Tenant Storage with Amazon DynamoDB](https://aws.amazon.com/blogs/apn/multi-tenant-storage-with-amazon-dynamodb/) |
|:----------|
| *Created: 28 JAN 2016 by Tod Golding* | 
| Editor’s note: For the latest information, visit the DynamoDB website. By Tod Golding, Partner Solutions Architect at AWS If you’re designing a true multi-tenant software as a service (SaaS) solution, you’re likely to devote a significant amount of time to selecting a strategy for effectively partitioning your system’s tenant data. On Amazon Web Services (AWS), your partitioning […] | 
|  | 

