# node-red

## Install Nginx Ingress controller in Kubernetes
'''bash
helm upgrade --install ingress-nginx ingress-nginx \
  --repo https://kubernetes.github.io/ingress-nginx \
  --namespace ingress-nginx --create-namespace
'''

## Install Helm charts
'''bash
helm upgrade  --install node-red-app
helm list
'''
![image](https://github.com/ahmedelmelegy/node-red/assets/62904201/bf2047d5-7e9b-44cb-bf34-8a3193ac7502)

### check deployment
'''bash
kubectl get deployment
'''
![image](https://github.com/ahmedelmelegy/node-red/assets/62904201/9c5b82c7-c4a6-4aa1-8aa1-6fd1277d9124)
'''bash
kubectl get pods
'''
![image](https://github.com/ahmedelmelegy/node-red/assets/62904201/a85f1484-29c4-4044-98d4-d257d0bd27e6)

### Open node-red in browser
![image](https://github.com/ahmedelmelegy/node-red/assets/62904201/706b07ab-c205-4c6d-a2ca-65755171ab9d)
