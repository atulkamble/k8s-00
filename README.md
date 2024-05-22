# k8s-00
kubernetes-practice

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

