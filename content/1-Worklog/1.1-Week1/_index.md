---
title: "Week 1 Worklog"
date: 2026-09-14
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

During the first week (14–18 September 2026), I studied cloud computing and the foundations of AWS. The topics included global infrastructure, ways to interact with AWS, cost management and hands-on activities with EC2, Amazon Bedrock and AWS Lambda.

### Week 1 Objectives

- Understand cloud computing, flexible resource usage and pay-as-you-go pricing.
- Distinguish Regions, Availability Zones and Edge Locations, and learn how the Console, CLI and SDK interact with AWS.
- Study access permissions and credential protection when using AWS resources.
- Become familiar with AWS Budgets, AWS Support and the AWS Well-Architected Framework.
- Practice launching EC2, using the Bedrock Playground and creating a simple web application with Lambda.

### Daily Worklog

| Day | Work | Start Date | Completion Date | References |
| --- | --- | --- | --- | --- |
| Monday | Studied the foundations of cloud computing, the benefits of AWS and the learning path for the program. Noted how flexible resources and usage-based pricing work. | 14 September 2026 | 14 September 2026 | [Module 01-01](https://www.youtube.com/watch?v=HxYZAK1coOI), [01-02](https://www.youtube.com/watch?v=IK59Zdd1poE), [01-03](https://www.youtube.com/watch?v=HSzrWGqo3ME); [First Cloud Journey](https://cloudjourney.awsstudygroup.com/) |
| Tuesday | Studied AWS global infrastructure, including Regions, Availability Zones and Edge Locations. Compared the AWS Management Console, CLI and SDK, and reviewed cost optimization and AWS Well-Architected. | 15 September 2026 | 15 September 2026 | [Module 01-04](https://www.youtube.com/watch?v=pjr5a-HYAjI), [01-05](https://www.youtube.com/watch?v=2PQYqH_HkXw), [01-06](https://www.youtube.com/watch?v=IY61YlmXQe8), [01-07](https://www.youtube.com/watch?v=Hku7exDBURo); [AWS Global Infrastructure](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/global-infrastructure.html) |
| Wednesday | Launched an EC2 instance using Amazon Linux 2023 and `t3.micro`; set up a key pair, network and security group, connected with EC2 Instance Connect, ran basic Linux commands and terminated the instance. Also studied AWS Budgets, cost budgets and actual/forecast alert thresholds. | 16 September 2026 | 16 September 2026 | [Activity 01: Amazon EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html); [Activity 02: AWS Budgets](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-managing-costs.html); [FCJ Lab07](https://000007.awsstudygroup.com/) |
| Thursday | Used the Amazon Bedrock Playground with Amazon Nova 2 Lite, entered a prompt and observed the response, token usage and latency. Created a Lambda function from an HTTP blueprint, opened its Function URL and verified the “Hello from AWS Lambda!” page. | 17 September 2026 | 17 September 2026 | [Amazon Bedrock Playground](https://docs.aws.amazon.com/bedrock/latest/userguide/playgrounds.html); [AWS Lambda Function URLs](https://docs.aws.amazon.com/lambda/latest/dg/lambda-urls.html); [AWS Lambda](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html) |
| Friday | Studied AWS support channels and request types, the information needed to describe an issue, and how to use the six Well-Architected pillars when reviewing an architecture. | 18 September 2026 | 18 September 2026 | [Lab09-01](https://www.youtube.com/watch?v=4FDcK0_kbfY), [09-02](https://www.youtube.com/watch?v=BAEh-_RzmNg), [09-03](https://www.youtube.com/watch?v=haafDPugAnE), [09-04](https://www.youtube.com/watch?v=ThJBaQ3DEBs); [FCJ Lab09](https://000009.awsstudygroup.com/); [Well-Architected pillars](https://docs.aws.amazon.com/wellarchitected/latest/framework/the-pillars-of-the-framework.html) |

### Achievements

- Summarized the foundations of cloud computing and the main components of AWS global infrastructure.
- Distinguished the roles of the Console, CLI and SDK when interacting with AWS services.
- Connected to and inspected an EC2 instance, then terminated it; learned the roles of key pairs and security groups.
- Learned the purpose of AWS Budgets and AWS Support, and became familiar with the six pillars of the AWS Well-Architected Framework.
- Received a response from Amazon Bedrock Playground and verified an HTML page returned through a Lambda Function URL.

### Lessons Learned

- Region and service choices should reflect workload requirements for latency, availability, data and cost.
- Private keys must be stored securely, and SSH rules should restrict access to the sources that need it.
- An unauthenticated Lambda Function URL can be called publicly, so access and cleanup should be considered after testing.
- AWS Budgets monitors spending and sends alerts; an alert does not automatically stop charges.
- A clear description of symptoms, timing and impact helps when requesting support.

### Next Steps

Continue with VPC and networking in Week 2, and explore how Bedrock and Lambda can be integrated into applications.
