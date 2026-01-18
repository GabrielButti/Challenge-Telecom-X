# 📊 Telecom X – Análise de Evasão de Clientes (Churn)

## 📌 Visão Geral
Este projeto tem como objetivo analisar a evasão de clientes (churn) da empresa fictícia **Telecom X**, identificando padrões e fatores que influenciam o cancelamento dos serviços.  

A partir da análise exploratória dos dados (EDA), o projeto busca gerar **insights estratégicos** que auxiliem na tomada de decisão e sirvam de base para modelos preditivos de churn.

---

## 🎯 Objetivos do Projeto
- Entender o perfil dos clientes que cancelam o serviço
- Identificar variáveis associadas à evasão
- Preparar os dados para análises estatísticas e modelos de Machine Learning
- Gerar insights acionáveis para retenção de clientes

---

## 🧠 Etapas do Projeto

1. **Extração de Dados**
   - Consumo de dados via API em formato JSON (GitHub)
   - Leitura direta com Pandas

2. **Tratamento e Limpeza**
   - Normalização de dados aninhados
   - Tratamento de valores ausentes
   - Correção de inconsistências
   - Remoção de duplicatas
   - Padronização de categorias

3. **Engenharia de Variáveis**
   - Criação da variável `Contas_Diarias`
   - Conversão de variáveis binárias (Sim/Não → 1/0)
   - Renomeação de colunas para maior clareza

4. **Análise Exploratória de Dados (EDA)**
   - Análise descritiva
   - Distribuição da variável alvo (Churn)
   - Comparação de variáveis numéricas por churn
   - Análise de churn por variáveis categóricas
   - Visualizações estratégicas

5. **Geração de Insights**
   - Identificação de fatores críticos de evasão
   - Base preparada para modelagem preditiva

---

## 📊 Principais Insights Encontrados

- Clientes com **contrato mensal** apresentam maior taxa de churn
- A evasão ocorre majoritariamente nos **primeiros meses de contrato**
- Clientes com **cobrança mensal e custo diário mais elevados** tendem a cancelar mais
- A ausência de **suporte técnico** está fortemente associada à evasão
- Métodos de pagamento não automáticos apresentam maior churn

---

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

