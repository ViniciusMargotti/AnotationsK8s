# Anotações-esK8s

## Minikube commands
minikube service <POD>

## Docker commands

docker save srlopes/fortunecookie:v1 | (eval $(minikube docker-env) && docker load) : Salvar Imagem Docker local para deployment no MiniKube(K8s)

docker-images: ver imagens da maquina

## K8s commands

kubectl create deployment fortunecookie --image=srlopes/fortunecookie:v1  : Criando deploy Sprint/Minibube

kubectl expose deployment fortunecookie --type=LoadBalancer --port=8080   : Liberando acesso da porta 8080 para a aplicação




