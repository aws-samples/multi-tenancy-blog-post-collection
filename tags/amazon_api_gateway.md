# amazon_api_gateway

## New articles

## Older posts
| [How SeatGeek uses AWS Serverless to control authorization, authentication, and rate-limiting in a multi-tenant SaaS application](https://aws.amazon.com/blogs/architecture/how-seatgeek-uses-aws-to-control-authorization-authentication-and-rate-limiting-in-a-multi-tenant-saas-application/) |
|:----------|
| *Created: 14 AUG 2023 by Umesh Kalaspurkar, Anderson Parra, Anton Aleksandrov, João Mikos, Samit Kumbhani* | 
| SeatGeek is a ticketing platform for web and mobile users, offering ticket purchase and reselling for sports games, concerts, and theatrical productions. In 2022, SeatGeek had an average of 47 million daily tickets available, and their mobile app was downloaded 33+ million times. Historically, SeatGeek used multiple identity and access tools internally. Applications were individually […] | 
|  | 

| [Enabling Tiering and Throttling in a Multi-Tenant Amazon EKS SaaS Solution Using Amazon API Gateway](https://aws.amazon.com/blogs/apn/enabling-tiering-and-throttling-in-a-multi-tenant-amazon-eks-saas-solution-using-amazon-api-gateway/) |
|:----------|
| *Created: 26 SEP 2022 by Ranjith Raman, Peter Yang* | 
| Every SaaS architecture must introduce mechanisms and policies that prevent noisy neighbor conditions. Getting these policies right is essential to building a robust SaaS solution that delivers a consistent experience to customers. This post looks at the different strategies that can be used to introduce the throttles (transaction rate) and quotas (transaction volume) that manage each tenant’s activity, exploring the various AWS services that can be used to bring these concepts to life. | 
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

