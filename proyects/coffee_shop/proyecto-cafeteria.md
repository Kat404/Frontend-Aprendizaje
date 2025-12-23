# Proyecto Final de HTML: "Aroma de Café" ☕

¡Felicidades! Has llegado al punto donde vamos a conectar todo lo aprendido en un solo **Mini Proyecto**.

En lugar de ejercicios sueltos, vamos a construir la página web completa para una cafetería ficticia llamada **"Aroma de Café"**.

**Objetivo:** Crear una estructura HTML semántica, robusta y lista para ser estilizada en el futuro. Usarás etiquetas que ya conoces e introduciremos algunas nuevas que son vitales para este tipo de sitios.

---

## 🛠️ Requisitos del Proyecto

Crea un archivo llamado `cafeteria.html` en tu nueva carpeta `proyects/coffee_shop` y sigue las siguientes instrucciones paso a paso.

### 1. Configuración Inicial y "Pincelada" de CSS
Aunque **NO** escribiremos estilos CSS todavía, vamos a dejar todo listo profesionalmente.
*   Crea una carpeta llamada `css` dentro de `proyects/coffee_shop`.
*   Dentro, crea un archivo vacío llamado `styles.css`.
*   En tu HTML, enlaza este archivo usando la etiqueta `<link>` en el `<head>`.
    *   *Nota: No pasará nada visualmente, pero es la forma correcta de integrar CSS.*

### 2. Estructura del Documento (`<head>`)
Además de lo básico (doctype, html, charset), incluye:
*   Un **título** descriptivo: "Aroma de Café - La mejor experiencia en cada taza".
*   **Meta etiquetas**:
    *   `description`: "Cafetería artesanal con granos seleccionados y ambiente relajante en el centro de la ciudad".
    *   `keywords`: "café, cafetería, espresso, postres, [Tu Ciudad]".
*   **Favicon**: (Opcional) Si quieres, busca un icono pequeño `.ico` o `.png` y enlázalo con `<link rel="icon" href="...">`.

### 3. Encabezado (`<header>`)
El encabezado debe contener:
*   Un `<h1>` con el nombre de la cafetería.
*   Una barra de navegación (`<nav>`) con enlaces internos a las secciones de la página:
    *   Inicio (`#inicio`)
    *   Sobre Nosotros (`#nosotros`)
    *   Menú (`#menu`)
    *   Ubicación (`#ubicacion`)
    *   Contacto (`#contacto`)

---

### 4. Contenido Principal (`<main>`)
El contenido se dividirá en varias secciones (`<section>`).

#### A. Sección de Inicio (`#inicio`)
*   Un mensaje de bienvenida (puede ser un `<h2>`).
*   Un párrafo introductorio invitando a los clientes.
*   **NUEVO**: Usa la etiqueta `<figure>` y `<figcaption>`.
    *   Incluye una imagen de una taza de café o el interior de un local.
    *   Usa `<figcaption>` para ponerle un pie de foto: "Nuestro Capuchino Especial de la casa".

#### B. Sección "Sobre Nosotros" (`#nosotros`)
*   Un artículo (`<article>`) que cuente brevemente la historia de la cafetería.
*   Usa `<p>`, `<strong>` para resaltar años o nombres, y tal vez `<em>` para el eslogan.
*   **NUEVO**: Usa la etiqueta `<blockquote>` para poner una reseña de un cliente satisfecho.
    *   *Extra*: Usa la etiqueta `<cite>` dentro del blockquote para poner el nombre del autor de la cita.

#### C. Sección del Menú (`#menu`)
Aquí aprenderemos a estructurar datos complejos.
*   Un título `<h2>` "Nuestro Menú".
*   **NUEVO**: Usa una **Tabla HTML** (`<table>`) para mostrar al menos 3 productos.
    *   Debe tener cabecera (`<thead>`) con: "Producto", "Descripción", "Precio".
    *   Cuerpo (`<tbody>`) con las filas de los productos.
    *   Pie de tabla (`<tfoot>`) (opcional) con algún mensaje como "Precios incluyen IVA".
*   **RETO OPCIONAL**: Alternativamente, intenta usar una **Lista de Definición** (`<dl>`, `<dt>`, `<dd>`) para una sub-sección de "Postres".
    *   `<dt>` (Término): Nombre del postre.
    *   `<dd>` (Descripción): Ingredientes y precio.

#### D. Sección Ubicación (`#ubicacion`)
*   Un título `<h2>`.
*   **NUEVO**: Usa la etiqueta `<address>`.
    *   Dentro, pon la dirección física, pero separa las líneas con `<br>`.
*   Inserta un **Mapa** usando un `<iframe>` de Google Maps (puedes buscar una ubicación cualquiera en Google Maps -> Compartir -> Insertar mapa).

#### E. Sección Contacto (`#contacto`)
Crea un formulario robusto para reservas:
*   Campos necesarios:
    *   Nombre (texto).
    *   Correo (email).
    *   Número de personas (number, min="1", max="10").
    *   Fecha y Hora (`datetime-local` o separados).
    *   Preferencia de mesa (usa `<select>` con `<optgroup>` si te animas, o solo `<option>`): "Interior", "Terraza", "Barra".
*   Botón de envío "Reservar Mesa".

---

### 5. Pie de Página (`<footer>`)
*   Derechos de autor (usa la entidad HTML `&copy;` seguido del año).
*   Enlaces a redes sociales (ficticias).
*   Enlace de "Volver arriba".

---

## 💡 Consejos
*   Mantén tu código indentado y limpio.
*   Usa comentarios `<!-- Sección Menú -->` para organizarte.
*   ¡No te preocupes si se ve "feo"! HTML es estructura; la belleza vendrá con CSS.
