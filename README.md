<h2>Dashboard de Análise de Vendas</h2>

Este é um dashboard interativo desenvolvido em Streamlit para a análise de dados de vendas. O sistema permite visualizar métricas importantes, como receita, quantidade de vendas e desempenho dos vendedores, através de diferentes visualizações gráficas.

<h2>Tecnologias Utilizadas</h2>

- Python
- Streamlit
- Pandas
- Plotly Express
- Requests

  
<h2>Funcionalidades</h2>

<h3>Filtros</h3>
- Região: Filtra dados por região do Brasil.
- Período: Opção de visualizar todos os anos ou selecionar um ano específico (2020-2023).
- Vendedores: Possibilidade de filtrar por vendedores específicos.

<h2>Abas de Visualização</h2>
<h3>Aba Receita</h3>

- Métricas de receita total e quantidade de vendas.
- Mapa geográfico da receita por estado.
- Gráfico de receita mensal.
- Top estados por receita.
- Receita por categoria de produto.

<h3>Aba Quantidade de Vendas</h3>

- Métricas de receita total e quantidade de vendas.
- Mapa geográfico das vendas por estado.
- Gráfico de vendas mensais.
- Top 5 estados em quantidade de vendas.
- Vendas por categoria de produto.

<h3>Aba Vendedores</h3>

Seletor de quantidade de vendedores a serem exibidos (2-10).
Ranking dos top vendedores por receita.
Ranking dos top vendedores por quantidade de vendas.
Estrutura de Dados

O dashboard consome dados de uma API (https://labdados.com/produtos) e processa as seguintes informações:

- Data da Compra
- Local da Compra
- Preço
- Vendedor
- Categoria do Produto
- Coordenadas Geográficas (latitude e longitude)
Funções Principais

formata_numero(valor, prefixo=''): Formata valores numéricos para exibição, convertendo para mil ou milhões conforme a magnitude do número.

<h2>Processamento de Dados</h2>

- Agrupamento de dados por estado, mês e categoria.
- Cálculos de receita e quantidade de vendas.
- Criação de visualizações interativas com Plotly Express.
- 
<h2>Visualizações</h2>

- Gráficos de barras.
- Gráficos de linha.
- Mapas geográficos.
- Métricas numéricas.


