<iframe src="https://share.streamlit.io/your-streamlit-app-url/main.py" width="100%" height="800"></iframe>
Tecnologias Utilizadas

Python
Streamlit
Pandas
Plotly Express
Requests
Funcionalidades

Filtros
Região: Filtra dados por região do Brasil.
Período: Opção de visualizar todos os anos ou selecionar um ano específico (2020-2023).
Vendedores: Possibilidade de filtrar por vendedores específicos.
Abas de Visualização
Aba Receita
Métricas de receita total e quantidade de vendas.
Mapa geográfico da receita por estado.
Gráfico de receita mensal.
Top estados por receita.
Receita por categoria de produto.
Aba Quantidade de Vendas
Métricas de receita total e quantidade de vendas.
Mapa geográfico das vendas por estado.
Gráfico de vendas mensais.
Top 5 estados em quantidade de vendas.
Vendas por categoria de produto.
Aba Vendedores
Seletor de quantidade de vendedores a serem exibidos (2-10).
Ranking dos top vendedores por receita.
Ranking dos top vendedores por quantidade de vendas.
Estrutura de Dados

O dashboard consome dados de uma API (https://labdados.com/produtos) e processa as seguintes informações:

Data da Compra
Local da Compra
Preço
Vendedor
Categoria do Produto
Coordenadas Geográficas (latitude e longitude)
Funções Principais

formata_numero(valor, prefixo=''): Formata valores numéricos para exibição, convertendo para mil ou milhões conforme a magnitude do número.
Processamento de Dados

Agrupamento de dados por estado, mês e categoria.
Cálculos de receita e quantidade de vendas.
Criação de visualizações interativas com Plotly Express.
Visualizações

Gráficos de barras.
Gráficos de linha.
Mapas geográficos.
Métricas numéricas.
