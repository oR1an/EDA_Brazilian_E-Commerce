<h1 align="center"> Análise exploratória </h1>

## 📌 Descrição

Projeto desenvolvido para a disciplina de **Projeto aplicado I** do curso Banco de Dados da Universidade Presbiteriana Mackenzie, segundo semestre.  
O foco deste projeto é desenvolver uma análise exploratória de dados.  

Os dados utilizados foram extraídos de uma base pública disponível no Kaggle, contendo informações detalhadas sobre o comércio eletrônico no Brasil, incluindo pedidos, produtos, clientes, pagamentos e avaliações de satisfação.  

📂 Dataset disponível em: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data)

---

## 🎯 **Objetivo Principal**

**Pergunta central:**  
Como a **localização geográfica**, a **categoria do produto** e os **atrasos nas entregas** impactam as **notas de avaliação** (*review scores*) dos clientes?

> *(Os fatores “vendedor” e outros aspectos complementares são mencionados apenas como possíveis extensões futuras, fora do escopo principal deste estudo, devido à limitação das bases utilizadas.)*

---

### a) **Análise da Taxa de Atraso vs. Notas de Avaliação**
- **Preparação dos Dados:**
  - Remover valores nulos nas colunas de data.  
  - Converter datas para o formato `datetime`.  
  - Calcular o atraso em dias para cada pedido (`data real de entrega - data estimada de entrega`).  
  - Calcular a **média de atraso** entre os pedidos entregues.  
- **Análise:**
  - Identificar a **distribuição dos atrasos**.  
  - Comparar as **notas de avaliação** entre pedidos **atrasados** e **entregues dentro do prazo**.  

---

### b) **Análise Geográfica**
- Cruzar os pedidos com os dados de **geolocalização** para identificar diferenças regionais de satisfação.  
- Determinar **em quais estados ou cidades** os pedidos tendem a ter **maiores índices de atraso** ou **menores notas de avaliação**.  

---

### c) **Análise por Categoria de Produto**
- Avaliar **quais categorias** concentram a maior proporção de **avaliações negativas**.  
- Verificar se há relação entre **tipo de produto** e **tempo médio de entrega**.  

---

### d) **Análise Multifatorial**
- **Pergunta-chave:** O atraso na entrega é o único fator que reduz as notas de avaliação?  
- **Subperguntas:**
  - Dentre as avaliações abaixo da média, qual porcentagem corresponde a pedidos atrasados?  
  - Existem **regiões** que concentram mais avaliações negativas?  
  - Há **categorias específicas** com notas consistentemente menores, mesmo sem atraso?  

---

## 📌 **Conclusão Esperada**

Com base nas análises, espera-se identificar **como os atrasos, a localização e as categorias de produtos** impactam a satisfação do cliente, medida pelas *review scores*.  

Além disso, busca-se compreender se os **atrasos nas entregas** são, de fato, o **principal fator determinante** das notas baixas, ou se **aspectos regionais e de categoria** também influenciam significativamente a percepção dos consumidores.




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
- Nour Hussein Barakat
- Guilherme de Araújo Esp. Santo


**Universidade Presbiteriana Mackenzie** \
**Curso Banco de dados** \
**Projeto Aplicado I - 2º Semestre  2025** 


