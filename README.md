# Introducción al analisis estadistico de datos (EDA)

## Introducción

El analisis estadistico de experimentos empieza con un analisis exploratorio de datos (EDA). El **EDA (Exploratory Data Analysis)** consiste en un conjuto de tecnicas de visualización y sintesis (resumir) de datos para tratar de responder a una pregunta clave: **¿Que pueden decirnos los datos?**. 

El EDA es bastante util para cosas como:
* Detectar errores.
* Verificar supocisiones.
* Determinar relaciones entre variables.
* Resumir y presentar informacion.

El EDA fue planteado por Jonh W. Tukey introduciendo tecnicas estadisticas (mean, median, quantiles, etc.) y diagramas sencillos (boxplots, scatterplots, etc).

## Tipos de datos

Los datos proceden de muchas fuentes (medicion de sensores, eventos, texto, imagenes, videos, informacion de bases de datos, etc). La mayoria de estos datos cuando se toman de la fuente (**raw data**), no se encuentran procesados por lo que el primer objetivo consistira en procesar dichos datos para presentarlos de una manera apropiada (**structured data**) para su posterior analisis. Una de la formas mas usuales en las que se presentan los tipos de datos es mediante tablas con filas y columnas.

Inicialmente, es necesario conocer el tipo de datos a tratar para lo cual existen dos grandes grupos:
* **Numericos**: Datos que se expresan en una escala numerica.
* **Categóricos**: Datos que solo pueden adoptar un numero especifico de valores que representan un conjunto de categorias posibles.

A su vez, cada uno de estos grupos se subdivide en subgrupos tal y como se describe en la siguiente tabla:
* **Tipos numericos**:
  
  |Tipo|Definición|Sinonimo|Ejemplos|
  |---|---|---|---|
  |**Discretos**|Datos que se expresan en una escala numerica|entero, contable|Recuento de veces que ocurre un evento, edad, numero de clicks, numero de estudiantes, etc|
  |**Continuos**|Datos que tomar cualquier valor dentro de un intervalo|intervalo, real|Temperatura, estatura, velocidad del viento, indice de masa corporal, etc|
 

* **Categoricos**:

  |Tipo|Definición|Sinonimo|Ejemplos|
  |---|---|---|---|
  |**Nominales**|Datos cuyos valores se asocian a categorias. Es importante decir que dentro de este tipo existe un caso especial que son los datos **binarios** los cuales se caracterizan por que solo pueden tomar dos posibles valores|entero, contable|Departamentos (Antioquia, Choco, Amazonas, etc.), ciudad (Medellin, Bogota,etc.), Tipos de pantallas TV (plasma, LCD, led, etc), sexo, si/no, Falso/Verdadero, Encendido/Apagado|
  |**Ordinales**|Datos categoricos que tienen un orden explícito|factor ordenado|Nivel académico, natisfacción de un servicio, estracto de los servicios publicos, etc|

Conocer el tipo de datos es importante por que es la manera como se le indica al software como debe procesarlos.

## Estructuras de datos

## Datos rectangulares

Los tipos de **datos rectangulares** (**rectangular data**) es la representación (estructura basica) de los datos para los modelos estadisticos. El termino general asociado a los datos rectangulares es una matriz bidimensional cuyas filas se asocian a los registros y sus columnas se asocian a las caracteristicas de cada registro. En aplicaciones como **R** y **Python**, el **data frame** (**Marco de datos**), es el formato específico para los **rectangular data**. 

La siguiente tabla resume los terminos claves asociados los datos rectangulares:

|Termino|Definición|Sinonimo|
|---|---|---|
|**Data Frame (Marco de dato)** |Son la estructura basica de datos (tablas) para los modelos estadisticos y de aprendizaje automatico||
|**Feature (Caracteristica)**|Columna de una tabla|attribute, input, predictor, variable|
|**Outcome (Resultado)**|Son el resultado de realizar el pronostico sobre los datos. A veces, las catacteristicas (features) se utilizan para pronosticar el resultado de un estudio.|dependent variable, response, target, output|
|**Records**|Fila dentro de una tabla|case, example, instance, observation, pattern, sample|

## Datos no rectangulares

Existen otro tipo de estructuras de datos mas complejar y variadas que las estructuras de datos rectangulares. Un ejemplo de estas estructuras son las series de tiempo y los datos espaciales por citar algunos.

La representación de datos asociados a este tipo e el **object**.


## Librerias Python para ciencia de datos

A continuación se muestran algunas librerias comunmente usadas en python para ciencia de datos.

### Toolboxes y librerias

|Libreria|URL|
|---|---|
|NumPy|[http://www.numpy.org/](http://www.numpy.org/)|
|SciPy|[https://www.scipy.org/scipylib](https://www.scipy.org/scipylib)|
|Pandas|[http://pandas.pydata.org/](http://pandas.pydata.org/)|
|SciKit-Learn|[http://scikit-learn.org/](http://scikit-learn.org/)|

### Librerias para visualización

|Libreria|URL|
|---|---|
|Matplotlib|[https://matplotlib.org/](https://matplotlib.org/)|
|Seaborn|[https://seaborn.pydata.org/](https://seaborn.pydata.org/)|


## Referencias

1. [The Future of Data Analysis](http://www.mat.ufrgs.br/~viali/estatistica/mat2274/material/textos/2237638.pdf)
2. [Experimental Design for Behavioral and Social Sciences](https://www.stat.cmu.edu/~hseltman/309/)
3. [Exploratory Data Analysis](https://www.stat.cmu.edu/~hseltman/309/Book/chapter4.pdf)
4. [Random Services](https://www.randomservices.org/)
5. [Rice Virtual Lab in Statistics](https://onlinestatbook.com/rvls.html)
6. [StatSci.org](http://www.statsci.org/)
7. [Introduction to Data Science](https://bcourses.berkeley.edu/courses/1267848)


