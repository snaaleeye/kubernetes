## What is Kubernetes?

Kubernetes (also known as k8s or “kube”) is an open source container orchestration platform that automates many of the manual processes involved in deploying, managing, and scaling containerized applications.

Kubernetes clusters together groups of hosts running containers, and helps you easily and efficiently manage those clusters.

Benefits:

Self Healing
Load Balancing and Service Dicov
Automated rollouts and rollback
Auto Scaling
Automatic bin packing
Storage orchestration

### Kubernetes should be used:
If your application uses a microservice architecture

Slow development and deployment

To lower infrastructure costs

### Kubernetes should not be used for:

Simple, lightweight applications

Short time frame for delivery

## What are K8 objects and services?


## What is a k8 cluster?

Kubernetes clusters together groups of hosts running containers, and helps you easily and efficiently manage those clusters.

A process that runs multiple instances of a Pod and keeps the specified number of Pods constant



## K8 Commands

`kubectl`

`kubectl get service` or `kubectl get svc`

`kubectl get deployment` or `kubectl get deploy`

`kubectl get pods`

`kubectl delete`

`kubectl get all`

`kubectl cluster-info`

For mac you need to explicilty allow the portsls

`kubectl describe deploy nginx` 

`kubectl edit deploy nginx` 

`kubectl create -f svc-nginx.yml`

`kubectl exec sparta-app-7b9f5cdf76-fkcwc env node seeds/seed.js`
