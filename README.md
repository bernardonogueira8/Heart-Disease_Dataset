# Heart Disease Dataset
Repositorio destinado ao teste de ML no dataset Heart Disease Dataset
Este conjunto de dados data de 1988 e consiste em quatro bancos de dados: Cleveland, Hungria, Suíça e Long Beach V. Ele contém 76 atributos, incluindo o atributo previsto, mas todos os experimentos publicados referem-se ao uso de um subconjunto de 14 deles. O campo "alvo" refere-se à presença de doença cardíaca no paciente. É um valor inteiro: 0 = sem doença e 1 = doença.

Atual modelo com score: 0.8207, ultilizando KNeighbors.
| #  | Model                     | Acurácia Treino (%) | Acurácia Teste (%) |
|----|---------------------------|---------------------|--------------------|
| 1  | KNeighbors                | 90.28               | 82.07              |
| 2  | Logistic Regression       | 91.67               | 81.38              |
| 3  | Random Forest Classifier  | 100.00              | 79.31              |
| 4  | Ada Boost                 | 100.00              | 76.55              |
| 5  | Decision Tree             | 100.00              | 67.59              |
# Conhecendo banco de dados
* **age**: Idade da pessoa, em anos
* **sex**: Sexo da pessoa (1 = masculino, 0 = feminino)
* **cp**: Tipo de dor no peito experimentada (Valor 1: angina típica, Valor 2: angina atípica, Valor 3: dor não anginosa, Valor 4: assintomático)
* **trestbps**: Pressão arterial de repouso da pessoa (em mm Hg, medida na admissão hospitalar)
* **chol**: Medida de colesterol da pessoa (em mg/dl)
* **fbs**: Glicemia de jejum da pessoa (> 120 mg/dl, 1 = verdadeiro; 0 = falso)
* **restecg**: Resultado do eletrocardiograma em repouso (0 = normal, 1 = anormalidade na onda ST-T, 2 = possível ou definitiva hipertrofia ventricular esquerda segundo os critérios de Estes)
* **thalach**: Frequência cardíaca máxima atingida pela pessoa
* **exang**: Angina induzida por exercício (1 = sim; 0 = não)
* **oldpeak**: Depressão do segmento ST induzida por exercício em relação ao repouso ('ST' se refere às posições no gráfico de ECG. Veja mais aqui)
* **slope**: Inclinação do segmento ST no pico do exercício (Valor 1: ascendente, Valor 2: plano, Valor 3: descendente)
* **ca**: Número de vasos principais (0–3)
* **thal**: Uma desordem sanguínea chamada talassemia (3 = normal; 6 = defeito fixo; 7 = defeito reversível)
* **target**: Doença cardíaca (0 = Não, 1 = Sim)
