# minikube commands



``` bash
minikube version  

# noted: by default settings, it use docker to install the minikube , we could change it to use virtualbox
VBoxManage -version

minikube start

minikube start --driver=virtualbox

minikube stop

minikube delete

minikube ip

minikube addons list

minikube addons enable dashboard

minikube dashboard --url

minikube dashboard 

# access minikube
minikube ip
ssh docker@192.168.59.101
# username: “docker”, password: “tcuser” for minikube login

# connect certain container, for example nginx
docker exec -it dd0cc1ebf95b sh

# check nginx container hostname
hostname
hostname -i  

# check nginx content by ip
curl 172.17.0.5

```