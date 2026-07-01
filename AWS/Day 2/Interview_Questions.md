# AWS Day 02 Interview Questions

## Theory Questions

1. What is IAM?
2. Why is IAM important?
3. Difference between Root User and IAM User.
4. What is an IAM Group?
5. What is an IAM Policy?
6. What are AWS Managed Policies?
7. What are Customer Managed Policies?
8. What are Inline Policies?
9. What is an IAM Role?
10. Difference between Role and User.
11. What is Authentication?
12. What is Authorization?
13. What is MFA?
14. Explain Least Privilege.
15. What is JSON in IAM Policies?
16. Why should Root User be avoided?
17. Can one user belong to multiple groups?
18. What are Access Keys?
19. Why are IAM Roles preferred over storing credentials on EC2?
20. Explain IAM in your own words.

20 Scenario-Based Interview Questions with Answers

1. A developer needs to view S3 buckets but should not upload files. How would you configure access?

Answer: Create an IAM user, add the user to a group with the AmazonS3ReadOnlyAccess policy, or attach an equivalent custom read-only policy.

2. Your company hires 20 new developers. How would you manage permissions efficiently?

Answer: Create a Developers IAM group, assign the required policies to the group, and add all developers to that group.

3. An EC2 instance needs to access an S3 bucket. Should you store AWS access keys on the server?

Answer: No. Attach an IAM Role to the EC2 instance. This provides temporary credentials and is more secure than storing access keys.

4. A user accidentally deleted an EC2 instance. How can IAM help reduce this risk?

Answer: Follow the Principle of Least Privilege by granting only the permissions the user needs. Avoid giving unnecessary delete permissions.

5. A user forgets their password. What should an administrator do?

Answer: Reset the IAM user's password through the IAM console and encourage the use of MFA.

6–20. Practice answering these yourself first:

6. Why shouldn't developers use the Root User?
7. How would you provide temporary AWS access to an external consultant?
8. What happens if an IAM user has no policies attached?
9. How would you give one team EC2 access but not S3 access?
10. Why is MFA important even if you have a strong password?
11. When would you create a custom policy instead of using an AWS managed policy?
12. A user belongs to two groups with different permissions. How are permissions evaluated?
13. How would you revoke access immediately for an employee leaving the company?
14. Why are IAM Roles preferred for AWS services?
15. How would you audit who has AdministratorAccess?
16. What risks come from sharing AWS credentials?
17. How would you implement least privilege for an intern?
18. A Lambda function needs to write logs to CloudWatch. What should you configure?
19. How would you securely allow an application to access AWS services?
20. What IAM best practices would you recommend for a new AWS account?