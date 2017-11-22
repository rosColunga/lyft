# Lyft

##### Ejercicio de maquetación utilizando los fundamentos de HTML y CSS.

* **Srint 2** _Retos de código_

***

## Objetivo

El reto consiste en maquetar una replica de el sitio **Lyft**, como se muestra a continuación:

![Lyft Website](docs/fullpage.png)

## Descripción del código

* Dentro del archivo base `index.html` se enlaza dentro de la etiqueta <**head**> el vínculo al archivo de estilos `main.css`, la fuente tipográfica *Montserrat* `Google Fonts`y el vínculo a la carpeta de tipografía iconográfica [Icomoon](https://icomoon.io/).

* Debajo a la misma altura de <**head**>, se coloca la etiqueta de estructura <**body**>, la cual contiene todo aquello que es visible dentro de la página web.

* Contenidas en <**body**> se encuentran *4 secciones* principales:

  1. <*nav*> Contine el menú de navegación de posición fija, dentro de la página, con dos elementos principales: 4 etiquetas <*a*> con texto a las cuales se les aplica un *:hover*. Se encuentran flotados a la izquierda; y flotado del lado derecho el logo de *Lyft*. Todo el menú contiene un background con opacidad del 50% dado por un canal alfa en rgba().

  2. <*header id="first-section"*> Independiente al menú de navegación, dentro de la primera pantalla, se subdivide en **dos secciones** sobre una gradación de tonalidades púrpura. En *la primera* se coloca una imagen tipo .gif y un formulario dentro de <*aside id="sign-up"*> para inscribirse como conductor del *Lyft*. En *la segunda* <*section id="first-section2"*> 3 párrafos descriptivos del lado izquierdo y del lado derecho una imagen .png con un Smartphone que tiene instalada la app.

  3. <*main class="info-videos-section"*> Contenedor de la "segunda pantalla", dando scroll down en la web. En esta sección encontramos la galería de videos de Youtube con la información y publicidad de **Lyft**, elaborada por medio de *Grid* o retícula id: "grid-container".

  4. <*footer*>
        <*section class="columns"*> Tercera parte además del menú, que contiene un texto a tres columnas y una adicional con el vínculo a las tiendas dónde adquirir la app. Además se incluyen iconos de **Icomoon**

* Para finalizar se cierran las etiquetas contenedoras: <*body*> y <*html*> de la estructura de nuestro archivo.


  > Nota: Ver resultado final en Github Projects de este repositorio
