# Kubernetes Basic

## Trouble Shooting

Cannot expose service to local machine: https://github.com/kubernetes/minikube/issues/11193

```cmd
minikube start --ports=30080:30080,30081:30081
```