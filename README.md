# Laboratorio-2_HTML5
Este repositorio contiene la solución completa del Laboratorio #2. El objetivo principal es practicar la configuración de metadatos, la maquetación semántica con HTML5, la construcción de tablas de datos y la aplicación de reglas de estilo independientes mediante CSS3.


### 📄 Documentos HTML

* **`tablas.html`**  
  * **Propósito:** Estructuración de datos tabulares complejos sin hoja de estilo externa.  
  * **Contenido:** Implementa el *Informe de gastos de viaje* mediante etiquetas `<table>`, `<tr>`, `<th>` y `<td>`. Incluye metadatos completos en el `<head>` (`charset`, `viewport`, `description`, `author`, `robots`) y atributos de accesibilidad como `headers` y `axis`.

* **`tablas2.html`**  
  * **Propósito:** Presentación visual de datos mediante tablas estilizadas dinámicamente.  
  * **Contenido:** Construye una tabla de ventas e impuestos vinculada a la hoja de estilos externa `estilosTabla.css`. Aplica clases como `.modo1` y `.modo2` a las filas para alternar bordes y colores.

* **`parrafos.html`**  
  * **Propósito:** Demostración práctica de selectores descendientes de CSS.  
  * **Contenido:** Contiene bloques de texto con citas (`<q>`) y énfasis (`<strong>`). Se conecta con `estilosParrafos.css` para modificar el diseño visual de etiquetas anidadas dentro de un párrafo.

* **`navegacion.html`**  
  * **Propósito:** Maquetación de tarjetas con hipervínculos seguros y pies de sección.  
  * **Contenido:** Integra bloques `<section class="card-seccion">`, enlaces externos configurados con seguridad (`target="_blank" rel="noopener"`) y un pie de recurso con selector único `#footer-recurso`.

* **`secciones.html`**  
  * **Propósito:** Estructuración maquetada con etiquetas totalmente semánticas de HTML5.  
  * **Contenido:** Implementa una arquitectura web compuesta por `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>` y `<footer>` con estilos visuales demostrativos para cada bloque.

---

### 🎨 Hojas de Estilos CSS

* **`estilosTabla.css`**  
  * **Propósito:** Hoja de estilo dedicada al formato de tablas.  
  * **Contenido:** Define el diseño de la clase `.tabla`, bordes decorativos, tipografía *Trebuchet MS*, conversión a mayúsculas con `text-transform: uppercase`, alineaciones y estilos intercalados para celdas de datos (`td`) y encabezados (`th`).

* **`estilosParrafos.css`**  
  * **Propósito:** Reglas de estilo para formateo de texto.  
  * **Contenido:** Define reglas específicas utilizando el selector descendiente `p strong`, aplicando un fondo amarillo pálido (`#ffc`), color de texto destacado y ajustes tipográficos.

---

## 💡 Conceptos Técnicos y Tecnologías Aplicadas

* **Metadatos y Cabecera HTML5:** Control de escala (`viewport`), codificación UTF-8 e indexación.
* **Estructura Semántica:** Uso adecuado de etiquetas contenedoras para mejorar la accesibilidad y el SEO.
* **Tablas HTML:** Agrupación lógica de datos mediante filas, celdas y cabeceras.
* **Selectores CSS3:** Control de especificidad mediante selectores de etiqueta, clases (`.class`), identificadores (`#id`) y descendientes (`p strong`).
