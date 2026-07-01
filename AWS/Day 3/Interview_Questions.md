# AWS Day 03 Interview Questions

## Theory Questions

1. What is Amazon EC2?
2. What is an AMI?
3. What is the purpose of a Key Pair?
4. What is a Security Group?
5. What is an EBS Volume?
6. What is User Data?
7. What is an Elastic IP?
8. Explain the EC2 lifecycle.
9. Difference between Stop and Terminate.
10. Difference between Reboot and Restart.
11. What are Instance Types?
12. What is SSH?
13. Why is Port 22 required?
14. Why is Port 80 required?
15. What is Apache?
16. What happens when an EC2 instance is stopped?
17. What happens when an EC2 instance is terminated?
18. What is the Free Tier?
19. What is the default username for Ubuntu EC2?
20. Why is EC2 important in AWS?

20 Scenario-Based Interview Questions with Answers

1. Your website hosted on EC2 is not opening. What would you check first?

Answer:

Verify the EC2 instance is running.
Check Security Group rules (HTTP port 80).
Ensure Apache is running.
Confirm the correct public IP is being used.
Review system logs if needed.

2. You receive "Permission denied (publickey)" while connecting to EC2. How do you troubleshoot?

Answer:

Verify the correct .pem file is being used.
Ensure the correct username (ubuntu for Ubuntu).
Check the instance's key pair.
Confirm SSH (port 22) is allowed in the Security Group.
Verify the public IP is correct.

3. An EC2 instance loses its public IP after being stopped and started. Why?

Answer:
By default, AWS assigns a dynamic public IP. To keep the same public IP, allocate and associate an Elastic IP.

4. Your manager wants Apache installed automatically every time a new EC2 instance is launched. What AWS feature would you use?

Answer:
Use User Data to run a startup script that installs and starts Apache automatically.

5. A developer accidentally terminates an EC2 instance. What data is typically preserved?

Answer:
If the EBS volume is configured to persist, its data may still be available. Instance-store data is lost when the instance is terminated.

Practice Questions (6–20)

6. How would you securely give SSH access to another administrator?
7. Why should SSH be limited to "My IP" instead of "Anywhere"?
8. When would you use an Elastic IP?
9. How would you identify why an EC2 instance failed to boot?
10. What would you do if Apache doesn't start?
11. How would you host a second website on the same EC2 instance?
12. Why are Security Groups stateful?
13. What is the benefit of EBS snapshots?
14. When would you choose a larger instance type?
15. How would you migrate a website from one EC2 instance to another?
16. How can you reduce EC2 costs for non-production environments?
17. Why should you avoid logging in as the root Linux user?
18. How would you automate software installation on every new EC2 instance?
19. What is the difference between a public and a private EC2 instance?
20. How would you troubleshoot a failed SSH connection after changing Security Group rules?