kubectl cluster-info

kubectl run php-pod --image=php:8.0.7-fpm-alpine3.13

kubectl get pods

kubectl describe pod php-pod

kubectl get pods --watch

kubectl apply -f .\pod-php-minikube.yml

minikube addons list

minikube addons enable ingress

minikube addons list

kubectl apply -f .\deployment-minikube.yml

kubectl get deployments

kubectl get rs

kubectl get pods

kubectl apply -f .\service-clusterip.yml

kubectl get services

kubectl apply -f .\ingress-nginx.yml

kubectl get ingress

minikube tunnel
