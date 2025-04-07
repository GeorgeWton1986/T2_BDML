# Problem Set 2: Predicting Poverty
## Integrantes: Nicolas Jácome; Zaira García; Jorge Viáfara; Laura Rivera

# Introducción:
El presente trabajo se inspira en el reciente concurso organizado por el Banco Mundial: Pruebas Pover-T: Predecir la pobreza. Según se afirma en el concurso, "medir la pobreza es difícil, lleva tiempo y es caro". Sin embargo, mediante la construcción de modelos predictivos más precisos, es posible realizar encuestas con menos preguntas y más específicas, lo que facilita una medición rápida y económica de la eficacia de las políticas públicas y las intervenciones sociales. Cuanto más exactos sean estos modelos, mayor será la precisión con la que Se podrán orientar las intervenciones y replicar políticas exitosas, maximizando el impacto y la rentabilidad de estas estrategias.
El objetivo de este estudio es predecir la pobreza a nivel de hogar en Colombia, utilizando datos proporcionados por el Departamento Administrativo Nacional de Estadística (DANE) y la misión para el Empalme de las Series de Empleo, Pobreza y Desigualdad - MESE. Estos datos contienen información tanto a nivel de hogar como a nivel individual, permitiendo la creación de variables adicionales que pueden mejorar la capacidad predictiva del modelo. La estructura del conjunto de datos incluye cuatro archivos divididos en entrenamiento y prueba para ambos niveles de análisis.

# Contenido
El análisis se divide en diferentes partes: con la adquisición y limpieza de los datos proporcionados en el marco del concurso. La información fue integrada utilizando la variable id para vincular los datos de nivel individual con los datos de nivel de hogar, asegurando la coherencia entre ambos conjuntos. Se aplicaron métodos de imputación estadística para tratar los valores faltantes, utilizando técnicas basadas en la media, la mediana para mantener la mayor cantidad de información posible. Este estudio utilizó cinco algoritmos de clasificación —regresión lineal, regresión logística, red elástica, random forest y boosting— para predecir la pobreza en Colombia, generando predicciones distintas. El proceso inició con la selección y entrenamiento de modelos, donde el XX obtuvo la mejor puntuación pública en Kaggle. Este modelo destacó por XX

# 01_Documents
En esta carpeta se encuentra el documento necesario para desarrollar el problem set, junto con la información del DANE y de la misión para el «Empalme de las Series de Empleo, Pobreza y Desigualdad - MESE» y contiene el documento final en pdf.

# 02_Script 
En esta carpeta se incluye el archivo en R Markdown donde se desarrolla el problem set y el script en R donde se deposita únicamente el código. 

# 03_Stores 
En esta carpeta se enceuntra la base de datos ya filtrada utilizada para realizar el problem set. 

# 04_Views 
En esta carpeta se evidencian los gráficos obtenidos del código en formato JPG y las tablas con algunos de los resultados
