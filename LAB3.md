# Tipos de  serviços CLOUD

## IaaS 

Infraestrutura como serviço: Oferece os servidores e armazenamento, firewalls e segurança. 

Oferece muito mais envolvimento do cliente já que o cliente só contrata a Infraestrutura, todo o resto sendo responsabilidade dele 


## PaaS

Plataforma como serviço: Inclui a Infraestrutura e agora também adiciona o database na nuvem, o gerenciamento fica como responsabilidade do provedor. Somente sobra a aplicação


## SaaS

Software como serviço: Inclui todo o processo. Os aplicativos também são hospedados e oferecidos pela nuvem, tirando tudo das mãos do contratatado e deixando nas mãos do provedor.

Tudo é determinado pela licença paga pelo cliente. 

Exemplos: Aplicativos oferecidos pelo Office 365 (Teams, word, excel, etc).


# Modelo de responsabilidade compartilhada

## IaaS

O IaaS tira a parte física da responsabilidade do cliente, deixando coisas como o sistema operacional, serviços e aplicativos na mão dele.


## PaaS 

Já o PaaS tira o sistema operacional e divide a responsabilidade dos aplicativos, controles de rede e afins com o cliente. O cliente determina as regras e a Plataforma impõe elas. 

## SaaS

Por fim, o SaaS remove todas as responsabilidades, deixando o apenas a Infraestrutura de identidade e as contas, dispositivos e informações como responsabilidades do cliente. Com isso, quase todas as responsabilidades ficam nas mãos do provedor da nuvem e do serviço.



# Configurando uma instância de banco de dados na Azure

Existem muitas opções possíveis para a criação e personalização das opções. 

Para a criação ele primeiramente pergunta o nome do DB, depois a região que ficará o servidor (O preço flutua basead na localidade, geralmente com os EUA sendo o local mais barato). Depois é necessário informar configurações da rede e segurança, como será feito o acesso e sua disponibilidade. A segurança oferece criptografia e a possibilidade de usar diferentes tipos de armazenamento da sua senha. 

Por fim é informado o valor por segundo e mensal, sendo possível mudar as configurações para diminuir esse valor. 
