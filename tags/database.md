# database

## New articles

| [How VMware consolidated a multi-tenant cloud asset data store on Amazon Aurora MySQL with Amazon RDS Proxy](https://aws.amazon.com/blogs/database/how-vmware-consolidated-a-multi-tenant-cloud-asset-data-store-on-amazon-aurora-mysql-with-amazon-rds-proxy/) |
|:----------|
| *Created: 05 OCT 2023 by Peter Fein, Rajesh Matkar, Sahil Thapar* | 
| This post is co-written with Peter Fein, Staff Engineer 2 at VMware VMware Tanzu CloudHealth, consolidated a multi-tenant, self-managed, 166-node sharded MySQL databases to Amazon Aurora MySQL-Compatible Edition and Amazon RDS Proxy. The goal was to support long-term, continuous, multi-factor data growth on their platform while improving reliability and simplifying operations. VMware Tanzu CloudHealth is […] | 
|  | 

| [Secure data at rest on Amazon RDS Custom for Oracle with TDE – Part 2: Multi-tenant environments](https://aws.amazon.com/blogs/database/secure-data-at-rest-on-amazon-rds-custom-for-oracle-with-tde-part-2-multi-tenant-environments/) |
|:----------|
| *Created: 23 AUG 2023 by Prasad Matkar, Domenico di Salvia* | 
| In Part 1 of this series, we discussed implementing Oracle Transparent Database Encryption (TDE) in Amazon Relational Database Service (Amazon RDS) Custom for Oracle with the local auto-login option in a database with the multi-tenant option disabled. In this post, we focus on outlining the implementation steps of TDE in an Oracle database with the […] | 
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

| [Build and load test a multi-tenant SaaS database proxy solution with Amazon RDS Proxy](https://aws.amazon.com/blogs/database/build-and-load-test-a-multi-tenant-saas-database-proxy-solution-with-amazon-rds-proxy/) |
|:----------|
| *Created: 13 OCT 2021 by Sam Sanders* | 
| Many software as a service (SaaS) customers on AWS are familiar with multi-tenancy and tenant isolation. Indeed, customers using MySQL, for instance, may have adopted the bridge model of multi-tenancy, where each tenant has access to their own isolated database or schema. AWS provides many tools and best practices to get started, but achieving database […] | 
|  | 

| [Implementing multi-tenant patterns in Amazon Redshift using data sharing](https://aws.amazon.com/blogs/big-data/implementing-multi-tenant-patterns-in-amazon-redshift-using-data-sharing/) |
|:----------|
| *Created: 11 FEB 2021 by Rajesh Francis, Jeetesh Srivastva, Neeraja Rentachintala* | 
| Software service providers offer subscription-based analytics capabilities in the cloud with Analytics as a Service (AaaS), and increasingly customers are turning to AaaS for business insights. A multi-tenant storage strategy allows the service providers to build a cost-effective architecture to meet increasing demand. Multi-tenancy means a single instance of software and its supporting infrastructure is […] | 
|  | 

| [Multi-tenant data isolation with PostgreSQL Row Level Security](https://aws.amazon.com/blogs/database/multi-tenant-data-isolation-with-postgresql-row-level-security/) |
|:----------|
| *Created: 18 MAY 2020 by Michael Beardsley* | 
|   Isolating tenant data is a fundamental responsibility for Software as a Service (SaaS) providers. If one of your tenants gains access to another tenant’s data, you lose trust and may permanently damage your brand or worse, lose your business. With the risks so great, it is critical to have an effective data isolation plan. […] | 
|  | 

| [Multi-Tenant Storage with Amazon DynamoDB](https://aws.amazon.com/blogs/apn/multi-tenant-storage-with-amazon-dynamodb/) |
|:----------|
| *Created: 28 JAN 2016 by Tod Golding* | 
| Editor’s note: For the latest information, visit the DynamoDB website. By Tod Golding, Partner Solutions Architect at AWS If you’re designing a true multi-tenant software as a service (SaaS) solution, you’re likely to devote a significant amount of time to selecting a strategy for effectively partitioning your system’s tenant data. On Amazon Web Services (AWS), your partitioning […] | 
|  | 

