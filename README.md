Quick-Mock-Up
=============

Front-End (HTML/CSS/Js) Framework para la creación rápida de Mock Up y en espanol.

La idea de este framework es para crear Mock up en base a wireframe de manera rápida y fácil, con la idea de poder presentársela al cliente/disenador/programador/amigo un vistazo rápido de lo que se esta hablando o intentando transmitir.

La diferencia con Bootstrap o Boilerplate es que este no es tan completo y complejo, por lo mismo, no lo recomiendo para la creación de una web compleja o muy grande, sino, como para bocetear una web (mock up).

Por ahora lo estoy probando en Chrome, Firefox, Internet Explorer 10 y 9 (En el 8 tengo problemas ahora).

Para la versión 2 será responsive basado en los ratios de Bootstrap.

La gracia es que al momento de poner los divs, le damos todas las características que queremos al div superior: si queremos que tengan un margen, un fondo, un borde, padding, etc...


COMO SE USA / How to
===========

1.- ESTRUCTURA
Achivo: core.css

Básicamente la estructura se basa en Header, Section y Footer. Junto con esto el la clase '.contenedor' quien contiene (valga la redunancia) todos los elementos como divs y botones.

Para definir el tamaño de un div solamente hay que decirle cuantas columnas habrán en la misma fila:

Ej. En este caso la columna te permite poner 3
<code>
<section>
    <div class="contenedor">
        <div class="columna_3"></div>
        <div class="columna_3"></div>
        <div class="columna_3"></div>
    </div>
</section>
</code>

Las clases son: .columna_1, .columna_2, .columna_3, .columna_4, .columna_5, .columna_6
Revisar grilla.html para ver mas ejemplos

1.1.-
Si desea agregar características a los divs solamente deben darle la clase al div 'contenedor'.
Clases:
.con_borde, .con_margen, con_padding

Ej. En este caso los divs de adentro (las columnas) tendrán un margen y un borde.
<code>
    <div class="contenedor con_margen con_borde">
        <div class="columna_3"></div>
        <div class="columna_3"></div>
        <div class="columna_3"></div>
    </div>
</code>

2.- BOTONES
Achivo: recursos.css
Existen botones en 3 tamanos: Grande, normal y chico. Los botones por defecto son blancos con un borde gris.

Para crear un botón solamente hay que poner la clase '.boton' a un '<a>'

Ej.
<code>
    <a href="#" class="boton">Boton</a>
</code>

3.- COLORES
Achivo: color.css
Para Agregar un color (rojo, azul o verde) a cualquier elemento solamente hay que agregar en la clase el color.

Ej.
<code>
    <div class="verde"> Aquí puede ir texto </div>
    <a href="#" class="rojo">link</a>
</code>


4.- RECURSOS
Achivo: recursos.css

Acá podrán encontrar diferentes recursos del tipo "sin fondo", "sin padding", Sin Margen, Flotar a la izquierda o derecha, etc...
Si deseas realizar algo mas especifico para un div acá lo podrán encontrar.


TO DO LIST
==========

Cosas que ire creando:
- Tablas
- header/Menu que te persiguen
- Pagina tipo
- Slider
- Espacios en Blanco
- Typo Open Sans 
- Responsive



