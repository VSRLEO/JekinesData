# Flask Kubernetes App

## Build and Push Docker Image

```bash
docker build -t your-dockerhub-username/flask-k8s-app:latest .
docker push your-dockerhub-username/flask-k8s-app:latest
```

## Deploy to Kubernetes

```bash
kubectl apply -f deployment.yaml
kubectl get pods
kubectl get service flask-service
```
