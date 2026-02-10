RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 10 de fevereiro de 2026

Empresa: Abstergo Industries

Responsável: Iandra

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Iandra. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos e otimizar a infraestrutura da plataforma farmacêutica.

Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

Nome da ferramenta: Amazon S3 com Intelligent-Tiering.

Foco da ferramenta: Armazenamento de objetos de baixo custo.

Descrição de caso de uso: Armazenamento de imagens de produtos e receitas médicas enviadas pelos clientes. O uso do Intelligent-Tiering permite que o sistema mova automaticamente arquivos pouco acessados para camadas de custo reduzido, gerando economia imediata sem necessidade de gestão manual.

Etapa 2:

Nome da ferramenta: Amazon Aurora (Serverless v2).

Foco da ferramenta: Banco de dados relacional escalável.

Descrição de caso de uso: Gestão do inventário de medicamentos e registros de vendas. Por ser Serverless, o banco de dados ajusta sua capacidade automaticamente conforme a demanda da farmácia. Durante a madrugada ou períodos de baixo acesso, os custos são drasticamente reduzidos, pois a empresa paga apenas pelo processamento utilizado.

Etapa 3:

Nome da ferramenta: Instâncias EC2 Spot.

Foco da ferramenta: Computação com alta economia.

Descrição de caso de uso: Utilização para o processamento de logs e geração de relatórios mensais de vendas. Como essas tarefas não são críticas em tempo real e podem ser retomadas, o uso de instâncias Spot oferece até 90% de desconto em comparação às instâncias sob demanda, reduzindo o custo operacional de backend.

Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução significativa nos gastos com armazenamento e computação, além de eliminar o desperdício de recursos subutilizados em períodos de baixa demanda. Isso aumentará a eficiência e a produtividade da empresa, permitindo reinvestir a economia em novas funcionalidades para a plataforma. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Anexos
Diagrama de arquitetura da VPC.

Tabela comparativa de custos: On-Demand vs Spot.

Manual de configuração do ciclo de vida do S3.

Assinatura do Responsável pelo Projeto: Iandra
