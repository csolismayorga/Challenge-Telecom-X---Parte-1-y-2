1. El documento Telecom-X_Total.ipynb integra la parte 1 y la parte 2 del challenge Telecom-X, lo cual permite contar con la perspectiva total de la solución brindada al challenge.

2. Con respecto a la parte 2 el documento está estructurado con las siguentes etapas de procesamiento de datos:

    * Depuración inicial de datos
    * Análisis de correlación de variables
    * Transformación de datos
    * Creación de modelos
    * Generación de métricas y matriz de confusión
    * Comparación de modelos
    * Conclusiones
      
3. La depuración inicial tiene como objetivo eliminar columnas irrelevantes que no aporta valor al modelo o que incluso puede afectarlo negativamente, se eliminan filas con campos numéricos que no tengan valores consistentes con su tipo de dato y depura la información contenida en columnas que podrían generar multicolinearidad.

4. El análisis de correlación de variables permite evaluar la correlación de variables numéricas mostrando un gráfico ilustrativo de calor en el cual se representan de forma más clara la intensidad de la correlación entre las diferentes variables, así como también se brinda una interpretación de las mismas.

5. La transformación de datos se realiza con el fin preparar los datos para ser introducidos a los dos modelos de clasificación usados que son el KNN y DecisionTreeClassifier, aplicando para ellos pasos tales como:
      
    *  Separación de la variable respuesta de las variables explicativas
    * Transformación de variables explicativas y de respuesta

6. La creación y entrenamiento de los modelos considera la preparación del detaset para dividirlo en datos de entrenamiento y datos de prueba a los cuales se les aplica un proceso de normalización de variables explicativas numéricas antes de someterlo a los modelos sobre los cuales este factor tiene mayor incidencia como lo es el Knn.

7. La generación de métricas, matriz de confusión y niveles de importancia de las variables según el modelo serán la base el análisis comparativo de los modelos.

8. En la comparación de modelos se responde preguntas tales como:

    * ¿Cual modelo tuvo el mejor desempeño basado en las métricas generadas a partir de las matrices de confusión?
    * ¿Algún modelo presentó overfitting o underfitting? 

9. Finalmente se generan conclusiones relacionadas con:
    * Conclusiones basadas en el análsis de la importancia de las variables según el modelo  DecisionTreeClassifier.
    * Conclusiones basadas en el análisis de la importania de las variables según el modelo Knn
    * Estrategia para evitar el abandono de clientes basada en el modelo  DecisionTreeClassifier.
    * Estrategia para evitar el abandono de clientes basada en el modelo  KNN.
