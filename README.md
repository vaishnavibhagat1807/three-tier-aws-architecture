# 🚀 Three-Tier Architecture on AWS

## 📌 Overview

This project demonstrates how to design and deploy a secure **three-tier architecture** on AWS.
The architecture separates the application into Web, Application, and Database layers to improve scalability, security, and performance.

---

## 🏗️ Architecture

Users → Application Load Balancer → Web Tier → App Tier → RDS Database

---

## 🧰 Services Used

* VPC (Virtual Private Cloud)
* Public & Private Subnets
* EC2 Instances
* Application Load Balancer (ALB)
* RDS (MySQL)
* Security Groups
* Internet Gateway
* Route Tables

---

## ⚙️ Implementation Steps

1. Created custom VPC with CIDR 10.0.0.0/16
2. Configured public and private subnets
3. Deployed Web Tier EC2 in public subnet
4. Deployed App Tier EC2 in private subnet
5. Created RDS database in private subnet
6. Configured security groups for controlled communication
7. Set up Application Load Balancer

---

## 🔐 Security

* Database not publicly accessible
* Private subnets for backend tiers
* Controlled traffic using Security Groups

---

## 📊 Outcome

Successfully deployed a secure and scalable cloud architecture demonstrating AWS networking and infrastructure best practices.

---

## 📸 Screenshots
## 🎉 Final Output

Application successfully deployed using AWS Three Tier Architecture.

![Final Output](final-output.png)


---

## 🧠 Key Learnings

* Cloud networking fundamentals
* High availability design
* Secure multi-tier deployment
* Load balancing concepts

---

## 👩‍💻 Author

Vaishnavi Bhagat

