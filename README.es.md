# 📝 Hoja Chuleta de HTML
Una guía rápida de referencia con los elementos esenciales de HTML, su estructura y buenas prácticas.

---
<br>

## 🏗️ Estructura Básica
| ETIQUETA | DESCRIPCIÓN | 
|---|---|
| `<!DOCTYPE html>` | Declaración del tipo de documento HTML5 |
| `<html>` | Elemento raíz de un documento HTML |
| `<head>` | Contiene metadatos/información para el documento | 
| `<body>` | Contiene el contenido visible del documento |
<br>

## 🔤 Elementos de Texto
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<h1>` a `<h6>` | Títulos (h1 es el de mayor jerarquía) |
| `<p>`| Párrafo |
| `<strong>`| Negrita (énfasis semántico fuerte) |
| `<em>` | Cursiva (énfasis semántico) |
| `<br>`| Salto de línea |
| `<hr>` | Separación temática (línea horizontal) |
| `<blockquote>` | Bloque de cita |
| `<pre>` | Texto preformateado (respeta espacios y saltos) |
| `<code>` | Código informático |
| `<mark>` | Texto resaltado |
| `<small>` | Texto pequeño (notas legales, etc.) |
| `<sub>` | Texto subíndice |
| `<sup>` | Texto superíndice |
<br>

## 🔗 Enlaces y Medios
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<a href="url">link</a>` | Enlace hipertexto |
| `<img src="image.jpg" alt="DESCRIPCIÓN">` | Imagen (siempre incluye `alt`) |
| `<video src="movie.mp4" controls>` | Reproductor de vídeo |
| `<audio src="sound.mp3" controls>` | Reproductor de audio |
| `<figure>` | Contenido autónomo como imágenes, diagramas |
| `<figcaption>` | Descripción para el contenido de `<figure>` |
| `<iframe src="url">` | Marco en línea para incrustar contenido externo |
| `<source>` | Recursos múltiples para `<video>` y `<audio>` |
| `<track>` | Subtítulos para `<video>` |
<br>

## 📋 Listas
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<ul>` | Lista desordenada (con viñetas) |
| `<ol>` | Lista ordenada (numerada) |
| `<li>` | Elemento de lista |
| `<dl>` | Lista de definición |
| `<dt>` | Término en una lista de definición |
| `<dd>` | Descripción en una lista de definición |
<br>

## 🧱 Estructura Semántica
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<header>` | Contenido introductorio (ej. logo, navegación) |
| `<nav>` | Enlaces de navegación |
| `<main>` | Contenido principal del documento (único en la página) |
| `<section>` | Agrupación temática de contenido |
| `<article>` | Contenido autónomo (ej. entrada de blog, comentario) |
| `<aside>` | Contenido secundario o lateral relacionado indirectamente |
| `<footer>` | Pie de página de una sección o del sitio |
| `<div>` | Contenido genérico sin valor semnántico |
| `<span>` | Contenedor en línea sin valor semántico |
| `<address>` | Información de contacto |
| `<details>` | Control de divulgación (puede expandirse) |
| `<summary>` | Encabezado para el elemento `<details>` |
| `<time>` | Fecha y/o hora específica |
<br>

## 📝 Formularios
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<form>` | Contenedor de controles de formulario |
| `<input type="text">` | Campo de texto |
| `<input type="email">` | Campo de correo (con validación automática) |
| `<input type="password">` | Campo de contraseña |
| `<input type="checkbox">` | Casilla de verificación |
| `<input type=radio">` | Botón de opción (radio) |
| `<input type="number">` | Campo numérico |
| `<input type="date">` | Selector de fecha |
| `<input type="file">` | Carga de archivos |
| `<input type="submit">` | Botón para enviar el formulario |
| `<input type="reset">` | Botón para restablecer el formulario |
| `<textarea>` | Área de texto multimedia |
| `<button>` | Botón clickeable |
| `<label for="id">` | Etiqueta asociada a un control (mejora de accessibilidad) |
| `<select>` | Lista desplegable |
| `<option>` | Opción dentro de un `<select>` |
| `<optgroup>` | Grupo de opciones en un `<select>` |
| `<fieldset>` | Grupo de controles relacionados |
| `<legend>` | Título para un `<fieldset>` |
| `<datalist>` | Lista de opciones para autocompletar |
| `<output>` | Contenedor para resultados de cálculos |
<br>

## 📊 Tablas
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<table>` | Define una tabla |
| `<caption>` | Título o leyenda de la tabla |
| `<thead>` | Grupo de filas de encabezado |
| `<tbody>` | Grupo de filas de cuerpo |
| `<tfoot>` | Grupo de filas de pie |
| `<tr>` | Fila de tabla |
| `<th>` | Celda de encabezado |
| `<td>` | Celda de datos |
| `<colgroup>` | Grupo de columnas |
| `<col>` | Define propiedades para columnas |
<br>

## ⚙️ Elementos en `head`
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<meta charset="UTF-8">` | Define la codificación de caracteres |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | Configura la vista responsiva |
| `<link rel="stylesheet" href="styles.css">` | Vincula una hoja de estilos CSS |
| `<link rel="icon" href="favicon.ico">` | Define el favicon (icono de la página) |
| `<title>` | Título de la página (aparece en la pestaña el navegador) |
| `<meta name="description" content="...">` | Descripción para motores de búsqueda |
| `<meta name="keywords" content="...">` | Palabras clave (menos relevante hoy en día) |
| `<meta name="author" content="...">` | Autor del documento |
| `<script src="script.js">` | Enlaza un archivo JavaScript |
| `<base href="...">` | URL base para todos los enlaces relativos  |
<br>

## Atributos Globales
| ATRIBUTOS | DESCRIPCIÓN |
|------|------------|
| `id` | Identificador único para un elemento |
| `class` | Clase(s) para estilos CSS y JavaScript |
| `style` | Estilos CSS en línea |
| `lang` | Idioma del contenido |
| `title` | Información adicional (tooltip) |
| `hidden` | Oculta el elemento |
| `data-*` | Almacena datos personalizados |
| `tabindex` | Orden de tabulación |
| `accesskey` | Tecla de acceso rápido |
| `contenteditable` | Permite editar el contenido del elemento |
<br>

## Elementos Obsoletos (Evitar)
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<center>` | Usa CSS: `text-align: center;`en su lugar |
| `<font>` | Usa CSS para estilos de texto |
| `<strike>` | Usa `<del>` o CSS: `text-decoration: line.through;` |
| `<frameset>`, `<frame>` | Usa `<iframe>` si es absolutamente necesario |
| Atributos como `bgcolor`, `align` | Usa CSS para estilos |
<br>

## 💡 Buenas Prácticas
- Usa siempre elementos semánticos (`<article>`, `<nav>`, etc.) para mejorar la accesibilidad y el SEO.
- Incluye el atributo `<alt>` en todas las imágenes.
- Usa nombres de etiquetas y atributos en minúsculas.
- Cierra correctamente las etiquetas (en HTML5, `<br>` es válido, pero `<br/>` también se acepta).
- Valida tu HTML con el [Validador del W3C](https://validator.w3.org/).
- Asegúrate de que tu sitio sea accesible siguiendo las pautas WCAG.
- Usa `<button>` para acciones y `<a>` para navegación entre páginas.
- No uses tablas para maquetar; utilízalas solo para datos tabulares.
- Optimiza las imágenes antes de subirlas (formato y tamaño adecuados).
- Estructura tus documentos con una jerarquía de encabezados clara (h1, h2, etc.).
<br>

## Glosario
- **Accesibilidad**: práctica de hacer sitios web utilizables por personas con diversas capacidades y discapacidades.
- **Atributo**: información adicional proporcionada en una etiqueta HTML (ej. href, src, class).
- **CDN**: Content Delivery Network. Red de servidores que entregan contenido web de forma más eficiente.
- **DOM**: Document Object Model. Representación en memoria de un documento HTML como un árbol de nodos.
- **Elemento**: una parte de una página HTML definida por etiquetas de apertura y cierre, o una etiqueta única para elementos vacíos.
- **Favicon**: pequeño icono asociado a un sitio web que aparece en la pestaña del navegador.
- **HTML**: HyperText Markup Language. Lenguaje de marcado estándar para crear páginas web.
- **Quirks Mode**: modo de renderizado en navegadores cuando falta la declaración DOCTYPE o es incorrecta.
- **Responsive**: diseño que se adapta a diferentes tamaños de pantalla y dispositivos.
- **Semántica**: uso de etiquetas HTML que transmiten significado sobre su contenido, no solo sobre su apariencia.
- **SEO**: Search Engine Optimization. Técnicas para mejorar la visibilidad de un sitio web en los motores de búsqueda.
- **Validación**: proceso de veriricar que un documento HTML cumple con las reglas y estándares del lenguaje.
- **Viewport**: área visible de una página web en la pantalla del dispositivo.
- **WCAG**: Web Content Accessibility Guidelines. Pautas para hacer el contenido web más accesible.

> 💡 **Consejo**: para documentación oficial, visita [MDN Web Docs – HTML](https://developer.mozilla.org/es/docs/Web/HTML).
