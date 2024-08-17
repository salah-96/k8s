Deploya images till Kubernetes

Nu när images är uppe på Docker Hub, kan du skapa Kubernetes-resurser för att deploya dem.

1. Navigera till k8s:

# cd ../k8s

2. Starta minikube:

# minikube start

3. Kolla så att minikube är igång:

# minikube status

4. Deploya till Kubernetes. kör följande kommando för att tillämpa alla filer i k8s:

# kubectl apply -f .

5. Öppna Kubernetes Dashboard

# minikube dashboard


# k8s
