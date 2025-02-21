# Secure-AWS-IAM-Environment

This project demonstrates how to create a secure AWS IAM environment with IAM roles, MFA enforcement, and CloudTrail logging.

## Project Overview
This project aims to:
- **Implement AWS IAM roles & policies** to enforce least privilege access.
- **Enforce Multi-Factor Authentication (MFA)** for enhanced security.
- **Enable AWS CloudTrail logging** to monitor and audit IAM activities.

## Technologies & Tools Used
- **AWS IAM** (Identity & Access Management)
- **AWS CloudTrail**
- **AWS Config**
- **AWS Identity Center (SSO)**
- **GitHub** (for documentation & version control)

##  Steps Implemented

### 1️ **IAM Roles & Policies Configuration**
- Created **IAM Roles** with least privilege permissions.
- Defined **custom IAM policies** for security compliance.
- Verified that IAM users inherit permissions **via roles & groups** only.

### 2️ **Enforcing MFA for IAM Users**
- Enabled **MFA enforcement** for IAM users.
- Ensured MFA is required for authentication.
- Configured AWS Identity Center for centralized access.

### 3️ **AWS CloudTrail Logging**
- Created a **CloudTrail** to track IAM activities.
- Enabled logging to **S3 bucket** for long-term storage.
- Configured CloudTrail **Event History** for security analysis.
- Implement **AWS GuardDuty** for threat detection.
- Configure **AWS Security Hub** for centralized security insights.
- Automate **IAM compliance checks** with AWS Config.

##  Project Structure
 Secure-AWS-IAM-Environment ┣  README.md (Project Documentation) ┣  IAM-Configurations (IAM roles & policies setup) ┣  MFA-Enforcement (MFA enforcement configurations) ┣  CloudTrail-Logs (CloudTrail setup & logs) ┣  security-policies.json (IAM policies JSON) ┣  screenshots/ (Visual documentation)


## Lessons Learned
- Understanding **IAM Role-Based Access Control (RBAC)**.
- Importance of **MFA enforcement** in IAM security.
- **Monitoring IAM activities** using AWS CloudTrail.


##  Author
**Muna** – Cybersecurity Enthusiast  | AWS Security | IAM & SIEM  
 **GitHub:** [https://github.com/munaaamohameddd]  


---


