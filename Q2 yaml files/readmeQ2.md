# Q2: Kubernetes Deployment

In this part , i deployed a MERN stack application onto a Kubernetes cluster (Minikube). i create YAML files for namespacing, persistent storage, and service orchestration.

### Commands and Descriptions


 `kubectl apply -f 00-namespace.yaml`  Create the namespace to isolate our application resources. 
 `kubectl apply -f 01-mongodb.yaml`  Deploy MongoDB with persistent storage (PVC) and exposes it via a ClusterIP service. 
 `kubectl apply -f 02-backend.yaml`  Deploy the backend API with 2 replicas and exposes it through a NodePort service on port 30300. 
 `kubectl apply -f 03-frontend.yaml`  Deploy the frontend UI with 2 replicas and exposes it through a NodePort service on port 30173. 
 `kubectl get all -n 22i2463-mern-app`  Shows the status of all pods, services. 
 `kubectl delete -f .`  Remove all resources defined in the YAML files from the cluster. 

