# Case Técnico – Data Scientist | iFood

## 1. Introdução

Este repositório contém a solução desenvolvida para o **case técnico de Data Science do iFood**, cujo objetivo é analisar dados de clientes, ofertas e transações para propor uma estratégia mais eficiente de distribuição de cupons e ofertas.

A análise foi conduzida com foco em **entendimento do comportamento dos clientes**, **avaliação da efetividade das ofertas** e **geração de insights acionáveis para o negócio**, utilizando Python e PySpark em ambiente Databricks.

Todo o processo, desde o tratamento dos dados até a extração de insights e apresentação dos resultados, foi estruturado para simular um cenário real de tomada de decisão orientada a dados.

---

## 2. Principais Insights da Análise

A partir da análise exploratória e das modelagens realizadas, foi possível extrair os seguintes insights:

- **Perfis distintos de clientes respondem de maneira diferente aos tipos de oferta**, indicando a importância de uma estratégia personalizada em vez de disparos genéricos.
- **Ofertas do tipo desconto apresentam maior taxa de conversão quando alinhadas ao histórico de consumo do cliente**, especialmente em clientes recorrentes.
- **Clientes com maior tempo de relacionamento com a plataforma tendem a responder melhor a ofertas direcionadas**, enquanto novos usuários se beneficiam mais de incentivos iniciais.
- **O canal de comunicação influencia diretamente o engajamento**, reforçando a necessidade de escolher o canal adequado para cada perfil.
- A segmentação baseada em comportamento e histórico tem potencial para **aumentar a eficiência das campanhas e reduzir custos com cupons pouco efetivos**.

Esses insights serviram como base para a proposta de estratégia apresentada nos slides finais.

---

## 3. Como Rodar o Projeto

Existem duas formas de executar este projeto e reproduzir a análise:

### Opção 1 – Executar diretamente pelo Databricks (Recomendado)

A maneira mais simples é acessar o projeto diretamente pelo ambiente Databricks:

🔗 **Link do Databricks:**  
https://databricks.meuprojeto.com.br/etc

Neste ambiente é possível:
- Executar os notebooks de processamento e análise
- Visualizar os resultados e gráficos
- Reproduzir todo o fluxo sem necessidade de configuração local

---

### Opção 2 – Rodar localmente (Jupyter / Notebook Python)

Caso prefira rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git

2. Crie um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
4. Execute os notebooks localizados na pasta **notebooks/**, respeitando a ordem:
   - 1_data_processing.ipynb
   - 2_analysis_and_modeling.ipynb

> Observação: Os arquivos de dados não estão versionados neste repositório. Para executar a análise completa, é necessário obter os dados conforme as instruções do case técnico.

## 4. Apresentação dos Resultados

Os principais resultados, insights e a proposta de estratégia de negócio estão consolidados em uma apresentação voltada para stakeholders não técnicos.

📊 **Link para os slides:**
https://link-para-sua-apresentacao.com


