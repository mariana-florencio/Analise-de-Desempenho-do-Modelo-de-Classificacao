# Análise de Desempenho do Modelo de Classificação
Este projeto contém um código que calcula a Matriz de Confusão e diversas métricas de desempenho para um modelo de classificação. As métricas incluem sensibilidade, especificidade, precisão, F1-score e acurácia, baseadas nas previsões do modelo em relação aos valores reais.

## Descrição do Código
O código utiliza a biblioteca scikit-learn para calcular a Matriz de Confusão, e a biblioteca numpy para calcular as métricas de desempenho.

## Fórmulas das Métricas
![download](https://github.com/user-attachments/assets/f90b03c3-8fa3-40ce-877b-6864b1508ec8)

VP: verdadeiros positivos;
FN: falsos negativos; 
FP: falsos positivos; 
VN: verdadeiros negativos; 
P: precisão; S: sensibilidade; 
N: total de elementos. 

## Passos principais do código:
**1. Definir os Dados:**

y_true: Lista contendo os valores reais das classes (valores esperados).
y_pred: Lista contendo os valores previstos pelo modelo.

**2. Calcular a Matriz de Confusão:**

A matriz é gerada usando a função confusion_matrix do scikit-learn, comparando os valores reais (y_true) com as previsões (y_pred).

**3. Calcular as Métricas:**

Sensibilidade (Recall): A habilidade do modelo de identificar corretamente os casos positivos.
Especificidade: A habilidade do modelo de identificar corretamente os casos negativos.
Precisão: A proporção de previsões corretas entre todas as previsões feitas para uma classe.
F1-Score: A média harmônica entre precisão e sensibilidade, útil para avaliar o equilíbrio entre essas métricas.
Acurácia: A proporção de previsões corretas em relação ao total de previsões feitas.

**4. Exibir os Resultados:**

A matriz de confusão e as métricas para cada classe são impressas no terminal.
