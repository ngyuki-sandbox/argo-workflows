
> https://argo-workflows.readthedocs.io/en/latest/quick-start/

```sh
kubectl config get-contexts

kubectl create namespace argo
kubectl apply -n argo -f https://github.com/argoproj/argo-workflows/releases/download/v3.5.11/quick-start-minimal.yaml
kubectl -n argo port-forward service/argo-server 2746:2746

open https://localhost:2746
```

```sh
kubectl apply -f k8s/
```
