# Continuous Deployment with Ansible

## Prerequisites

- Ansible installed on your system
- Docker installed on your system
- Minikube installed and running

## Instructions

1. **Create Ansible Playbook**
- You Can view the web application by viewing `deploy.yaml` file.
2. **Configure CI/CD Pipeline**
- Set up a CI/CD pipeline to trigger the Ansible playbook on code push. This example uses GitHub Actions.
- The following file named `.github/workflows/deploy.yaml` showcase it.
- The Ansible playbook will now automate the deployment process, and the CI/CD pipeline will trigger the deployment on code push.