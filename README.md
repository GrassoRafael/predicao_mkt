## Análise de Investimentos em Publicidade e Predição de Retorno de Vendas
# Introdução
Uma empresa está investindo mensalmente em plataformas de publicidade online, como Youtube, Facebook e jornais (newspaper), para a prospecção de leads (pessoas interessadas em seus produtos). Para acompanhar o desempenho desses investimentos, a empresa registra todos os gastos com publicidade e todos os retornos de vendas gerados a partir desses investimentos.

O objetivo deste projeto é analisar a relação entre os investimentos em publicidade e os retornos de vendas, além de identificar os fatores que mais impactam na geração de leads. Com base nessa análise, também buscamos criar um modelo de predição para estimar o retorno de vendas a partir de um determinado investimento em publicidade.

Estrutura do Projeto
Este repositório contém o código e os dados utilizados na análise e na criação do modelo de predição. Abaixo estão as etapas principais do projeto:

# 1. Importação de Módulos
As bibliotecas utilizadas neste projeto são:

````python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import plotly.express as px

from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import r2_score
````
# 2. Análise Exploratória de Dados (EDA)
Nesta etapa, realizamos a análise exploratória dos dados para entender melhor a distribuição dos investimentos e o retorno de vendas. Utilizamos visualizações gráficas para identificar padrões e correlações.

# 3. Pré-processamento de Dados
Os dados são preparados para a modelagem, incluindo a divisão em conjuntos de treinamento e teste.

# 4. Modelagem
Construímos um modelo de regressão linear para prever o retorno de vendas com base nos investimentos em publicidade. Avaliamos o desempenho do modelo utilizando métricas apropriadas.

# 5. Avaliação do Modelo
Utilizamos o coeficiente de determinação (R²) para avaliar a precisão do modelo na predição dos retornos de vendas.

Como Usar
Clone este repositório:

````bash
git clone https://github.com/GrassoRafael/predicao_mkt.git
````

Navegue até o diretório do projeto:
````bash
cd predicao_mkt
````

Execute o script principal:
````bash
python base.ipynb
````
