# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 13/10/2024
Empresa: Abstergo Industries 
Responsável: Julia Martílio

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Julia Martílio. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon EC2
- Permite criar e gerenciar máquinas virtuais de maneira escalável e flexível.
- O EC2 pode ser utilizado para executar servidores virtuais que hospedam aplicações internas da empresa, como sistemas de gestão de inventário e registros de pacientes. Usando instâncias sob demanda, reservadas ou spot, a empresa pode ajustar a capacidade computacional conforme necessário, reduzindo custos com infraestrutura física e pagando apenas pelos recursos que utilizar. Irá gerar uma redução significativa de custos com montagem e manutenção de servidores ou data centers físicos.

Etapa 2: 
- Amazon S3
- Armazenamento de dados não estruturados e backups com baixo custo.
- O S3 pode ser utilizado para armazenar grandes volumes de documentos, como relatórios médicos, dados históricos de vendas, ou imagens de exames médicos, que não precisam de acesso frequente, mas devem ser arquivados de forma segura. O S3 também é ideal para armazenar backups de bancos de dados e arquivos de grande volume, utilizando classes de armazenamento como o S3 Glacier Instant Retrieval para arquivos que precisam ser mantidos a longo prazo e são raramente acessados, mas que exigem recuperação rápida.

Etapa 3: 
- Amazon RDS
- Gerenciamento automatizado de bancos de dados relacionais.
- O RDS pode ser usado para gerenciar o banco de dados da empresa, como o registro de transações e inventário de medicamentos. O RDS é compatível com diversos mecanismos de banco de dados, como MySQL, Oracle, MariaDB entre outros. Ao usar o RDS, a empresa pode se beneficiar de patches automatizados, gerenciamento de backup facilitado, atualizações e escalabilidade sem precisar se preocupar com a manutenção do hardware físico. Isso reduz custos operacionais e minimiza o risco de erros humanos, além de otimizar a performance e a segurança dos bancos de dados críticos para o negócio.



## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado redução de custos com hardware físico, flexibilidade e escalabilidade de servidores virtuais conforme necessidade, armazenamento de baixo custo para grandes volumes de dados e gerenciamento automatizado de bancos de dados*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[Amazon EC2](https://aws.amazon.com/pt/ec2/?did=ft_card&trk=ft_card)

[Documentação Amazon EC2](https://docs.aws.amazon.com/ec2/?icmpid=docs_homepage_featuredsvcs)

[Amazon S3](https://aws.amazon.com/pt/s3/?did=ft_card&trk=ft_card)

[Documentação Amazon S3](https://docs.aws.amazon.com/s3/?icmpid=docs_homepage_featuredsvcs)

[Amazon RDS](https://aws.amazon.com/rds/?did=ft_card&trk=ft_card)

[Documentação Amazon RDS](https://docs.aws.amazon.com/rds/?icmpid=docs_homepage_featuredsvcs)



Assinatura do Responsável pelo Projeto:

Julia Martílio
