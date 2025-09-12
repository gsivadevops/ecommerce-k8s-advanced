# ecommerce-k8s-advanced
Advanced Kubernetes deployment of an ecommerce application with StatefulSets, Autoscaling configurations.

**Overview**
This repository showcases an advanced deployment of a microservices-based ecommerce application on Kubernetes.
It focuses on StatefulSets for databases and autoscaling strategies to handle production workloads efficiently.

**Architecture**

Frontend → Stateless service with HPA enabled.

Backend Services → Cart, User, Catalogue, Payment, Shipping with HPA.

Database → MongoDB / MySQL deployed using StatefulSet with persistent volumes.

Kubernetes Features → StatefulSets, Horizontal Pod Autoscaler (HPA)

Load Balancing → For routing external traffic.
