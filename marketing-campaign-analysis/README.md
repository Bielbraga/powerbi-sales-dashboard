# 📊 Marketing Campaign Analysis — Power BI

Dashboard desenvolvido como parte dos estudos práticos da **Data Science Academy (DSA)**, utilizando o Power BI para análise de clientes, comportamento de consumo e desempenho de campanhas de marketing.

---

## 🎯 Objetivo

O projeto tem como objetivo analisar o perfil dos clientes, seus padrões de consumo e os resultados das campanhas de marketing, permitindo uma visão geral sobre:

- Perfil e características dos clientes;
- Comportamento de gasto;
- Relação entre salário anual e consumo;
- Desempenho das campanhas de marketing;
- Resultados de compra dos clientes;
- Padrões de compra por país e ponto de venda.

---

## 📊 Dashboard

O projeto é dividido em diferentes visões de análise.

### 👥 Visão Cliente

Apresenta uma visão geral do perfil dos clientes, incluindo:

- Total de clientes;
- Salário anual médio;
- Compras realizadas em lojas;
- Compras realizadas pela web;
- Compras realizadas via catálogo;
- Compras com descontos;
- Distribuição de clientes por escolaridade;
- Distribuição de clientes por estado civil;
- Análise por país.

O dashboard apresenta **1.999 clientes** e salário anual médio de aproximadamente **51,98 mil**. Também são apresentadas métricas de compras em lojas, web, catálogo e compras com descontos.

---

### 💰 Comportamento de Gasto do Cliente

Esta visão analisa os padrões de consumo dos clientes e sua relação com características socioeconômicas e familiares.

As análises incluem:

- Total de gasto × salário anual;
- Total de gasto × quantidade de filhos em casa;
- Total de gasto × quantidade de adolescentes em casa;
- Relação entre gasto, estado civil e escolaridade.

A análise permite observar como diferentes características dos clientes estão relacionadas ao comportamento de consumo.

---

### 📈 Performance das Campanhas de Marketing

Esta seção apresenta os resultados das campanhas de marketing.

Entre as análises estão:

- Efetividade das campanhas;
- Clientes que compraram e não compraram;
- Resultado das campanhas de marketing;
- Média de salário anual por resultado da campanha;
- Efetividade da campanha × quantidade de filhos;
- Relação entre resultado da campanha, estado civil e escolaridade.

Na visualização apresentada, aproximadamente **83,99%** dos clientes não realizaram uma compra, enquanto **16,01%** realizaram uma compra.

---

### 🌎 Padrões de Compras por Ponto de Venda

A última visão analisa os padrões de consumo considerando diferentes países e períodos.

São apresentadas análises de:

- Total gasto em diferentes categorias por país;
- Total gasto por ano e país;
- Comparação entre países;
- Evolução dos gastos entre 2018 e 2023.

Os países analisados incluem Estados Unidos, Espanha, Chile, Brasil, Argentina, Portugal e Alemanha.

---

## 🛠️ Ferramentas

- **Power BI**
- **CSV**

---

## 📁 Estrutura do Projeto

```text
marketing-campaign-analysis/
│
├── README.md
│
├── dashboard.pbix
│
├── datasets/
│   └── dados_marketing.csv
│
└── images/
    └── dashboard.pdf
