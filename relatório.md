Análise e Previsão do Preço de Casas Usando Regressão

1. Objetivo
O objetivo principal deste projeto foi desenvolver um modelo de regressão preditivo para estimar o preço de casas com base em diferentes características,
como metragem quadrada, número de quartos, número de banheiros, idade da construção e qualidade da vizinhança. Buscamos fornecer uma análise rica e detalhada,
explorando diversas técnicas de processamento de dados, visualização e modelagem estatística.



3. Tecnologias Utilizadas
Linguagem: Python

Bibliotecas:

pandas: Manipulação e exploração de dados

numpy: Operações matemáticas e vetorização

matplotlib e seaborn: Visualização de dados

scikit-learn: Modelagem e avaliação de algoritmos de regressãostatsmodels: Testes estatísticos e visualizações avançadas



3. Pré-processamento e Limpeza de Dados
Os dados foram analisados para verificar a presença de valores ausentes e outliers. Para lidar com valores discrepantes, optou-se por realizar a transformação logarítmica da variável dependente, o que garantiu uma melhor distribuição dos dados e melhorou o desempenho do modelo de regressão linear.



4. Análise Exploratório dos Dados
Durante a análise exploratória, foram gerados gráficos de dispersão e boxplots para verificar a relação entre o preço das casas e as variáveis preditivas. Esta fase permitiu identificar padrões interessantes, como a correlação positiva entre metragem quadrada e preço, além da importância de variáveis como o tamanho do lote e a qualidade do bairro.


![image](https://github.com/user-attachments/assets/ff06244c-44f7-4cda-a881-2410ef6e1c93)


5. Modelagem
Para a modelagem, utilizamos o algoritmo de Regressão Linear. O modelo foi treinado usando o conjunto de dados transformado logaritmicamente, buscando minimizar o erro absoluto médio (MAE) e o erro quadrático médio (MSE). As métricas do modelo foram satisfatórias, indicando uma forte capacidade de previsão:

Mean Absolute Error (MAE): 51.521
Mean Squared Error (MSE): 4.485.183.820
R² (Coeficiente de Determinação): 0.93

![image](https://github.com/user-attachments/assets/356afbbd-2aba-4d3a-950f-f216e9726a25)



6. Avaliação e Validação
Os resultados demonstraram que a transformação logarítmica trouxe ganhos significativos para a performance do modelo, como visto no gráfico de previsões vs valores reais, onde a maioria dos pontos se aproxima da linha vermelha (indicando previsões precisas).



7. Conclusão
O modelo de regressão linear ajustado após a transformação dos dados foi capaz de explicar cerca de 93% da variabilidade nos preços das casas.
Além disso, as variáveis mais importantes para a previsão foram o tamanho do terreno, a metragem quadrada e o número de banheiros.
O projeto demonstrou a eficácia de técnicas de transformação de variáveis e o uso de modelos lineares em problemas de regressão.

