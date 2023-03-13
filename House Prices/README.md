# **House Prices: Advanced Regression Techniques - Projeto de Machine Learning**

Este é o meu projeto de Machine Learning para o desafio "House Prices: Advanced Regression Techniques" do Kaggle. O objetivo deste projeto é prever o preço de venda de casas com base em diversas variáveis descritivas das propriedades.

## **Dados**

Os dados para este projeto podem ser baixados diretamente do **[Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)**. O conjunto de dados consiste em dois arquivos CSV, um para treinamento e outro para teste.

## **Dependências**

Este projeto foi implementado em Python e utiliza diversas bibliotecas populares, como:

- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- CatBoost

## **Workflow**

Este projeto segue um workflow comum para problemas de machine learning:

1. **Análise exploratória de dados (EDA)**: exploração e visualização dos dados para identificar padrões e relacionamentos importantes.
2. **Pré-processamento de dados**: tratamento de valores ausentes, codificação de variáveis categóricas, padronização de dados, etc.
3. **Engenharia de recursos**: criação de novas variáveis e seleção de variáveis importantes.
4. **Modelagem de machine learning**: treinamento e ajuste de vários modelos de machine learning para encontrar o melhor modelo para o problema.
5. **Avaliação do modelo**: avaliação do desempenho do modelo final no conjunto de testes.

## **Modelo Final**

Após testar diversos modelos de machine learning, escolhi o CatBoostRegressor como meu modelo final. O CatBoost é um algoritmo de gradient boosting de árvore que é altamente escalável e preciso em problemas de regressão. Ele também possui recursos poderosos, como lidar com variáveis categóricas automaticamente e lidar com dados desbalanceados.

## **Resultados**

O modelo final apresentou uma boa pontuação no Kaggle e um bom desempenho no conjunto de testes.
