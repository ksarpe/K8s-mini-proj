# K8s-mini-proj

# Starting minikube
minikube start --driver=docker -> `starting the node`

# Some useful commands
kubectl get nodes -> `to check the nodes (pods/services/deployment/replicaset also can be viewed)`
kubectl version -> `client and server should be listed`

# Creating a deployment (indirectly creates a pod) "kubectl create deployment <name> --image=<image-name>"
# It is a blueprint for creating pods
kubectl create deployment nginx-depl --image=nginx





