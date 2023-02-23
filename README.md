### Requirements
Docker, kubectl, minikube

### Commands
```bash
kubectl apply -f deployment.yml #apply deployment
kubectl get pods #check if pods are running
kubectl get svc #get services
minikube service kubernetes-app #open app in browser
```

#### Articles
https://www.digitalocean.com/community/tutorials/how-to-use-minikube-for-local-kubernetes-development-and-testing
https://www.digitalocean.com/community/tutorials/how-to-migrate-a-docker-compose-workflow-to-kubernetes
https://www.digitalocean.com/community/tutorials/building-optimized-containers-for-kubernetes