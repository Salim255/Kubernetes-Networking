# Kubernetes-Networking

# This application consist of three differents backend APIs which will work togethern three different container in the end

# Run: $minikube status

# Be sure there are on going deployemnt run: $kubectl get deployment => kubectl delete deploy story-deployment

# Be sure : kubectl get services => kubectl delete service backend

# Create users deployment yaml file, then apply it to our cluster

# 🍎 Service allow us to do two main things:

## 1\ They gave a stable address

## 2\ Allow outside world access

# Create user service yaml file

# run: kubectl service user-service.yaml

# To get the service name the url adres: minikube service users-service
