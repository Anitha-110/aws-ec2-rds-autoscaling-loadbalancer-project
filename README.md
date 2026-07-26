# AWS Highly Available E-Commerce Application

## Project Overview

Designed and deployed a highly available PHP-based e-commerce application on AWS using EC2, Application Load Balancer, Auto Scaling Group, Amazon RDS MySQL, Read Replica, KMS Encryption, and VPC networking.

---

## AWS Services Used

- Amazon EC2
- Amazon VPC
- Internet Gateway
- NAT Gateway
- Public & Private Subnets
- Route Tables
- Security Groups
- Application Load Balancer
- Auto Scaling Group
- Amazon RDS MySQL
- Amazon RDS Read Replica
- AWS KMS
- IAM
- Apache
- PHP
- MySQL

---

## Architecture

- Internet Gateway
- Application Load Balancer
- Auto Scaling Group
- EC2 Instances
- Amazon RDS MySQL
- Read Replica
- KMS Encryption

---

## Features

- Highly Available Architecture
- Multi Availability Zone Deployment
- Auto Scaling
- Load Balancing
- Secure Database
- Read Replica
- PHP E-Commerce Website
- MySQL Database
- Apache Web Server

---

## Technologies

- AWS
- PHP
- Apache
- MySQL
- Bash
- Ubuntu

---

## Deployment

Launch EC2

↓

Install Apache & PHP

↓

Deploy PHP Application

↓

Connect Amazon RDS

↓

Create AMI

↓

Launch Template

↓

Auto Scaling Group

↓

Application Load Balancer

↓

Test Application

---

## Screenshots
##  🗄️ Amazon RDS MySQL
##  🔄 Amazon RDS Read Replica

Configured an Amazon RDS Read Replica to improve read performance and support high availability. The replica handles read-only database requests, reducing the workload on the primary database and enhancing application scalability.

Created an Amazon RDS MySQL database in private subnets to securely store application data. Configured the database with a dedicated security group, database subnet group, and KMS encryption to ensure secure, reliable, and scalable data storage for the E-Commerce application.
Created a MySQL RDS instance in private subnets to securely store application data.
Configured an RDS Read Replica to improve database read performance and provide high availability.
<img width="1365" height="768" alt="03-RDS png" src="https://github.com/user-attachments/assets/65569e39-8a8a-4a3f-929d-46f7c17d66e5" />
##  🖥️ Amazon EC2 Instance

Successfully launched and configured an Ubuntu Amazon EC2 instance to host the PHP-based E-Commerce application. Apache Web Server, PHP, and MySQL client were installed to deploy and run the application while securely connecting to the Amazon RDS database.
<img width="1366" height="768" alt="09-EC2 png" src="https://github.com/user-attachments/assets/7d5ecddd-39c9-4ef4-958a-2e7a39542f1a" />
## 📈 Auto Scaling Group

Configured an Amazon EC2 Auto Scaling Group to automatically launch or terminate EC2 instances based on application demand. This ensures high availability, fault tolerance, and consistent application performance during varying traffic loads.
<img width="1366" height="768" alt="06-auto-scaling png" src="https://github.com/user-attachments/assets/642e0222-3cb5-46da-8375-d2a575a1b579" />
## ⚖️ Application Load Balancer

Configured an Application Load Balancer (ALB) to distribute incoming HTTP traffic across multiple EC2 instances. Health checks were enabled to ensure requests are routed only to healthy instances, improving application reliability and availability.
<img width="1366" height="641" alt="04-load-balancer png" src="https://github.com/user-attachments/assets/93d0a931-446b-407f-bfe4-0cdd6158948b" />
## 🎯 Target Group

Created an Application Load Balancer Target Group to manage EC2 instances running the E-Commerce application. Configured HTTP health checks to monitor instance health and automatically route traffic only to healthy EC2 instances, ensuring high availability and reliable application performance.
<img width="1354" height="758" alt="07-target-group png" src="https://github.com/user-attachments/assets/dfb09024-0f76-4836-8397-a684e39a42f3" />


## 🚀 EC2 Launch Template

Created an EC2 Launch Template using the custom AMI, instance type, security group, key pair, and user data script. The Launch Template enables automated and consistent EC2 instance provisioning for the Auto Scaling Group.
<img width="1361" height="767" alt="05-launch-template png" src="https://github.com/user-attachments/assets/f0e2d56b-221c-48a5-9374-33beaf80781d" />
## 🖼️ Amazon Machine Image (AMI)

Created a custom Amazon Machine Image (AMI) from the configured EC2 instance after installing Apache, PHP, and deploying the E-Commerce application. The AMI provides a reusable template for launching identical EC2 instances, ensuring consistent application deployment and faster recovery.
<img width="1365" height="768" alt="08-ami png (2)" src="https://github.com/user-attachments/assets/6e7f8c0e-bef4-48a5-86ff-7946935d18a4" />
## 🏠 E-Commerce Application Homepage

Successfully deployed the PHP-based E-Commerce application on an Amazon EC2 instance using the Apache Web Server. The homepage displays a responsive beauty product catalog with product images, names, prices, and an **Add to Cart** option. The application is integrated with Amazon RDS MySQL and designed to support a highly available AWS architecture using Auto Scaling and an Application Load Balancer.
<img width="1366" height="767" alt="01-homepage png" src="https://github.com/user-attachments/assets/c67e23e9-f173-4bf3-babb-dba80022fc39" />

<img width="1366" height="768" alt="02-add-products png" src="https://github.com/user-attachments/assets/316cb46e-845e-46b9-bfaa-3d9d9d664c63" />










