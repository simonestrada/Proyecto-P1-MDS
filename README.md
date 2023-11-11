Repositorio Proyecto-P1-MDS
Este repositorio contiene un conjunto de scripts y notebooks para el análisis exploratorio de datos (EDA). A continuación, se detallan las principales bibliotecas y herramientas utilizadas en este proyecto:

Librerías Principales
pandas: Librería fundamental para la manipulación y análisis de datos. Utilizada para cargar y procesar conjuntos de datos.

os: Utilizada para la manipulación y creación de directorios.

datetime: Usada para trabajar con fechas y horas.

matplotlib y seaborn: Herramientas de visualización esenciales para crear gráficos y visualizaciones.

scipy: Utilizada para realizar pruebas estadísticas, como la prueba de chi-cuadrado.

numpy: Librería para operaciones matemáticas y manipulación de matrices.

itertools: Utilizada para realizar combinaciones de variables categóricas.

sklearn: Biblioteca de aprendizaje automático en Python.

Preprocesamiento y Transformación de Datos
sklearn.preprocessing.FunctionTransformer: Permite aplicar funciones específicas en un pipeline de scikit-learn.

sklearn.impute.SimpleImputer: Utilizada para la imputación de valores nulos en los datos.

pandas.api.types.is_string_dtype: Verifica si un tipo de columna es de tipo cadena en pandas.

re: Librería para expresiones regulares, utilizada para manipulación de cadenas.

Pipelines y Transformadores
sklearn.compose.ColumnTransformer: Para aplicar diferentes transformaciones a diferentes columnas del conjunto de datos.

sklearn.preprocessing.MinMaxScaler: Escala características numéricas al rango [0, 1].

sklearn.preprocessing.PowerTransformer: Utilizada para transformar variables para que sigan una distribución normal o parecida a la normal.

sklearn.pipeline.Pipeline: Estructura que permite encadenar múltiples pasos en el proceso de análisis.

Análisis de Clusters y Detección de Anomalías
sklearn.decomposition.PCA: Análisis de componentes principales, utilizado para la reducción de dimensionalidad.

sklearn.cluster.KMeans: Algoritmo de agrupamiento KMeans.

sklearn.preprocessing.LabelEncoder: Codificación de etiquetas para variables categóricas.

sklearn.ensemble.IsolationForest: Algoritmo para la detección de anomalías basado en bosques aislantes.

sklearn.svm.OneClassSVM: SVM para la detección de anomalías.

Visualización y Gráficos
matplotlib.pyplot y seaborn: Utilizados para crear visualizaciones y gráficos informativos.
Copia de Archivos y Directorios
shutil: Usada para operaciones de copia de archivos y directorios.
Asegúrese de instalar estas librerías antes de ejecutar cualquier script o notebook en este repositorio. Puede instalarlas utilizando pip install -r requirements.txt y creando un entorno virtual para su proyecto.
