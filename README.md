# DevOps Internship Tasks by Ujjawal Rawat 🚀

6 internship tasks completed — **Terraform, Docker, Ansible, Jenkins, EC2 deployments**  

**Internship Duration:** Completed by Oct 3, 2025  
**Submission Due:** Mar 4, 2026  

---

## 📋 Project Summary
This repository contains full documentation, step-by-step commands, configurations, and screenshots for all 6 internship tasks.

You can view tasks individually with screenshots, commands, and detailed steps.

---

## ⚡ Tasks Overview

### Task 1 — Ansible: Configuration Management
**Description:** Install Docker, pull Docker image, run container with restart policy.  
**Playbook:** `docker-playbook.yml`  

**Screenshots:**  
[![SSH](./screenshots/task1_ssh.png)](./screenshots/task1_ssh.png)  
[![Inventory](./screenshots/task1_inventory.png)](./screenshots/task1_inventory.png)  
[![Playbook](./screenshots/task1_playbook.png)](./screenshots/task1_playbook.png)  
[![Docker ps](./screenshots/task1_dockerps.png)](./screenshots/task1_dockerps.png)  
[![Browser](./screenshots/task1_browser.png)](./screenshots/task1_browser.png)  

---

### Task 2 — Terraform: EC2 Infrastructure
**Description:** Launch EC2 instance, open ports 80 & 22, install Docker via `user_data`.  

**Screenshots:**  
[![Terraform init](./screenshots/task2_init.png)](./screenshots/task2_init.png)  
[![Terraform apply](./screenshots/task2_apply.png)](./screenshots/task2_apply.png)  
[![EC2](./screenshots/task2_ec2.png)](./screenshots/task2_ec2.png)  

---

### Task 3 — Docker Compose: Multi-Environment
**Description:** Run Nginx static site with optional Watchtower container.  

**Screenshots:**  
[![Compose](./screenshots/task3_compose.png)](./screenshots/task3_compose.png)  
[![Nginx](./screenshots/task3_nginx.png)](./screenshots/task3_nginx.png)  

---

### Task 4 — Webhook Integration: GitHub → Jenkins
**Description:** Configure webhook to trigger Jenkins job on push to main branch.  

**Screenshots:**  
[![Webhook](./screenshots/task4_webhook.png)](./screenshots/task4_webhook.png)  
[![Jenkins](./screenshots/task4_jenkins.png)](./screenshots/task4_jenkins.png)  

---

### Task 5 — Deploy to EC2
**Description:** SSH into EC2, pull Docker image, run container, expose on port 80/8080.  

**Screenshots:**  
[![Pull](./screenshots/task5_pull.png)](./screenshots/task5_pull.png)  
[![Run](./screenshots/task5_run.png)](./screenshots/task5_run.png)  
[![Web](./screenshots/task5_web.png)](./screenshots/task5_web.png)  

---

### Task 6 — Jenkins Pipeline
**Description:** Declarative Jenkinsfile to build Docker image and push to DockerHub.  

**Screenshots:**  
[![Jenkinsfile](./screenshots/task6_jenkinsfile.png)](./screenshots/task6_jenkinsfile.png)  
[![Build](./screenshots/task6_build.png)](./screenshots/task6_build.png)  
[![DockerHub](./screenshots/task6_dockerhub.png)](./screenshots/task6_dockerhub.png)  

---

## 🗂 Project Structure


internship/
├─ screenshots/ # All task screenshots
├─ docker-playbook.yml # Ansible playbook
├─ docker-compose.yml # Docker Compose file
├─ Jenkinsfile # Jenkins pipeline
├─ terraform/ # Terraform scripts for EC2
└─ README.md # Project overview (this file)


---

## 🛠 Technologies Used
- **Ansible** — Configuration Management  
- **Terraform** — Infrastructure as Code  
- **Docker & Docker Compose** — Containerization  
- **Jenkins** — CI/CD Pipeline  
- **AWS EC2** — Cloud Deployment  

---

## 👤 Author
**Ujjawal Rawat**  
[GitHub Profile](https://github.com/Ujjawal17-alt)  

---


