# Lab 2 – Dashboard de Vendas, Custo, Margem de Lucro e KPI

Este laboratório tem como objetivo analisar dados de vendas utilizando o Power BI, construindo visualizações para responder perguntas de negócio fundamentais relacionadas a lucro, custos, mercados e desempenho ao longo do tempo.

---

## 📊 Perguntas de Negócio

1. **Qual foi o total de valor de venda por modo de envio?**  
   → Criado utilizando um **gráfico de cascata (Waterfall Chart)**.

2. **Quais mercados tiveram o maior custo médio de envio?**  
   → Criado com um **Treemap**, destacando os mercados com maior custo médio.

3. **A empresa deseja manter uma média mensal de 350 no valor de venda.**  
   → Construído um **KPI (Indicador de Desempenho)**.  
   → Pergunta: *No mês de Abril/2014 a empresa ficou acima ou abaixo da meta?*  
   → Resultado: **Ficou abaixo**, com média de 246,49.

4. **Considerando que lucro = valor venda – custo envio, qual categoria apresentou o maior lucro médio?**  
   → Visual elaborado com **gráfico de rosca (Donut Chart)**.

5. **Qual foi o comportamento da margem de lucro ao longo do tempo?**  
   → Criado com um **gráfico de linha**, onde  
     margem de lucro = lucro / valor venda.

---

## 📈 Dashboard Desenvolvido

Abaixo está o dashboard criado contendo todas as respostas solicitadas no Lab 2:

*(Inserir a imagem – conforme fornecida pelo usuário)*  
![Dashboard Lab2](/portifolio_data_analitcs_and_science/Data_Science_Academy/03_Modelagem_relacionamento_e_dax/imagens/Dash.png)

---

## 🔗 Modelo de Dados

O modelo foi construído no formato estrela, utilizando a tabela **Vendas** como fato e as tabelas:

- Clientes  
- Pedidos  
- Produtos  

como tabelas de dimensão.

*(Inserir a imagem do relacionamento – conforme fornecida pelo usuário)*  
![Relacionamentos](/portifolio_data_analitcs_and_science/Data_Science_Academy/03_Modelagem_relacionamento_e_dax/imagens/relacionamento.png)



---

## ✔️ Resumo das Conclusões

- **Modo de envio com maior valor de venda:** Classe Padrão.  
- **Maior custo médio de envio por mercado:** APAC.  
- **KPI abril/2014:** abaixo da meta (350).  
- **Categoria com maior lucro médio:** Tecnologia.  
- **Margem de lucro ao longo do tempo:** comportamento crescente, apesar de oscilações.

---

## 📚 Fonte  
Dataset fornecido pela **Data Science Academy**.

---
# Lab 2 – Sales, Cost, Profit Margin and KPI Dashboard

This lab aims to analyze sales data using Power BI, building visualizations to answer key business questions related to profit, cost, markets, and performance over time.

---

## 📊 Business Questions

1. **What is the total sales value for each shipping mode?**  
   → Visualized using a **Waterfall Chart**.

2. **Which markets had the highest average shipping cost?**  
   → Displayed using a **Treemap**.

3. **The company targets a monthly average sales value of 350.**  
   → Built a **KPI Indicator** to monitor the average sales value.  
   → Question: *In April/2014, was the company above or below the target?*  
   → Result: **Below target**, with a value of 246.49.

4. **Considering profit = sales value – shipping cost, which product category had the highest average profit?**  
   → Answered with a **Donut Chart**.

5. **What was the behavior of the profit margin over time?**  
   → Visualized with a **Line Chart**, where  
     margin = profit / sales value.

---

## 📈 Developed Dashboard

Below is the dashboard created for Lab 2:

*(Insert dashboard image as provided)*  
![Dashboard Lab2](/portifolio_data_analitcs_and_science/Data_Science_Academy/03_Modelagem_relacionamento_e_dax/imagens/Dash.png)

---

## 🔗 Data Model

The model follows a star schema, using the **Sales** table as the fact table and the following as dimension tables:

- Customers  
- Orders  
- Products  

*(Insert data model image)*  
![Relationships](/portifolio_data_analitcs_and_science/Data_Science_Academy/03_Modelagem_relacionamento_e_dax/imagens/relacionamento.png)

---

## ✔️ Summary of Findings

- **Shipping mode with highest sales value:** Standard Class.  
- **Market with highest average shipping cost:** APAC.  
- **KPI for April/2014:** below target (350).  
- **Category with highest average profit:** Technology.  
- **Profit margin over time:** upward trend with normal fluctuations.

---

## 📚 Source  
Dataset provided by **Data Science Academy**.
