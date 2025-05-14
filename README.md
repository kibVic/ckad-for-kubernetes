# ckad-for-kubernetes
minikube version
kubectl version
minikube start
kubectl create deployment nginx-deployment --image=nginx
kubectl get pod
kubectl logs podname
kubectl get nodes
kubectl get deployment
kubectl exec -it podname -- bin/bash

kubectl delete deployment deployment_name 
kubectl get pod pod_name -o wide
kubectl get pod pod_name --watch
kubectl get all 
kubectl get service
kubesctl get configmap
kubectl get secret
kubectl edit pod podname 
kubect apply -f deploymnet.yaml
kubectl delete -f deployment.yaml

kubectl get  deployment  deployment_name -o yaml > mongo-result.yaml

echo -n 'username' | base64
echo -n 'password' | base64