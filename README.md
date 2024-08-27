# Kube commands to achieve this

minikube installation (linux)

curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube && rm minikube-linux-amd64

minikube start

kubectl get po -A

minikube kubectl -- get po -A

minikube dashboard


to deploy yaml and loadbalancer : 

kubectl apply -f user-service-deployment.yaml
kubectl apply -f user-service.yaml


![image](https://github.com/user-attachments/assets/967f5c54-a5d0-4b54-a131-7462a2a8b483)
