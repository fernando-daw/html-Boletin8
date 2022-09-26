**Boletin 1- Soluciones**

a) 

<?xml version="1.0" ?>

 <nombre>Richal</nombre> 

b)

<?xml version="1.0" ?>

<datos>

 <nombre>Richal</nombre>

 <email>richal@ejemplo.com</email>

</datos>

c)

<?xml version="1.0" encoding="UTF-7" ?>

 <album>

 <autor>SABINA Y CIA Nos sobran los motivos</autor>

 <titulo>Joaquín Sabina</titulo>

 <formato>MP3</formato>

 <localizacion>Varios CD5 </localizacion>

 </album>

2) Estructura en arbol

![Captura de pantalla 2022-09-20 181024](C:\Users\nando\OneDrive\Desktop\DAW\XMLS\Captura de pantalla 2022-09-20 181024.jpg)

Codigo en XML:

<?xml version="1.0" encoding="UTF-8"?>

<cartadesayunos>

​        <desayuno>

​                  <nombre>Gofres Belgas</nombre>

​                  <precio>5.95</precio>

​                  <descripcion>Dos de nuestros famosos Gofres belgas con abundante sirope</descripcion>

​                  <calorias>650</calorias>

​        </desayuno>

​        <desayuno>

​                  <nombre>Gobres Belgas con fresas</nombre>

​                  <precio>7.95</precio>

​                  <descripcion>Ligeros gofres belgas cubiertos de fresas y nata montada</descripcion>

​                  <calorias>900</calorias>

​        </desayuno>

​        <desayuno>

​                  <nombre>Gofres Belgas con frutas del bosque</nombre>

​                  <precio>8.95</precio>

​                  <descripcion>Ligeros gofres belgas cubiertos con frutas del bosque y nata montada</descripcion>

​                  <calorias>900</calorias>

​        </desayuno>

​        <desayuno>

​                  <nombre>Tostada Francesa</nombre>

​                  <precio>4.50</precio>

​                  <descripcion>Dos gruesas rebanadas de nuestro pan francés</descripcion>

​                  <calorias>600</calorias>

​        </desayuno>

​        <desayuno>

​                  <nombre>Desayuno de la casa</nombre>

​                  <precio>6.95</precio>

​                  <descripcion>Dos huevos, bacon o salchicha, tostada y patatas fritas</descripcion>

​                  <calorias>950</calorias>

​        </desayuno>

</cartadesayunos>

3)

 a)  <desayuno>

​                  <nombre>Gofres Belgas</nombre>

​                  <precio>5.95</precio>

</desayuno>

​                  <descripcion>Dos de nuestros famosos Gofres belgas con abundante sirope</descripcion>

​                  <calorias>650</calorias>

**la etiqueta desayuno estaría mal colocada, tendria que ir al final del codigo**

b) 

<nombre>Gofres Belgas</nombre>

<Nombre>Gofres Austriacos</Nombre>

​            **Son dos etiquetas distintas**

c) <libro>

​     <capitulo>

​          <titulo>Introducción</titulo>

​     </capitulo>

<libro>

d) <lista>

​     <AAA></AAA>

​     <BBB></BBB>

</lista>

e)<Un.nombre.separado.con.puntos/>

f)  <varios primero="1" segundo = '2' tercero= "3"/>

g) <texto>Los caracteres < y & no pueden escribirse  si no es como comienzo de marcas</texto>

**este ejemplo estaría mal ejecutado, a continuacion la solucion**

```
<texto>Los caracteres &lt; y &amp; no pueden escribirse
  si no es como comienzo de marcas</texto>
```

h) <texto>También pueden sustituirse los caracteres >, ", ' </texto>

**este ejemplo estaría mal ejecutado, a continuacion la solucion**

<texto>También pueden sustituirse los caracteres   &gt;(&gt)," (&quot), y &apos; (&apos)  </texto>

****

i)<ejemplo>

<!-- esto es un comentario en XML -->

</ejemplo>



​    

