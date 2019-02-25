# E8 - Ensemble Trees Overview

Write at least 300 words explaining why ensemble is a succesful strategy in machine learning.


Los métodos de ensemble combinan varios modelos de árboles de decisión para producir uno con una mejor capacidad predictiva. El principio detrás de este modelo es que un grupo de modelos débiles puede unirse para crear uno más robusto, incrementando el accuracy del modelo. El Ensemble ayuda a reducir la  varianza y el sesgo presentes naturalmente en un único modelo. Existen dos grandes técnicas de ensemble: bagging y boosting.

Bagging (o bootstrap aggregation) es la aplicación del proceso de bootstrap para árboles de  decisión. Funciona seleccionando un subset de observaciones (bootstrap o muestreo con reemplazo) y, a partir de ellas, agrupar la data de entrenamiento. Esto se repite múltiples veces y se agregan las estimaciones de todos los modelos. Cuando se trabaja con el baggin de árboles de decisión el overfitting no es un problema ya que  cada árbol por su cuenta llega  hasta el nivel más bajo del mismo. Al agruparse, el problema del overfitting desaparece. Esto quiere decir que, si se aumentan el número de árboles, el sesgo y la varianza tienden a disminuir. 

Por el contrario, boosting se  refiere a un grupo de algoritmos que utiliza promedios ponderados para convertir modelos débiles  en robustos. Lo  que hace esta técnica es que en cada corrida  del modelo le asigna un peso a cada uno de los predictores del modelo y  así busca entrar el mejor. 

En últimas, la decisión sobre qué método usar radica en la data y cuál problema tenga esta. Si la data puede sufrir de overfitting, se debería usar el modelo de bagging. Si lo que se busca es estabilidad del modelo, boosting puede proveer un mejor resultado. 

