# Cloud-Based Analysis of Council Voting Patterns Using AWS Services

## Descriptive Analysis
The duality of the dataset used in this project is that it has the voting history of the council members. This project aims to conduct a descriptive analysis using various AWS services to uncover voting trends, identify members who tend to vote similarly, and detect patterns. This analysis can inform council decisions to be more open and transparent. Simple statistics and visualization tools will be used to explain the dataset.

## Project Description
This project explores council voting records with cloud-based tools. Data is stored in Amazon S3, processed with AWS Glue and Glue DataBrew, queried with Athena, and visualized in QuickSight. IAM and KMS secure the data, while CloudWatch supports monitoring. EC2 may be used for additional workloads. The goal is to create clean, interpretable data and generate useful dashboards and reports.

## Project Title
**Cloud-Based Analysis of Council Voting Patterns Using AWS Services**

## Objective
To study and understand the voting patterns of council members using cloud services. This includes exploring voting frequency, consensus on topics, and decision trends. The project highlights working with real data in a secure and modern way using cloud infrastructure.

## Dataset
The dataset contains voting records in CSV format. It includes information about who voted, how they voted, and on what issues. It is stored in S3 and is clean and comprehensive for analysis.

![image](https://github.com/user-attachments/assets/8860ca5e-fabc-4eb4-be0b-0454493eee77)


## Methodology
1. Upload dataset to Amazon S3
2. Clean and transform using AWS Glue and DataBrew
3. Query using Amazon Athena
4. Secure access via IAM and KMS
5. Visualize results through dashboards and reports

![image](https://github.com/user-attachments/assets/e66ed03e-6052-4c16-8e74-ebebe881d2b1)

![image](https://github.com/user-attachments/assets/c4434931-ea7f-46ec-b953-87d63c6c0736)


## Tools and Technologies
- **Amazon S3**: Data storage
- **AWS Glue & Glue DataBrew**: Data transformation
- **Amazon Athena**: Querying data
- **Amazon QuickSight**: Data visualization
- **IAM & KMS**: Security
- **Amazon EC2**: Optional compute
- **Amazon CloudWatch**: Monitoring and logs

![image](https://github.com/user-attachments/assets/d6182c23-3bc4-49de-a6d1-98815e37335a)

![image](https://github.com/user-attachments/assets/0106ced5-0171-4a8b-9ccd-09b6f2a579d0)


## Deliverables
- Cleaned dataset
- SQL queries on Athena
- Summary reports and dashboards
- Visualizations of voting patterns

## AWS Deployment and Service Models
- **Deployment Model**: Public Cloud
- **Service Models**: Platform as a Service (PaaS), Software as a Service (SaaS)

![image](https://github.com/user-attachments/assets/eb2214ce-691e-4b90-bb5e-d07877b066cb)

![image](https://github.com/user-attachments/assets/16396259-1f28-47ce-ae58-6f8ff9864e0d)

![image](https://github.com/user-attachments/assets/f1d5e3dd-8f69-4e12-882c-8000cce884e4)

![image](https://github.com/user-attachments/assets/9b331dfc-2a1c-4006-9251-ed1137d62189)


## AWS Cost Analysis
The cost is determined by the usage of services:
- S3: Low cost
- Glue/DataBrew: Charged by jobs and sessions
- Athena: Charged per data scanned
- EC2: Pay per usage
- IAM/KMS: Basic usage is free
- CloudWatch: Free tier with optional additional cost

![image](https://github.com/user-attachments/assets/9b70fb15-0522-45b4-8ac9-64a39a269778)


## AWS Global Infrastructure
AWS’s global data center network offers high availability and resilience. The project benefits from scalability, security, and performance enhancements by choosing the appropriate AWS region.

![image](https://github.com/user-attachments/assets/d8f250f2-5e7f-451c-9083-c5467ed9eeec)

![image](https://github.com/user-attachments/assets/9250831c-a872-4125-b448-338afc758855)


## AWS IAM
IAM manages user access and permissions, logs actions, supports multi-factor authentication, and integrates with KMS for encryption. It ensures secure, role-based access control.

![image](https://github.com/user-attachments/assets/891a9c3a-1b7b-4a89-abea-7df4a02bbd7a)


## AWS VPC
Amazon VPC provides a private cloud network for managing services like EC2, with support for IP configurations, subnets, and gateways. It helps secure the project and manage traffic flow.

## AWS Lambda
AWS Lambda enables running code in response to events without server management. It is cost-effective and supports automation (e.g., triggering Glue jobs upon new uploads).

## AWS EBS
Amazon EBS provides persistent storage for EC2. While not a primary storage, it’s helpful for EC2-based tasks or local processing.

---
