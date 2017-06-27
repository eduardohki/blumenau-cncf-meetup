# Kubernetes 101

1. Componentes Básicos do Kubernetes
---
  https://kubernetes.io/docs/concepts/
  - Pods
  - Service
  - Volume
  - Namespace
  - Replication Controllers
    - ReplicaSet
    - Deployment
    - StatefulSet
    - DaemonSet
    - Job
  - Ingress
  - Master
    - apiserver
    - etcd
    - network
    - controller-manager
    - scheduler
  - Node/Minion
    - kubelet
    - proxy

2. kubectl
---
  https://kubernetes.io/docs/user-guide/kubectl-overview/
  - Especificações YAML
  - Operações: create / delete / apply / run
  - Exibições: describe / explain / edit / logs
  - Acesso: proxy / expose / port-forward

3. Criar uma aplicação Stateless
---
  https://github.com/kelseyhightower/lobsters-on-kubernetes
  - Docker image
  - MySQL
  - Lobsers
  - Jobs
  - Accessing
  - Rolling Updates
  - Scaling
