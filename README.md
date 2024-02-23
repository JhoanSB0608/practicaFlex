![](https://github.com/JhoanSB0608/practicaFlex/blob/ejercicio2/storage/img/ejercicio2.png)

### HTML:
- Se define un documento HTML5 con la etiqueta `<!DOCTYPE html>`.
- Se establece el idioma del documento como español mediante el atributo `lang="es"`.
- En el encabezado (`<head>`), se especifica la codificación de caracteres y la configuración de la vista del dispositivo.
- Se asigna un título a la página dentro de la etiqueta `<title>`.
- Se enlaza un archivo de estilo CSS externo utilizando la etiqueta `<link>`.

### CSS:
- **`.menu-item`**: Se aplica a cada elemento de menú dentro del menú. Se utiliza la propiedad `display: flex` para convertirlos en elementos flexibles y alinearlos horizontalmente. `justify-content: space-between` se utiliza para distribuir el espacio disponible entre los elementos del menú y `align-items: center` se utiliza para alinear verticalmente los elementos del menú. Se define un relleno de 20px para agregar espacio alrededor del contenido. Se establece un fondo gris claro (`#c9bfbf`) y un borde de 1px sólido de color gris (`#ccc`).
- **`.menu-item:last-child`**: Se aplica a la última instancia de `.menu-item` dentro del menú. Se anula el borde inferior utilizando `border-bottom: none;` para evitar un borde adicional en la última fila del menú.
- **`.menu-item span`**: Se aplica al texto dentro de cada elemento de menú. Se establece un tamaño de fuente de 18px.
- **`.menu-item a`**: Se aplica a los enlaces dentro de cada elemento de menú. Se establece un tamaño de fuente de 18px y se especifica un color de texto negro (`black`). Se asigna un fondo blanco a los enlaces y se agrega un relleno de 5px vertical y 10px horizontal para espaciar el texto del enlace del borde de la caja.

Este código genera un menú vertical con elementos de menú que contienen un texto y un enlace "ENTRAR". Cada elemento de menú tiene un fondo gris claro con un borde gris, y los enlaces tienen un fondo blanco con texto negro. El diseño y los estilos se han definido de manera que el menú se vea limpio y fácil de leer.