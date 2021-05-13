# k8s-nginx-mysql

Esse repositório sobe dois pods validados pelo minikube, nginx e mysql, mapeando a porta 80 do nginx para acesso externo ao cluster e permitindo que o contêiner do nginx tenha comunicação de rede no contêiner mysql pela porta 3306. 

## Execucão

Criação dos pods e serviços:
* kubectl apply -f .

Acesso ao nginx externo:
* minikube service myapp-loadbalancer
