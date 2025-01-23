# 📌 Descrição do Projeto

### Português:
Este projeto tem como objetivo prever o preço médio de imóveis em uma região com base em características demográficas e estruturais. Utilizamos técnicas de análise exploratória de dados (EDA) e regressão linear para construir um modelo preditivo que possa ajudar investidores e profissionais do mercado imobiliário a tomar decisões baseadas em dados.

### English:
This project aims to predict the median price of properties in a region based on demographic and structural characteristics. We utilized exploratory data analysis (EDA) techniques and linear regression to build a predictive model that can assist investors and real estate professionals in making data-driven decisions.


# 🛠️ Etapas do Projeto | Project Steps
### Análise Exploratória de Dados (EDA) | Exploratory Data Analysis (EDA):
- Examinamos a distribuição dos preços dos imóveis e outras variáveis importantes.
- Criamos gráficos, como histogramas e matrizes de correlação, para identificar padrões e relações entre as variáveis.
- Conclusão principal: Renda média (median_income) mostrou a maior correlação com o preço dos imóveis.
  

### Pré-processamento dos Dados | Data Preprocessing:
- Tratamos valores ausentes e outliers em variáveis como quantity e unitprice.
- Realizamos o one-hot encoding para transformar variáveis categóricas (ocean_proximity) em colunas numéricas.

### Construção do Modelo | Model Building:
- Utilizamos regressão linear para prever o preço médio dos imóveis.
- Dividimos os dados em conjuntos de treino e teste (80/20) para avaliar o desempenho do modelo.
- 
### Avaliação do Modelo | Model Evaluation:
- Avaliamos o modelo com métricas como R² e MAE (Erro Absoluto Médio).
- Visualizamos a comparação entre os preços reais e previstos, observando que o modelo funciona bem, mas apresenta desvios para preços muito altos.

## 📊 Principais Descobertas | Key Findings
- Distribuição de Preços: A maioria dos imóveis está entre $100.000 e $300.000, com valores extremos acima de $500.000.
- Correlação: Renda média é o principal fator relacionado ao preço de um imóvel.
- Desempenho do Modelo: O modelo previu bem a maioria dos preços, mas pode ser aprimorado para lidar com outliers.

## 📁 Tecnologias Utilizadas | Technologies Used
- Linguagem: Python
- Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learngit 
- Modelagem: Regressão Linear