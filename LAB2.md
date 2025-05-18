
# Benefícios da nuvem

- ## Alta disponibilidade:

O sistema sempre fica disponivel a todo momento, no contrato é implementado o SLA, explicando que o sistema pode fiar indisponível por algum tempo.

As opções incluem, por exemplo: 99% do tempo, 99.90% e 99.95%. Todos sinalizando a porcentagem do tempo que o serviço estaria disponível por contrato. Caso aconteça do serviço ficar indisponível por mais tempo do que o estipulado no contrato, será ressarcido o valor proporcional ao tempo.

- ## Escalabilidade 

A escalabilidade se refere à capacidade do servidor de ajustar os recursos para atender à demanda, os serviços em nuvem oferecem esse serviço, por um valor adicional (Caso a capacidade ultrapasse à estipulada no contrato).

- ## Elasticidade

Caso seja experienciado um salto repentino no uso de recursos, ou sua necessidade, a nuvem oferece uma expansão temporária para suprir a demanda. Também é oferecido uma redução nos recurso, quando ocorre uma queda na demanda.

- ## Confiabilidade

Devido ao design decentralizado, é possível acessar os recursos de vários lugares, e também no caso de erros, é possível recuperar o serviço instantaneamente ou em pouquíssimo tempo.

- ## Previsibilidade

Também, a nuvem oferece a Previsibilidade, no caso de problemas, a Azure oferece uma previsão de conserto e previsão dos ajustes e indisponibilidade

- ## Segurança 

As políticas e atualizações de segurança são aplicadas automaticamente. Isso melhora a segurança em ambientes cloud. (Lembrando que a segurança é responsabilidade do contratante e não do provedor.)

- ## Governança 

A auditoria em nuvem ajuda a sinalizar qualquer recurso que esteja fora da conformidade, e oferece ferramentas de mitigação desses problemas. 

- ## Gerenciabilidade

Um dos principais benefícios da computação em nuvem. Os serviços oferecem milhares de recursos para fazer esse gerenciamento de várias formas diferentes.



# Criação de máquinas virtuais no Azure

## Áreas de disponibilidade

A Azure oferece zonas específicas para disponibilizar seus serviços, sendo configurado na hora da criação da máquina. Quanto maior o número de zonas, mais caro será a implementação, e maior será a necessidade de recursos. 

## Opções de redundância

A Azure também oferece serviços de redundância no caso de falha em 4 tipos. A cópia local, usada para serviços não críticos. A cópia em outra zona geográfica, feita geralmente para 
backups. A cópia com redundância de zona, feita para caso ocorra falhas no datacenter, visando agilizar o reestabelecimento do serviço. E por fim, o serviço com cópia em redundância de zona geográfica, feita para ser a solução mais rápida e segura, consequentemente sendo a mais cara. 

## Conclusão

A Azure oferece vários serviços para segurança e disponibilidade, mas é necessário se atentar ao SLA disponível e aos preços, que podem escalar rapidamente. 

