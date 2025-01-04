# 3-Tier Architecture Project Guide  

**GitHub Repository**: [3-Tier Architecture App](https://github.com/KastroVKiran/3TierArchitectureApp.git)  

---

## Table of Contents  
1. [Introduction](#introduction)  
2. [Setting Up the Project Infrastructure](#setting-up-the-project-infrastructure)  
    1. [VPC Creation](#1-vpc-creation)  
    2. [S3 Bucket and IAM Role Setup](#2-s3-bucket-and-iam-role-setup)  
    3. [Database Configuration](#3-database-configuration)  
    4. [Application Tier Setup](#4-application-tier-setup)  
    5. [Web Tier Setup](#5-web-tier-setup)  
    6. [SSL Certification and Domain Mapping](#6-ssl-certification-and-domain-mapping)  
3. [Cleaning Up Resources](#cleaning-up-resources)  

---

## Introduction  

The 3-Tier Architecture separates the presentation, application, and database layers, enhancing scalability, manageability, and security. This guide provides step-by-step instructions to implement this architecture on AWS using various services like VPC, EC2, RDS, S3, IAM, and Route 53.

---

## Setting Up the Project Infrastructure  

### 1. VPC Creation  

Design and create a Virtual Private Cloud (VPC) as the foundation for the project infrastructure.  

```bash
# Use AWS Management Console or CLI to create the VPC
