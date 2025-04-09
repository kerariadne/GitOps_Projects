# EKS GitOps Project with ArgoCD & Nginx

This project demonstrates deploying an Nginx web server on **AWS EKS**, managed via **ArgoCD** using GitOps principles.

## 🔧 Tools Used

- AWS EKS
- ArgoCD
- Kubernetes
- GitOps Workflow

## 📁 Project Files

- [`nginx-deployment.yaml`](./nginx-deployment.yaml) — Deploys Nginx to the cluster
- [`nginx-service.yaml`](./nginx-service.yaml) — Exposes Nginx via LoadBalancer
- [`argocd-app.yaml`](./argocd-app.yaml) — Configures ArgoCD to sync this app

## 🌐 Access

After deployment, the app is available via the LoadBalancer DNS.

## 📸 Screenshots

### 🔹 Deployed App (Nginx)

![Nginx App Screenshot](nginx_app.png)

### 🔹 ArgoCD UI

![ArgoCD UI](argocd.png)

## ✅ Status

- [x] EKS cluster created
- [x] ArgoCD installed
- [x] Nginx deployed
- [x] ArgoCD GitOps pipeline set up
