# 📊 Dashboard Gerencial de Produtos – Metabase

Este repositório apresenta uma **análise de dados desenvolvida no Metabase**, utilizando o ambiente disponibilizado pela  **Escola DNC**. O projeto tem como objetivo fornecer uma visão gerencial sobre **produtos, pedidos, avaliações e clientes**, consolidando indicadores estratégicos em um dashboard interativo.

---

## 🧠 Contexto do Projeto

- **Ferramenta de BI:** Metabase  
- **Ambiente de Dados:** https://dex.dnc.group/browse  
- **Integração de Dados:** Realizada diretamente no Metabase, por meio do **editor visual de relacionamentos** 
- **Objetivo:** Explorar, integrar e analisar múltiplas tabelas para gerar insights de negócio de forma visual e acessível  

---

## 🗂️ Conjunto de Dados Utilizados

Foram analisadas e integradas as seguintes tabelas:

- **Products** – Informações cadastrais dos produtos (categoria, preço, etc.)  
- **Reviews** – Avaliações e ratings dos produtos  
- **Orders** – Dados de pedidos, faturamento e volume de vendas  
- **People** – Informações demográficas e geográficas dos clientes  

As tabelas foram relacionadas no Metabase por meio de chaves comuns (ex.: `products_id`, `orders_id`, `people_id`), utilizando exclusivamente a interface visual da ferramenta.

---

## 🔗 Modelagem e Integração dos Dados

- A modelagem foi feita **sem código**, utilizando o recurso de **Relationships** do Metabase  
- As tabelas foram conectadas para permitir análises cruzadas, como:  
  - Produtos × Avaliações  
  - Produtos × Pedidos  
  - Clientes × Pedidos  

Essa abordagem demonstra domínio de **modelagem conceitual** e **data storytelling**, mesmo sem SQL.

---

## 📈 Métricas e Indicadores Analisados

### 🔹 Indicadores Gerais
- Faturamento Bruto Total  
- Preço Médio dos Produtos  
- Quantidade Total de Avaliações  
- Média Geral de Avaliação  

### 🔹 Análises por Categoria de Produto
- Média de preço por categoria  
- Quantidade de produtos por categoria  
- Média de avaliação por categoria  
- Quantidade de produtos avaliados por categoria  

### 🔹 Análises Temporais e Geográficas
- Proporção de pedidos por categoria ao longo dos meses  
- Quantidade de pedidos por estado  

---

## 🖥️ Dashboard

![Dashboard Gerencial de Produtos](./Dash%20Gerencial.gif)

O dashboard foi construído com foco em **clareza visual**, **tomada de decisão** e **análise exploratória**, utilizando gráficos de barras, donut charts e indicadores de destaque.

---

## 🎯 Principais Insights

- As categorias apresentam **preços médios semelhantes**, com leve destaque para *Widget*  
- A média de avaliações gira em torno de **3.5**, indicando oportunidade de melhoria na experiência do produto  
- Algumas categorias concentram maior volume de avaliações, sugerindo maior engajamento dos clientes  
- O faturamento total demonstra forte potencial de escala do portfólio de produtos  

---

## 🚀 Aprendizados e Competências Demonstradas

- Análise de dados aplicada a negócio  
- Modelagem de dados sem SQL  
- Uso avançado do Metabase (relacionamentos, métricas e dashboards)  
- Visualização de dados orientada a insights  
- Comunicação clara de resultados  

---

## 📌 Observações Finais

Este projeto foi desenvolvido com fins educacionais, utilizando dados disponibilizados pela **DNC**. Ele demonstra a capacidade de transformar dados brutos em **informação estratégica**, mesmo em ambientes *low-code/no-code*.
