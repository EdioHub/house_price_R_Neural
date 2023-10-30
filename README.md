# house_price_R_Neural


#  Previsão de Preços de Imóveis com Rede Neural Densa

Neste projeto, desenvolvemos uma rede neural densa para prever os preços de imóveis. Inicialmente, enfrentamos resultados insatisfatórios, o que nos levou a aprimorar o modelo expandindo o conjunto de características consideradas na previsão.

Utilizamos uma rede neural com 4 camadas densas e treinamos o modelo ao longo de 100 épocas. Essas etapas adicionais de treinamento e aumento das características permitiram uma melhoria significativa no desempenho do modelo.
Utilizamos algumas métricas de avaliação para verificar o desempenho do modelo, de forma comparativa:

- **Raiz Quadrada do Erro Médio (RMSE - Root Mean Squared Error):**
  - RMSE = 130,306.953

- **Erro Quadrático Médio (MSE - Mean Squared Error):**
  - MSE = 16.979.902.082,83851

- **Erro Médio Absoluto (MAE - Mean Absolute Error):**
  - MAE = 74.879,80061644153

- **Coeficiente de Determinação (R²):**
  - R² = 0,8677562462031143

Além disso, também calculamos o R² ajustado, que é uma métrica útil para verificar o ajuste do modelo considerando o número de características utilizadas:

- **R² Ajustado:**
  - R² Ajustado = 0,8675846920376995

Os altos valores de R² e R² ajustado indicam que nosso modelo possui uma capacidade sólida de explicar a variabilidade nos preços dos imóveis. A RMSE e o MAE oferecem insights sobre a precisão das previsões, enquanto o MSE quantifica o erro médio ao quadrado. Com base nessas métricas, podemos afirmar que nossa rede neural densa é capaz de realizar previsões bastante precisas dos preços de imóveis.

Este projeto é um exemplo de como o uso de redes neurais densas pode ser uma ferramenta valiosa na previsão de preços de imóveis, e as métricas fornecidas nos ajudam a avaliar seu desempenho de maneira abrangente.
