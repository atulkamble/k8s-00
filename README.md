# k8s-00
kubernetes-practice
```
Clear-History
cd D:/project
mkdir k8s-00
cd k8s-00
Git clone https://github.com/atulkamble/k8s-00.git
cd k8s-00
Minikube start
New-Item deployment.yaml
code .
New-Item service.yaml
Kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
git add .
git status
git commit -m "added deployemnt and service files"
git push origin main
kubectl get nodes
kubectl get pods
kubectl apply -f deployment.yaml
kubectl get pods
kubectl get services
kubectl apply -f services.yaml
kubectl apply -f service.yaml
kubectl get services
kubectl get pods
kubectl describe pod my-deployment-cfb4dd9fc-lmb6v
kubectl get services
kubectl get deployments
kubectl scale deployment my-deployment --replicas=5
kubectl get pods
kubectl scale deployment my-deployment --replicas=2
kubectl get pods
```

