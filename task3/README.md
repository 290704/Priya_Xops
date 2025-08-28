#  CI/CD Pipeline – Automatic Deployment on AWS EC2

##  Project Overview
This project is part of **XOps Microchallenge #3 – "CI/CD Pipeline in Action!"**.  
It demonstrates how to set up a **CI/CD pipeline** using **GitHub Actions** to automatically deploy a simple web app on an **AWS EC2 instance**.

---

##  Objective
- Build a simple web app (**HTML / Flask / Node.js**).
- Push code to **GitHub**.
- Automatically connect to **EC2 instance** via **SSH**.
- Deploy the code and restart the web server.

---

##  What I Learned
- Basics of **CI/CD automation** with GitHub Actions.  
- **SSH-based deployment** to EC2.  
- Secure credential management with **GitHub Secrets**.  
- Script-based deployment practices.  
- Setting up and hosting on **EC2 web servers**.  
- Fundamentals of **continuous delivery mindset**.  

---

##  Setup Guide

### 1️ Prepare Your EC2 Web Server
- Launch an EC2 instance (**Amazon Linux 2 / Ubuntu**).
- Install NGINX:
  ```bash
  # Ubuntu
  sudo apt update -y && sudo apt install nginx -y
  sudo systemctl start nginx && sudo systemctl enable nginx
