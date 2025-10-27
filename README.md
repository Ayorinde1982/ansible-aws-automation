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
[![Ansible](https://img.shields.io/badge/Ansible-2.16-red?logo=ansible)](https://www.ansible.com/)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-24.04-orange?logo=ubuntu)](https://ubuntu.com/)
[![Docker](https://img.shields.io/badge/Docker-Latest-blue?logo=docker)](https://www.docker.com/)
[![GitHub stars](https://img.shields.io/github/stars/yourusername/ansible-aws-automation)](https://github.com/yourusername/ansible-aws-automation/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
