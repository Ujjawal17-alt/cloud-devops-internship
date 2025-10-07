# DevOps Internship Tasks by Ujjawal Rawat

## Overview
I have successfully completed 6 DevOps internship tasks demonstrating skills in **Terraform, Docker, Ansible, Jenkins, and AWS EC2 deployments**.  
This README contains detailed explanations of each task, commands used, and project workflow. Logos are used for better visual understanding.

---

## 🛠 Tools & Technologies Used
| Tool | Purpose |
|------|---------|
| ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white) | Configuration Management |
| ![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white) | Infrastructure as Code (IaC) |
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) | Containerization |
| ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white) | CI/CD Automation |
| ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white) | Cloud Hosting & EC2 |

---

## 📌 Tasks Overview

### 1️⃣ Ansible — Configuration Management
**Objective:** Automate Docker installation, pull images, and run containers.  
**Playbook:** `docker-playbook.yml`  
**Steps:**
1. Configure Ansible inventory file with target hosts.
2. Write a playbook to install Docker on remote server.
3. Pull a Docker image (like Nginx) and run container with restart policy.
4. Verify Docker container status using `docker ps`.

**Tools / Icons:**  
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

### 2️⃣ Terraform — EC2 Infrastructure
**Objective:** Provision AWS EC2 instance with open ports and Docker installed automatically.  
**Steps:**
1. Write Terraform scripts (`main.tf`) to launch EC2 instance.
2. Open ports **22 (SSH)** and **80 (HTTP)** using security groups.
3. Use `user_data` to install Docker on instance automatically.
4. Apply configuration with `terraform init` and `terraform apply`.
5. Verify EC2 instance status and Docker installation.

**Tools / Icons:**  
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

---

### 3️⃣ Docker Compose — Multi-Environment Setup
**Objective:** Run a static Nginx site and optional Watchtower container.  
**Steps:**
1. Create `docker-compose.yml` for Nginx service.
2. Optionally add Watchtower for automatic container updates.
3. Start containers with `docker-compose up -d`.
4. Verify Nginx site running via browser.

**Tools / Icons:**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

### 4️⃣ GitHub → Jenkins — Webhook Integration
**Objective:** Automate Jenkins job triggering on GitHub push.  
**Steps:**
1. Create a Jenkins job to build Docker image.
2. Configure GitHub webhook pointing to Jenkins job URL.
3. Push changes to main branch on GitHub.
4. Verify Jenkins job triggers automatically.

**Tools / Icons:**  
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

### 5️⃣ Deploy to EC2
**Objective:** SSH into EC2, pull Docker image, and run container accessible on port 80/8080.  
**Steps:**
1. SSH into EC2 instance.
2. Pull Docker image from DockerHub.
3. Run container with port mapping `-p 80:80`.
4. Verify the application in browser.

**Tools / Icons:**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

---

### 6️⃣ Jenkins Pipeline
**Objective:** Create declarative Jenkins pipeline to build and push Docker image.  
**Steps:**
1. Write `Jenkinsfile` with stages: Checkout → Build → Push.
2. Connect Jenkins to DockerHub account.
3. Trigger pipeline manually or via webhook.
4. Verify image appears on DockerHub.

**Tools / Icons:**  
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## ✅ Summary
- 6 internship tasks completed with practical DevOps tools.  
- Skills demonstrated: **IaC, CI/CD, Containerization, Cloud Deployment, Configuration Management**.  
- This README is structured for **clarity, explainability, and professional presentation**.

---

Built with ❤️ by **Ujjawal Rawat**  
[GitHub](https://github.com/Ujjawal17-alt)
