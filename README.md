# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 18/04/2024

Empresa: Abstergo Industries 

Responsável: Wesley de Andrade Santos

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Wesley de Andrade Santos. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: AWS Lambda
- Foco da ferramenta: Computação sem servidor
- Descrição de caso de uso:
  O custo de execução do Lambda para sua carga de trabalho é determinado por três fatores:
    - o número de execuções,
    - a duração e o uso de memória (combinados como gigabytes-segundos) e
    -  a transferência de dados.
      A otimização desses fatores pode reduzir significativamente os custos.
- Redução do tempo de execução: Linguagens compiladas geralmente executam o código mais rapidamente do que as linguagens interpretadas, mas podem levar mais tempo para inicializar. Portanto, escolher o tempo de execução correto pode impactar o custo.
- Frequência de invocação: Dependendo de quais eventos estão acionando as funções Lambda, existem vários controles que você pode usar para diminuir o número total de invocações. Além disso, o AWS Lambda pode melhorar a comunicação com os clientes, permitindo respostas rápidas e automatizadas a eventos específicos, como solicitações de API ou alterações em bancos de dados.
  

Etapa 2: Amazon S3
- Foco da ferramenta: Armazenamento de objetos
- Descrição de caso de uso: 
  O Amazon S3 oferece classes de armazenamento flexíveis que permitem gerenciar seus custos ajustando os níveis de acesso aos dados de acordo com os custos correspondentes.
  Automatização de economia de custos: Com o S3 Intelligent-Tiering, o Amazon S3 otimiza os custos de armazenamento para você, movendo automaticamente os dados para o nível de acesso mais econômico quando os padrões de acesso mudam. O Amazon S3 também pode melhorar a comunicação com os clientes, fornecendo um local centralizado e seguro para armazenar e recuperar dados do cliente, além de oferecer classes de armazenamento flexíveis que permitem gerenciar seus custos ajustando os níveis de acesso aos dados de acordo com os custos correspondentes.


Etapa 3: AWS Fargate 
- Foco da ferramenta: Computação para containers
- Descrição de caso de uso:
  Redução de custos através do dimensionamento correto: O dimensionamento correto das tarefas do Fargate é um passo importante para a otimização de custos. O dimensionamento correto das tarefas do Fargate pode reduzir os custos em 30-70% para tarefas de longa duração.
O AWS Fargate também pode melhorar a comunicação com os clientes, permitindo a criação de aplicativos escaláveis e seguros que respondem rapidamente às solicitações dos clientes.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a diminuição de custos imediatos, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Assinatura do Responsável pelo Projeto:

Wesley de Andrade Santos
