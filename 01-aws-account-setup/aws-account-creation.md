# AWS Account Creation Documentation

## 1. Overview
An AWS account is the primary container for AWS resources.
It is created using a **root user**, which has full administrative privileges.

> Best Practice: The root user should be secured and rarely used.

---

## 2. Steps to Create an AWS Account

1. Go to the AWS sign-up page
2. Click **Create an AWS Account**
3. Enter:
   - Email address
   - Account name
   - Password
4. Verify email address

---

## 3. Contact & Billing Information

- Enter personal or business details
- Add a valid debit/credit card
- Identity verification via phone or SMS

> AWS Free Tier applies automatically for new accounts.

---

## 4. Root User Security Setup (Critical)

After account creation, immediately secure the root user:

### 4.1 Enable MFA
- Go to **IAM → Security credentials**
- Enable **Multi-Factor Authentication (MFA)**

### 4.2 Do NOT Use Root for Daily Tasks
- Root user should only be used for:
  - Account settings
  - Billing
  - AWS Organizations setup

---

## 5. Billing & Cost Management Setup

- Enable **Billing Alerts**
- Enable **Cost Explorer**
- Set budgets to avoid unexpected charges

---

## 6. Best Practices
- Never share root credentials
- Enable MFA immediately
- Create IAM users for daily operations

---

## 7. Summary
AWS account creation is the foundation of cloud security and governance.
All other AWS services depend on this initial setup.
