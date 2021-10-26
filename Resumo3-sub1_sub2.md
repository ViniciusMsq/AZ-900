# [Certificação AZ-900](https://docs.microsoft.com/pt-br/learn/certifications/exams/az-900)- Azure Fundamentals </a>
---------------------------------------------------


### Serviços de Storage

# Blob
* Arquivos de log, arquivos de texto, imagem, que podemos guardar dentro de um container, feito para otimizar grande armazenamento de arquivos não estruturados

# Disk
* Utilizamos ele na VM quando criamos indexamos a ela um disco virtual, podemos anexar varios outros discos, tipos de disco: ultra disk, premium ssd, standart ssd, hdd

# File
* Serviço de file share, servidor de compartilhamento, onde nossos outros serviços conseguem obter esses arquivos, suporte a protocolos SMB e NFS

# Archive
* Classe de armazenamento, para armezenar em longo periodo

### Storage account

* Dentro da conta de storage, vai ficar os containers de compartilhamento arquivamento, o disco funciona um pouco separado, é possivel ter varias contas de storage

### reduncia regional storage
* caso caia uma região primaria você tem um backup em outra regiao

### Tiers de acesso

* Hot: Dados com frequentes acessos

* Cool: Acesso infrequente, arquivos com 30 dias

* Archive: depois de 180 dias, temos uma latencia maior para acessar