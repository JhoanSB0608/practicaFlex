![](https://github.com/JhoanSB0608/practicaFlex/blob/ejercicio4/storage/img/ejercicio4.png)

Este análisis detalla el proceso de creación del código HTML y CSS para implementar una galería de imágenes utilizando Flexbox.

### HTML

- **Estructura Básica HTML:** Se define la estructura básica del documento HTML con la declaración del tipo de documento y la apertura de las etiquetas `<html>`, `<head>`, y `<body>`.
- **Contenedor y Galerías:** Se utiliza un contenedor principal `<div>` con la clase `.container` para contener las dos galerías de imágenes.
- **Imágenes:** Se agregan las imágenes dentro de dos galerías `<div>` con las clases `.gallery1` y `.gallery2`. Cada galería contiene un conjunto de imágenes en una subgalería `<div>` con la clase `.subgallery`.
- **Atributos:** Se asignan atributos como `src` y `alt` a cada imagen para especificar la fuente y el texto alternativo respectivamente.

### CSS

- **Estilos Generales:** Se establecen estilos básicos para el cuerpo y el HTML para ocupar el 100% de la altura disponible y eliminar márgenes.
- **Contenedor y Galerías:** Se utiliza flexbox para crear un diseño flexible y responsivo. El contenedor principal `.container` se configura con `display: flex;` para organizar las galerías en línea. Se define la altura del contenedor al 100% y se permite el desplazamiento horizontal en caso de que el contenido exceda el ancho de la pantalla.
- **Galerías y Subgalerías:** Se utiliza la propiedad `flex` para establecer el ancho relativo de cada galería dentro del contenedor. Las subgalerías se muestran en línea utilizando `display: flex;` y `flex-wrap: wrap;` para permitir que las imágenes se envuelvan en múltiples líneas si es necesario.
- **Estilos de Imágenes:** Se aplican estilos a las imágenes para ajustar su tamaño y márgenes. Se utiliza una sombra suave (`box-shadow`) para resaltar visualmente las imágenes y crear un efecto tridimensional.

### Observaciones Finales

- Se utiliza Flexbox de manera efectiva para crear una galería de imágenes flexible y responsiva.
- Los estilos CSS se organizan de manera clara y estructurada, lo que facilita su mantenimiento y comprensión.
- Se utilizan clases semánticas en HTML y CSS para mejorar la legibilidad y la escalabilidad del código.