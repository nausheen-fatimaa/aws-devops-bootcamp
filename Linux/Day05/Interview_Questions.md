# Linux Day 05 Interview Questions

## Networking

### 1. What is Networking?

Networking is the process of connecting multiple computers and devices so they can communicate and share resources.

---

### 2. What is an IP Address?

An IP Address is a unique numerical identifier assigned to every device connected to a network.

---

### 3. Difference between Public and Private IP?

Public IP is accessible from the internet.

Private IP is used only within a private network.

---

### 4. Difference between IPv4 and IPv6?

IPv4 uses 32-bit addressing.

IPv6 uses 128-bit addressing and provides a much larger address space.

---

### 5. Difference between TCP and UDP?

TCP is reliable and connection-oriented.

UDP is faster but connectionless.

---

### 6. What is DNS?

DNS converts domain names into IP addresses.

---

### 7. What is HTTP?

HTTP (HyperText Transfer Protocol) is used for transferring web pages between clients and servers.

---

### 8. What is HTTPS?

HTTPS is the secure version of HTTP that encrypts communication using SSL/TLS.

---

### 9. What is a Port?

A Port is a logical communication endpoint used by applications to exchange network traffic.

---

### 10. What is a VPC?

A VPC is an isolated virtual network within AWS where cloud resources are deployed securely.

---

### 11. What is a Subnet?

A Subnet is a smaller network created within a VPC to organize AWS resources.

---

### 12. What is an Internet Gateway?

An Internet Gateway enables communication between a VPC and the internet.

---

### 13. What is a Route Table?

A Route Table contains rules that determine where network traffic should be directed.

---

### 14. What is a Security Group?

A Security Group is a stateful virtual firewall that controls inbound and outbound traffic for AWS resources.

---

### 15. Explain the AWS architecture you built.

I created a custom VPC with one public subnet and one private subnet. I attached an Internet Gateway, configured a Route Table for internet access, launched an Ubuntu EC2 instance in the public subnet, connected using SSH, installed Apache, and hosted a custom webpage.