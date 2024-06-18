# 2.1 ESTRUCTURA BASICA

## Estructura de una Página WEB

La estructura de una página web está definida por el lenguaje de marcado HTML. Una página web típica sigue una estructura jerárquica específica que ayuda a organizar el contenido y proporciona la base para el estilo y la funcionalidad. A continuación, se describen los componentes principales de la estructura de una página web, junto con ejemplos y explicaciones detalladas.

#### Componentes Principales de una Página Web

1. **Declaración del Tipo de Documento (Doctype):**
   - La declaración del tipo de documento debe ser la primera línea en un documento HTML. Informa al navegador sobre la versión de HTML que se está utilizando.
   - **Sintaxis:**
     ```html
     <!DOCTYPE html>
     ```

2. **Elemento `<html>`:**
   - El elemento `<html>` envuelve todo el contenido de la página y representa la raíz del documento HTML.
   - **Sintaxis:**
     ```html
     <html lang="es">
     </html>
     ```
   - El atributo `lang` especifica el idioma del contenido del documento.

3. **Elemento `<head>`:**
   - El elemento `<head>` contiene metadatos, enlaces a hojas de estilo, y otros elementos que no son visibles directamente en la página.
   - **Componentes del `<head>`:**
     - **Metadatos (`<meta>`):**
       - **Ejemplo:**
         ```html
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         ```
     - **Título (`<title>`):**
       - Define el título de la página, que aparece en la pestaña del navegador.
       - **Ejemplo:**
         ```html
         <title>Mi Página Web</title>
         ```
     - **Enlace a Hojas de Estilo (`<link>`):**
       - Enlaza hojas de estilo CSS externas.
       - **Ejemplo:**
         ```html
         <link rel="stylesheet" href="styles.css">
         ```
     - **Scripts (`<script>`):**
       - Puede incluir enlaces a archivos JavaScript.
       - **Ejemplo:**
         ```html
         <script src="script.js"></script>
         ```

4. **Elemento `<body>`:**
   - El elemento `<body>` contiene todo el contenido visible de la página, incluyendo texto, imágenes, enlaces, etc.
   - **Sintaxis:**
     ```html
     <body>
       <!-- Contenido de la página -->
     </body>
     ```

#### Ejemplo Completo de una Página HTML

A continuación, se muestra un ejemplo completo de una página web básica con todos los elementos esenciales:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Página Web</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Mi Página Web</h1>
    <nav>
      <ul>
        <li><a href="#inicio">Inicio</a></li>
        <li><a href="#acerca">Acerca de</a></li>
        <li><a href="#contacto">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="inicio">
      <h2>Inicio</h2>
      <p>Esta es la sección de inicio de la página.</p>
    </section>
    <section id="acerca">
      <h2>Acerca de</h2>
      <p>Esta es la sección acerca de la página.</p>
    </section>
  </main>

  <footer>
    <p>Contacto: <a href="mailto:info@mipaginaweb.com">info@mipaginaweb.com</a></p>
  </footer>
</body>
</html>
```

#### Desglose del Ejemplo

1. **`<!DOCTYPE html>`:**
   - Define el documento como HTML5.

2. **`<html lang="es">`:**
   - El idioma del documento se especifica como español.

3. **`<head>`:**
   - **`<meta charset="UTF-8">`:** Establece la codificación de caracteres.
   - **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`:** Configura la vista para ser compatible con dispositivos móviles.
   - **`<title>Mi Página Web</title>`:** Define el título de la página.
   - **`<link rel="stylesheet" href="styles.css">`:** Enlaza la hoja de estilos externa.

4. **`<body>`:**
   - **`<header>`:**
     - Contiene el encabezado de la página, incluyendo un título y una barra de navegación.
   - **`<main>`:**
     - Contiene el contenido principal de la página, dividido en secciones (`<section>`).
     - **`<section id="inicio">` y `<section id="acerca">`**: Secciones con encabezados y párrafos.
   - **`<footer>`:**
     - Contiene el pie de página, incluyendo información de contacto.


### Resumen

- La estructura básica de una página web HTML incluye `<!DOCTYPE html>`, `<html>`, `<head>`, y `<body>`.
- **`<head>`** contiene metadatos, títulos, enlaces a estilos y scripts.
- **`<body>`** contiene todo el contenido visible de la página.
- Las etiquetas semánticas como `<header>`, `<main>`, `<section>`, y `<footer>` ayudan a organizar el contenido y mejorar la accesibilidad y SEO.

Esta estructura es la base de cualquier página web y entenderla es crucial para desarrollar sitios web efectivos y bien organizados.


##

[BACK](1-estructura-de-una-etiqueta.md)  

[Practica 1](../Practica-1/Ejercicios-2-1.md) 

[Lección 2.2](../2.2.párrafos-y-encabezados.md)  



