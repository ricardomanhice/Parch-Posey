# 🎯Parch & Posey - Power BI Dashboard

Este repositório apresenta um projeto de Business Intelligence desenvolvido com base no dataset fictício **Parch & Posey**, amplamente utilizado para fins educacionais e de análise de dados.
## 🏢Sobre a empresa
Parch & Posey é uma fabricante fictícia de papel personalizado (como papel timbrado, cartões e envelopes), que vende principalmente para empresas. O dataset simula informações reais de vendas, clientes, produtos e eventos online.

## 📊Objectivo do Projecto
O objetivo deste projeto foi criar um dashboard interativo no Power BI que oferecesse insights relevantes sobre o desempenho de vendas da empresa, comportamento dos clientes e tendências por produto e região.

## 🧩Fontes de dados
O dataset está dividido nas seguintes tabelas principais:

Orders – Detalhes de cada pedido de venda (data, produto, receita, quantidade, etc.)

Accounts – Informações sobre os clientes (nome, indústria, região, site, etc.)

Sales_Reps – Detalhes dos representantes de vendas responsáveis por contas e pedidos

Region – Detalhes sobre as regiões de atuação da empresa

Web_Events – Atividades online dos clientes no site da empresa

## 🛠️Ferramentas Utilizadas
**Power BI** - Visualização e modelagem de dados

**Power Query** - ETL dos dados

**DAX** - Cálculo de métricas e KPIs

**GitHub** - Documentacao

## 🎯Paginas do Dashboard

**1. Página Inicial (Capa)**

Apresenta um resumo executivo com os principais KPIs:

Receita Total

Total de Clientes

Interface amigável com menus em forma de botões, permitindo uma navegação fluida entre as páginas:

🔘 Visão do Produto

🔘 Visão do Cliente

Inclui também um botão "Relatório", posicionado abaixo dos KPIs, que redireciona diretamente para a Página 1 (Visão do Produto), facilitando o acesso imediato às análises detalhadas.


**2. Visao Geral do Produto**

A Visão do Produto apresenta uma análise aprofundada do desempenho comercial de cada tipo de papel vendido pela Parch & Posey. Essa página foi construída para responder a perguntas como:

➡️ Quais produtos geram mais receita?

➡️ Como a performance varia ao longo do tempo e entre regiões?

➡️ Qual o valor médio gerado por tipo de folha?

🔹 KPIs Apresentados

> Total de Pedidos: quantidade total de vendas realizadas

> Receita Total: valor bruto obtido com as vendas

> Receita Média por Pedido: métrica calculada como Receita Total / Total de Pedidos

### 📊 Visualizações e Métricas Detalhadas

***Receita Total e Quantidade de Pedidos por Ano e Trimestre***

Permite identificar tendências sazonais e evolução de vendas ao longo do tempo.

Exibe crescimento ou queda por período.


***Receita Total por Tipo de Folha (Standard, Gloss, Poster)***

Analisa quais produtos são os mais rentáveis.

Permite comparar a contribuição de cada tipo de papel para o faturamento geral.


***Valor Médio por Tipo de Folha***

Indica o preço médio efetivo por tipo de produto.

Útil para entender a precificação ou posicionamento no mercado.


***Receita Total por Região***

Identifica quais regiões geográficas geram maior retorno financeiro.

Ajuda a localizar oportunidades de expansão ou reforço comercial.


***Receita Total por Mês***

Permite observar flutuações mensais.

Útil para ações de marketing sazonal ou campanhas promocionais.


### 🎯 Objetivo da Página
Ajudar gestores e analistas a:

Compreender o desempenho de produtos em diferentes períodos e regiões

Identificar oportunidades de aumento de receita

Reavaliar estratégias de vendas por tipo de produto

Avaliar consistência nas vendas e valor agregado por tipo de papel



**3. Visão do Cliente**

A Visão do Cliente oferece uma análise centrada no comportamento dos clientes, sua distribuição geográfica, sua contribuição para o faturamento e a atuação dos representantes de vendas. Esta página permite identificar os clientes mais valiosos, entender a penetração da empresa por região e avaliar o desempenho dos canais de venda.

### 📊Visualizações e Métricas Apresentadas

***Total de Clientes por Região***
Mostra a distribuição geográfica da base de clientes.

Permite identificar regiões com maior concentração de contas ativas.

Útil para decisões estratégicas de expansão comercial.


***Receita Total por Cliente***
Identifica os principais clientes em termos de faturamento.

Pode ser usada para análises de dependência comercial e oportunidades de fidelização.


***Total de Eventos Web por Canal de Venda***
Quantifica as interações dos clientes com os canais digitais da empresa (ex: Google, Facebook, Email, etc.).

Permite entender quais canais geram maior engajamento online.

Suporta decisões em marketing e vendas digitais.


***Ranking de Representantes de Vendas (Sales Reps)***
Matriz com as seguintes colunas:

Nome do representante de vendas (sales_reps)

Receita total gerada

Percentual da receita total que cada um representa

Apresentada em ordem decrescente de receita (ranking)

Útil para avaliação de desempenho individual e definição de metas comerciais


### 🎯 Objetivo da Página
Mapear a contribuição dos clientes e regiões para o resultado da empresa

Avaliar o engajamento nos canais digitais

Monitorar o desempenho dos representantes de vendas

Identificar oportunidades de reforço comercial, relacionamento e marketing direcionado

