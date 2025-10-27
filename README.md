# Ansible AWS Automation Project

## Overview
This project demonstrates infrastructure automation using Ansible on AWS EC2 instances.

## Infrastructure
- **Control Node:** Ubuntu 24.04 LTS (AWS EC2)
- **Managed Node:** Ubuntu 24.04 LTS (AWS EC2)
- **Configuration Management:** Ansible

## What's Included

### Playbooks
1. **install-git.yml** - Installs Git on managed nodes
2. **install-nginx.yml** - Installs and configures Nginx web server
3. **install-docker.yml** - Installs Docker and runs Apache container
4. **deploy-webserver-role.yml** - Deploys webserver using Ansible roles

### Roles
- **webserver** - Modular role for deploying Nginx with custom templates

## Project Structure
