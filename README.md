# Proyecto final IA
Proyecto final de IA, en el cual se utilizan métodos de machine learning para resolver un problema. En este caso el problema a resolver era clasificar la clase de automovil dependiendo de ciertas características de cada uno de los automoviles. Se planteo una solución supervisada de tipo clasificatoria.

Se aplicó el método de clasificación KNN después de haber normalizado y haber optimizado las caracteristicas de los datos. La comprobación del resultado de la predicción se realizó mediante la matriz de conflicto, teniendo en cuenta el accuracy, el f1 score y el MCC score. 

Finalmente se explica el método de grid search el cual fue utilizado para optimizar los hiperparametros del método, que en este caso fue la metrica, el peso, el número de vecinos cercanos y el algoritmo. De igual forma se explica el resultado obtenido por cross-validación.

Finalmente se concluyó que el método de KNN no es el más efectivo para realizar una clasificación de datos, pero si es un método muy rápido, ayuda a tener una idea de un posible resultado sin necesidad de un alto nivel de procesamiento. En ese mismo sentido, se aclaró la importancia de realizar normalización, PCA y grid search en los problemas de clasificación supervisados. 

Por último los resultados obtenidos de la clasificación KNN con los datos proporcionas fueron: accuracy: 0.50, f1 score promedio: 0.48, MCC socre 0.42 y cross-validación de 0.48
