
# Kubernetes YAML Examples (CKA Prep)

This repository contains basic Kubernetes manifest files to help practice for the **Certified Kubernetes Administrator (CKA)** exam.

## 📂 Contents:

* **Pod** – basic pod definition
* **Deployment** – stateless applications with replicas
* **Service** – ClusterIP, NodePort, LoadBalancer
* **ConfigMap & Secret** – configuration and sensitive data management
* **Namespace** – multi-tenancy and resource isolation
* **Ingress** – expose HTTP/S applications
* **DaemonSet** – run a pod on all (or specific) nodes
* **Job & CronJob** – batch and scheduled tasks

## 🛠️ Usage

Apply any YAML manifest with:

```bash
kubectl apply -f <file.yaml>
```

Verify resources:

```bash
kubectl get pods,deploy,svc,cm,secret,ns
```

Delete resources:

```bash
kubectl delete -f <file.yaml>
```

## 🎯 Notes

* All manifests are **minimal examples**.
* Customize images, labels, and resource limits as needed.
* Useful for **CKA practice labs** and building muscle memory with `kubectl`.
