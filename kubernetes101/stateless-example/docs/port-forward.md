# Access NodePort via Port Forwarding

```
kubectl get pod | grep lobsters
```

```
kubectl port-forward lobsters-<pod_id> 3000:3000
```
