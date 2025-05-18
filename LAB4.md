# Componentes de arquitetura do Azure

## Regiões 

Os preços flutuam baseados no local do servidor. Serviços também podem ser limitados por região.

É muito importante prestar atenção em qual região você colocará as suas máquinas e infraestrutura. Baseados em localização, preços e disponibilidade.

Cada região é composta por um ou mais datacenters muito próximos, quanto mais datacenters, maior a disponibilidade dos serviços. 
As vezes pode ocorrer uma falha de região, é necessário se atentar a isso, pois caso seu servidor esteja em só 1 região, essa falha deixará o seu serviço completamente indisponível. As vezes é necessário colocar sua infraestrutura em mais de uma região, para evitar esse problema.

### Pares de Regiões

Cada região tem uma região par. Geralmente separa por 300 milhas, visando melhorar a disponibilidade no caso de uma falha de região. Lembrando que isso só estaria disponível para serviços usando a redundância por zonas.

### Regiões soberanas

São regiões somente usadas para usos militares, ou por agências dos EUA. Somente disponíveis para o governo, e não está disponível para usuários normais.

Também há uma região soberana na China, administrada pela 21ViaNet. É limitada para se conformar com as leis locais, por exemplo, todos os dados ficam somente dentro do território chinês.

###


## Recursos Azure


### Grupos de Recursos

Armazena todos os recursos, todos os recurso devem pertencer a um grupo, usado para o gerenciamento dos recursos. 

- Cada recurso pode existir em apenas um grupo. 
- Cada recurso pode existir em várias regiões.
- Um aplicativo pode usar vários grupos de recursos.



## Assinaturas Azure

Uma conta pode ter diversas Assinaturas, mas uma assinatura pode ter somente uma conta.

As assinaturas são: assinatura de desenvolvimento, de teste e de produção.

### Limite de cobrança

É possível gerar relatórios de cobrança e faturas, todos separados para cada assinatura. (É possível também separar as cobranças por projeto, afim de ajudar no gerencimento de custos).

### Limites de controle de acesso

É possível também, limitar o acesso de certas assinaturas, para manter as coisas seguras e organizadas.


## Grupos de gerenciamento

Grupos de gerenciamento podem ter várias assinaturas do Azure e essas assinaturas herdam as condições aplicadas ao grupo de gerenciamento.

## Infraestrutura global da Azure

- A região do Brasil oferece duas regiões, a South e SouthEast.

- A SouthEast é só usada mediante contrato e no cenário de tragédias dentro do País.

- O site da Azure oferece uma imagem do globo com todos os servidores, e até tours virtuais nos datacenter.
