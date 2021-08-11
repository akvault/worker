# worker
worker app 

```kubectl config set-context --current --namespace=vote```

```helm install -f helm/worker.yaml worker helm/worker```

```helm uninstall worker```

```kubectl get pods -n vote```

