# AJUDA BOOTCAMP 2021

# DATASET

* **make_classification** - _datasets_
> Gere um problema de classificação aleatória de n classes.


# PRÉ-PROCESSAMENTO

* **SimpleImputer** - _impute_
> Transformador de imputação para completar os valores ausentes.

* **OneHotEncoder** - _preprocessing_
> Codifique recursos categóricos como uma matriz numérica one-hot.

* **OrdinalEncoder** - _preprocessing_
> Codifique recursos categóricos como uma matriz de inteiros.

* **LabelEncoder** - _preprocessing_
> Codifique rótulos de destino com valor entre 0 e n_classes-1.

* **MinMaxScaler** - _preprocessing_
> Transforme recursos dimensionando cada recurso para um determinado intervalo.

* **StandardScaler** - _preprocessing_
> Padronize os recursos removendo a média e escalonando para a variância da unidade.



# DIVISÃO DOS DADOS

* **train_test_split** -  _model_selection_
> Divida arrays ou matrizes em trem aleatório e subconjuntos de teste


# MODELOS DE IA

* **linearRegression** - _linear_model_
> Regressão Linear de mínimos quadrados ordinários.

* **LogisticRegression** - _linear_model_
> Classificador de regressão logística

* **KneighborsClassifier** - _neighbors_
> Classificador que implementa a votação de k-vizinhos mais próximos. 

* **DecisionTreeClassifier** _tree_
> Um classificador de árvore de decisão.

* **RandomForestClassifier** _ensemble_
> Um classificador de floresta aleatório.


# MÉTRICAS

* **classification_report** - _metric_
> Crie um relatório de texto mostrando as principais métricas de classificação.

* **confusion_matric** - _metric_
> Calcule a matriz de confusão para avaliar a precisão de uma classificação.



# PIPELINE

* **Pipeline** - _pipeline_
> Pipeline de transformações com um estimador final.

* **make_pipeline** - _pipeline_
> Construa a a Pipelinepartir dos estimadores fornecidos.

* **make_column_transformer** - _compose_
> Construa um ColumnTransformer a partir dos transformadores fornecidos.


# VALIDAÇÃO CRUZADA

* **cross_val_score** - _model_selection_
> Validação cruzada: avaliando o desempenho do estimador
