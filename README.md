# Desafío de programación: Python para ciencia de datos
Este es el repositorio del curso de LinkedIn Learning `Desafío de programación: Python para ciencia de datos`. El curso completo está disponible en [LinkedIn Learning][lil-course-url].

![COURSENAME][lil-thumbnail-url] 

## Instrucciones
Dentro de este repositorio contiene las respuestas del curso "Desafío de Programación: Python para Ciencia de Datos" de LinkedIn Learning. Aquí encontrarás mis soluciones de los ejercicios planteados en el curso en los diferentes modulos, diseñados para fortalecer tus habilidades en Python y ciencia de datos.

**Part 1: Limpieza de Datos**

| Ejercicio                                  | Descripción                                                                  |
|--------------------------------------------|------------------------------------------------------------------------------|
| [1. Valores nulos](/My%20Solutions/Part%201%20Limpieza%20de%20Datos/Solution%20SRTM%2001_01.ipynb)   | Hay columnas dentro del dataframe que tienen valores NaN o None. Tu tarea es calcular el número de valores faltantes para cada columna.|
| [2. Eliminación de columnas](/My%20Solutions/Part%201%20Limpieza%20de%20Datos/Solution%20SRTM%2001_02.ipynb)  | Identifique la columna que tiene mayor número de valores nulos y eliminar dicha columna de nuestro dataframe.|
| [3. Eliminación de filas](/My%20Solutions/Part%201%20Limpieza%20de%20Datos/Solution%20SRTM%2001_03.ipynb) | Encuentre y elimine las filas que contengan valores nulos dentro de nuestro dataframe. |
| [4. Detección de datos duplicados](/My%20Solutions/Part%201%20Limpieza%20de%20Datos/Solution%20SRTM%2001_04.ipynb)  | Averiguar si el dataframe contiene filas duplicadas.       |
| [5. Eliminación de datos duplicados](/My%20Solutions/Part%201%20Limpieza%20de%20Datos/Solution%20SRTM%2001_05.ipynb)  | Eliminar duplicaciones en el dataframe ya que podrían afectar los resultados de nuestros futuros análisis.   |
| [6. Reemplazar datos faltantes (Imputación)](/My%20Solutions/Part%201%20Limpieza%20de%20Datos/Solution%20SRTM%2001_06.ipynb)   | Hacer uso de la técnica de imputación para reemplazar los valores faltanrtes con valores sensibles. Llenar los datos faltantes de la columna de edad con la media de edad.             |
| [7. Reemplazar datos faltantes (Imputación de regresión)](/My%20Solutions/Part%201%20Limpieza%20de%20Datos/Solution%20SRTM%2001_07.ipynb)  | Utilizar la imputación de regresión para la columna de edad denuestro dataframe, la cual contiene valores vacíos.   |

**Part 2: Procedimiento y Análisis**

| Ejercicio                                  | Descripción                                                                  |
|--------------------------------------------|------------------------------------------------------------------------------|
| [1. Correlación entre dos variables](/My%20Solutions/Part%202%20Procedimiento%20y%20análisis/Solution%20SRTM%2002_01.ipynb)   | Averiguar si existe una relación entre los años de experiencia laboral y el salario, utilizando Python y la librería de Pandas|
| [2. Calcular la media (promedio) para cada columna](/My%20Solutions/Part%202%20Procedimiento%20y%20análisis/Solution%20SRTM%2002_02.ipynb)  | Obtener el promedio de cada una de las columnas de nuestro dataframe, utilizando Python y la librería de Pandas.|
| [3. Obtener el mínimo, máximo, desviación estándar y varianza de un dataframe](/My%20Solutions/Part%202%20Procedimiento%20y%20análisis/Solution%20SRTM%2002_03.ipynb) | Encontrar el mínimo, el máximo, la varianza y la desviación estándar del dataframe que contine información de temperaturas. |
| [4. Normalizar las columnas de un dataframe](/My%20Solutions/Part%202%20Procedimiento%20y%20análisis/Solution%20SRTM%2002_04.ipynb)  | Aplicar una técnica de normalización en las columnas del dataframe.       |
| [5. Agregar un registro a un dataframe](/My%20Solutions/Part%202%20Procedimiento%20y%20análisis/Solution%20SRTM%2002_05.ipynb)  | Agregar una nueva fila a nuestro dataframe.   |
| [6. Eliminar encabezados, convertir los datos a flotantes](/My%20Solutions/Part%202%20Procedimiento%20y%20análisis/Solution%20SRTM%2002_06.ipynb)   | Primero, eliminar el encabezado o la primera fila del arreglo. Segundo, convertir el tipo dato e imprimir el resultado.             |
| [7. Extraer los nombres de las columnas que sean de tipo numérico](/My%20Solutions/Part%202%20Procedimiento%20y%20análisis/Solution%20SRTM%2002_07.ipynb)  | Extraer solamente aquellas columnas que sean de tipo float o int(flotantes o integers).   |
| [8. Extraiga filas que cumplan con un criterio](/My%20Solutions/Part%202%20Procedimiento%20y%20análisis/Solution%20SRTM%2002_08.ipynb)  | Extraer las filas de donde el CO2(la columna con índice 4) sea mayor que 204. E imprimir el resultado.   |
| [9. Extraer los registros más altos](/My%20Solutions/Part%202%20Procedimiento%20y%20análisis/Solution%20SRTM%2002_09.ipynb)  | Extraer las primeras 10 filas que tengan el valor más alto en columna con índice 4. El resultado debe serordenado de mayor a menor.   |
| [10. Cambiar el orden de las columnas en un dataframe](/My%20Solutions/Part%202%20Procedimiento%20y%20análisis/Solution%20SRTM%2002_10.ipynb)  | Extraer solamente aquellas columnas que sean de tipo float o int(flotantes o integers).   |

**Part 3: Técnicas de Agrupamiento**

| Ejercicio                                  | Descripción                                                                  |
|--------------------------------------------|------------------------------------------------------------------------------|
| [1. Agrupación Mean-Shift](/My%20Solutions/Part%203%20Técnicas%20de%20agrupamiento/Solution%20SRTM%2003_01.ipynb)   | Encontrar los clústers y graficarlos en 3D.|
| [2. Agrupamiento de K-means](/My%20Solutions/Part%203%20Técnicas%20de%20agrupamiento/Solution%20SRTM%2003_02.ipynb)  | Cargar un archivo clusters.csv en el dataframe. Divide los datos en cuatro grupos utilizando k-means de scikit-learn. Haz una predicción basada en este modelo (k-means). Imprime las coordenadas del centroide de cada grupo. Grafica los resultados y los centros de las agrupaciones determinados por el estimador de k-means.|
| [3. Agrupación jerárquica](/My%20Solutions/Part%203%20Técnicas%20de%20agrupamiento/Solution%20SRTM%2003_03.ipynb) | Crea un dendrograma para decir el número de clústeres. Crea un modelo de agrupamiento jerárquico aglomerativo de scikit-learn, con la cantidad de clústeres que encontró en el punto 1. Encontrar las etiquetas de los puntos. Graficar los grupos. |
| [4. Agrupamiento DBSCAN](/My%20Solutions/Part%203%20Técnicas%20de%20agrupamiento/Solution%20SRTM%2003_04.ipynb)  | Mostrar los grupos que se forman a partir de los datos que se nos han dado.       |

**Part 4: Modelos de Aprendizaje Automático(Machine Learning)**

| Ejercicio                                  | Descripción                                                                  |
|--------------------------------------------|------------------------------------------------------------------------------|
| [1. Regresión Lineal](/My%20Solutions/Part%204%20Modelos%20de%20Aprendizaje%20Automático%20(Machine%20Learning)/Solution%20SRTM%2004_01.ipynb)   | Encontrar la relación entre las variables experiencia y salario, utilizando el dataframe proporcionado.|
| [2. Regresión Lineal Múltiple](/My%20Solutions/Part%204%20Modelos%20de%20Aprendizaje%20Automático%20(Machine%20Learning)/Solution%20SRTM%2004_02.ipynb)  | Predecir el dióxido de carbono que emite un automóvil a partir de su longitud, anchura y altura.|
| [3. Regresión Logística](/My%20Solutions/Part%202%20Procedimiento%20y%20análisis/Solution%20SRTM%2002_03.ipynb) | Usar la regresión logística básica para predecir si un estudiante pasará o no un examen en función de las horas que ha estudiado. |
| [4. Arboles de decisión (Decision Tree Classifier)](/My%20Solutions/Part%204%20Modelos%20de%20Aprendizaje%20Automático%20(Machine%20Learning)/Solution%20SRTM%2004_04.ipynb)  | Usar el 70% de los datos para el entrenamiento de un modelo y el otro 30% de los datos para probarlo. Hacer uso de la función train_test_split() de scikit-learn. Con la clase DecisionTreeClassifier crear un modelo de clasificación. Entrenar el modelo con el conjunto de datos de entrenamiento.|
| [5. Bosques aleatorio Clasificación (Random forests)](/My%20Solutions/Part%204%20Modelos%20de%20Aprendizaje%20Automático%20(Machine%20Learning)/Solution%20SRTM%2004_05.ipynb)  | Crear un modelo de clasificación usando RandomForestClassifier de scikit-learn, establecer random_state en 42. Entrenar el modelo con el conjunto de datos de entrenamiento. Imprimir la precisión del modelo. Realizar predicciones con los datos de prueba. Graficar la matriz de confusión.|
| [6. Detección de valores atípicos (Local Outlier Factor)](/My%20Solutions/Part%204%20Modelos%20de%20Aprendizaje%20Automático%20(Machine%20Learning)/Solution%20SRTM%2004_06.ipynb)   | Usar la clase LocalOutlierFactor de scikit-learn para analizar valores atípicos en el conjunto de datos dados. Crear una nueva columna en el DataFrame llamada 'local_outlier'. En la columna 'local_outlier', guardar el resultado de la predicción y determinar si cada muestra es normal o atípica (1 normal, -1 atípico). Mostrar el toal de valores atípicos en este conjunto de datos.|
| [7. Bosques de aislamiento (Isolation Forest)](/My%20Solutions/Part%204%20Modelos%20de%20Aprendizaje%20Automático%20(Machine%20Learning)/Solution%20SRTM%2004_07.ipynb)  | Detectar aquellos salarios que sean atípicos.|
| [8. Aumento de gradiente (Gradient Boosting)](/My%20Solutions/Part%204%20Modelos%20de%20Aprendizaje%20Automático%20(Machine%20Learning)/Solution%20SRTM%2004_08.ipynb)  | Definir y ajustar modelo usado GradientBoostingRegressor de la librería sklearn. Evaluar el modelo con los datos de prueba. Imprimir el puntaje de R^2.   |
| [9. Bayesiano ingenuo multinomial (MultinomialNB)](/My%20Solutions/Part%204%20Modelos%20de%20Aprendizaje%20Automático%20(Machine%20Learning)/Solution%20SRTM%2004_09.ipynb)  | Usar la columna de asunto como variable de destino. Usar la función train_test_split() con 20% de datos para pruebas o validación. Utilizar la clase CountVectorizer para convertir la columna detalle en un vector de números. Guardar estos datos en una variable que será el set de datos para entrenamiento.|

## Creditos

**Lincy González Rojas**

Echa un vistazo a mis otros cursos en [LinkedIn Learning](https://www.linkedin.com/learning/instructors/lincy-gonzalez-rojas).

[0]: # (Replace these placeholder URLs with actual course URLs)
[lil-course-url]: https://www.linkedin.com/learning/desafio-de-programacion-python-para-ciencia-de-datos/desafiate-con-python
[lil-thumbnail-url]: https://media.licdn.com/dms/image/C4E0DAQGIhvEbEaAO8g/learning-public-crop_675_1200/0/1677586020672?e=2147483647&v=beta&t=m9NxnqJZRD7V9bZACeD9K_hrkQVddkSpLflpifD-dzI
