# minikube-keycloak

```
kubectl create ns keycloak
kubectl apply -f keycloak.yaml
```

Optional create Ingress:
```
minikube addons enable ingress
replace 192.168.59.102 with your $(minikube ip)
kubectl apply -f ingress.yaml
```
