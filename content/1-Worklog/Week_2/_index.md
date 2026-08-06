---
title: "Worklog Week 2"
weight: 2
chapter: false
pre: " <b> 1.2 </b> "
---

### Objectives

- Learn about the serverless architecture on AWS and system deployment models.
- Research the AWS services used in the project.
- Understand the automated image processing workflow on the AWS platform.
- Learn about access control mechanisms and resource management on AWS.
- Prepare the necessary knowledge for system development and integration.

---

### Tasks Performed

| Task | Start Date | Completion Date | Reference |
|------|------------|-----------------|-----------|
| Study Amazon S3 and the Object Storage model | 29/06/2026 | 30/06/2026 | https://docs.aws.amazon.com/s3 |
| Study Amazon DynamoDB and the NoSQL database model | 30/06/2026 | 01/07/2026 | https://docs.aws.amazon.com/dynamodb |
| Study AWS Lambda and the Serverless model | 01/07/2026 | 02/07/2026 | https://docs.aws.amazon.com/lambda |
| Study Amazon CloudWatch and system monitoring mechanisms | 02/07/2026 | 02/07/2026 | https://docs.aws.amazon.com/AmazonCloudWatch |
| Study AWS IAM and access control mechanisms between services | 02/07/2026 | 03/07/2026 | https://docs.aws.amazon.com/iam |
| Analyze the architecture and processing workflow of the Image Optimization system | 03/07/2026 | 03/07/2026 | |
| Research how AWS services integrate and exchange data within the system | 03/07/2026 | 03/07/2026 | |
| Research AWS services suitable for AWS Free Tier usage | 03/07/2026 | 03/07/2026 | |

---

### Results Achieved

- Understood the roles of AWS services in the automated image processing system:

  - **Amazon S3**
    - Used to store input images and processed images as objects.
    - Managed data through buckets and objects.

  - **AWS Lambda**
    - Executes image processing tasks using the serverless model.
    - Automatically triggered by events from Amazon S3.

  - **Amazon DynamoDB**
    - Understood the NoSQL data storage mechanism.
    - Learned how DynamoDB is used to store system information.

  - **Amazon CloudWatch**
    - Monitors logs and the operational status of AWS services.
    - Supports system monitoring and error troubleshooting during execution.

  - **AWS IAM**
    - Understood the management of users, roles, and policies.
    - Learned the principles of access control between AWS services.

- Gained an overall understanding of the automated image processing architecture on AWS and the workflow between different services.

- Understood how to deploy applications using a serverless architecture, which helps reduce operational costs and improve scalability as the system grows.

- Learned the criteria for selecting suitable AWS services within the AWS Free Tier to optimize costs during development and testing.