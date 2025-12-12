# Ejercicios de Práctica HTML - Nivel 3

¡Felicidades por llegar hasta aquí! Ya dominas la estructura básica, tablas y formularios esenciales.
Ahora vamos a "vitamina" tus páginas con multimedia, formularios avanzados y etiquetas perfectas para un portafolio de tecnología como el tuyo.

## Ejercicio 1: El mundo Multimedia (`<video>`, `<audio>`, `<iframe>`)
Una web moderna no es solo texto. Vamos a insertar contenido rico.
**Etiquetas nuevas:**
*   `<video>`: Para mostrar videos nativos. Usa el atributo `controls` para que el usuario pueda darle play.
*   `<audio>`: Similar al video, pero solo sonido.
*   `<iframe>`: Es una "ventana" a otra web. Se usa mucho para insertar videos de YouTube o mapas de Google Maps.

**Tu tarea:**
Crea una sección llamada "Mis Media".
1.  Inserta un video de YouTube de alguna conferencia de Linux o tecnología que te guste usando `<iframe>` (en YouTube: botón "Compartir" -> "Insertar").
2.  Agrega una etiqueta `<audio>` con el atributo `controls`. Si no tienes un archivo de audio real, puedes usar un enlace de ejemplo o simplemente dejar la etiqueta lista para ver cómo se renderiza el reproductor.

## Ejercicio 2: Formularios Avanzados (`radio`, `select`, `date`)
Ya usaste checkboxes, pero ¿qué pasa si quieres que el usuario elija **solo una** opción de varias? ¿O una lista desplegable?
**Conceptos nuevos:**
*   `<input type="radio">`: Botones circulares. **Truco:** Para que sean excluyentes (solo puedas elegir uno), todos deben tener el mismo atributo `name`.
*   `<select>` y `<option>`: Para crear menús desplegables.
*   `<input type="date">`: Un calendario nativo para elegir fechas.

**Tu tarea:**
Mejora tu formulario de contacto agregando:
1.  **Género:** Usa 3 botones de radio (Masculino, Femenino, Otro). Recuerda usar el mismo `name` (ej: `name="genero"`) para que funcionen bien.
2.  **País:** Un menú desplegable (`<select>`) con 3 opciones (ej: México, Colombia, España).
3.  **Fecha de nacimiento:** Un selector de fecha (`<input type="date">`).

## Ejercicio 3: Blog Semántico (`<article>`, `<time>`, `<blockquote>`)
Como te gusta Linux y la seguridad, seguro querrás escribir artículos. HTML tiene etiquetas especiales para eso.
**Conceptos nuevos:**
*   `<article>`: Ideal para contenido independiente (como un post de blog).
*   `<time>`: Para marcar fechas de una forma que las máquinas entiendan. Usa el atributo `datetime="YYYY-MM-DD"`.
*   `<blockquote>`: Para citar frases o textos de otros autores. Se suelen ver con sangría automáticamente.

**Tu tarea:**
Crea una pequeña entrada de blog simulada sobre "Por qué usar Linux".
1.  Envuelve todo en una etiqueta `<article>`.
2.  Pon la fecha de hoy usando la etiqueta `<time>`.
3.  Escribe un párrafo de introducción.
4.  Usa `<blockquote>` para citar una frase famosa (ej: "El software es como el sexo: es mejor cuando es libre. - Linus Torvalds").

## Ejercicio 4: Mostrando Código (`<pre>`, `<code>`)
Para tu portafolio de scripts y configuraciones, estas etiquetas son obligatorias.
**Conceptos nuevos:**
*   `<code>`: Para marcar pequeños fragmentos de código en línea (ej: `sudo apt update`).
*   `<pre>`: Mantiene el formato exacto (espacios y saltos de línea). Ideal para bloques grandes de código.

**Tu tarea:**
Muestra un script o comando de Linux.
1.  Escribe una frase que mencione un comando usando `<code>`.
2.  Muestra un pequeño bloque de configuración (como unas líneas de `.bashrc` o un script simple) usando `<pre>` y `<code>` juntos (el `<code>` va dentro del `<pre>`).

## Ejercicio 5: Metaetiquetas Sociales (Open Graph)
Esto va en el `<head>`. Sirve para que cuando compartas tu link en WhatsApp o Twitter, salga una tarjeta bonita con imagen y título.
**Conceptos nuevos:**
*   `<meta property="og:title" content="...">`
*   `<meta property="og:description" content="...">`
*   `<meta property="og:image" content="...">`

**Tu tarea:**
Ve al `<head>` de tu documento y agrega estas 3 etiquetas Open Graph inventando los datos para tu página de prácticas.

---

¡Adelante! Con esto tu HTML estará listo para presentar contenido real y profesional.
