# Desafio-COMPET---IA


Resumo das Etapas:

Pré-processamento: Os dados são carregados, a variável alvo ('diabetes') é separada das preditoras. O desbalanceamento de classes é tratado com SMOTE. Os dados são divididos em treino/teste, variáveis categóricas são codificadas (LabelEncoder) e as numéricas são escalonadas (StandardScaler).

Treinamento: Um modelo RandomForestClassifier é treinado usando os dados de treino pré-processados.

Avaliação: O modelo treinado faz previsões no conjunto de teste. Seu desempenho é medido pela acurácia, matriz de confusão e relatório de classificação.
