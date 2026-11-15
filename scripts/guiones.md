# Guiones de los videos

Reglas para todos los videos:

- Graben **solo en CodePen**, con el zoom del navegador al 150 % o más para que el código se lea bien.
- Usen narración en off y pongan texto en pantalla con la idea clave de cada lección.
- No muestren nombres, logos ni la cuenta de CodePen de nadie del equipo.
- Empiecen con: "En esta lección vas a aprender..." y terminen con: "En la siguiente lección...".
- Cuando aparezca una palabra técnica, explíquenla en palabras simples.
- En la descripción de YouTube pongan el enlace al CodePen inicial de la lección.

---

## Lección 1: ¿Qué es un sitio web? (5 min). Integrante A

- **Idea clave en pantalla:** Sitio web = Contenido (HTML) + Estilo (CSS)
- **Qué decir:** una página web es un archivo de texto que el navegador "traduce" a algo visual. Compárenlo con una casa: HTML son las paredes y los muebles, y CSS es la pintura y la decoración.
- **Demo:** pegar el `starter` (solo texto) y luego el `completed` (con HTML y CSS). Borrar el CSS en vivo para mostrar la diferencia.
- **Pausa de práctica:** "Pausa el video y cambia el texto del h1 por tu nombre."

## Lección 2: La estructura de una página HTML (8 min). Integrante A

- **Idea clave en pantalla:** `<etiqueta>contenido</etiqueta>` = elemento
- **Qué decir:** las etiquetas siempre se abren y se cierran. `head` es información que no se ve y `body` es lo que se ve. Un atributo es información extra dentro de la etiqueta.
- **Demo:** completar los PASOS 1 al 5 escribiendo despacio.
- **Pausa de práctica:** "Pausa y escribe un segundo párrafo contando qué te gusta hacer."

## Lección 3: Títulos, párrafos y listas (8 min). Integrante B

- **Idea clave en pantalla:** `ul` = viñetas · `ol` = números · `li` = cada elemento
- **Qué decir:** de h1 a h6 hay títulos de mayor a menor importancia, y h1 se usa una sola vez por página.
- **Demo:** PASOS 1 al 4 y luego el RETO con `<strong>`.
- **Pausa de práctica:** "Pausa y crea tu propia lista de tus 3 canciones favoritas."

## Lección 4: Imágenes y enlaces (7 min). Integrante B

- **Idea clave en pantalla:** `src` = de dónde sale · `alt` = qué muestra · `href` = a dónde lleva
- **Qué decir:** `<img>` no tiene etiqueta de cierre. El `alt` ayuda a las personas que usan lectores de pantalla.
- **Demo:** PASOS 1 al 3. Mostrar qué pasa si el `src` está mal escrito (aparece el texto `alt`).
- **Pausa de práctica:** "Pausa y agrega un enlace a tu página favorita."

## Lección 5: Introducción a CSS (8 min). Integrante C

- **Idea clave en pantalla:** `selector { propiedad: valor; }`
- **Qué decir:** CSS no cambia el contenido, solo cómo se ve. Hay tres selectores: de elemento (`h1`), de clase (`.destacado`) y de id (`#titulo-principal`).
- **Demo:** pegar el HTML en el panel HTML y completar los PASOS 1 al 4 en el panel CSS.
- **Pausa de práctica:** "Pausa y cambia los colores por tus favoritos." (Mostrar el selector de color de CodePen.)

## Lección 6: Estilos simples (8 min). Integrante C

- **Idea clave en pantalla:** `margin` = espacio afuera · `padding` = espacio adentro · `border` = el borde
- **Qué decir:** explicar la diferencia entre centrar texto (`text-align`) y centrar una caja (`margin: 0 auto`).
- **Demo:** PASOS 1 al 4 y luego el RETO.
- **Pausa de práctica:** "Pausa y prueba otros tipos de borde: `dotted`, `double`, `solid`."

## Lección 7: Proyecto, tu página de perfil (10 min). Integrante D

- **Idea clave en pantalla:** ¡Junta todo lo que aprendiste!
- **Qué decir:** `header`, `main`, `section` y `footer` sirven para ordenar la página en partes. Recordar brevemente cada lección anterior mientras se usa.
- **Demo:** completar los PASOS 1 al 9. Al final, mostrar el botón de guardar o compartir de CodePen.
- **Pausa de práctica:** "Pausa y personaliza tu perfil: tu nombre, tus pasatiempos y tus colores."

## Lección 8: Detective de errores y próximos pasos (6 min). Integrante D

- **Idea clave en pantalla:** Todos cometemos errores. Lo importante es saber encontrarlos.
- **Qué decir:** los 4 errores típicos de HTML (etiquetas que no coinciden, etiquetas sin cerrar, falta de `alt`, enlaces sin `https://`) y los 4 de CSS (falta `;`, propiedad mal escrita, falta el punto de la clase, falta `}`).
- **Demo:** pegar el `starter` y dar 1 minuto de reto: "Pausa y busca los errores". Luego corregir uno por uno.
- **Cierre:** recomendar MDN y validator.w3.org, felicitar y animar a compartir su página.
