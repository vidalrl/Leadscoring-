# Leadscoring

## Vision general del proyecto
El modelo funciona para  predecir que clientes serian leads exitosos

## ¿Que se puede lograr con estos datos?
Con estos datos podemos gestionar mejor el tiempo ya que solo se contactarían clientes con altas posibilidades de comprar, ya que son problemas el que se saturen los canales del área de venta, provocando quejas internas por la mala calidad de los leads

## Calidad de datos y EDA
Se hace analisis numerico, estadistico y grafico para seguir limpiando datos y confirmar que no hay nada raro, ademas de entender las caracteristicas de los clientes

![Variables Categoricas](https://github.com/vidalrl/Leadscoring-/blob/main/imagenes/graficas%20variables%20categoricas.png)

![Variables Numericas](https://github.com/vidalrl/Leadscoring-/blob/main/imagenes/graficas%20variables%20numericas.png)

## Construccion del modelo para la clasificación 
Se construye un modelo con LogisticRegression ya que la regresión logística es un método utilizado ampliamente en el mundo comercial, utilizando Gridsearch para optimizar los hiperparametros, se utiliza ROC AUC para medir el modelo con un valor de 0.847

## Pipeline
En la creacion del pipeline se hace un transform para todo lo de pandas y calidad de datos, se aplica one hot encoder a las variables categoricas y minmaxscaler a las variables numericas
