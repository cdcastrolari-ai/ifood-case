# Case Técnico Data Science - iFood

## 1. Introdução

Este repositório contém a solução (parcial) desenvolvida para o **case técnico de Data Science do iFood**, cujo objetivo é analisar dados de clientes, ofertas e transações. Além disso, desenvolver um modelo que propõe uma estratégia mais eficiente de distribuição de cupons e ofertas para cada cliente.

Os tratamentos das bases de dados, **offers, profile e transactions**, foram realizados na versão gratuita da plataforma Databricks, utilizando Python e PySpark. A partir destes, foi construído o dataset final **customer_engagement**.
A análise tem com foco no **perfil dos clientes** e **avaliação da efetividade das ofertas**.

A etapa de modelagem está **pendente** nessa versão, trazendo impacto para a entrega do case técnico e apenas uma solução parcial para o desafio proposto.


## 2. Principais Insights
*(To do)*

## 3. Orientações para execução do projeto

Este projeto foi desenvolvido para ser executado **no Databricks**, utilizando PySpark e recursos nativos da plataforma.

### Executando no Databricks via GitHub

Para reproduzir a análise, siga os passos abaixo utilizando uma **conta do Databricks**.

---

### 1. Clonar o repositório no Databricks

1. No menu lateral do Databricks, acesse **Workspace > Repos**
2. Clique em **Create Git Folder**
3. Informe a URL do repositório: https://github.com/cdcastrolari-ai/ifood-case.git
4. Clique em **Create Git Folder**
O Databricks irá clonar automaticamente o projeto para o seu workspace.

---

### 2. Executar o notebook de setup do ambiente

Após o repositório ser importado:

1. Navegue até o diretório: **notebooks/**

2. Abra o notebook: **0_setup.ipynb**

3. Execute todas as células do notebook clicando em **Run all**

Este notebook é responsável por:
- Criar **schemas** necessários para a execução do projeto
- Criar e configurar **volumes** utilizados para armazenamento dos dados

---

### 3. Executar o processamento de dados

Após a conclusão do setup:

1. Ainda no diretório `notebooks/`, abra o notebook: **1_data_processing.ipynb**

2. Execute todas as células do notebook clicando em **Run all**

Este notebook realiza:
- Leitura e processamento dos dados
- Transformações e consolidação das informações
- Geração de **tabelas** intermediárias
- Criação de **gráficos e visualizações** ao longo do processamento, que auxiliam na análise exploratória dos dados

Os resultados gerados neste notebook servem de base para as análises e insights apresentados neste case.

> Os dados para a realização do case também podem ser acessados através desse link: https://data-architect-test-source.s3.sa-east-1.amazonaws.com/ds-technical-evaluation-data.tar.gz

## 4. Apresentação dos Resultados

*(To do)*

📊 **Link para os slides:**

https://docs.google.com/presentation/d/1q9RHkP0nIF8g3MHG9zAH4fkQGFys1bFIklHxa9HuTqI/edit?usp=sharing


