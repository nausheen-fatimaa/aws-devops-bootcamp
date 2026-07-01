# AWS Day 5 Interview Questions

## Theory Questions

1. What is a VPC?
2. What is CIDR?
3. Difference between Public and Private Subnets.
4. What is an Internet Gateway?
5. What is a Route Table?
6. What is a NAT Gateway?
7. Difference between NAT Gateway and Internet Gateway.
8. Difference between Security Groups and Network ACLs.
9. What is a Bastion Host?
10. Explain the architecture you built.

---

## Scenario-Based Questions

### 1. Your EC2 instance has a public IP but the website is not opening.

Answer:

- Verify the Security Group allows HTTP (port 80).
- Check the Route Table has a `0.0.0.0/0` route to the Internet Gateway.
- Confirm the Internet Gateway is attached.
- Ensure Apache is running.
- Verify the EC2 has a public IP.

---

### 2. Why can't a private EC2 access the Internet?

Answer:

Because it requires a NAT Gateway and the correct route configuration.

---

### 3. Why should databases remain in a private subnet?

Answer:

To prevent direct Internet access and improve security.

---

### 4. Why would you use a Bastion Host?

Answer:

To securely SSH into private EC2 instances without exposing them to the Internet.

---

### 5. Difference between Security Groups and Network ACLs?

Answer:

Security Groups operate at the instance level and are stateful, while Network ACLs operate at the subnet level and are stateless.