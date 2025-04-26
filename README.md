# Trabalho de Análise - Fazenda Urbana

## Codigo do projeto [aqui](https://github.com/AlexandreDSantos01/Pim-4)

Este repositório contém o trabalho realizado para o curso de **Análise e Desenvolvimento de Sistemas (ADS)**, onde foi realizada a análise e modelagem de um sistema para **uma fazenda urbana**. O objetivo deste projeto foi mapear e criar um modelo de software para gerenciar as operações de uma fazenda urbana, utilizando boas práticas de análise de sistemas, como diagramas, definição de regras de negócios e a normalização do banco de dados até a sexta forma normal.

### Metodologia Scrum

Durante o desenvolvimento deste projeto, utilizamos a metodologia **Scrum** para gerenciar as atividades e a evolução do trabalho. O Scrum foi adotado para organizar o trabalho em ciclos curtos e entregáveis chamados **sprints**, com reuniões diárias para acompanhamento das atividades e gestão do progresso. Essa abordagem ajudou a manter o foco nas entregas e facilitar a comunicação dentro da equipe.

## Objetivo do Projeto

O objetivo deste trabalho foi estudar e estruturar as necessidades de um sistema para uma fazenda urbana. A fazenda urbana tem como propósito o cultivo sustentável de alimentos em áreas urbanas, aproveitando espaços como telhados, paredes e terrenos abandonados. O sistema que foi analisado irá permitir o gerenciamento das atividades agrícolas, controle de produção, relacionamento com fornecedores e clientes, além da gestão de recursos como insumos e equipamentos.

## Funcionalidades Analisadas

As funcionalidades do sistema que foram modeladas durante a fase de análise incluem:

1. **Gestão de Cultivos (CRUD)**: Controle de plantios, monitoramento de ciclos de cultivo e acompanhamento de produção.
2. **Gestão de Insumos**: Controle de insumos agrícolas como sementes, fertilizantes e outros materiais.
3. **Gestão de Fornecedores**: Cadastro e gestão dos fornecedores de insumos e materiais.
4. **Gestão de Funcionários (CRUD)**: Controle dos dados dos funcionários, como registros de entradas, saídas, funções e pagamentos.
5. **Gestão de Clientes**: Controle dos clientes, com foco em vendas diretas de produtos da fazenda.
6. **Gestão Financeira**: Acompanhamento de custos, receitas e relatórios financeiros da fazenda.

## Diagramas Desenvolvidos

Durante a fase de análise, foram criados os seguintes diagramas para modelar o sistema de maneira eficiente:

1. **Diagrama de Caso de Uso**:
   - O diagrama de caso de uso foi desenvolvido para identificar as principais funcionalidades que os usuários do sistema iriam interagir, como cadastrar fornecedores, registrar vendas, acompanhar o estoque de insumos, entre outros.

2. **Diagrama de Classes**:
   - O diagrama de classes foi utilizado para representar a estrutura de dados do sistema. Ele detalha as classes, atributos e métodos necessários para realizar a gestão dos dados da fazenda urbana.

3. **Diagrama de Atividades**:
   - O diagrama de atividades descreve os fluxos de trabalho dentro do sistema, como o processo de compra de insumos, o ciclo de cultivo, e o processo de venda de produtos da fazenda.

4. **Diagrama Entidade-Relacionamento (ER)**:
   - O diagrama ER foi criado para definir as entidades principais e os relacionamentos entre elas, como os produtos, fornecedores, clientes e transações financeiras.

5. **Diagrama de Sequência**:
   - Este diagrama foi utilizado para ilustrar a sequência de operações no sistema, como o processo de cadastro de um fornecedor e a venda de produtos.

## Regras de Negócio

O sistema da fazenda urbana segue as seguintes regras de negócio:

1. **Cadastro de Cultivos**: Apenas um cultivo por área disponível. Quando a área for plantada, o sistema gerencia automaticamente o ciclo de cultivo até a colheita.
   
2. **Gestão de Insumos**: O sistema deve alertar o usuário quando o estoque de insumos estiver abaixo do nível mínimo e permitir a compra de novos insumos de acordo com o histórico de consumo.
   
3. **Gestão de Funcionários**: O sistema realiza o controle do ponto de funcionários, além de registrar dados importantes, como funções, pagamentos e movimentações de cada colaborador.

4. **Relatório Financeiro**: O sistema gera relatórios mensais de receitas e despesas, com base nas vendas realizadas e custos com insumos, mão de obra e outros recursos.

5. **Gestão de Fornecedores e Clientes**: Para cada fornecedor, o sistema gerencia um histórico de compras, e para cada cliente, ele mantém um histórico de vendas realizadas, possibilitando o envio de ofertas personalizadas.

6. **Vendas**: As vendas podem ser feitas diretamente para o cliente final ou por meio de revendedores, e o sistema deve controlar o estoque disponível após cada venda.

## Tecnologia Utilizada

O sistema foi desenvolvido utilizando as seguintes tecnologias:

- **Linguagem de Programação**: O sistema foi desenvolvido em **C#** utilizando o framework **ASP.NET Core MVC**.
- **Banco de Dados**: Utilizamos **SQL Server** para o armazenamento de dados, aplicando a normalização do banco de dados até a **sexta forma normal (6NF)** para garantir a eficiência e consistência dos dados.
- **API**: Foi desenvolvida uma **API RESTful** para a integração com a versão mobile do sistema, utilizando **ASP.NET Core Web API**.
- **Ferramentas de Modelagem**: Utilizamos ferramentas como **Astah** para criar os diagramas.

## Tipos de Plataforma

Este sistema foi desenvolvido nas versões:

1. **Versão Web**: Para facilitar o acesso e gerenciamento do sistema via navegador.
2. **Versão Mobile**: Aplicativo para dispositivos móveis que permite o acesso e controle das operações de qualquer lugar.
3. **Versão Desktop**: Aplicativo para computador, utilizando uma interface gráfica completa, mais robusta para uso em ambiente de escritório.

## Mais Projetos

Veja mais projetos desenvolvidos em meu portfólio [aqui](https://alexandredsantos01.github.io/MeuPortfolio/).
