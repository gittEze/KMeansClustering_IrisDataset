# Segmentación de flores Iris con K-Means  

En este proyecto se implementó el algoritmo **K-Means** para segmentar las observaciones del dataset **Iris**.  
Se trabajó con las variables **sepal_length, sepal_width, petal_length y petal_width**, que reflejan características de cada flor.  

Tras escalar los datos con **StandardScaler**, se evaluó el modelo con `k = 3`, ya que corresponde con la cantidad de especies presentes en el dataset.  

## Resultados  

El **Cluster 0** muestra la especie *Iris-versicolor*, donde se agruparon 39 registros. Por otro lado, el **Cluster 1** muestra en su mayoría a la especie *Iris-setosa*, con un total de 48 registros. Y, el **Cluster 2** se vinculó con la especie *Iris-virginica*, agrupando 36 registros. Estos resultados muestran que el algoritmo pudo separar de manera razonable a las especies, capturando las diferencias en sus medidas de sépalos y pétalos.  

Y tambien destacar que la segmentación **no fue 100% precisa**, ya que no todas las especies quedaron registradas de forma exclusiva en cada cluster. Algunas flores quedaron clasificadas en clusters distintos a su especie original.

## Conclusión  

La implementación de **K-Means sobre el dataset Iris** permite observar cómo este algoritmo es capaz de identificar patrones y formar grupos aunque si bien no alcanza una separación perfecta, el resultado obtenido es coherente con la estructura de datos. 

<img width="574" height="837" alt="image" src="https://github.com/user-attachments/assets/3b1547e7-7a6b-4112-94a7-26f301ffc30c" />
