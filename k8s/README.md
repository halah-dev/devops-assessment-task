# Kubernetes Deployment

## Prerequisites

- Minikube installed and running
- Docker image of the web application pushed to Docker Hub

## Instructions

1. **Create Kubernetes Manifests**
- You Can view the created `deployment.yaml` and `service.yaml` in the same directory.
2. **Deploy to Kubernetes**
- Apply the manifests to your local Kubernetes cluster:
```bash 
    kubectl apply -f deployment.yaml
    kubectl apply -f service.yaml
```
3. **Check Deployment Status**
- Verify the deployment and service status:
```bash 
    kubectl get deployments
    kubectl get services
```
