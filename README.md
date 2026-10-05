# Sales & Marketing Intelligence | Power BI

Projeto autoral de Business Intelligence desenvolvido com **dados simulados**, integrando Marketing, Funil Comercial, Vendas, Produtos e Clientes em uma visão analítica única.

O projeto percorre o processo desde a preparação e validação dos dados até a modelagem, construção de KPIs em DAX e desenvolvimento de um dashboard executivo no Power BI.

## 🎯 Objetivo

Construir uma solução analítica capaz de responder à seguinte pergunta de negócio:

> **Quais fatores de Marketing e do processo Comercial estão associados à conversão, rentabilidade e recompra dos clientes?**

A análise foi estruturada em três resultados principais:

**Conversão → Rentabilidade → Recorrência**

## 📊 Escopo dos dados

- **7 bases de dados**
- **200 leads**
- **1.866 eventos de pipeline**
- **175 pedidos**
- **112 clientes compradores**
- **100 SKUs cadastrados**

As bases representam informações de campanhas, leads, pipeline comercial, vendas, clientes, produtos e vendedores.

## 🔄 ETL & Data Quality

A preparação dos dados foi realizada principalmente no **Power Query**, preservando a camada bruta e construindo um processo reproduzível de transformação.

Entre os tratamentos e validações realizados:

- definição da granularidade das tabelas;
- padronização de tipos e valores;
- tratamento de valores nulos;
- normalização de campos percentuais;
- remoção e análise de duplicidades;
- validação de chaves;
- testes de integridade entre tabelas;
- recálculo de receita, custo e margem;
- validação do fluxo do funil comercial;
- auditoria de métricas como CPL, CAC, ROAS e conversão.

## 🧩 Modelagem de dados

O modelo conecta as principais entidades do processo comercial:

`Campanhas → Leads → Pipeline → Vendas`

Além das dimensões de:

`Clientes | Produtos | Vendedores | Calendário`

Foram definidos relacionamentos, cardinalidades e direções de filtro de acordo com a granularidade de cada tabela.

## 🧮 DAX & KPIs

Foi criada uma camada dedicada de medidas para centralizar os indicadores utilizados no dashboard.

Entre os principais KPIs:

- Receita Líquida
- Margem Bruta
- Margem %
- Total de Pedidos
- Ticket Médio
- CPL
- CAC
- ROAS
- Taxa de Conversão
- Conversão entre etapas
- Tempo Médio até Venda
- Interações Médias por Lead
- Taxa de Recorrência
- Receita de Clientes Recorrentes
- Performance por Produto e Vendedor

Também foram criadas colunas auxiliares para análises de **primeira compra, faixas de desconto, tempo de contato, ordenação do funil e comportamento de recompra**.

## 📈 Dashboard

O dashboard foi dividido em cinco páginas analíticas:

### 1. Visão Executiva
Consolidação dos principais indicadores de Marketing, Vendas, Margem, Conversão e Recorrência.

### 2. Marketing
Análise de investimento, CPL, CAC, ROAS, campanhas, canais e origens dos leads.

### 3. Funil Comercial
Acompanhamento das etapas do funil, conversão por vendedor, perdas, velocidade de contato e tempo médio entre etapas.

### 4. Vendas & Margem
Análise de receita, margem, categorias, produtos, descontos e performance comercial.

### 5. Clientes & Recorrência
Análise do comportamento de recompra, ticket, primeira compra e relação entre descontos e recorrência.

## 🛠️ Tecnologias utilizadas

- **Microsoft Excel**
- **Power Query**
- **Power BI**
- **DAX**
- Modelagem de Dados
- Data Quality
- Business Intelligence
- Análise de Marketing e Vendas

## 📥 Arquivo Power BI

O arquivo `.pbix` completo está disponível neste repositório e pode ser aberto no **Power BI Desktop** para visualizar o modelo, medidas DAX, relacionamentos e dashboard interativo.

## 🚧 Próxima etapa

A próxima evolução do projeto será utilizar **SQL** para realizar consultas, agregações, joins e análises diretamente sobre a camada de dados.

---

**Projeto autoral para portfólio | Dados simulados**
