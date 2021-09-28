# [Certificação AZ-900](https://docs.microsoft.com/pt-br/learn/certifications/exams/az-900)- Azure Fundamentals </a>
---------------------------------------------------

### Precificação das Vms

* pay as you go

* Instancias Reservadas: Exemplo -> Planejou um projeto que vai precisar de 4 instancias durante 2 anos, fica mais barato, usar instancias reservadas, do que o modo pague pelo uso, contendo a possivilidade ainda de adiantar pagamentos

* Instancias spot: Permite usar capacidade ociosa das Vms , logo é um custo bem barato, mas elas podem ser interrompidas mediante a avisos 


### Subscription 

* É a assinatura que fazemos, que funciona como um container para colocar dentro dela os recursos que vamos utilizar, em uma conta, podemos ter varias assinaturas


### Grupo de Recursos

* Os grupos servem para organizar e gerenciar as tecnologias que estou usando, está abaixo do subscription, podendo separar a parte de vm storage, dentro de um grupo especifico, assim criando facilidade de deploy, updates, e de exclusão de grupos

### Gerenciamento de custos

* Billing account -  conta do administrador onde irá receber a cobrança

* subscription: Guarda chuva, onde está provisionado seus recursos

* possibilidade de ver a analise completa dos custos, quais grupos de recursos foram usados, é possivel criar alertas para valores que queira gastar.

### [Suporte](https://azure.microsoft.com/en-us/support/plans/)

* Basic: incluido para todos, Developer: $29/mes, Standard: $100/mes e Professional Direct: $1000/mes

------------------------

### [CLI](https://docs.microsoft.com/en-us/cli/azure/reference-index?view=azure-cli-latest)

* Cada provedor tem a sua CLI, para trabalhar nas linhas de comando, usando essa ferramenta, é possivel criar scripts para automatização nos processos de criação

* Lista o grupo de rescursos
>User@Azure:~$ az group list

* Criando um grupo de recursos
> User@Azure:~$ az group create --location westus --resource-group labazcli


* Listando somente o nome dos grupos de recurso
> User@Azure:~$ az group list | grep name

* Criando uma Vm com chave ssh para conexão
> User@Azure:~$ az vm create -n MyVm1 -g labazcli --image UbuntuLTS --generate-ssh-keys

* acessar a maquina
> User@Azure:~$ ssh 40.118.000.000(endereço publico)

* Deletar o grupo de recursos
> User@Azure:~$ az group delete --resource labazcli


