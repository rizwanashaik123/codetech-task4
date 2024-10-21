# Nginx Kubernetes Deployment

This project contains Kubernetes deployment and service files to deploy and expose an Nginx server.

## Files

1. `nginx-deployment.yaml`: Defines a Kubernetes Deployment for Nginx with 2 replicas.
2. `nginx-service.yaml`: Exposes the Nginx deployment using a LoadBalancer.

## Steps to Deploy

### Deploy the Nginx App to a Kubernetes Cluster

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/k8s-nginx-deployment.git
   cd k8s-nginx-deployment
