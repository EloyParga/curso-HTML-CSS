# ESTRUCTURA DE UNA ETIQUETA HTML

## Estructura de una Etiqueta HTML

Las etiquetas HTML son los componentes básicos de un documento HTML. Cada etiqueta define un elemento en la página web y suele venir en pares de apertura y cierre, aunque hay algunas etiquetas auto-cerradas. A continuación, se describe la estructura general de una etiqueta HTML y se proporcionan ejemplos para ilustrar su uso.

### Componentes de una Etiqueta HTML

1. **Etiqueta de Apertura:**
   - La etiqueta de apertura marca el comienzo de un elemento HTML. Está formada por el nombre de la etiqueta encerrado entre corchetes angulares `<>`.
   - **Sintaxis:**
     ```html
     <nombreDeEtiqueta>
     ```
   - **Ejemplo:**
     ```html
     <p>
     ```

2. **Contenido del Elemento:**
   - El contenido del elemento es lo que se encuentra entre las etiquetas de apertura y cierre. Puede ser texto, otras etiquetas HTML, o ambos.
   - **Ejemplo:**
     ```html
     <p>Este es un párrafo.</p>
     ```

3. **Etiqueta de Cierre:**
   - La etiqueta de cierre marca el final de un elemento HTML. Es similar a la etiqueta de apertura, pero incluye una barra diagonal (`/`) antes del nombre de la etiqueta.
   - **Sintaxis:**
     ```html
     </nombreDeEtiqueta>
     ```
   - **Ejemplo:**
     ```html
     </p>
     ```

### Ejemplo Completo de una Etiqueta HTML

Un párrafo en HTML se define utilizando las etiquetas `<p>` y `</p>`. Aquí hay un ejemplo completo:

```html
<p>Este es un párrafo de ejemplo.</p>
```

### Atributos de las Etiquetas

Las etiquetas HTML pueden tener atributos que proporcionan información adicional sobre el elemento. Los atributos se escriben dentro de la etiqueta de apertura y tienen un nombre y un valor.

- **Sintaxis de un Atributo:**
  ```html
  <nombreDeEtiqueta nombreAtributo="valorAtributo">
  ```
- **Ejemplo:**
  ```html
  <a href="https://www.example.com">Visita nuestro sitio</a>
  ```

En este ejemplo, el atributo `href` define el URL al que apunta el enlace.

### Ejemplo Completo con Atributos

```html
<img src="imagen.jpg" alt="Descripción de la imagen">
```
En este ejemplo, la etiqueta `<img>` incluye dos atributos:
- `src` especifica la ruta de la imagen.
- `alt` proporciona un texto alternativo que describe la imagen.

### Etiquetas Auto-cerradas

Algunas etiquetas HTML no tienen contenido y se cierran en la misma etiqueta de apertura. Estas se conocen como etiquetas auto-cerradas o vacías.

- **Sintaxis de una Etiqueta Auto-cerrada:**
  ```html
  <nombreDeEtiqueta />
  ```
- **Ejemplo:**
  ```html
  <br />
  ```

La etiqueta `<br />` se usa para insertar un salto de línea y no tiene contenido ni etiqueta de cierre.

## Resumen

- Las etiquetas HTML definen elementos en un documento HTML.
- Cada etiqueta tiene una estructura básica con una etiqueta de apertura, contenido del elemento y una etiqueta de cierre.
- Las etiquetas pueden tener atributos que proporcionan información adicional sobre el elemento.
- Algunas etiquetas son auto-cerradas y no necesitan una etiqueta de cierre.

### Ejemplos Adicionales

**Encabezado:**
```html
<h1>Este es un encabezado de nivel 1</h1>
```

**Enlace:**
```html
<a href="https://www.google.com">Ir a Google</a>
```

**Lista Desordenada:**
```html
<ul>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <li>Elemento 3</li>
</ul>
```

**Formulario:**
```html
<form action="/enviar" method="post">
  <label for="nombre">Nombre:</label>
  <input type="text" id="nombre" name="nombre">
  <input type="submit" value="Enviar">
</form>
```

Entender la estructura de una etiqueta HTML es fundamental para crear páginas web correctamente estructuradas y funcionales. Con esta base, podrás construir documentos HTML más complejos y funcionales a medida que avances en tu aprendizaje.

##

[Lección Anterior](/1-Introducción/3-editor-codigo.md)  

[Siguiente Leccón](2-estructura-pagina-web.md)  