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
Las consultas es una tecnica que nos permite visualizar el contenido de una o varias tablas con solo unas lineas, incluso 
podemos darle formato a esas consultas. En el tema 6 visualizamos un la sintaxis basica de las consultas con un 
`select nomColumna from nomTabla`. Si ponemos `select * from personas` nos sacara todas las columnas e informacion de la tabla
personas, asi que el asterisco es una de las cosas muy importantes de saber.

Posteriormente vimos los alias que podemos poner a las columnas, se suele poner `as` para establecer el alias pero si lo dejamos sin poner
nos funcionara igualmente. Ademas de los alias tabmien vimos los operadores condiciones `<,>,!=,>=,<=`, operadores logicos `and,or y not`,
la concatenacion de columnas en una con las tuberias `|| ||`, pero sobre todo la clausula que nos permite establecer condiciones 
respecto al select es la llamada `where`, con ella podemos poner una condicion con todos los operadores que hemos visto anteriormente e incluso
muchas cosas como funciones (between, in, like ...). Para ir terminando sobre la sintaxis basica tambien hay que recalcar la parte en la que podemos 
ordenar con la clausula `order by nomColumna (desc|asc)`.

Las funciones es otra cosa que hemos visto y que son importantes, con ellas podemos redondear numeros, extraer letras de los datos
de una columna, sacar las fechas y darlas formato, etc. Oracle nos permite convertir textos en numeros y viceversa, y textos a fechas
y viceversa, para ello se utilizan `to_char(),to_number() y to_date()`. En la conversion de fechas a textos exiten una serie de simbolos
que se utilizan para convertir esa fecha al formato que queramos, lo mismo ocurre con al convertir numeros en texto. Pero sobre todo lo
mas caracteristico de este tema 6 son las expresiones regulares. Algunas de estas estan basadas en otras funciones que solemos utilizar. Las 
expresiones regulares sirven practicamente para realizar consultas de una manera mas sencilla que con funciones normales, es decir, con la funcion
`substr` se nos puede complicar hacer esa consulta y por ello se utiliza `regexp_substr`. Antes de terminar tambien se nos permite realizar
condiciones en Oracle y para ello se utilizan `case` y `decode`,la primera se escoge para hacer condiciones mas complejas que con la segunda
se nos hacen "cuesta arriba".

El tema 7 es mas corto que el 6 pero es igual de importante ya que entran en juego las consultas a varias tablas, para ello se utiliza
`join` sin embargo, esta clausula dispone de 3 variantes `join using`,`join on`,`natural join`. La primera y la tercera sirven para cruzar tablas
pero solo si la clave primaria de una tabla y la clave foranea de la otra tabla se llaman igual, en cambio el `join on` tambien se puede usar para la
misma funcion que las anteriores, pero ademas para cuando la clave primaria de una tabla y la clave foranea de la otra tabla no se llamen igual.

Lo siuie



