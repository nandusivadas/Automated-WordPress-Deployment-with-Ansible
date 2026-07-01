#  Automated WordPress Deployment with Ansible on AWS EC2 (Linux)

![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![Ansible](https://img.shields.io/badge/Ansible-Automation-red)
![Linux](https://img.shields.io/badge/Linux-Amazon%20Linux-blue)
![Nginx](https://img.shields.io/badge/Nginx-Web%20Server-green)
![WordPress](https://img.shields.io/badge/WordPress-CMS-blue)
![MariaDB](https://img.shields.io/badge/MariaDB-Database-brown)

##  Project Overview

This project automates the deployment of a secure **WordPress hosting environment** on **AWS EC2 (Amazon Linux 2023)** using **Ansible Roles**. Following the principles of **Infrastructure as Code (IaC)**, the solution automates the installation and configuration of **Nginx**, **PHP**, **MariaDB**, **WordPress**, **phpMyAdmin**, **SFTP**, and **Let's Encrypt SSL**, delivering a secure, consistent, and repeatable deployment process.



# 📖 Architecture

<p align="center">
<img src="screenshots/00.png" width="900">
</p>



# ✨ Features

- 🚀 Infrastructure as Code (IaC)
- ⚙️ Automated WordPress Deployment
- 📦 Modular Ansible Role-Based Architecture
- 🌐 Nginx Web Server Configuration
- 🐘 PHP Installation & Configuration
- 🗄️ MariaDB Database Setup
- 📝 WordPress Deployment
- 💻 phpMyAdmin Integration
- 🔐 Secure SFTP Configuration
- 🌍 DuckDNS Domain Integration
- 🔒 HTTPS using Let's Encrypt SSL



# 🛠 Technologies Used

| Category | Technology |
|-----------|------------|
| Cloud Platform | AWS EC2 |
| Operating System | Amazon Linux 2023 |
| Automation | Ansible |
| Web Server | Nginx |
| Database | MariaDB |
| CMS | WordPress |
| Programming Language | PHP |
| Database Tool | phpMyAdmin |
| Secure File Transfer | OpenSSH (SFTP) |
| SSL | Certbot & Let's Encrypt |
| Version Control | Git & GitHub |



# 📂 Project Structure

```text
wordpress-project/
├── ansible.cfg
├── inventory
├── site.yml
├── roles/
│   ├── nginx/
│   ├── php/
│   ├── mariadb/
│   ├── wordpress/
│   ├── phpmyadmin/
│   ├── sftp/
│   └── ssl/
├── docs/
│   └── Automated-WordPress-Deployment-with-Ansible.pdf
├── screenshots/
└── README.md
```



# ⚙️ Deployment Workflow

```text
AWS EC2
    │
    ▼
Ansible Playbook
    │
    ▼
Ansible Roles
    │
    ├── Nginx
    ├── PHP
    ├── MariaDB
    ├── WordPress
    ├── phpMyAdmin
    ├── SFTP
    └── SSL
    │
    ▼
Fully Automated WordPress Website
```



# 📷 Project Screenshots

## AWS EC2 Infrastructure

![AWS EC2](screenshots/01.png)



## Project Structure

<p align="center">
<img src="screenshots/03.png" width="1000">
</p>



## Main Ansible Playbook

<p align="center">
<img src="screenshots/04.png" width="1000">
</p>



## Nginx Role Execution

![Nginx Role](screenshots/05.png)



## WordPress Installation Wizard

![WordPress Installation](screenshots/09.png)

![WordPress Installation](screenshots/10.png)


## WordPress Dashboard

![WordPress Dashboard](screenshots/11.png)



## Domain Configuration

![Domain Configuration](screenshots/13.png)



## Final Project Output

![Final Output](screenshots/19.png)

---

# 📚 Documentation

Complete project documentation is available in the **docs** directory.

```text
docs/
└── Automated-WordPress-Deployment-with-Ansible.pdf
```



# 👨‍💻 Author

**Nandu Sivadas**

Cloud & DevOps Enthusiast

- LinkedIn: https://www.linkedin.com/in/nandu-sivadas-556264396

---
