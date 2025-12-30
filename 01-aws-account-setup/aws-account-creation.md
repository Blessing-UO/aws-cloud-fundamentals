# Creating an AWS Free Tier Account

After learning AWS Cloud fundamentals, service categories, and global infrastructure,
benefits, and pricing, the next step is to create an AWS Free Tier account and start building hands-on.

---

## Step-by-Step Guide to Create an AWS Account

1. Go to the AWS Free Tier page (https://aws.amazon.com/free/)
2. Click **Create a Free Account**
3. Enter your email address and account name
   - Use your name or company name
4. Verify your email using the code sent to your inbox
5. Set a strong, secure password
6. Provide contact information:
   - Choose **Personal** for learning/testing
   - Choose **Professional** for business use
7. Add a payment method (used for identity verification only)
8. Verify your identity via phone
9. Choose a Support Plan:
   - **Basic** (free and recommended for beginners)
10. Click **Complete Sign-Up**

You can now log in to the **AWS Management Console**.

---

## Secure Your Root Account with MFA (Highly Recommended)

The **root user** is the account owner and has unrestricted access.
It will need to be secured immediately.

Steps:
1. Go to the **IAM Dashboard**
2. Select **Add MFA**
3. Use an authenticator app such as:
   - Google Authenticator
   - Authy

This adds an extra layer of protection against unauthorized access.

---

## Creating an AWS Account Alias

An **Account Alias** replaces the default 12-digit AWS account ID with a
custom, human-friendly sign-in URL.

### Example
Instead of:
https://<account-id>.signin.aws.amazon.com/console

Use:
https://<account-alias>.signin.aws.amazon.com/console



### Benefits
- Easier to remember
- More professional appearance
- Simplifies login for IAM users and administrators

### Steps to Create an Alias
1. Open **IAM Dashboard**
2. Go to **Account Settings**
3. Click **Create Account Alias**
4. Enter your preferred name (e.g., `blessing-cloud`)
5. Save changes

---

## Final Tip

Your AWS Free Tier account opens the door to a real cloud experience —
from compute and storage to AI, analytics, and automation.

Take time to explore, learn, and **secure your environment properly**.

