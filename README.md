# PORTFOLIO-GBD-MARZO 

### Indice
* [Resumen](#resumen)  
* [Reflexiones personales](#reflexiones)  
* [Ejercicios Significativos](#ejersign)  
* [Ejercicios de invencion propia](#ejerpropios)  
* [Conclusión](#conclusiones) 


## Resumen
En los temas 6 y 7 estuvimos viendo lo que es considerado como la parte mas importante junto con la creacion de tablas,
esa parte son las **consultas**.
Las consultas es una **tecnica que nos permite visualizar el contenido de una o varias tablas con solo unas lineas**, incluso 
podemos darle formato a esas consultas. En el tema 6 visualizamos un la sintaxis básica de las consultas con un 
`select nomColumna from nomTabla`. Si ponemos `select * from personas` nos sacará todas las columnas e información de la tabla
personas, asi que el asterisco es una de las cosas muy importantes de saber.

Posteriormente, hemos visto los alias que podemos poner a las columnas, se suele poner `as` para establecer el alias pero si lo dejamos sin poner
nos funcionara igualmente. Además de los alias tambien observamos los **operadores condiciones** `<,>,!=,>=,<=`, operadores lógicos `and,or y not`,
la **concatenación de columnas** en una con las tuberias `|| ||`, pero sobre todo la **cláusula que nos permite establecer condiciones 
respecto al select es la llamada `where`**, con ella podemos poner una condición con todos los operadores que hemos visto anteriormente e incluso
muchas cosas como funciones *(between, in, like ...)*. Para ir terminando sobre la sintaxis basica tambien hay que recalcar la parte en la que podemos 
ordenar con la cláusula *`order by nomColumna (desc|asc)`*.

Las **funciones** es otra cosa que hemos visto y que son importantes, **con ellas podemos redondear números, extraer letras de los datos
de una columna, sacar las fechas y darlas formato, etc.** Oracle nos permite convertir textos en números y viceversa, y textos a fechas
y viceversa, para ello se utilizan `to_char(),to_number() y to_date()`. En la conversión de fechas a textos existen una serie de símbolos
que se utilizan para convertir esa fecha al formato que queramos, lo mismo ocurre con al convertir números en texto. Pero sobre todo lo
mas caracteristico de este tema 6 son las expresiones regulares. Algunas de estas están basadas en otras funciones que solemos utilizar. Las 
expresiones regulares sirven practicamente para realizar consultas de una manera mas sencilla que con funciones normales, es decir, con la funcion
`substr` se nos puede complicar hacer esa consulta y por ello se utiliza `regexp_substr`. Antes de terminar tambien se nos permite realizar
condiciones en Oracle y para ello se utilizan `case` y `decode`,la primera se escoge para hacer condiciones mas complejas que con la segunda
se nos hacen "cuesta arriba".

El tema 7 es mas corto que el 6 pero es igual de importante ya que entran en juego las consultas a varias tablas, para ello se utiliza
`join` sin embargo, esta clausula dispone de 3 variantes `join using`,`join on`,`natural join`. La primera y la tercera sirven para cruzar tablas
pero solo si la clave primaria de una tabla y la clave foranea de la otra tabla se llaman igual, en cambio el `join on` tambien se puede usar para la
misma funcion que las anteriores, pero ademas para cuando la clave primaria de una tabla y la clave foranea de la otra tabla no se llamen igual.

Lo ultimo que vimos son las cláusulas `group by`(sirve para agrupar por cada columna) `having` (similar al where pero para hacer condiciones con
totales) y  por supuesto las cláusulas totales como `sum` `avg` `count`, etc


## Reflexiones personales

Personalmente yo ya conocía el tema de las consultas de SQL y me parece algo fascinante pero a la vez complicado de aprender,
no obstante, yo creo que lo positivo que saco de todo esto es que este año he podido aprender a realizar consultas y sobre todo 
entender como funciona el enunciado y poder sacar la consulta correctamente, esto del final es la parte que más hay que practicar ya que si 
no entendemos el enunciado y tampoco sabemos de que va relacionado el propio tema vamos muy mal.
En cuanto a lo negativo me quedo con las veces que he intentado la consulta y finalmente no lo he conseguido, aunque no me salga
por lo menos lo he intentado hacer y he puesto ganas.
En resumen, este tema me ha aportado mucho a la hora de pensar y razonar y que con otras asignaturas o cosas no lo han hecho.


