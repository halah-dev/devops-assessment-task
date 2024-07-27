# DevOps Engineer Task: Automated Deployment and Container Orchestration

To set up an automated deployment pipeline for a sample web application using Ansible, Docker, and Kubernetes, follow these steps:
1. For local K8s environment, I used Minikube.
2. I created a sample Node.js application, that only print `Hello, World :)`.

## Prerequisites
- A system running a Linux-based OS
- `curl` and `sudo` installed on your system

## Instructions:
1. **Install Minikube**
```bash
   curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
   sudo install minikube-linux-amd64 /usr/local/bin/minikube
   ```
2. **Start Minikube**
```bash 
    minikube start
```
3. **Install Docker**
```bash 
    sudo apt install apt-transport-https ca-certificates curl software-properties-common
    curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
    sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"
    sudo apt install docker-ce
```
4. **Verify Installation**
```bash 
    docker --version
    minikube status
```
