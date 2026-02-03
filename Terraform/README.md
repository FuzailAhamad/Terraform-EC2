# AWS EC2 Setup – Internship Task 2

## Overview
This task is about understanding AWS EC2 and learning two ways to create an EC2 instance:
1. Manually using AWS Console  
2. Automatically using Terraform  

---

## Part 1: Manual EC2 Deployment (AWS Console)

In this step, I created an EC2 instance manually using the AWS Management Console.

### Steps followed:
1. Logged in to the AWS Management Console
2. Opened the EC2 service
3. Clicked on “Launch Instance”
4. Selected Amazon Linux AMI
5. Chose instance type as t2.micro (free tier)
6. Created/selected a key pair for SSH access
7. Allowed SSH (port 22) in the security group
8. Launched the EC2 instance

### Result:
- EC2 instance was successfully created
- Instance status was running
- Instance details were visible in the EC2 dashboard

---

## Part 2: Automatic EC2 Deployment (Terraform)

In this step, I learned how to create an EC2 instance automatically using Terraform (Infrastructure as Code).

### Steps followed:
1. Installed Terraform on local machine
2. Configured AWS credentials locally
3. Created Terraform configuration files
4. Initialized Terraform
5. Planned and applied the Terraform configuration

### Result:
- Terraform created an EC2 instance automatically
- No manual interaction was required
- Instance appeared in AWS EC2 dashboard
- This method is faster and reusable compared to manual setup

---

## Key Learnings

- Understood AWS EC2 basics
- Learned difference between manual and automated infrastructure setup
- Understood how Terraform helps in Infrastructure as Code (IaC)
- Learned how automation reduces manual effort and errors

---

## Conclusion

Both manual and automated EC2 deployments were successfully completed.
Manual setup helped understand AWS Console, while Terraform helped understand automation and real-world DevOps practices.

---

## Author

Name: Fuzail Ahmad
