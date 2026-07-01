# AWS Day 03 Assignment

## Q1. What is Amazon EC2?

Amazon EC2 (Elastic Compute Cloud) is an AWS service that provides scalable virtual servers in the cloud. It allows users to launch and manage virtual machines on demand.

---

## Q2. What is an AMI?

An Amazon Machine Image (AMI) is a template containing an operating system and software configuration used to launch EC2 instances.

---

## Q3. What is the purpose of a Key Pair?

A Key Pair provides secure authentication for SSH access to Linux EC2 instances. It consists of a public key stored by AWS and a private key (.pem file) stored securely by the user.

---

## Q4. Explain Security Groups.

Security Groups act as virtual firewalls that control inbound and outbound traffic for EC2 instances.

---

## Q5. What is EBS?

Elastic Block Store (EBS) provides persistent block storage for EC2 instances. Data remains available even after the instance is stopped.

---

## Q6. What is User Data?

User Data is a script that runs automatically when an EC2 instance launches. It is commonly used to install software and configure the server.

---

## Q7. What is an Elastic IP?

An Elastic IP is a static public IPv4 address that remains associated with an EC2 instance until it is released or reassigned.

---

## Q8. Explain the EC2 Lifecycle.

The EC2 lifecycle includes Launch, Running, Stop, Start, Reboot, and Terminate states.

---

## Q9. Difference between Stop, Reboot, and Terminate.

Stop:
The instance is shut down, but the EBS volume remains attached.

Reboot:
The instance restarts without changing its configuration.

Terminate:
The instance is permanently deleted. Any attached instance-store data is lost.

---

## Q10. Why is EC2 important?

EC2 allows businesses to deploy applications quickly, scale resources based on demand, and avoid maintaining physical servers.