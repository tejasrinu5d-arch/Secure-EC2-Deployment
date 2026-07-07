# Secure EC2 Deployment

## AWS Cloud Resume Project

This project demonstrates a secure deployment of an Amazon EC2 instance using AWS best practices. It covers launching an EC2 instance, configuring secure access with SSH, hosting a web application using Apache, managing Amazon EBS storage, creating snapshots, building a Golden AMI, and monitoring the instance with Amazon CloudWatch.

## Project Objectives



- Launch a secure Amazon EC2 instance.

- Configure SSH access using a key pair.

- Deploy Apache Web Server.

- Host a custom web page.

- Create and manage Amazon EBS volumes.

- Create EBS snapshots for backup.

- Build a reusable Golden AMI.

- Monitor the instance using Amazon CloudWatch.

- Follow AWS security best practices.

## AWS Services Used



- Amazon EC2

- Amazon EBS

- Amazon Machine Image (AMI)

- Amazon CloudWatch

- AWS Identity and Access Management (IAM)

- Amazon VPC

- Security Groups

## Project Architecture



User Browser

↓

Amazon EC2 Instance (Amazon Linux 2023)

↓

Apache Web Server

↓

Custom Web Page




### Additional AWS Services:

- Amazon EBS for persistent storage

- EBS Snapshot for backup

- Amazon Machine Image (AMI) for Golden Image creation

- Amazon CloudWatch for monitoring


## Project Structure



Secure-EC2-Deployment/

├── README.md

├── architecture/

├── docs/

└── screenshots/


## Implementation Phases



- Phase 1 – Environment Preparation

- Phase 2 – Launch EC2 Instance

- Phase 3 – Secure SSH Access

- Phase 4 – Deploy Apache Web Server

- Phase 5 – Configure Amazon EBS Storage

- Phase 6 – Create EBS Snapshot

- Phase 7 – Create and Verify Golden AMI

- Phase 8 – Monitor EC2 with CloudWatch


## Screenshots



The project includes screenshots demonstrating each major implementation step:



- EC2 Instance Launch

- SSH Connection

- Apache Web Server

- Custom Web Page

- Amazon EBS Volume

- Mounted Storage Verification

- EBS Snapshot

- Golden AMI

- EC2 Instance launched from Golden AMI

- Amazon CloudWatch Monitoring


## Learning Outcomes


Through this project, I learned how to:



- Launch and configure Amazon EC2 instances

- Secure Linux server access using SSH key pairs

- Deploy and manage an Apache web server

- Create, attach, format, and mount Amazon EBS volumes

- Configure persistent storage using `/etc/fstab`

- Create Amazon EBS snapshots for backup

- Build reusable Golden AMIs

- Launch EC2 instances from custom AMIs

- Monitor EC2 resources using Amazon CloudWatch

- Apply AWS security and operational best practices


## Author



**Name:** Teja Srinu



**Role:** B.Tech CSE (Cyber Security) Student | Aspiring Cloud Security Engineer



**GitHub:** https://github.com/tejasrinu5d-arch







