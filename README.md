**Como queria um cluster utilizando Kind**

***Cluster simples***

1.Passo - Instalar o Kind 

2.Passo - Inatalar o Docker

3.Passo - Criar o cluster 
- kind creater cluster (Esse comando cria um cluster simples de um unico nó)

***Cluster MultiNodes***

Seguir o passo 1 e 2 do Cluster Simples

- criar um arquivo nomedocluster.yaml
- Colocar dentro do arquivo as configuração do arquivo kind-cluster.yaml desse repositorio
- Dar o comando kind create cluster --config kind-cluster.yaml --name giropops (Isso criara o cluster olhando para as configurações que você colocar no arquivo nomedocluster.yaml)
