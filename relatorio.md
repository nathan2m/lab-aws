**_(ATENÇÃO! O conteúdo deste relatório é de INFORMAÇÕES FICTÍCIAS.)_**

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data**: 18/04/2024

**Empresa**: Abstergo Industries 

**Responsável**: Nathan

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Nathan**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

#### Etapa 1: 
- [_Amazon CloudFront_](https://aws.amazon.com/pt/cloudfront/)
- O foco desta ferramenta é garantir a entrega rápida do conteúdo de uma página web para um usuário localizado em qualquer parte do mundo.
- Um exemplo de uso dessa ferramenta é a garantia da rapidez de acesso a uma mesma página web por usuários de localizações geográficas distantes um do outro. Isso acontece pois esse conteúdo da página web é armazenado em cache em diferentes servidores interligados espalhados pelo mundo. Assim o usuário de cada localização acessa a versão em cache da respectiva página web do servidor mais próximo dele geograficamente.

#### Etapa 2: 
- [_Amazon EC2 Auto Scaling_](https://aws.amazon.com/pt/ec2/autoscaling/)
- Seu foco é manter a disponibilidade constante de uma aplicação ao permitir a adição ou remoção dinâmica de instâncias de recursos de hardware que mantêm o funcionamento da aplicação. Isso para alcançar um equilíbrio entre disponibilidade constante do serviço e evitar a ociosidade de recursos de hardware minimizando assim os custos de sua manutenção.
- Um exemplo de uso dessa ferramenta é quando uma apliação tem tendência de alto acesso durante os dias úteis e de baixo acesso durante os finais de semana. Para então garantir a disponibilidade constante dessa aplicação e evitar a alocação ociosa de recursos de hardware, é então que essa ferramenta busca alocar mais recursos de hardware conforme o aumento do número de acessos e desaloca os recursos ociosos quando há um menor número de acessos a essa aplicação.

#### Etapa 3: 
- [_Amazon S3 - Intelligent-Tiering_](https://aws.amazon.com/pt/s3/storage-classes/intelligent-tiering/)
- Tem como foco a economia automática de custos de armazenamento de dados quando os padrões de acesso a estes dados são alterados, sem impacto na performace ou sobrecarga operacional.
- Um exemplo de uso dessa ferramenta é a alocação automática dos dados de usuários pouco acessados para níveis de acesso de custo inferior. E quando esses mesmos dados passam a ter uma maior frequência de acesso, passa então esses dados para níveis de acesso mais rápido.



## Conclusão
A implementação de ferramentas na empresa **Abstergo Industries** tem como esperado os seguintes benefícios: **a garantia da rapidez de acesso ao site da empresa por usuários localizados em qualquer parte do mundo; a economia de recursos alocados equilibrada com a disponibilidade constante do site da empresa; e a economia com os custos dos dados armazenados dos usuários conforme o uso destes.** O que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


### Assinatura do Responsável pelo Projeto:

Nathan