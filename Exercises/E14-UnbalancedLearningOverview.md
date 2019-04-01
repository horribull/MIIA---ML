# E14 - Unbalanced Learning Overview

Research about the impact of unbalanced datasets in binary classification problems and the most common solutions.

https://link.springer.com/content/pdf/10.1186%2Fs40537-018-0151-6.pdf

Quiz at the beggining of the next class.

Los desbalances de los datasets pueden afectar negativamente el performance de un modelo de clasificación, incorporando un sesgo en la predicción de la clase que es mayoría (o más frecuente). Este problema se conoce como un under-over sampling problem. Partiendo que se tiene un interés especial por la clase cuyo grupo es el menos frecuente y un falso negativo es mucho más costoso que un falso positivo (por ejemplo en temas relacionados a fraude o enfermedades graves). Además, si se está trabajando en un marco de big data, este problema es aún más fuerte. Existe dos técnicas, una enfocada en la eficiencia de los datos y la otra en la de los algoritmos. En general, los métodos de random over sampling son los que muestran mejores resultados. Por el lado de los algoritmos, los resultados no son concluyentes y hay resultados conflictivos. El objetivo de este paper es hacer un estudio comparativo basado en casos reales y evaluar su impacto en el performance de los modelos.
