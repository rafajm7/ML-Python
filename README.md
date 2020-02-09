# Modelos de ML
Este repositorio trata de resolver problemas de ML usando diferentes algoritmos presentes en la librería scikit-learn de Python. Las técnicas que se cubren aquí son:

* ![Vecinos más cercanos (KNN).](KNN).
* ![Árboles de decisión](Árboles_de_decisión).
* ![Máquinas de Soporte Vectorial](SVM).
* ![Redes neuronales](Redes_Neuronales).

Por cada uno de estos algoritmos vamos a resolver tres problemas diferentes:

1. Dado un conjunto de datos pequeño, vamos a aplicar el algoritmo de manera "manual", para poder comprender completamente cómo funciona.
2. Dado el problema de clasificación del Blood Transfusion Training Center, vamos a dividir los datos en train/test para aplicar el algoritmo sobre los datos de entrenamiento y obtener la mayor precisión posible al evaluar los modelos en los datos de test.
3. Dado el problema de regresión de Energy Efficiency, vamos a seguir los mismos pasos que en el problema 2 pero usando el error cuadrático medio (MSE) como medida para obtener el error en la predicción de la variable de salida por parte de nuestro modelo.

El repositorio está dividido en diferentes carpetas (una por algoritmo), cada una de ellas teniendo su propio PDF para explicar como los 3 problemas deben resolverse y un Jupyter Notebook autoexplicativo que contiene todo el código. Los datos que se van a usar están bajo la carpeta datos/.

Para resumir, este repositorio te permite entender cómo trabajan diferentes técnicas de Machine Learning, mediante el uso de ejemplos en conjuntos de datos pequeños, para posteriormente mostrar cómo se pueden aplicar a casos de uso reales. 

### Dependencias
Para poder ejecutar este proyecto se necesita tener instalado Jupyter Notebook y las siguientes librerías de python: scikit-learn, matplotlib, pandas y numpy.
