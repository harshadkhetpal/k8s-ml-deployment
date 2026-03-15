# ☸️ Kubernetes ML Deployment — Helm + ArgoCD + KEDA

> GitOps ML deployment on Kubernetes — Helm, ArgoCD, KEDA scale-to-zero, and canary rollouts.

## 🚠 Deploy
```bash
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
kubectl apply -f argocd/apps/ml-platform.yaml
```
