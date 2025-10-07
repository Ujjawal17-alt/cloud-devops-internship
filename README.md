# DevOps Internship Tasks by Ujjawal Rawat

**6 internship tasks completed — Terraform, Docker, Ansible, Jenkins, EC2 deployments.**

---

## Project Summary
Full documentation and screenshots for all 6 internship tasks with step-by-step commands, configs, and verification.

---

## Quick Links
| Docs | |
|------|----------------|
| [Doc 1](./docs/doc1.md) | Ansible |
| [Doc 2](./docs/doc2.md) | Terraform |
| [Doc 3](./docs/doc3.md) | Docker Compose |
| [Doc 4](./docs/doc4.md) | Webhook Integration |
| [Doc 5](./docs/doc5.md) | EC2 Deployment |
| [Doc 6](./docs/doc6.md) | Jenkins Pipeline |

---

## Tasks Overview

### Task 1 — Ansible ![Ansible](https://img.shields.io/badge/Ansible-DD0000?style=for-the-badge&logo=ansible&logoColor=white)
**Description:** Install Docker, pull Docker image, run container with restart policy.  
**Playbook:** `docker-playbook.yml`  

**Screenshots:**  
![SSH](./screenshots/task1_ssh.png) ![Inventory](./screenshots/task1_inventory.png) ![Playbook](./screenshots/task1_playbook.png) ![Docker ps](./screenshots/task1_dockerps.png) ![Browser](./screenshots/task1_browser.png)

---

### Task 2 — Terraform ![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white)
**Description:** Launch EC2 instance, open ports 80 & 22, install Docker via user_data.  

**Screenshots:**  
![Terraform Init](./screenshots/task2_init.png) ![Terraform Apply](./screenshots/task2_apply.png) ![EC2](./screenshots/task2_ec2.png)

---

### Task 3 — Docker Compose ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
**Description:** Run Nginx static site with optional Watchtower container.  

**Screenshots:**  
![Compose File](./screenshots/task3_compose.png) ![Nginx](./screenshots/task3_nginx.png)

---

### Task 4 — GitHub → Jenkins ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
**Description:** Configure webhook to trigger Jenkins job on push to main.  

**Screenshots:**  
![Webhook](./screenshots/task4_webhook.png) ![Jenkins](./screenshots/task4_jenkins.png)

---

### Task 5 — Deploy to EC2 ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
**Description:** SSH into EC2, pull Docker image, run container, expose on port 80/8080.  

**Screenshots:**  
![Pull](./screenshots/task5_pull.png) ![Run](./screenshots/task5_run.png) ![Web](./screenshots/task5_web.png)

---

### Task 6 — Jenkins Pipeline ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
**Description:** Declarative Jenkinsfile to build Docker image and push to DockerHub.  

**Screenshots:**  
![Jenkinsfile](./screenshots/task6_jenkinsfile.png) ![Build](./screenshots/task6_build.png) ![DockerHub](./screenshots/task6_dockerhub.png)

---

## Screenshots Gallery
All screenshots are grouped by task. Place all files in `/screenshots/` folder.

---

**Built with ❤️ by Ujjawal Rawat**  
[GitHub](https://github.com/Ujjawal17-alt)
