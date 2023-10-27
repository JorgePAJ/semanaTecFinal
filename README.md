# TC1002S_semanaTec
Semana Tec TC1002S: Herramientas computacionales

## Conclusiones para la Actividad 2 - Obtención de estadisticas descriptivas
```txt
El archivo cuenta con 244 entradas y cuenta con 18 diferentes variables.
Las calorias cuentan con una media de 193, pero sus rangos estan muy disperos dentro de su respectivo, dado por el valor obtenido de su desviacion.
Las grasas cuentan con una media de 1.6 y su desviacion nos muestra que los valores son mas cercanos entre si que los valores de calorias.
Las grasas saturadas cuentan con una media de 0.03 y tiene la desviacion estandar mas baja entre todas las variables.
Proteina y sodio tienen un promedio de 7 y 8 respectivamente, y unos valores parecidos en desviacion, pero no tan grandes como el valor de calorias, dando a entender que estos valores no estan tan separados los unos de los otros.
Cholesterol y azucares tiene una media y desviacion similares, pero en el caso de esta ultima es mayor a las variables anteriores.
Fibra cuenta con un promedio de 0.8 y tiene la segun desviacion mas pequena entre todas las variables.
Finalmente, de las categorias se puede saber que la categoria con mas entradas son las bebidas expresso, pero en conjunto los frappes ganan en cantidad
```

## Conclusiones para la Actividad 3 - Mapas de color y boxplots
```txt
Conclusiones:

¿Hay alguna variable que no aporta información?
No. Todas las variables son importantes ya que indica la información nutrimental de las bebidas principales de Starbucks. Todos estos son importantes ya que afectan directamente en nuestra salud y para poder tomar una mejor decisión de que consumir es importante conocer la información que nos puede proporcionar este documento.

Si tuvieran que eliminar variables, ¿cuáles quitarías y por qué?
Quitariamos la de beverage_prep ya que este dato indica el tamaño o la leche que ellos están tomando en cuenta para realizar el cálculo de la información nutrimental pero esto puede cambiar según la decisión del cliente, lo que quiere decir que esto no es inalterable a la hora de servir la bebida.

¿Existen variables que tengan datos extraños?
Si, en las gráfica de cuantiles se pueden ver datos que van por afuera del En la gráficas realizadas podemos observar que las tazo tea drinks tiene valores atípicos en todos los parámetros analizados. Esto podría significar que sus ingredientes pueden ser procesados, por lo cual son más dañinos a la salud.
Otras gráficas que muestran grupos con varios valores atípicos son la de fibras dietéticas, trans fat y sodio.
Podemos observar que el grupo de coffee es el que tiene menos valores atípicos, lo que podría significar que es menos dañino a la salud.

Si comparan las variables, ¿todas están en rangos similares? ¿Crees que esto afecte?
En las gráficas de dispersión podemos observar que con existe una relación lineal positiva con algunas variables como en el caso de calories y sugar o cholesterol y sugar.
En otras gráficas los puntos no aumenta de forma diagonal positiva pero si están concentrados cerca los unos a los otro de esa misma categoría pero sin mostrar un patrón claro como lo es en el caso de protein y satured fats.
Si las variables tienen diferentes escalas o rangos de valores, esto puede afectar la interpretación de los gráficos de dispersión y la identificación de patrones.

¿Puedes encontrar grupos qué se parezcan? ¿Qué grupos son estos?
Sí, es posible identificar grupos que muestran similitudes en los gráficos de dispersión según la proximidad de los puntos y la distribución de los datos. En el caso de los datos proporcionados, se observa una similitud entre los grupos de frapuchinos, blended coffee y blended creme en la relación entre proteínas y carbohidratos totales. Además, en la relación entre colesterol y azúcares, se observa una similitud general entre todos los grupos, lo que indica una posible relación lineal similar entre estos parámetros en todos los grupos.
```

## Conclusiones para la Actividad 4 - Patrones con K-means
```txt
¿Qué para qué variables fue más conveniente usar: modelo linea o polilineal? Polilineal, para todas las variables daban mejores scores

¿Crees que estos clusters puedan ser representativos de los datos? ¿Por qué? Puede que sean tipos de comida con un cierto tipo de metricas altas. Los grupos conseguidos estan disperos entre cierto rangos, que podrian ser considerados grandes. Puede que cada grupo tenga ciertas cualidades particulares.

¿Cómo obtuviste el valor de k a usar? Viendo la grafica de silueta

¿Los centros serían más representativos si usaras un valor más alto? ¿Más bajo? Seria menos representativos en cada lado, la grafica de silueta muestra que por mucho el mejor valor para k es 4

¿Qué distancia tienen los centros entre sí? ¿Hay alguno que este muy cercano a otros? En ma mayoria de los casos donde los datos son menos anomalos, los centros representan de manera muy adecuada que las distancias entre puntos no son muy diferentes.

¿Qué pasaría con los centros si tuviéramos muchos datos anómalos en el análisis de cajas y bigotes? Los centros estarian dispersos a zonas donde en principio no deberian de estar

¿Qué puedes decir de los datos basándose en los centros de los clusters y en los modelos?

Usan los colores de las graficas, los grupos 3 y 4 no son recomendables por sus altos grados de azucares y cholestorelos, mientras que el grupo 0 tal vez pudiera usar un poco mas en algunas metricas.
```
