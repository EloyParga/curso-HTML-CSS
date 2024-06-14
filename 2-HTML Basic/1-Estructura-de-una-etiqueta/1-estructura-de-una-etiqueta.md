# ESTRUCTURA DE UNA ETIQUETA 


HTML (HyperText Markup Language) es el lenguaje estándar utilizado para crear páginas web. Las etiquetas HTML son los elementos fundamentales que estructuran y definen el contenido de una página web. Cada etiqueta HTML tiene una estructura específica que se debe seguir para que los navegadores web puedan interpretar y renderizar correctamente el contenido.

## Componentes de una Etiqueta HTML

Una etiqueta HTML se compone de varios elementos clave:

### 1.1 Etiqueta de Apertura
La etiqueta de apertura marca el comienzo de un elemento HTML. Está encerrada entre corchetes angulares (`<` y `>`). Por ejemplo, la etiqueta de apertura para un párrafo es `<p>`.

### 1.2 Contenido del Elemento
El contenido del elemento es el texto o los elementos anidados que se encuentran entre la etiqueta de apertura y la etiqueta de cierre. Por ejemplo, en un párrafo, el contenido del elemento podría ser un bloque de texto.

### 1.3 Etiqueta de Cierre
La etiqueta de cierre marca el final de un elemento HTML. Es similar a la etiqueta de apertura, pero incluye una barra inclinada (`/`) antes del nombre de la etiqueta. Por ejemplo, la etiqueta de cierre para un párrafo es `</p>`.

### 1.4 Atributos
Los atributos proporcionan información adicional sobre un elemento HTML. Se incluyen dentro de la etiqueta de apertura y constan de un nombre y un valor. Por ejemplo, el atributo `class` se utiliza para asignar una clase CSS a un elemento: `<p class="mi-clase">`.

## Ejemplo de Etiqueta HTML

A continuación se muestra un ejemplo completo de una etiqueta HTML:

```html
<p class="mi-clase">Este es un párrafo con una clase.</p>
```

En este ejemplo:
- `<p>` es la etiqueta de apertura.
- `class="mi-clase"` es un atributo que asigna la clase "mi-clase" al párrafo.
- `Este es un párrafo con una clase.` es el contenido del elemento.
- `</p>` es la etiqueta de cierre.

## Tipos de Etiquetas HTML

### 1.5 Etiquetas en Pares
La mayoría de las etiquetas HTML vienen en pares, con una etiqueta de apertura y una de cierre. Ejemplos comunes incluyen:

```html
<h1>Título Principal</h1>
<a href="https://www.ejemplo.com">Enlace</a>
<div>Contenido de la División</div>
```

### 1.6 Etiquetas Auto-cerradas
Algunas etiquetas HTML no tienen contenido y se cierran automáticamente. Estas etiquetas no requieren una etiqueta de cierre separada. Ejemplos comunes incluyen:

```html
<img src="imagen.png" alt="Descripción de la imagen">
<br>
<hr>
```



## Atributos Comunes en HTML

### 1.7 `id`
El atributo `id` proporciona un identificador único para un elemento HTML. Es útil para estilos CSS específicos o para interactuar con JavaScript.

```html
<div id="header">Encabezado</div>
```

### 1.8 `class`
El atributo `class` se utiliza para asignar una o más clases a un elemento. Esto permite aplicar estilos CSS o seleccionar el elemento con JavaScript.

```html
<p class="intro">Este es un párrafo introductorio.</p>
```

### 1.9 `src`
El atributo `src` especifica la ruta de un archivo externo, como una imagen, video o script.

```html
<img src="logo.png" alt="Logo de la empresa">
```

### 1.10 `href`
El atributo `href` especifica la URL de un enlace.

```html
<a href="https://www.ejemplo.com">Visita nuestro sitio web</a>
```

## Buenas Prácticas al Usar Etiquetas HTML

1. **Uso Semántico**: Utiliza etiquetas HTML semánticas para mejorar la accesibilidad y el SEO. Por ejemplo, usa `<header>`, `<footer>`, `<article>`, y `<section>` en lugar de `<div>` para definir las partes de una página.

2. **Anidamiento Correcto**: Asegúrate de que las etiquetas HTML estén correctamente anidadas. Una etiqueta de apertura debe tener una etiqueta de cierre correspondiente, y no deben cruzarse.

```html
<!-- Correcto -->
<div>
    <p>Texto aquí</p>
</div>

<!-- Incorrecto -->
<p>
    <div>Texto aquí</div>
</p>
```

3. **Atributos Consistentes**: Utiliza atributos de manera consistente y correcta. Los valores de los atributos deben estar entre comillas y ser relevantes para el elemento.

4. **Código Limpio y Legible**: Mantén el código HTML limpio y legible con indentación y comentarios cuando sea necesario. Esto facilita el mantenimiento y la colaboración.

Con una comprensión sólida de la estructura de las etiquetas HTML, estarás bien encaminado para crear páginas web bien estructuradas y funcionales.

##

[Lección Anterior](/1-Introducción/3-editor-codigo.md)

[Siguiente Leccón](2-estructura-pagina-web.md)