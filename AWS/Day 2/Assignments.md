# AWS Day 02 Assignment

## Q1. What is IAM?

IAM (Identity and Access Management) is an AWS service that controls who can access AWS resources and what actions they are allowed to perform.

---

## Q2. Difference between Root User and IAM User.

Root User:
- Full access
- Created during AWS account setup
- Should only be used for account-level tasks

IAM User:
- Created by the Root User or an administrator
- Has limited permissions based on assigned policies
- Used for daily operations

---

## Q3. What is an IAM Group?

An IAM Group is a collection of IAM users. Permissions are assigned to the group so all members inherit the same access.

---

## Q4. Why do we use IAM Policies?

IAM Policies define permissions by specifying which AWS actions are allowed or denied on specific resources.

---

## Q5. Difference between Managed and Inline Policies.

AWS Managed Policy:
Created and maintained by AWS.

Customer Managed Policy:
Created and maintained by the customer.

Inline Policy:
Attached directly to one user, group, or role and cannot be reused.

---

## Q6. What is an IAM Role?

An IAM Role provides temporary credentials to AWS services or trusted entities without using permanent access keys.

---

## Q7. Difference between Authentication and Authorization.

Authentication verifies the identity of a user.

Authorization determines what actions the authenticated user is allowed to perform.

---

## Q8. Explain the Principle of Least Privilege.

Users should receive only the permissions required to perform their tasks, reducing the risk of accidental or unauthorized actions.

---

## Q9. Why is MFA important?

MFA adds an extra layer of security by requiring a second form of verification in addition to the password.

---

## Q10. Why should the Root User not be used daily?

The Root User has unrestricted access to all AWS resources. Using it daily increases the risk of accidental changes and security incidents.