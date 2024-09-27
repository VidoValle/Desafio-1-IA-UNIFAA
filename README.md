Datasets: Este é o conjunto de dados sobre animais do zoológico, que serve como base para o aprendizado de máquina.
Select Columns: Aqui, selecionamos quais características dos animais serão usadas no treinamento e quais serão o alvo da classificação.
Data Table: Mostra os dados organizados em forma de tabela para garantir que estão corretos antes do treinamento.
Distributions: Exibe graficamente a distribuição das características, como "número de pernas" ou "tipo de animal", ajudando a entender a variabilidade.
Scatter Plot: Visualiza a relação entre duas variáveis, como tipo de animal e número de pernas, para explorar padrões.
Data Sampler: Separa uma amostra dos dados, garantindo a divisão adequada para treinamento e teste.
Modelos (Naive Bayes, SVM, Tree, kNN): Diferentes algoritmos de classificação são usados. Cada um tem uma abordagem distinta para prever a classe de um animal.
Test and Score: Avalia os modelos com base em métricas como precisão (CA) e mostra qual tem o melhor desempenho.
Confusion Matrix: Exibe onde o modelo está acertando e errando ao comparar as previsões com os dados reais.
Save Model & Predictions: Salva o modelo treinado e realiza previsões com base no modelo para novos dados.

Naive Bayes: Rápido e simples, baseado em probabilidades e assume que todas as características são independentes. Bom para dados grandes e problemas simples.
SVM (Support Vector Machine): Encontra o hiperplano que melhor separa as classes. Ótimo para dados complexos e de alta dimensionalidade, mas pode ser lento em grandes datasets.
Árvore de Decisão (Tree): Baseada em perguntas "se-então", fácil de interpretar, mas pode sofrer de overfitting se não for bem controlada.
kNN (K-Nearest Neighbors): Classifica com base nos vizinhos mais próximos. Simples, mas pode ser lento e ineficiente para grandes datasets.
