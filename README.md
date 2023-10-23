# node-red

## Install Nginx Ingress controller in Kubernetes
'''
helm upgrade --install ingress-nginx ingress-nginx \
  --repo https://kubernetes.github.io/ingress-nginx \
  --namespace ingress-nginx --create-namespace
'''

## Install Helm charts
helm upgrade  --install node-red-app .
'''

### check deployment
'''
kubectl get deployment
'''
![image](https://github.com/ahmedelmelegy/node-red/assets/62904201/9c5b82c7-c4a6-4aa1-8aa1-6fd1277d9124)

### Open node-red in browser
![image](https://github.com/ahmedelmelegy/node-red/assets/62904201/706b07ab-c205-4c6d-a2ca-65755171ab9d)
