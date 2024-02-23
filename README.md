![](https://github.com/JhoanSB0608/practicaFlex/blob/ejercicio1/storage/img/ejercicio1.png)


HTML:

Se define un documento HTML5 con la etiqueta '<!DOCTYPE html>'.

Se especifica el idioma del documento como inglés (lang="en").

En el encabezado ('<head>'), se establecen metadatos como la codificación de caracteres y la escala inicial de la vista.

Se enlaza un archivo de estilo CSS externo (style.css) y un archivo de script JavaScript externo (main.js).

En el cuerpo del documento ('<body>'), se encuentra la estructura del encabezado.

El encabezado ('<header>') contiene tres elementos principales:

Un contenedor para el logotipo ('<div class="logo">') que incluye una imagen.

Un menú de navegación ('<nav>') que consiste en una lista desordenada ('<ul>') con cuatro elementos de lista ('<li>'), cada uno conteniendo un enlace ('<a>').


Dos contenedores ('<div class="language-container1">' y '<div class="language-container2">') para la selección de idioma, cada uno con su respectivo elemento de idioma ('<div class="language1">' y '<div class="language2">').


CSS:


Se establecen estilos básicos para el cuerpo (body) del documento, como eliminar el margen y especificar la fuente.


Los estilos para el encabezado (header) incluyen flexbox para alinear los elementos horizontalmente y distribuir el espacio disponible 

entre ellos.


Se limita el tamaño máximo del logotipo (logo img) a 155 píxeles de ancho.


Para el menú de navegación (nav ul), se eliminan los márgenes y el espaciado entre los elementos de lista (nav ul li), y se define un 

estilo para los enlaces (nav ul li a).


Los contenedores de idioma (language-containers) se configuran como flexbox para alinear los contenedores internos horizontalmente.


Los estilos para los elementos de idioma (language1 y language2) incluyen un tamaño de fuente, un borde, un relleno y una alineación a 

la derecha (margin-left: auto). Además, se establece un fondo gris medio oscuro y un color de texto blanco para resaltar los elementos.


En resumen, este código crea un encabezado simple y flexible para una página web, con un logotipo, un menú de navegación y opciones para 

seleccionar el idioma. Los estilos CSS proporcionan un diseño limpio y legible para estos elementos.