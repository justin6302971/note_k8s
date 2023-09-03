# kubenetes practice


``` bash
kubectl version --client --output=yaml

kubectl cluster-info

kubectl config view

kubectl help

kubectl get node

kubectl get pods
kubectl get pods  --namespace=kube-system 

kubectl get pods -o wide


kubectl get namespaces

kubectl run ngnix --image=nginx

kubectl describe pod ngnix

kubectl delete pod ngnix

kubectl create deployment nginx-dev --image=nginx

kubectl get deployment

kubectl describe deployment nginx-dev 

kubectl scale deployment nginx-dev --replicas=5

kubectl expose deployment nginx-dev --port=8080 --target-port=80

kubectl get services 

kubectl describe service nginx-dev 

kubectl delete deployment nginx-dev
kubectl delete service nginx-dev


```