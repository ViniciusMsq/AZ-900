# [Certificação AZ-900](https://docs.microsoft.com/pt-br/learn/certifications/exams/az-900)- Azure Fundamentals </a>
---------------------------------------------------

# Segurança

* Defense in depth: tambem conhecida como defesa em camadas, segue uma filosofia de uma defesa militar , seu objetivo é proteger a informação, prevenindo que seja acessado por de forma não autorizada, uma estrategia, é colocar varios mecanismos que retardam o avanço indevido.

* Security azure firewall: Similar ao firewall de rede que usaria no data-center, utiliza ele como serviço, ai inves de comprar e colocar no on premise coisas como cisco, nokia, voce vai utilizar eles na azure, e ela tomara conta, também ajuda a segregar o trafego o ambiente externo, on premises e ambiente das vms

* Network Security groups: Entendivel como um firewall interno, está vinculado com o recurso, , complementa o firewall, trabalhando em formato de camadas, servindo como filtro na camada de rede ainda interno do firewall, por padrão todo tráfego originado na própria Vnet é permitido. Ou seja, as máquinas podem se comunicar entre si.

* Azure DDoS protection: Serviço para mitigar ataques DDoS, o plano basic, já utiliza a estrutura da azure mata evitar acessos indevidos, sem custo, no plano pago, tem uma amplitude maior de serviço, envolvendo relatorios e outras verificações

* Azure Security Center: Faz acompanhamentos, gera relatorios, faz acompanhamentos dos niveis de segurança, podendo trabalhar da forma hibrida

* Azure Defender: Monitoramento, direto na maquina, verificando banco de dados, container, varrendo bugs, problemas, para notificar, para medidas preventivas, quanto mais serviços verificados, maior o custo

* Azure key vault: Cofre para armazenar, chaves como ssh, certificados, feito para armazenar infomações sensiveis com segurança, onde sua aplicação pode acessar essas chaves no vault para fazer validações, serviço standard, que é digital via software, e o premium trabalha com modulo fisico para proteger sua informação.

* Azure Information protection: Serviço para classificar informação, classifica, emails documentos, para atender normas, marcando com labels, documentos sensiveis ou não, publicos ou não, pode ser integrado com o microsoft 365.

* Advanced Threat Protection: está integrado no active directory da azure, azure monitor logs e azure security center, ele monitora tentativas de logins, para alertar sobre ataques de força bruta, tentativas de invasão.

* Azure Sentinel: Segurança da informação em gerenciamento de eventos, observa a rede e co-relacionando os fatos, exemplo, alguem fez 3 tentativas de login, e está acessando determinada porta, e com isso posso automatizar repostas, como por exemplo gerar alertas, ou bloquear ip.

* Azure Dedicated Hosts: Hardware exclusivo, sem divisão de maquinas entre servidores ou clientes
