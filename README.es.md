# 📝 Hoja Chuleta de HTML

Una guía rápida de referencia con los elementos esenciales de HTML, su estructura y buenas prácticas.

---

## 🔤 Elementos de Texto
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<h1> a <h6>` | Títulos (h1 es el de mayor jerarquía) |
| `<p>`| Párrafo |
| `<strong>`| Negrita (énfasis semántico fuerte) |
| `<em>` | Cursiva (énfasis semántico) |
| `<br>`| Salto de línea |
| `<hr>` | Separación temática (línea horizontal) |

## 🔗 Enlaces y Medios
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<a href="url">link</a>` | Enlace hipertexto |
| `<img src="image.jpg" alt="DESCRIPCIÓN">` | Imagen (siempre incluye `alt`) |
| `<video src="movie.mp4" controls>` | Reproductor de vídeo |
| `<audio src="sound.mp3" controls>` | Reproductor de audio |

## 📋 Listas
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<ul>` | Lista desordenada (con viñetas) |
| `<ol>` | Lista ordenada (numerada) |
| `<li>` | Elemento de lista |

## 🧱 Estructura Semántica
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<header>` | Contenido introductorio (ej. logo, navegación) |
| `<nav>` | Enlaces de navegación |
| `<main>` | Contenido principal del documento |
| `<section>` | Agrupación temática de contenido |
| `<article>` | Contenido autónomo (ej. entrada de blog) |
| `<aside>` | Contenido secundario o lateral |
| `<footer>` | Pie de página de una sección o del sitio |

## 📝 Formularios
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<form>` | Contenedor de controles de formulario |
| `<input type="text">` | Campo de texto |
| `<input type="email">` | Campo de correo (con validación automática) |
| `<input type="password">` | Campo de contraseña |
| `<input type="checkbox">` | Casilla de verificación |
| `<input type="radio">` | Botón de opción (radio) |
| `<textarea>` | Área de texto multilínea |
| `<button>` | Botón clickeable |
| `<label for="id">` | Etiqueta asociada a un control (mejora accesibilidad) |

## ⚙️ Elementos en `head`
| ETIQUETA | DESCRIPCIÓN |
|------|------------|
| `<meta charset="UTF-8">` | Define la codificación de caracteres |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | Configura la vista responsiva |
| `link rel="stylesheet" href="styles.css">` | Vincula una hoja de estilos CSS |
| `<title>` | Título de la página (aparece en la pestaña del navegador) |

## 💡 Buenas Prácticas
- Usa siempre elementos semánticos (`<article>`, `<nav>`, etc.) para mejorar la accesibilidad y el SEO.
- Incluye el atributo `<alt>` en todas las imágenes.
- Usa nombres de etiquetas y atributos en minúsculas.
- Cierra correctamente las etiquetas (en HTML5, `<br>`es válido, pero `<br/>` también se acepta).
- Valida tu HTML con el [Validador del W3C](https://validator.w3.org/).

> 💡 **Consejo**: Para documentación oficial, visita [MDN Web Docs – HTML](https://developer.mozilla.org/es/docs/Web/HTML).
