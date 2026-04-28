# Assessment Helm Chart

Simple Helm chart to deploy a microservices app on Kubernetes.

## Services

* Frontend (UI)
* API Gateway
* Quote Service

---

## Install

```bash
helm install assessment ./assessment-chart
```

---

## Upgrade

```bash
helm upgrade assessment ./assessment-chart
```

---

## Uninstall

```bash
helm uninstall assessment
```

---

## Check

```bash
helm status assessment
kubectl get pods
kubectl get svc
```

---

## Access

```bash
minikube ip
```

Open in browser:

```
http://<minikube-ip>:30080
```

---

## Notes

* Frontend calls API using NodePort
*
```

---

## Author

Aqib Hafeez
