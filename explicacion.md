RECORDATORIO ELEMENTOS DE CSS
==============================

Profe ha enumerado una serie de elementos que utlizaremos nada / poco / mucho / prohibido usarlos.

PDF esta en notion - Material

### HTML5 —>
[html5-cheatsheet-emezeta.pdf](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/18bb3201-88ed-4e15-bbb2-92fb19e2ef6e/html5-cheatsheet-emezeta.pdf)

### CSS3 —>
[css3-cheatsheet-emezeta.pdf](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/17ff3e0b-d1ab-41e8-92b2-002a3fa34c56/css3-cheatsheet-emezeta.pdf)

IMAGENES CON COMENTARIOS DEL PROFE Y LEYANDA (hecho mal):
https://github.com/sosan/banner/blob/master/img/desktop/css_cheatsheet.png
https://github.com/sosan/banner/blob/master/img/desktop/css_cheatsheet2.png


Atomic Design
====================

Metodologia Atomic Design - idead por Brad Frost, pretende acabar con las inconsistencias de css

Cada vez hay mas tamaños de pantalals y para distingots dispositovos, necestamos unos procesos fijos que eviten errores y faciliten el desarrollo.

Hay 5  niveles originales:

Atomos => Un atomo es una unidad minima que puede existir. un input, un button, un H1....
Moleculas => Una molecula es una union de atomos. Por ejemplo, label y un input, un figure y un figcaption, un ul una molecula y un li un atomo
Organismos => Repeticion de moleculas. sucesion de imagenes con texto, un formulario (inputs, textos, botones,....), etc...
Plantillas => Una plantilla es un wireframe, no solo son organismos sino que podemos incorporar atomos, moleculas. Con este conjunto conseguimos una plantilla (wireframe)
Paginas => Son los propotipos, cuando acabamos el wireframe y mejoramos el wireframe con imagenes, estilos de textos, etc... llegamos a un prototipo.

Luego se añadio un 6 nivel:
(protones, electones, neutrones => colores) Añadido este nivel mas adelante de los 5 originales.


Las ventajas de un atomic Design son:

* facilita la crecion de la guia de estilos de la web
* permite hacer mas rapidos los propotipos ya que los elemiten ya existiran
HAce mas rapido el proceso de acutalizar el diseño de la web y/o añadir nuevas funcionalidades, ya que lso cambios no haran que se programar desde cero.
Menos compoenents hara el diseño y el codigo mas consistentes y eficientes
Permite reutilizar atomos para crear cualquiera diseño que se requiera.


Atomos => boton y un baner
Molecula => boton, texto, imagenes
Organismos => 3 moleculas
Plantilla => 1 header, 2 organismos 
Pagina => 3 plantillas, etc...

Cuando realizamos un proyecto grande, cuanod queramos realizar cambios, se puede volver una locura el organizar los elementos sin utilizar el diseño atomico.

Diseño Atomico Figma (Editable):
https://www.figma.com/file/EqsuezoVXbsZFZSGFfCtyf/Dise%C3%B1o-Atomico?node-id=0%3A1


CONTROL ESTADOS DEL USUARIO
===================================

Responden a eventos del usuario desde el navegador
hover => se activa cuando el raton pasa encima de un elemento.

active => clickear y matener click sobre un elemento.

focus  => se utiliza en formularios para rellenar un campo se lanza el evento

Font awesome tiene una liberia hover.css donde permite realizar pequeñas animaciones con hover, active y focus.
Ejemplo:
https://codepen.io/toaster99/pen/BpgzQR



FIGMA- CREACION DE COMPONENTES E INSTANCIAS DE ESOS COMPONENTES.
================================================================================
Esta tecnica desde figma podemos crear un componente (padre), realizar una o varias instancias de ese componente (hijos).
Si cambiamos al componente (padre), si cambiamos los componentes instanciados (componentes hijos), 
pero al mismo tiempos esas instancias conservaran sus propias modificaciones si no interfieren con las modificaciones hechas en el componente padre.

LINK BAJAR VIDEO (click "download" en la pagina de github):
https://github.com/sosan/banner/blob/master/video/explicacionfigma.mp4

