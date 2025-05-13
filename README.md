# 🌩️ NimbusScale App

**Scalable and Secure Cloud Architecture with AWS**  
This project showcases a production-style cloud infrastructure designed entirely on AWS, following the principles of the AWS Well-Architected Framework.

---

## 📌 Description

NimbusScale is a cloud infrastructure project built to simulate a real-world web application hosted in a highly available, secure, and auto-scalable AWS environment.

It is intended as a **portfolio project** and **certification practice** for the **AWS Certified Solutions Architect – Associate (SAA-C03)** level.

---

## 🧱 Technologies & Services Used

- **Amazon VPC** (custom networking with public/private subnets)
- **Amazon EC2** (with Auto Scaling and Load Balancer)
- **Amazon RDS** (Multi-AZ database instance)
- **Amazon S3** (for static frontend or asset storage)
- **Amazon CloudFront** (CDN with HTTPS and caching)
- **IAM** (roles and policies for secure access control)
- **CloudWatch** (logs, metrics, alarms)
- **SNS** (notifications)
- **CloudTrail** (activity tracking and auditing)

---

## 🏗️ Architecture Overview

The architecture includes:

- A custom **VPC** with 2 public and 2 private subnets (Multi-AZ)
- An **Application Load Balancer** connected to an **Auto Scaling Group** of EC2 instances
- A **Multi-AZ RDS** instance in private subnets
- A static frontend hosted on **S3**, distributed via **CloudFront**
- **IAM roles and security groups** for granular access control
- **CloudWatch** monitoring and **SNS** notifications
- Optional **CloudFormation** or **Terraform** for Infrastructure as Code (IaC)

---

## 🎯 Learning Objectives

- Apply best practices from the **AWS Well-Architected Framework**
- Design for **fault tolerance**, **high availability**, and **cost optimization**
- Implement real-world AWS services used in production
- Build a project that can be showcased in interviews or added to your resume

---

## 📁 Project Structure (Planned)

