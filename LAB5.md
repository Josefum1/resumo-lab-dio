# Computação e rede na azure

É um serviço Sob demanda que fornece serviços de computação, como discos, processamento, memória, rede e sistemas operacionais. 

É possível criar máquinas virtuais com emulações de software de computadores físicos.

## Conjuntos de disponibilidade de VM

- É dividido em RAcks, chamados de domínios de falha. Geralmente é recomendado a divisão das VMs em pelo menos 3 domínios de falha, para manter os serviços altamente disponíveis. 


## Criação de VMs Azure

É possível criar VMs com configurações pré definidas, otimizadas para memória ou computação, e com Sistemas operacionais específicos.

Os exemplos são:

- LAMP Stack (Linux, Apache, MySQL e PHP) usando a arquiterua Azure.

- Scalable WordPress

- VM Starter Kit Linux

Cada opção tem configurações de DEV/Prod, produção em pequena escala e produção full, aumentando em preço para cada opção.

É possível escolher a zona, as opções de redundância de infraestrutura.
Também há opções de escala, escolhendo as escalas e versões de VM.

As Condições de dimensionamento são altamente customizáveis, e é importante saber o que é necessário para diminuir os custos.

Pode ser escolhido o tamanho da máquina (processamento e RAM).

Você pode escolher o Spot da Azure, com um grande desconto mas com nenhuma confiabilidade.


Existem várias séries, mudando baseado nos níveis de processamento e uso de CPU e RAM. Também variando em valores.


Depois é necessário escolher o tamanho e tipo de disco (HD ou SSD).

Por fim é possível determinar o funcionamento, opções de exclusão e desligamento automático.
