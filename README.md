<h1 align="center"> Análise exploratória </h1>

## 📌 Descrição

Projeto desenvolvido para a disciplina de **Projeto aplicado I** do curso Banco de Dados da Universidade Presbiteriana Mackenzie, segundo semestre.  
O foco deste projeto é desenvolver uma análise exploratória de dados.  

Os dados utilizados foram extraídos de uma base pública disponível no Kaggle, contendo informações detalhadas sobre o comércio eletrônico no Brasil, incluindo pedidos, produtos, clientes, pagamentos e avaliações de satisfação.  

📂 Dataset disponível em: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data)

---

## 🎯 Objetivo Principal

**Pergunta central:**  
Como a **localização**, o **vendedor**, a **categoria do produto** e os **atrasos nas entregas** impactam as notas de avaliação (*review scores*) dos clientes?

### a) Análise da Taxa de Atraso vs. Notas de Avaliação
- **Fonte de Dados:** `olist_orders_dataset` & `olist_products_dataset`  
- **Preparação dos Dados:**  
  - Remover valores nulos das colunas de data.  
  - Converter datas para o formato `datetime`.  
  - Calcular o atraso em dias para cada pedido (`data real de entrega - data estimada de entrega`).  
  - Calcular a taxa média de atraso.  
- **Análise:**  
  - Visualizar a taxa média de atraso.  
  - Comparar notas de avaliação para pedidos **com atraso acima e abaixo da média**.  

### b) Desempenho do Vendedor
- Identificar **qual vendedor tem a maior taxa de pedidos atrasados**.  

### c) Análise Geográfica
- Determinar **em quais zonas geográficas** (estados/municípios) os pedidos são mais frequentemente atrasados.  

### d) Análise Multifatorial
- **Pergunta-chave:** O atraso é o único fator que reduz as notas de avaliação?  
- **Subperguntas:**  
  - Dentre as avaliações abaixo da média, qual porcentagem corresponde a pedidos atrasados?  
  - Existe algum estado que contribui de forma desproporcional para o número de avaliações ruins?  
  - Quais **categorias de produtos** concentram a maioria das avaliações ruins?  

---

## 📌 Conclusão Esperada
Sintetizar os resultados para determinar como cada fator — **desempenho do vendedor**, **localização geográfica**, **categoria do produto** e **atraso nas entregas** — impacta **individualmente** e **coletivamente** as notas de avaliação dos clientes.  

---

## 🗂️ Dataset


- `olist_orders_dataset.csv`  (usado)  
- `olist_order_reviews_dataset.csv`  (usado)  
- `olist_products_dataset.csv`  (usado)  
- `olist_geolocation_dataset.csv`  (usado)  
- `olist_order_items_dataset.csv`  -
- `olist_customers_dataset.csv`   -
- `olist_order_payments_dataset.csv`   -
- `product_category_name_translation.csv` -

---

## 📖 Referências do Dataset

- **Origem dos Dados:**  
  O conjunto de dados foi obtido por meio da plataforma **Kaggle**, no dataset *Brazilian E-Commerce Public Dataset by Olist* (https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data), disponibilizado pela empresa **Olist**.  

- **Originalidade e Limitações:**  
  Este dataset foi construído a partir de transações reais realizadas na plataforma Olist. Os dados são anonimizados, e algumas informações foram traduzidas para maior acessibilidade.  

- **Período da Coleta:**  
  Os pedidos foram realizados entre **2016 e 2018**.  

- **Limitações de Uso:**  
  Por se tratar de um dataset público e de fonte secundária, seu uso é destinado a fins acadêmicos e de pesquisa. Os insights devem ser analisados considerando as limitações de representatividade (somente dados da Olist) e possíveis simplificações feitas para a versão pública.  



## Integrantes
Este projeto foi desenvolvido pelos seguintes integrantes:

- Ryan Rodrigues Pereira
-
-


**Universidade Presbiteriana Mackenzie** \
**Curso Banco de dados** \
**Projeto Aplicado I - 2º Semestre  2025** 


