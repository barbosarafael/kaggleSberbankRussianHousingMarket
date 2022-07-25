# Sberbank Russian Housing Market

## 1. Contexto 

Essa é uma competição do Kaggle, que pode ser encontrada nesse [link](https://www.kaggle.com/c/sberbank-russian-housing-market). Os dados se tratam de características de casas da Rússia disponibilizadas pelo banco Sberbank, também russo. O dataset possui a granularidade a nível casa, ou seja, cada linha do banco possui informações de uma casa em específico. 

## 2. Objetivo

Dados os dados, queremos predizer a variável preço da casa com as demais características que temos dela. 

## 3. Métrica de "sucesso"

A métrica para avaliarmos os modelos será o RMSLE: Root Mean Squared Log Error. Que é denotada com a seguinte fórmula: 

$$ \text{RMSLE} = \sqrt{ \frac{1}{n} \sum_{i = 1}^{n} (\log(y_{i} + 1) - (\log(\hat{y_{i}} + 1) )^{2} } $$

Essa métrica é comum de ser usada quando estamos lidando com modelos de regressão sendo a variável target (ou y) em uma escala relativamente grande. 

