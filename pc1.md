> Bases de Datos 2, Prueba corta 1  
> Miguel Ku Liang - 2019061913

# 1.

## a.

El disco es la unidad más lenta de la computadora, por lo que las consultas que requieran acceder al disco son muy lentas.

## b.

Se puede utilizar como memoria principal, pero si se empieza a llenar, este realiza swapping con la memoria principal y esta acción afecta negativamente a la base de datos.

## c.

La memoria es uno de los componentes más rápidos, por lo que almacenar los índices en ella permite consultas rápidas. Si se tiene poca memoria y la cantidad de información que se tiene que procesar es bastante, puede generar context switch, reduciendo el rendimiento de la base de datos.

## d.

La caché del CPU debe ser suficiente para poder sacar provecho al CPU ya que una buena CPU con poca caché lo que ocasionaría es que el CPU necesite consultar a la memoria, por lo que se deaprovecha la caché que tiene y las consultas serían más lentas.

## e.

El CPU es el encargado de procesar las instrucciones, por lo que una buena CPU nos permite tiempos de respuesta más cortos.

# 2.

Los tiempos de respuesta son más rápidos ya que la memoria caché es más rápida que la memoria principal. Además, guarda las consultas realizadas y sus resultados para que la próxima vez que se realice la misma consulta, esta sea más rápida y así, evitar consultar a la base de datos para que otra consulta, que la pueda llegar a necesitar, pueda utilizar la base de datos.

# 3.

Un índice es un conjunto de documentos que se encuentra optimizado, en el cual cada documento es un conjunto de campos y estos campos son las llaves que contienen los datos. 

# 4.

El mapping consiste en que Elasticsearch agrega nuevos campos en el índice. Se indexan datos y Elasticsearch realiza el mapping entre los valores de los datos con los tipos de datos de Elasticsearch.