# ⚙️ CI/CD Pipeline Lab

This project demonstrates the implementation of a complete **CI/CD pipeline** using **GitLab CI/CD**, **Docker**, and automation scripts in **Shell** and **Python**.

It was developed as part of my Software Engineering studies and simulates a **real DevOps environment**, where every code change triggers an automated workflow — from build to deployment and notifications.

---

## 🎯 Project Goal

Create a professional-grade pipeline for a virtual store application that:

- Automates build, test, deploy, and notification stages  
- Uses Docker for consistent environments  
- Executes on every commit (Continuous Integration)  
- Provides real-time feedback through logs and notifications  
- Simulates a production-ready DevOps workflow  

This lab transforms manual, error-prone processes into **automated, reliable, and repeatable flows**.

---

## 🧱 Architecture Overview

The pipeline is composed of four main stages:

1. **Build**  
   - Builds the Docker image of the application  
2. **Test**  
   - Validates the container and execution flow  
3. **Deploy**  
   - Prepares the application for production  
4. **Notify**  
   - Sends success or failure notifications  

The workflow is defined in a `.gitlab-ci.yml` file using YAML and runs automatically on each commit to the `main` branch.

---

## 🛠 Technologies & Tools

- GitLab CI/CD  
- Docker  
- YAML  
- Shell Script  
- Python  
- Git  

Key files in this project:

- `.gitlab-ci.yml` — Full pipeline definition  
- `Dockerfile` — Container configuration  
- `notificacaoSucesso.sh` — Success notification script  
- `notificacaoFalhas.sh` — Failure notification script  
- `relogio.py` — Timestamp utility for execution tracking  

---

## 📊 What This Project Shows

- Understanding of CI/CD concepts  
- Infrastructure as Code mindset  
- Automation of software delivery  
- Integration between tools in a DevOps stack  
- Monitoring and observability through logs and statuses  
- Professional workflow used in real-world environments  

---

## 🌱 What I Learned

- How to structure a multi-stage pipeline  
- How Docker improves consistency across environments  
- How automation reduces errors and increases delivery speed  
- How DevOps practices connect development and operations  
- How every commit can become a safe, traceable deployment  

This project represents my first hands-on experience with **Agile Infrastructure** and modern DevOps practices.

It’s not just about tools — it’s about building systems that are **reliable, transparent, and scalable**.
