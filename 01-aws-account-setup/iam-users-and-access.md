# IAM Users, Groups, Roles & Policies

## 1. What is IAM?
AWS Identity and Access Management (IAM) controls:
- Who can access AWS
- What actions they can perform
- Which resources they can access

---

## 2. IAM Core Components

### IAM Users
- Individual identities
- Used by people or applications

### IAM Groups
- Collection of users
- Permissions assigned at group level

### IAM Roles
- Temporary access
- Used by AWS services or cross-account access

### IAM Policies
- JSON documents defining permissions
- Managed or Inline

---

## 3. Creating an IAM User

1. Go to **IAM → Users**
2. Click **Create user**
3. Enter username (e.g. `admin-user`)
4. Select access type:
   - AWS Management Console
   - Programmatic access (optional)
5. Assign permissions:
   - Add user to group (recommended)
6. Review and create user

---

## 4. Creating IAM Groups

Example:
- Group name: `Admins`
- Policy attached: `AdministratorAccess`

Best Practice:
- Assign permissions to groups, not users directly

---

## 5. IAM Policies

### Managed Policies
- AWS-managed (e.g. AmazonS3ReadOnlyAccess)
- Customer-managed

### Inline Policies
- Embedded directly into a user or role
- Use sparingly

---

## 6. Security Best Practices

- Enable MFA for IAM users
- Follow least privilege principle
- Rotate access keys
- Avoid using root account

---

## 7. Summary
IAM is the backbone of AWS security.
Always control access using users, groups, roles, and policies.
