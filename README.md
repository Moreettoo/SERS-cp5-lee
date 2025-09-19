# SERS-cp5-lee

Este projeto realizou uma análise preditiva completa sobre um conjunto de dados meteorológicos com o objetivo de prever a radiação solar. Utilizando variáveis como temperatura, umidade, pressão e velocidade do vento, o desafio foi abordado através de duas tarefas distintas de machine learning: classificação e regressão.

Na tarefa de classificação, o objetivo era prever se a radiação estaria acima ou abaixo de um nível mediano. Foram testados os algoritmos Árvore de Decisão, Random Forest e SVM. Após a otimização dos modelos, o Random Forest se destacou com a maior acurácia.

Na tarefa de regressão, o desafio era prever o valor numérico exato da radiação (em W/m²). Foram comparados os modelos de Regressão Linear, Árvore de Regressão e Random Forest Regressor. Novamente, o Random Forest Regressor apresentou um desempenho muito superior, com o maior R² e os menores erros (MAE e RMSE).

A conclusão principal do projeto é que a relação entre as condições ambientais e a radiação solar é complexa e não-linear. Por isso, o algoritmo Random Forest, em ambas as suas formas, foi o mais eficaz, pois sua arquitetura de conjunto (ensemble) é capaz de capturar essas interações complexas de forma mais robusta do que modelos lineares ou árvores de decisão individuais.

Passo 1: Preparação do Ambiente

Passo 2: Organização dos Arquivos
Para que o script funcione corretamente, organize seus arquivos da seguinte maneira:

Passo 3: Execução da Análise

Passo 4: Verificação dos Resultados
Após a execução, os resultados serão apresentados de duas formas:
