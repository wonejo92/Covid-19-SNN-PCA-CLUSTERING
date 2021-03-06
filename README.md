# Covid-19-SNN-PCA-CLUSTERING

Se presenta un cuaderno de Jupyter que demuestra el funcionamiento de una Red Neuronal con la implementación de PCA y CLUSTERING.
Realizaremos un análisis de PCA el cual nos permite realizar una reducción de dimensionalidad   y obtener una cierta cantidad de componentes principales, Para la Red neuronal utilizamos los componentes principales ya previamente obtenidos por el PCA, de igual manera se procede a realizar los K óptimos con los datos ya procesados.

1: Carga y procesamiento de los datos: Se realiza una limpieza, estandarización de los datos para Tener en formato Numérico.

2: Análisis de PCA: Se realiza un análisis de con una cierta cantidad de componentes.

3: Entrenamiento de la Red Neuronal: Se realiza un splitting de 20% para Train y 80% para test

4: Predicción y Evaluación: El sistema Realizara las predicciones para determinar qué clase de personas son más propensas a contraer el virus, o bien si ya es portador del virus en relación a sus síntomas.

# Distribución de archivos
### 2.COVID19_clasificacionnn.csv :
En este archivo se puede encontrar el dataset original [1] [2].
### COVID-19Notebook.ipynb :
En este archivo vamos a encontrar lo detallado en el 'método propuesto' ,utilizando librerías ,técnicas de machine learning para analizar  el dataset original.
### COVID-19NotebookHTML.ipynb.html :
Se puede leer el cuarderno con el metodo propuesto de mejor manera en esta versión.
### DatasetPreprocesado.csv :
En este archivo encontramos el resultado del dataset luego de aplicarle técnicas de limpieza ,de reducción de dimensionalidad y de formación de nuevas variables.

# Requisitos.
- Python 3.8
- Dataset: 2.COVID19_clasificacion [1]

# Librerias Necesarias.
- pandas
- numpy
- matplotlib
- OneHotEncoder
- StandardScaler
- LabelEncoder
- preprocessing
- train_test_split
- Pipeline

# Referencias
[1] 2.COVID19_clasificacion:https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/LQDFSE

[2] Fauci, A. S., Lane, H. C., & Redfield, R. R. (2020). Covid-19 — Navigating the Uncharted. New England Journal of Medicine, 382(13), 1268-1269. https://doi.org/10.1056/nejme2002387

