### Kubernetes:
It’s developed by google borg. its open source and it’s used as Container orchestration platform 

### Kubernetes Architechture:
![diagram](https://miro.medium.com/v2/resize:fit:5756/1*t2kujM8JnnAU1EmJkBX-QQ.png)
### Kubernetes component:
#### Control Plane/Master Node:
- Api server
- Scheduler
- Etcd
- Controller 
- Cloud controller manager 

#### Data Plane/Worker Node:
- Kubelet
- Kube proxy
- Container runtime 

### Kops-K8s Production System:
Kops: Kubernetes operation for aws and azure
#### Life cycles of Kubernetes and its managed by kops 
- Creation of cluster
- upgrade 
- Modification 
- Deletion

### K8s distribution:
- Kubernetes 
- Openshift
- Tanzu
- Eks
- Aks
- Gke
- Dke

### Kubernetes Deployment:
a deployment is a declarative way to manage and control the deployment of applications using replica set.

#### Pod vs Deployment
- A pod is a unit including one or more containers
- A Deployment is a management tool for controlling the behavior of pods.

- Deployment->Replica set->Pods

### Kubernetes Service:
- Load Balancing
- service discovery-Lebels and slectors
1. Cluster ip- its default one which is only access inside the k8s cluster
2. Node port- its only access from inside the organisation and its acess to from node
3. load balancer: its acess from external world

#### Ingress Controller:

1. Path based routing: http://example.com/about
- Note: /about is path based routing

2. Host based routing: http://support.example.com
- Note: support. Is host based routing

3. Ssl termination:
Https- which is secure 

### RBAC: Role based access control 
1. Service account / user
2. Roles / cluster roles
3. Role binding / cluster role binding (CRB)

Service account - Role - Role Binding 

### Custom Resources (CR)
Its a instance of crd

### Custom Resources Definition (CRD)
To extend kubernetes api or to create new resources in kubernetes 

### Custom Controller (CC)
Custom controller implement CRD and make sure that current state matches the desire state

### Terms:
- Cluster - Group of nodes
- Loadbalncing
- Namespace - its a way to organize isolated virtual sub-cluster in cluster
- Kubernetes is master and node architecture 
- Cncf - Cloud native computing foundation 
