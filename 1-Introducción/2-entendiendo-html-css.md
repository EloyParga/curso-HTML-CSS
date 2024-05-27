
# ENTENDIENDO HTML Y CSS

## COMO FUNCIONA HTML/CSS
HTML (HyperText Markup Language) y CSS (Cascading Style Sheets) son las tecnologías fundamentales para crear y diseñar páginas web.

### HTML: La Estructura de la Web
- **HTML**: 
    - Es el lenguaje de marcado utilizado para estructurar el contenido en la web. Define elementos como **encabezados**, **párrafos**, **enlaces**, **imágenes** y otros componentes del contenido.
    - Es decir el programador escribe texto y gracias a el marcado este texto puede ser interpretado acorde a lo que quiere el desarrollador.

    - HTML es un lenguaje interpretado, es decir para que funcione, tiene que ser interpretado por otro programa, este programa es **El interprete**

- **Elementos y Etiquetas**: HTML utiliza etiquetas para marcar el inicio y el final de los elementos. Por ejemplo, `<p>` para párrafos, `<a>` para enlaces y `<img>` para imágenes.

- **Atributos**: Son propiedades adicionales que se pueden añadir a las etiquetas HTML para proporcionar información adicional sobre los elementos, como `href` para enlaces o `src` para imágenes.

### ETIQUETAS HTML

<details>
<summary>ETIQUETAS </summary>

| Etiqueta | Funcionalidad |
|----------|---------------|
| `<a>`    | Define un hipervínculo. |
| `<p>`    | Define un párrafo. |
| `<div>`  | Define una sección o un contenedor en un documento. |
| `<span>` | Define una sección en línea dentro de un documento. |
| `<h1>` to `<h6>` | Define encabezados de nivel 1 a 6. |
| `<img>`  | Define una imagen. |
| `<ul>`   | Define una lista desordenada. |
| `<ol>`   | Define una lista ordenada. |
| `<li>`   | Define un elemento de lista. |
| `<table>`| Define una tabla. |
| `<tr>`   | Define una fila en una tabla. |
| `<td>`   | Define una celda en una tabla. |
| `<th>`   | Define una celda de encabezado en una tabla. |
| `<form>` | Define un formulario HTML para la entrada del usuario. |
| `<input>`| Define un control de entrada. |
| `<button>` | Define un botón clicable. |
| `<label>` | Define una etiqueta para un control de formulario. |
| `<select>` | Define un cuadro de lista desplegable. |
| `<option>` | Define una opción en un cuadro de lista desplegable. |
| `<textarea>` | Define un área de texto de varias líneas. |
| `<link>` | Define la relación entre un documento y un recurso externo (usualmente utilizado para enlaces a hojas de estilo). |
| `<meta>` | Define metadatos sobre un documento HTML. |
| `<script>` | Define un script de cliente. |
| `<style>` | Define información de estilo para un documento. |
| `<header>` | Define un encabezado para un documento o sección. |
| `<footer>` | Define un pie de página para un documento o sección. |
| `<nav>` | Define un conjunto de enlaces de navegación. |
| `<article>` | Define contenido autónomo en un documento. |
| `<section>` | Define una sección en un documento. |
| `<aside>` | Define contenido adicional que está al margen del contenido principal. |
| `<figure>` | Define contenido ilustrativo como imágenes, diagramas, etc. |
| `<figcaption>` | Define un pie de foto para el elemento `<figure>`. |
| `<audio>` | Define contenido de audio. |
| `<video>` | Define contenido de video. |
| `<source>` | Define múltiples recursos multimedia para elementos `<audio>` y `<video>`. |

</details>

### CSS: El Estilo de la Web
- **CSS**: Es el lenguaje utilizado para describir la presentación de los documentos HTML. Permite aplicar estilos como colores, fuentes, márgenes y posiciones a los elementos HTML.
- **Selectores**: Son patrones utilizados para seleccionar los elementos HTML a los que se aplicarán los estilos. Los selectores pueden ser de ``etiqueta``, de ``Clase`` ó de ``ID``. 

Por ejemplo en el caso del siguiente codigo HTML podemos estilarlo de varias formas:

```HTML
<p class="parrafo" id="id_parrafo"> Soy un Parrafo </p>
```
Estilar todos los elementos ``<p>``
```CSS
p{
    color:"red"
}
```
Estilar todos los elementos con la ``Clase "parrafo"``
```CSS
.parrafo{
    color:"red"
}
```
Estilar el elemento con el ``ID "id_parrafo"``
```CSS
#id_parrafo{
    color:"red"
}
```

- **Propiedades y Valores**: CSS utiliza pares de propiedad-valor para definir los estilos. Por ejemplo, `color: blue;` establece el color del texto a azul, y `margin: 20px;` añade un margen de 20 píxeles alrededor de un elemento.

```css
.mi-clase{
    color: blue; 
    margin: 20px;
}
```

### PROPIEDADES CSS

<details>
<summary>PROPIEDADES </summary>

| Propiedad     | Funcionalidad                                                                         |
|---------------|---------------------------------------------------------------------------------------|
| `color`       | Establece el color del texto.                                                         |
| `background-color` | Establece el color de fondo de un elemento.                                      |
| `width`       | Establece el ancho de un elemento.                                                    |
| `height`      | Establece la altura de un elemento.                                                   |
| `margin`      | Establece el margen exterior de un elemento.                                          |
| `padding`     | Establece el relleno interior de un elemento.                                         |
| `border`      | Establece las propiedades del borde de un elemento.                                   |
| `font-size`   | Establece el tamaño de la fuente del texto.                                           |
| `font-family` | Establece la familia de fuentes del texto.                                            |
| `text-align`  | Establece la alineación del texto.                                                    |
| `display`     | Establece el tipo de caja de un elemento (block, inline, inline-block, none, etc.).   |
| `position`    | Establece el tipo de posicionamiento de un elemento (static, relative, absolute, fixed). |
| `top`         | Establece la posición superior de un elemento posicionado.                            |
| `bottom`      | Establece la posición inferior de un elemento posicionado.                            |
| `left`        | Establece la posición izquierda de un elemento posicionado.                           |
| `right`       | Establece la posición derecha de un elemento posicionado.                             |
| `z-index`     | Establece el orden z de un elemento posicionado.                                      |
| `overflow`    | Establece cómo manejar el contenido desbordante (visible, hidden, scroll, auto).      |
| `opacity`     | Establece la opacidad de un elemento.                                                 |
| `transition`  | Establece los efectos de transición entre dos estados de un elemento.                 |
| `transform`   | Aplica una transformación 2D o 3D a un elemento.                                      |
| `flex`        | Establece las propiedades de flexibilidad para los elementos flexibles.               |
| `grid`        | Establece las propiedades de diseño de cuadrícula para los elementos de la cuadrícula.|
| `align-items` | Establece la alineación de los elementos flexibles a lo largo del eje transversal.    |
| `justify-content` | Establece la alineación de los elementos flexibles a lo largo del eje principal.  |
| `background-image` | Establece una imagen de fondo para un elemento. 

</details>

### Integración de HTML y CSS
- **Inline CSS**: Se aplica directamente a los elementos HTML utilizando el atributo `style`.
- **Internal CSS**: Se define dentro de la etiqueta `<style>` en el encabezado de un documento HTML.
- **External CSS**: Se coloca en archivos separados con extensión `.css` y se enlaza al documento HTML utilizando la etiqueta `<link>`.

Conocer cómo funcionan HTML y CSS es fundamental para desarrollar y diseñar sitios web eficaces y visualmente atractivos.

##

[Lección Anterior](1-entendiendo-la-web.md)  

[Siguiente lección](3-editor-codigo.md)  