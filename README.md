# ShopKube Manifests

GitOps repository for ShopKube Kubernetes manifests.

## Structure
apps/shopkube/ → Main application manifests
argocd/        → ArgoCD Application definitions

## Deployment
ArgoCD automatically syncs changes to the cluster.
Do NOT run kubectl apply manually in production.
