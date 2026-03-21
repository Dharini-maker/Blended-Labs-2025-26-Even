# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture

Author : Dharini.S

Reg no : 212224040072

Date : 16-03-2026

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

Step 1: Login to the Amazon Web Services Management Console and review the existing Amazon EC2 architecture.

Step 2: Create a Launch Template with AMI, instance type, security group, and key pair.

Step 3: Create an Amazon EC2 Auto Scaling group using the launch template.

Step 4: Configure minimum, maximum, and desired number of instances.

Step 5: Create an Application Load Balancer using Elastic Load Balancing.

Step 6: Create a target group and attach the Auto Scaling Group to it.

Step 7: Configure scaling policies using Amazon CloudWatch alarms.

Step 8: Generate traffic and test load balancing and automatic scaling.

---

## Output Screenshots 
![c6 1](https://github.com/user-attachments/assets/324e7a5f-7c40-4e94-b488-98426be28f2c)

![c6 3](https://github.com/user-attachments/assets/67f47b93-c308-4fa1-ad59-eef1038e302f)

![c6 8](https://github.com/user-attachments/assets/54df1a86-fc78-4036-9a0d-141883de4c34)


---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
