# Ejercicios de Práctica HTML - Nivel 2

¡Genial que quieras seguir practicando! Aquí tienes una nueva serie de ejercicios para reforzar tu lógica y aprender nuevas etiquetas muy útiles.
Al igual que antes, puedes crear un archivo nuevo como `practica-2.html` para resolverlos.

## Ejercicio 1: Tablas Mejoradas (`<caption>`, `<tfoot>`)
En el ejercicio anterior hiciste una tabla básica. Ahora vamos a hacerla más semántica y completa.
**Conceptos nuevos:**
*   `<caption>`: Sirve para ponerle un título a la tabla. Va justo después de abrir la etiqueta `<table>`.
*   `<thead>`: Agrupa la cabecera (donde están los `<th>`).
*   `<tbody>`: Agrupa el cuerpo de la tabla (los datos principales).
*   `<tfoot>`: Agrupa el pie de tabla (como para mostrar totales).

**Tu tarea:**
Crea una tabla que represente una **Lista de Compras**.
1.  Usa `<caption>` para ponerle el título "Lista del Supermercado".
2.  Usa `<thead>` para los encabezados: "Producto", "Cantidad", "Precio".
3.  Usa `<tbody>` para listar al menos 3 productos.
4.  Usa `<tfoot>` para una fila final que diga "Total" en la primera columna y el precio total en la última.

## Ejercicio 2: Imágenes con Enlaces y `target`
Ya sabes usar imágenes y enlaces por separado. ¡Ahora vamos a unirlos!
**Conceptos nuevos:**
*   **Imágenes como enlaces:** Puedes poner una `<img>` *dentro* de una etiqueta `<a>`. Así, al hacer clic en la imagen, te llevará al enlace.
*   `target="_blank"`: Es un atributo para la etiqueta `<a>` que hace que el enlace se abra en una **pestaña nueva**.

**Tu tarea:**
Crea una pequeña "Galería de Favoritos".
1.  Busca 2 o 3 imágenes pequeñas (o usa las mismas de antes).
2.  Haz que cada imagen sea un enlace a una página web diferente (ej: Google, YouTube, GitHub).
3.  Asegúrate de que al hacer clic, las páginas se abran en una **pestaña nueva** usando `target="_blank"`.

## Ejercicio 3: Formularios Profesionales con `<label>` y `<textarea>`
Hasta ahora tus formularios solo tenían campos sueltos. Para que sean accesibles y se vean mejor, usamos etiquetas.
**Conceptos nuevos:**
*   `<label>`: Es la etiqueta para el texto que acompaña al input (ej: "Nombre:"). Se conecta al input usando el atributo `for="id-del-input"`.
*   `<textarea>`: A diferencia del `input text`, este permite escribir múltiples líneas (ideal para mensajes largos).
*   `<input type="checkbox">`: Una casilla cuadrada para marcar opciones (sí/no).

**Tu tarea:**
Crea un formulario de "Comentarios o Sugerencias".
1.  Un campo para el Nombre, con su `<label>` correspondiente correctamente enlazado.
2.  Un campo grande para el Mensaje usando `<textarea>`.
3.  Una casilla checkbox que pregunte: "¿Deseas recibir respuesta al correo?".
4.  Un botón de enviar.

## Ejercicio 4: Semántica Básica (`header`, `main`, `footer`)
En lugar de tirar todo el contenido suelto en el `<body>`, los desarrolladores usamos etiquetas que dicen "qué es cada parte".
**Conceptos nuevos:**
*   `<header>`: Para el encabezado visible de la página (título principal, logo, menú). Ojo: no confundir con `<head>`.
*   `<main>`: Para el contenido principal y único de la página.
*   `<footer>`: Para el pie de página (copyright, enlaces de contacto al final).

**Tu tarea:**
Re-estructura una página sencilla (puede ser vacía o con texto de relleno "Lorem Ipsum") usando estas tres secciones.
1.  Dentro del `<header>`, pon un `<h1>` con el título de tu sitio.
2.  Dentro del `<main>`, pon dos párrafos `<p>` explicando de qué trata la página.
3.  Dentro del `<footer>`, pon un texto pequeño que diga "Creado por [Tu Nombre] - 2024".

## Ejercicio 5: Acordeones Nativos (`<details>` y `<summary>`)
Este es un truco divertido de HTML moderno que no requiere JavaScript.
**Conceptos nuevos:**
*   `<details>`: Crea una caja que se puede abrir y cerrar.
*   `<summary>`: Es el título visible que, al hacerle clic, revela el contenido oculto.

**Tu tarea:**
Crea una sección de **Preguntas Frecuentes (FAQ)**.
1.  Usa la etiqueta `<details>`.
2.  Dentro, usa `<summary>` para escribir la pregunta (ej: "¿Cuál es mi color favorito?").
3.  Debajo del summary (pero dentro del details), pon la respuesta en un párrafo.
4.  Haz esto para al menos 2 preguntas.

---

¡Disfruta practicando! Estos ejercicios te acercan mucho más a cómo se escriben las páginas web profesionales hoy en día.
