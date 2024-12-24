# Predicao_de_Infarto_Random_Forest

Preparação dos Dados:
Balanceamento das classes utilizando SMOTE.

Treinamento e Ajustes do Modelo:
Teste inicial com Random Forest padrão.
Ajuste de hiperparâmetros com GridSearchCV.
Alteração de thresholds para priorizar o recall.

Avaliação do Modelo Final:
Acurácia: 76%
Recall (Infartos): 95%

O modelo final alcançou:

95% de recall, identificando quase todos os casos de infarto.
Por que priorizamos o recall?
No contexto médico, é crucial identificar o máximo possível de casos de infarto (minimizar os falsos negativos), mesmo que isso ocasione um pequeno aumento nos falsos positivos. A saúde dos pacientes deve ser a prioridade máxima.
