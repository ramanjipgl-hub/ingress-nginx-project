# 🚀 AKS Ingress Demo Project

This mini project deploys a sample web and API application to Azure Kubernetes Service (AKS) and exposes them using the NGINX Ingress Controller.

---

## 🧩 Prerequisites
- AKS cluster running (`ramaks` in `ram_rg`)
- `az`, `kubectl`, and `helm` installed
- Logged in:
  ```bash
  az login
  az aks get-credentials -g ram_rg -n ramaks --overwrite-existing
