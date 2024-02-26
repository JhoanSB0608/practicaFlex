![](https://github.com/JhoanSB0608/practicaFlex/blob/ejercicio3/storage/img/ejercicio3.png)

Este análisis descriptivo detalla el proceso de realización del código HTML y CSS para lograr el efecto de centrado vertical y horizontal de un contenido dentro de un contenedor.

## Análisis Descriptivo - Realización del Código

Este análisis detalla el proceso de creación del código HTML y CSS para lograr el efecto de centrado vertical y horizontal de un contenido dentro de un contenedor.

### HTML

- **Estructura Básica HTML:** Se inicia con la declaración del tipo de documento (`<!DOCTYPE html>`) y se abre la etiqueta `<html>` con el atributo `lang` establecido en "en" para indicar el idioma.
- **Head:** En la sección `<head>` se incluyen metadatos como la codificación de caracteres y la configuración de la vista en dispositivos móviles. También se especifica el título de la página y se enlazan los archivos de estilos CSS y scripts JavaScript.
- **Body:** El contenido visible de la página está dentro del `<body>`, donde se encuentra un contenedor `<div>` con la clase `.centrar`. Dentro de este contenedor se encuentra un título `<h1>` y un párrafo `<p>` con texto explicativo.

### CSS

- **Estilos del Contenedor (.centrar):** Se definen estilos específicos para el contenedor con la clase `.centrar`. Se utiliza flexbox para centrar el contenido tanto vertical como horizontalmente. Los atributos `align-content: center;` y `justify-content: flex-start;` aseguran el centrado del contenido en ambas direcciones.
- **Estilos del Body:** Se establecen estilos para el cuerpo del documento para centrar el contenedor `.centrar` en la pantalla. Se utiliza flexbox con `display: flex;`, `justify-content: center;` y `align-items: center;` para lograr este efecto.
- **Estilos del Párrafo:** Se definen estilos adicionales para el párrafo, estableciendo un margen superior para separarlo del título.

### Observaciones Finales

- Se utiliza flexbox de manera efectiva para lograr el centrado tanto vertical como horizontal del contenido.
- Se especifican estilos adicionales para mejorar la presentación del texto dentro del contenedor.
- Los comentarios en el código pueden mejorar la legibilidad y comprensión del mismo.
