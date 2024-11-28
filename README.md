# Análise da Qualidade de Maçãs

## Descrição

Este projeto tem como objetivo construir um modelo de Machine Learning para prever a qualidade de maçãs com base em suas características físico-químicas. O modelo será treinado utilizando um conjunto de dados contendo informações sobre diversas características das maçãs, como acidez, doçura, suculência, etc. O objetivo é classificar as maçãs como "boa" ou "ruim".

## Equipe

- Caio Bonato - 822165248
- Gabriel Castro - 822157975
- Gabriel Dias - 822144973
- Laysla Rodrigues - 821216057
- Leonardo Freitas - 822135116
- Lucas Quireza - 822229907
- Vinicius Almeida - 821246691


## Dataset

O dataset utilizado neste projeto foi obtido do arquivo "apple_quality.csv". O dataset contém informações sobre diversas características das maçãs, incluindo a qualidade (boa/ruim).

## Metodologia

1. **Exploração e Preparação dos Dados:**
    - Importação das bibliotecas necessárias (Pandas, NumPy, Scikit-learn, Matplotlib e Seaborn).
    - Leitura dos dados do arquivo "apple_quality.csv" para um DataFrame Pandas.
    - Análise exploratória dos dados para entender a distribuição dos dados, identificar valores ausentes e outliers.
    - Preparação dos dados, incluindo tratamento de valores ausentes, conversão de variáveis categóricas para numéricas e normalização dos dados.
2. **Treinamento e Avaliação de Modelos:**
    - Divisão dos dados em conjuntos de treinamento e teste.
    - Treinamento de diversos modelos de classificação, incluindo XGBoost, Regressão Linear, SVM, Naive Bayes, Árvore de Decisão, Random Forest e Regressão Logística.
    - Ajuste de hiperparâmetros dos modelos usando Grid Search para encontrar a melhor configuração.
    - Avaliação do desempenho dos modelos usando métricas como acurácia, precisão, recall e F1-score.
    - Comparação dos resultados dos diferentes modelos para selecionar o modelo com melhor desempenho.
3. **Visualização dos Resultados:**
    - Criação de gráficos para visualizar a matriz de confusão, curva ROC e outros resultados relevantes.
    - Interpretação dos resultados e conclusões sobre o desempenho do modelo.

## Resultados

Os resultados da análise e avaliação dos modelos são apresentados no notebook do projeto. O modelo XGBoost com ajuste de hiperparâmetros apresentou o melhor desempenho, com uma acurácia de aproximadamente 90%.

## Conclusões

Este projeto demonstrou a aplicação de técnicas de Machine Learning para prever a qualidade de maçãs. O modelo XGBoost com ajuste de hiperparâmetros se mostrou promissor para essa tarefa.

## Próximos Passos

- Explorar outros modelos de Machine Learning para melhorar a acurácia da previsão.
- Coletar mais dados para treinar o modelo e torná-lo mais robusto.
- Implementar o modelo em um sistema real para auxiliar na tomada de decisões sobre a qualidade das maçãs.


## Como executar o projeto

1. Clone este repositório.
2. Abra o notebook do projeto no Google Colab.
3. Execute as células do notebook para realizar a análise e avaliação dos modelos.

## Dependências

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost

## Observações

- Os códigos foram comentados para facilitar a compreensão.
- As bibliotecas utilizadas foram importadas no início do notebook.
- Os resultados da execução dos códigos foram omitidos neste relatório.
