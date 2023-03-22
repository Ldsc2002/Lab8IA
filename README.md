# Mixed Model Clustering

### ¿Implementación Manual o Implementación con SKLearn?
La implementación que utiliza SKLearn creó un modelo ligeramente mejor que el algoritmo manual, con un índice Davies–Bouldin de 0.42 contra un índice de 0.43 para el algoritmo manual. Esto puede ser el resultado de una mejor implementación de K-Means por SKLearn; sin embargo, cabe destacar que se implementó PCA en la sección del modelo utilizando librerías. 

Con relación al índice Davies–Bouldin, mientras más bajo sea el índice... mejor es la separación/diferenciación entre los clusters. Cabe destacar que el valor máximo promedio de este índice es entre 2 a 3 (pero podría llegar hasta el infinito positivo), por lo cual que estos valores estén cercanos a 0 es casi que excelente. 