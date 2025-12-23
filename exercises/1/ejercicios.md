# Ejercicios de Práctica HTML

Aquí tienes una lista de ejercicios diseñados para reforzar lo que ya sabes y desafiarte un poco más con nuevos elementos.

Puedes resolver todos estos ejercicios en un nuevo archivo llamado `practica.html` o `ejercicios.html`.

## Ejercicio 1: Estructura "Head" Correcta
En tus archivos actuales (`index.html` y `apuntes-de-html.html`), el contenido está directamente en el `<body>`.
**Tu tarea:** Crea un documento HTML que tenga la estructura completa, incluyendo la etiqueta `<head>`.
*   Dentro del `<head>`, añade un `<title>` que diga "Mis Ejercicios de HTML".
*   Añade también la etiqueta meta para caracteres especiales: `<meta charset="UTF-8">`.

## Ejercicio 2: Listas Mixtas (Anidación)
Ya sabes usar `<ul>` (listas desordenadas). Ahora vamos a probar con `<ol>` (listas ordenadas, 1, 2, 3...) y a combinarlas.
**Tu tarea:** Crea una lista ordenada (`<ol>`) que describa los pasos para hacer tu comida favorita (o algo simple como "Hacer un café").
*   Al menos uno de los pasos debe tener adentro una lista desordenada (`<ul>`) con los ingredientes necesarios para ese paso específico.
    *   *Pista:* La lista `<ul>` va **dentro** de la etiqueta `<li>` del paso correspondiente.

## Ejercicio 3: Tu Primera Tabla
Las tablas son útiles para mostrar datos organizados.
**Tu tarea:** Crea una tabla sencilla (`<table>`) que muestre un horario de clases o una lista de precios.
*   Debe tener al menos 3 filas (`<tr>`).
*   Debe tener encabezados de columna (`<th>`) en la primera fila (ej: "Día", "Actividad").
*   Debe tener datos (`<td>`) en las filas siguientes.

## Ejercicio 4: Formulario de Contacto Básico
Mencionaste `input` en tus apuntes, ¡es hora de usarlo!
**Tu tarea:** Crea un formulario (`<form>`) simple para que alguien te contacte. Debe incluir:
*   Un campo para el nombre (`<input type="text">`).
*   Un campo para el correo electrónico (`<input type="email">`).
*   Un botón para enviar (`<button>` o `<input type="submit">`).
*   *Extra:* Usa el atributo `placeholder` para dar una pista al usuario en los campos de texto.

## Ejercicio 5: Navegación Interna
**Tu tarea:** Crea un pequeño menú de navegación al principio de tu archivo.
*   Usa una lista desordenada `<ul>` con enlaces `<a>`.
*   Los enlaces deben llevar a las diferentes secciones de tus ejercicios (por ejemplo, al Ejercicio 1, Ejercicio 2, etc.).
*   *Pista:* Necesitarás usar el atributo `id` en los títulos de cada ejercicio y poner ese id en el `href` del enlace (ej: `href="#ejercicio-1"`).

---

¡Cuando termines, avísame y revisaré tu código para darte feedback!
