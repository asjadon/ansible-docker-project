# 🚀 Ansible Docker Deployment on AWS EC2

This project demonstrates how to use Ansible to automatically install Docker and deploy an Nginx container on an AWS EC2 instance.

---

## 📌 Project Overview

Using Ansible as a control node, we:

- Connect to EC2 instance via SSH
- Install Docker using YUM
- Start and enable Docker service
- Add ec2-user to Docker group
- Pull Nginx image
- Run Nginx container on port 8081

---

## 🏗 Architecture

Control Node (Local Machine / WSL)
        |
        | SSH (Port 22)
        |
Managed Node (AWS EC2 - Amazon Linux 2023)
        |
        | Docker
        |
Nginx Container (Port 8081 → 80)

---

## 🛠 Technologies Used

- Ansible
- Docker
- AWS EC2
- Amazon Linux 2023
- Git & GitHub

---

## 📂 Project Structure

