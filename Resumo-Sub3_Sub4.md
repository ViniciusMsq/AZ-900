# [Certificação AZ-900](https://docs.microsoft.com/pt-br/learn/certifications/exams/az-900)- Azure Fundamentals </a>
---------------------------------------------------
### Vatagens da computação nuvem
* Alta disponibilidade: A aplicação não fica fora do ar, podendo ter replicas entrando em ação em momentos de quebra da aplicação, garante que esteja sempre disponivel.

* Escalabilidade: É possível rapidamente expandir a capacidade computacional. usando conceito de vertical e horizontal, verticalmente é possivel aumentar: nucleos do processador, quantidade memoria ram, armazenamento, E horizontalmente, é possivel colocar maquinas trabalhando em paralelo

* Agilidade: Facilidade de fazer um deploy, com apenas alguns passos, já possível colocar uma aplicação na nuvem totalemnte disponivel

* Geo-distribuição: entra em conjunto com a alta disponibilidade, que cria um SLA do serviço bem bacana

* Desastre Recovery: Seguindo os padrões de segurança, existem diversos planos para garantia que os dados não serão perdidos, por exemplo, uma duplicidade da aplicação, sua aplicação pode funcionar em outras regiões que não tiveram problemas.

### Modelos de serviço nuvem

* > "Porque uma solução em nuvem é geralmente mais barata?" <br> é mais barata quando é devidamente planejada, devidamente implementada, dimensonada, não é apenas trasferir do seu local, para nuvem, existem diversos criterios para que isso seja uma verdade.

* Principio de pay-as-you-go: Pague para o uso, você paga apenas pelo que usa, precisou de mais, paga por isso, não precisa mais, custo é reduzido, isso permite que possa ir alocando seu projeto conforme a necessidade, já que advinhar a capacidade necesaria de um servidor sai caro, na nuvem você tem essa dinamica de poder ir aumentando ou diminuindo os recursos com o tempo.

* > Modelos de serviço: <br> * IaaS: Infraestrutura como serviço, nesse modelo não precisa se preocupar com o hardware, ele é mantido pelo meu provedor, eu tomo conta do sistema operacional, aplicações de patch, são responsabilidade minhas <br> * PaaS: Plataforma como serviço, diferença do anterior, é que nesse nivel, tambem não é responsabilidade nossa manter o sistema ou softwares em dia e funcionando, ex: software do banco. <br> * SaaS: Serviço: esse é o nivel mais avançado, voce usa tudo como serviço, você apenas alimenta o sistema com dados e rescursos, e usufrui de tudo.

### Tipos de Nuvem
* > On premises: Tudo local
* > Hybrid Cloud: Parte Local, parte no provedor
* > Public Cloud: provedor, onde varias pessoas usam
*  O ideal é ir se migrando as coisas aos poucos, principalmente se está começando com a nuvem, partindo de tudo localmente na sua maquina, evoluindo para virtualização, subindo alguns serviços, e depois avançando para migração total.

### Serviços AWS para Azure
* > [Compração categorizada entre serviços da AWS e AZURE](https://docs.microsoft.com/pt-br/azure/architecture/aws-professional/services)

### Infraestrutura Global Azure

* Definida por dois componentes: a parte fisica e a conectividade via componentes de rede,, +160 data centers distribuidos em regiões, existem varias aréas de operações da azure ao redor do mundo.

* Terminologia: Geografia > Regioes > zonas de disponibilidade. [Ver mais...](https://azure.microsoft.com/en-us/global-infrastructure/geographies/)

* Regioes/Zonas de Disponibilidade: são data center fisicamente separados dentro de uma região da azure, cada zona, é composta por uma ou mais data centers, equipados com energia, refrigeração, e redes idependentes. Uma zona de disponibilidade é configurada para ter um limite de isolamento, se uma zona cair a outra continua funcionando. A no minimo três zonas por região.

* Pares de regiões da azure:  assim como uma região é formada por varias zonas de disponibilidades, uma geografia é formada por varias regiões, regiões estão conectadas pela mesma geografia, e são separas por 300 milhas, a alta distancia é para evitar problemas de desastres naturais, falhou a região a outra assume.

### Azure Marketplace

* Recursos prontos para ti montar e configurar vários cenarios para suas aplicações.
 

### Preços da Azure

* Simulando custos operacionais com a azure em determinados cenarios  [Preços](https://azure.microsoft.com/en-us/pricing/)

* Preço por produto: detalha valores de cada tipo de recurso

* Calculadora de preço: ti mostra custo, da configuração desejada, cada detalhe da configuração, interfere diretamente no valor

* Calculadora TCO: Faz um comparativo entre o custo on promises e rodar tudo isso na nuvem. relatório detalhado considerando varios custos que você teria localmente.