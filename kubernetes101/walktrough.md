# Kubernetes 101

1. Componentes Básicos do Kubernetes
---
  https://thenewstack.io/kubernetes-an-overview/
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

#### Componentes Lógicos
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

#### Infra
  - Master
    - apiserver
    - etcd
    - network
    - controller-manager
    - scheduler

  - Node/Minion
    - kubelet
    - container runtime
    - proxy

![Kubernetes Architecture](https://cdn.thenewstack.io/media/2016/11/Chart_02_Kubernetes-Architecture.png)

![Master Detail](https://cdn.thenewstack.io/media/2016/11/Chart_03_Kubernetes-Master.png)

![Node Detail](https://cdn.thenewstack.io/media/2016/11/Chart_04_Kubernetes-Node.png)

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
