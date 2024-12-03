```shell
kubectl config use-context docker-desktop

helm repo add argo https://argoproj.github.io/argo-helm
helm install argo-cd argo/argo-cd --version 7.7.5 --namespace argo-cd --create-namespace
```
