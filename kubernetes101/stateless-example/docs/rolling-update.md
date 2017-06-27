# Rolling Update

```
kubectl set image deployment lobsters lobsters=kelseyhightower/lobsters:1.1.0
```

# Scaling Pods

```
kubectl scale --replicas=2 deployments/lobsters
```
