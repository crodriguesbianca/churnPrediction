# Análise de evasão de Clientes

<p align="center">
  <img src="https://github.com/crodriguesbianca/churnPrediction/blob/main/imagem-capa.jpg" alt="imagem relacionada ao tema">
</p>



A análise preditiva de churn possibilita identificar clientes com maior risco de cancelamento antes que isso aconteça. Essa antecipação permite implementar ações estratégicas, como ofertas personalizadas, melhorias nos serviços ou ajustes de marketing, resultando em maior retenção e valorização da base de clientes.

Este projeto foi desenvolvido para a disciplina Data Discovery e Analytics do curso de Pós-Graduação em Ciência de Dados da PUC Minas, visando prever a evasão de clientes (churn) em uma empresa de telecomunicação, permitindo ações estratégicas de retenção.


## 🛠 Etapas do projeto

- Entendimento do problema
- Pré-processamento
- Tratamento de valores ausentes e outliers
  - Transformação de variáveis qualitativas em dummies (para regressão logística)
  - Conversão de fatores restantes em numéricos
  - Balanceamento da base (undersampling)
  - Seleção de variáveis via stepwise (AIC)
- Validação Cruzada
- Modelagem: Regressão Logística e Arvore de Decisão
- Avaliação: acurácia, precisão, recall, F1-score, balanced accuracy, matriz de confusão


## Conclusão

A regressão logística se destaca por gerar previsões mais confiáveis de churn (menos falsos positivos), enquanto a árvore de decisão apresenta desempenho mais equilibrado entre clientes que evadem e que permanecem.

Como o objetivo da analise consiste em prever a evasão de clientes (churn), o modelo de regressão logistica se saiu melhor. Mas no geral, ambos os modelos são eficazes na previsão de churn e podem ser combinados para aproveitar o melhor de cada um.


[Link para o projeto completo]()


