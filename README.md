# GitOps with ArgoCD

## Setup ArgoCD
Cluster
```
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/core-install.yaml
```

Local
Install ArgoCD CLI utility


## CLI

Before using `argocd`
```
kubectl config set-context --current --namespace=argocd

argocd admin dashboard

argocd app list
```