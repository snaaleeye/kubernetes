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

## What is a K8 objects?

Kubernetes objects are persistent entities in the Kubernetes system. Kubernetes uses these entities to represent the state of your cluster. A Kubernetes object is a "record of intent"--once you create the object, the Kubernetes system will constantly work to ensure that object exists. By creating an object, you're effectively telling the Kubernetes system what you want your cluster's workload to look like; this is your cluster's desired state.

## What is a K8 service?
An abstract way to expose an application running on a set of Pods as a network service.
With Kubernetes you don't need to modify your application to use an unfamiliar service discovery mechanism. Kubernetes gives Pods their own IP addresses and a single DNS name for a set of Pods, and can load-balance across them.


## What is a K8 cluster?

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
