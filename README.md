# Introducción al analisis estadistico de datos

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
  |Discretos|Datos que se expresan en una escala numerica|entero, contable|Recuento de veces que ocurre un evento, edad, numero de clicks, numero de estudiantes, etc|
  |Continuos|Datos que tomar cualquier valor dentro de un intervalo|intervalo, real|Temperatura, estatura, velocidad del viento, indice de masa corporal, etc|
 

* **Categoricos**:

  |Tipo|Definición|Sinonimo|Ejemplos|
  |---|---|---|---|
  |Nominal|Datos cuyos valores se asocian a categorias. Es importante decir que dentro de este tipo existe un caso especial que son los datos **binarios** los cuales se caracterizan por que solo pueden tomar dos posibles valores|entero, contable|Departamentos (Antioquia, Choco, Amazonas, etc.), ciudad (Medellin, Bogota,etc.), Tipos de pantallas TV (plasma, LCD, led, etc), sexo, si/no, Falso/Verdadero, Encendido/Apagado|
  |Ordinales|Datos categoricos que tienen un orden explícito|factor ordenado|Nivel académico, natisfacción de un servicio, estracto de los servicios publicos, etc|

## Referencias

1. [The Future of Data Analysis](http://www.mat.ufrgs.br/~viali/estatistica/mat2274/material/textos/2237638.pdf)
2. [Experimental Design for Behavioral and Social Sciences](https://www.stat.cmu.edu/~hseltman/309/)
3. [Exploratory Data Analysis](https://www.stat.cmu.edu/~hseltman/309/Book/chapter4.pdf)
4. [Random Services](https://www.randomservices.org/)
5. [Rice Virtual Lab in Statistics](https://onlinestatbook.com/rvls.html)
6. [StatSci.org](http://www.statsci.org/)


