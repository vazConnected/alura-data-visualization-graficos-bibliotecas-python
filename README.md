# Data Visualization: criando gráficos com bibliotecas Python

Este repositório faz parte da minha sequência de estudos em Data Science e Data Visualization. Como guia nesta trajetória, o curso [Data Visualization: criando gráficos com bibliotecas Python](https://cursos.alura.com.br/course/data-visualization-graficos-bibliotecas-python) da [Alura](https://www.alura.com.br/) foi tomado como base.

## 1. Conhecendo a biblioteca Matplotlib

No primeiro capítulo foram introduzidos recursos base da biblioteca [Matplotlib](https://matplotlib.org/). Para isso, uma [base de dados](dados/canadian_immegration_data.csv) sobre imigrações para o Canadá foi utilizada.

Clique [aqui](notebooks/01-conhecendo_a_bibliteca_matplotlib.ipynb) para acessar o caderno do capítulo 1.

## 2. Criando figuras com Matplotlib

No segundo capítulo foi introduzido o conceito de subplots, permitindo que mais de um gráfico fosse criado em uma figura.

Clique [aqui](notebooks/02-criando_figuras_com_matplotlib.ipynb) para acessar o caderno do capítulo 2.

## 3. Customizando com Matplotlib

No terceiro capítulo foram abordados conceitos de estilização de gráficos e exportação das figuras para diferentes formatos de arquivos.

Com esses conhecimentos, foram exportados os seguintes gráficos:

![Imigração brasileira para o Canadá (1980 a 2013)](resultados/line_chart_imigracao_brasil_para_o_canada.png)

![Imigração para o Canadá por países da américa do sul (1980 a 2013)](resultados/horizontal_bar_chart_imigracao_paises_america_do_sul_para_o_canada.png)

Clique [aqui](notebooks/03-customizando-com-matplotlib.ipynb) para acessar o caderno do capítulo 3.

## 4. Conhecendo a biblioteca Seaborn

No quarto capítulo foram abordados a biblioteca Seaborn, aspectos de estilização e a importância das cores para a mensagem a ser transmitida com um gráfico.

Como aplicação desses conhecimentos, foi criado um gráfico com as 10 países de onde mais vieram imigrantes para o Canadá (de 1980 a 2013). As cores foram utilizadas para ressaltar positividade para altos fluxos migratórios para o país.

![Top 10 países que mais imigraram para o Canadá](resultados/top_10_paises_imigracao_canada.png)

Clique [aqui](notebooks/04-conhecendo-a-biblioteca-seaborn.ipynb) para acessar o caderno do capítulo 4.

## 5. Gráficos interativos com Plotly

No quinto capítulo foi apresentado o Plotly e seus diferentes recursos para criar gráficos interativos. A fim de colocar todos os conhecimentos em prática, foi criar o gráfico interativo [Imigração de países da América do Sul para o Canadá (1980 a 2013)](resultados/america_do_sul_imigracao_para_canada.html).

Clique [aqui](notebooks/05-graficos-interativos-com-plotly.ipynb) para acessar o caderno do capítulo 5.
