## Ex 4 Deployment and configuration of a Private Cloud in AWS
## NAME: VIJAY GOPALA ADHITHYAA J R
## REG NO: 212224030028
## Aim:
To set up of a Private Cloud in AWS.

Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC), involves creating a logically isolated virtual network that you can use to launch AWS resources. This provides you with full control over your virtual networking environment, including resource placement, connectivity, and security. Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual networking environment, including resource placement, connectivity, and security. Get started by setting up your VPC in the AWS service console. Next, add resources to it such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.

## Procedure:
## Plan Your VPC:
● Determine your needs:

Define your use case, including application requirements, security needs, and compliance standards.
● Plan IP address ranges:

Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
● Select Availability Zones:

Decide which Availability Zones (AZs) you'll use for your resources, considering redundancy and performance.
● Plan internet connectivity:

Determine if you need public internet access and how to configure it.
● Define security:

Plan your security groups, network ACLs, and access controls to ensure a secure environment.
Create Your VPC:
• Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.

• Choose "Create VPC": Initiate the VPC creation process.

• Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and other necessary settings.

• Create subnets: Define subnets within your VPC to isolate different parts of your network.

• Create route tables: Specify how traffic is routed within and outside the VPC.

• Create security groups: Define access control rules for your resources.

Deploying Resources:
• Launch EC2 instances: Create and launch virtual machines within your VPC.

• Set up RDS instances: Deploy databases for your applications.

• Configure networking: Connect your resources to the appropriate subnets, security groups, and route tables.

• Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

Managing and Monitoring:
• Use AWS CloudWatch: Monitor your VPC and resources for performance and health.

• Configure logging and auditing: Track access and activity within your VPC for security and compliance.

• Implement security best practices: Regularly review and update your security configuration.

• Scale and adjust as needed: Adjust your VPC infrastructure to meet changing demands.

## Output:
## Snapshot 1: Create VPC image
![442378906-f1bbe800-eb49-4fc4-a8b4-0b2c45b87da4](https://github.com/user-attachments/assets/138b83e6-5e34-4479-8c5d-78ff94755959)
## Snapshot 2: Configuring Subnets
![442378921-5c4d49dd-503e-44b7-8c00-783c7d7c9b16](https://github.com/user-attachments/assets/1f43bf05-e879-4d50-8bc1-297cd7a88880)
## Snapshot 3: Configure Subnets
![442378934-2dd70a6f-21c0-4390-9569-546792f76a81](https://github.com/user-attachments/assets/9459ef00-e882-47cc-8a57-95719965902c)
## Snapshot 4: Setting Internet gateway
![442378965-9531c864-6e80-40aa-91df-104d2a5724cc](https://github.com/user-attachments/assets/e07a2900-c403-460e-9e0b-ad5eee6e5a08)
## Snapshot 5: Creating Internet gateway
![442379180-88a01fd1-add8-4f6e-a018-32d0d34edfcc](https://github.com/user-attachments/assets/1487c5a0-2be5-414b-8e17-4fa9e73b1438)
## Snapshot 6: Setting Internet gateway
![442379212-b857ff77-0d91-4558-8327-c53a2887dce8](https://github.com/user-attachments/assets/f866c848-3a29-4aa0-a296-ab3fa03f4659)
## Snapshot 7: Creating route table
![442379255-5d9b8973-6962-465b-94e0-4ad0bc7f5db6](https://github.com/user-attachments/assets/599954b7-d749-467b-87f4-55fa379a1170)
## Snapshot 8: Configuring route table
![442379294-b70e1607-37e5-481a-92f2-543177903903](https://github.com/user-attachments/assets/a6d926a1-977f-4ecc-a9f3-6b8903a25422)
## Snapshot 9: Editing routes
![442379554-fc6a6898-19bc-443f-93d7-369c9521ab1c](https://github.com/user-attachments/assets/57d6ef50-b8bd-4e03-929f-8978663c36e7)
## Snapshot 10: Creating route table
![442379583-75e0f1e3-cf04-45b5-a554-ee807f00c668](https://github.com/user-attachments/assets/76fec13f-eef0-4958-b66f-74101c130df3)

## Result:
Thus, a private cloud on AWS involves using VPCs has been created for a dedicated, isolated network where we can manage our resources and control access according to our requirements.
