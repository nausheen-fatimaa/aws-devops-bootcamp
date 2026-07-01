# Linux Day 05 Assignment

## Objective

Build and configure a custom AWS networking environment and deploy a web server.

---

## Tasks Completed

### Linux

- Displayed network interfaces
- Checked routing table
- Verified system IP
- Tested internet connectivity
- Downloaded webpage using wget
- Retrieved webpage using curl
- Displayed active ports
- Performed DNS lookup

---

### AWS

- Created Custom VPC
- Configured CIDR Block
- Created Public Subnet
- Created Private Subnet
- Created Internet Gateway
- Attached Internet Gateway to VPC
- Configured Route Table
- Associated Public Subnet
- Created Security Group
- Launched Ubuntu EC2
- Connected using SSH
- Installed Apache
- Created Custom HTML Webpage
- Hosted Website Successfully

---

## Questions

### 1. What is a VPC?

A Virtual Private Cloud is a logically isolated private network inside AWS where cloud resources can be securely deployed.

---

### 2. Difference between Public and Private Subnet?

Public Subnet has internet access through an Internet Gateway.

Private Subnet does not have direct internet access.

---

### 3. Why is an Internet Gateway required?

It allows communication between the VPC and the Internet.

---

### 4. What is a Route Table?

A Route Table defines rules that determine where network traffic is directed.

---

### 5. What is a Security Group?

A Security Group acts as a virtual firewall that controls inbound and outbound traffic for an EC2 instance.

---

### 6. Why is Apache used?

Apache is a web server used to host websites and web applications.

---

### Learning Outcome

I successfully created a complete AWS networking environment, deployed an EC2 instance inside a custom VPC, and hosted a custom webpage using Apache.