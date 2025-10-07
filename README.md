# DevOps Internship Tasks by Ujjawal Rawat

6 internship tasks completed — Terraform, Docker, Ansible, Jenkins, EC2 deployments.

---

## Project Summary
Full documentation and screenshots for all 6 internship tasks with step-by-step commands, configs, and verification.

---

## Quick Links
- [Doc 1 — Ansible](./docs/doc1.md)  
- [Doc 2 — Terraform](./docs/doc2.md)  
- [Doc 3 — Docker Compose](./docs/doc3.md)  
- [Doc 4 — Webhook Integration](./docs/doc4.md)  
- [Doc 5 — EC2 Deployment](./docs/doc5.md)  
- [Doc 6 — Jenkins Pipeline](./docs/doc6.md)  

---

## Tasks Overview

### Task 1 — Ansible
**Description:** Install Docker, pull Docker image, run container with restart policy.  
**Playbook:** `docker-playbook.yml`  

**Screenshots:**  
![SSH](./screenshots/task1_ssh.png)  
![Inventory](./screenshots/task1_inventory.png)  
![Playbook](./screenshots/task1_playbook.png)  
![Docker ps](./screenshots/task1_dockerps.png)  
![Browser](./screenshots/task1_browser.png)  

---

### Task 2 — Terraform
**Description:** Launch EC2 instance, open ports 80 & 22, install Docker via `user_data`.  

**Screenshots:**  
![Terraform Init](./screenshots/task2_init.png)  
![Terraform Apply](./screenshots/task2_apply.png)  
![EC2](./screenshots/task2_ec2.png)  

---

### Task 3 — Docker Compose
**Description:** Run Nginx static site with optional Watchtower container.  

**Screenshots:**  
![Compose File](./screenshots/task3_compose.png)  
![Nginx](./screenshots/task3_nginx.png)  

---

### Task 4 — GitHub → Jenkins
**Description:** Configure webhook to trigger Jenkins job on push to main.  

**Screenshots:**  
![Webhook](./screenshots/task4_webhook.png)  
![Jenkins](./screenshots/task4_jenkins.png)  

---

### Task 5 — Deploy to EC2
**Description:** SSH into EC2, pull Docker image, run container, expose on port 80/8080.  

**Screenshots:**  
![Pull](./screenshots/task5_pull.png)  
![Run](./screenshots/task5_run.png)  
![Web](./screenshots/task5_web.png)  

---

### Task 6 — Jenkins Pipeline
**Description:** Declarative Jenkinsfile to build Docker image and push to DockerHub.  

**Screenshots:**  
![Jenkinsfile](./screenshots/task6_jenkinsfile.png)  
![Build](./screenshots/task6_build.png)  
![DockerHub](./screenshots/task6_dockerhub.png)  

---

## Screenshots Gallery
All screenshots are grouped by task. Place all files in the `/screenshots/` folder.

---

Built with ❤️ by Ujjawal Rawat  
[GitHub](https://github.com/Ujjawal17-alt)
