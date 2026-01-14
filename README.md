# Ansible Webserver Project

## Project Overview
Automated deployment of a web server using Ansible roles.

This project demonstrates configuration management and automation by preparing a Linux server from scratch, installing Docker, and running an Nginx container that serves a custom web page.

## Tools
- Ansible
- Docker
- Nginx
- Linux (Ubuntu)

## Folder Structure
--- bash
ansible-webserver-project/
├── inventory
├── playbook.yml
├── roles/
│   ├── common/
│   │   └── tasks/main.yml
│   ├── docker/
│   │   └── tasks/main.yml
│   └── nginx/
│       └── tasks/main.yml
├── files/
│   └── index.html
├── screenshots/
│   ├── ansible-run.png
│   └── web-page.png
└── README.md

---

## Prerequisites
- Ubuntu-based target server
- Ansible installed on control node
- SSH access to target server
- Python installed on target server

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/sagedsalah/ansible-webserver-project.git
cd ansible-webserver-project
