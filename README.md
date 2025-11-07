# README
mkdir simpleK8s
client-pod.yaml

minikube start
kubectl cli...

Types of objects:
- Pod: run one or more closely related containers (with similar properties)
- Service: sets up networking on a kubernetes clusters
   - ClusterIP:
   - NodePort: Exposes a container to the outside world
   - LoadBalancer:
   - Ingress:

kubectl apply -f client-pod.yaml 

kubectl apply -f client-node-port.yaml 

kubectl get pods

kubectl get services

minikube ip // docker desktop kebernetes users should access at localhost:31515

kubectl describe