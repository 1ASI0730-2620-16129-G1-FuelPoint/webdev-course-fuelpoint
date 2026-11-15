# Fundamentos de Desarrollo Web

## Resumen del Curso

Este curso introductorio de aproximadamente 1 hora guía a estudiantes de secundaria en la creación de sitios web sencillos desde cero utilizando HTML y CSS. **¡No requiere descargas!** Solo necesitas tu navegador web.

- **Duración total**: ~60 minutos
- **Público objetivo**: Estudiantes de secundaria (12 a 17 años) sin experiencia previa en programación
- **Prerrequisitos**: Ninguno
- **Herramientas necesarias**: Navegador web (Chrome, Firefox, Safari o Edge) y editores en línea (CodePen, JSFiddle o Replit)
- **Lista de reproducción en YouTube**: [Curso completo de HTML y CSS (Playlist)](https://youtube.com/playlist?list=PLFNoV-_eWwFQ&si=3nSYAdbMrG5S2MLr)
- **Repositorio de código fuente**: [https://github.com/1ASI0730-2620-16129-G1-FuelPoint/webdev-course-fuelpoint](https://github.com/1ASI0730-2620-16129-G1-FuelPoint/webdev-course-fuelpoint)

---

## Secuencia de lecciones

### Lección 1: ¿Qué es un sitio web? (5 minutos)

- **Descripción**: Aprende qué hay detrás de una página web, la diferencia entre contenido (HTML) y estilo (CSS) mediante la analogía de la casa, y cómo probar tus primeras líneas de código directamente en el navegador usando CodePen.
- **Consejos clave**: Sitios web = Contenido (`HTML`) + Estilo (`CSS`). Un editor en línea como CodePen permite escribir código a la izquierda y ver el resultado al instante a la derecha, sin descargas.
- **Video**: [Ver lección en YouTube](https://youtu.be/YaChPShdf-A)
- **Empieza a programar**: [Abrir CodePen](https://codepen.io/pen) (editor en línea sin instalaciones)
- **Archivos de práctica**: [Archivo inicial](starter-files/leccion-01/index.html) · [Ejemplo completo](completed-examples/leccion-01/index.html) · [Estilos CSS](completed-examples/leccion-01/style.css) · [Guion](scripts/leccion-01/guion-leccion-01.md)

### Lección 2: La estructura de una página HTML (7 minutos)

- **Descripción**: Comprende qué son las etiquetas (`<p>`, `</p>`), los elementos y los atributos, y construye paso a paso el esqueleto completo de una página web (`<!DOCTYPE html>`, `<html>`, `<head>` y `<body>`).
- **Consejos clave**: Todo documento HTML comienza con `<!DOCTYPE html>` dentro de `<html lang="es">`; el `<head>` guarda metadatos como `<meta charset="UTF-8">` y `<title>`, mientras que el `<body>` contiene todo lo visible (`<h1>`, `<p>`). Cierra siempre cada etiqueta con `/` y utiliza comillas rectas en los atributos como `title`.
- **Video**: [Ver lección en YouTube](https://youtu.be/gnN7IYBbT4Q)
- **Práctica**: [Abrir CodePen](https://codepen.io/pen) (no requiere registro)
- **Archivos de práctica**: [Archivo inicial](starter-files/leccion-02/index.html) · [Ejemplo completo](completed-examples/leccion-02/index.html) · [Guion](scripts/leccion-02/guion-leccion-02.md)

### Lección 3: Títulos, párrafos y listas (8 minutos)

- **Descripción**: Organiza el contenido de una página web utilizando jerarquía de encabezados (`<h1>` a `<h6>`), párrafos, énfasis con `<strong>` y listas con viñetas (`<ul>`) o numeradas (`<ol>`).
- **Consejos clave**: Usa un único `<h1>` principal por página, reserva `<h2>` y `<h3>` para subtítulos y recuerda que cada ítem dentro de `<ul>` o `<ol>` va envuelto en `<li>`.
- **Video**: [Ver lección en YouTube](https://youtu.be/vg8cPlvLH8E)
- **Práctica**: [Abrir CodePen](https://codepen.io/pen) (no requiere registro)
- **Archivos de práctica**: [Archivo inicial](starter-files/leccion-03/index.html) · [Ejemplo completo](completed-examples/leccion-03/index.html) · [Guion](scripts/guiones.md#lección-3-títulos-párrafos-y-listas-8-min-integrante-b)

### Lección 4: Imágenes y enlaces (7 minutos)

- **Descripción**: Incorpora imágenes con `<img>` y enlaces externos con `<a>` para conectar tu página con otros sitios web de forma accesible.
- **Consejos clave**: `<img>` no lleva etiqueta de cierre; indica la ruta en `src` y describe la imagen en `alt` para lectores de pantalla. En `<a>` usa `href` con `https://` completo y `target="_blank"` para abrir en una nueva pestaña.
- **Video**: [Ver lección en YouTube](https://youtu.be/d1xERCYz5NM)
- **Práctica**: [Abrir CodePen](https://codepen.io/pen) (no requiere registro)
- **Archivos de práctica**: [Archivo inicial](starter-files/leccion-04/index.html) · [Ejemplo completo](completed-examples/leccion-04/index.html) · [Guion](scripts/guiones.md#lección-4-imágenes-y-enlaces-7-min-integrante-b)

### Lección 5: Introducción a CSS (8 minutos)

- **Descripción**: Da color y formato a tu página HTML escribiendo tus primeras reglas CSS (`selector { propiedad: valor; }`) y aplicando selectores de elemento (`body`, `h1, h2`), de clase (`.destacado`) y de identificador (`#titulo-principal`).
- **Consejos clave**: El selector define a quién aplicas el estilo: por nombre de etiqueta (`body`), con punto para clases reutilizables (`.destacado`) y con numeral para elementos únicos (`#titulo-principal`). No olvides cerrar cada declaración con `;`.
- **Video**: [Ver lección en YouTube](https://youtu.be/IKArYzcWaBE)
- **Práctica**: [Abrir CodePen](https://codepen.io/pen) (no requiere registro)
- **Archivos de práctica**: [HTML inicial](starter-files/leccion-05/index.html) · [CSS inicial](starter-files/leccion-05/style.css) · [HTML completo](completed-examples/leccion-05/index.html) · [CSS completo](completed-examples/leccion-05/style.css)

### Lección 6: Estilos simples: centrar, bordes y espacios (8 minutos)

- **Descripción**: Controla la distribución visual entendiendo el modelo de caja básico (`margin`, `padding` y `border`), centra bloques completos y texto, y aplica esquinas redondeadas con `border-radius`.
- **Consejos clave**: `text-align: center` centra el texto dentro de su contenedor, mientras que `margin: 0 auto` (junto con `max-width`) centra la caja completa en pantalla; `padding` da respiro interior y `border` define grosor, tipo (`solid`, `dashed`, `dotted`, `double`) y color.
- **Video**: [Ver lección en YouTube](https://youtu.be/_U5hqKsP3QU)
- **Práctica**: [Abrir CodePen](https://codepen.io/pen) (no requiere registro)
- **Archivos de práctica**: [HTML inicial](starter-files/leccion-06/index.html) · [CSS inicial](starter-files/leccion-06/style.css) · [HTML completo](completed-examples/leccion-06/index.html) · [CSS completo](completed-examples/leccion-06/style.css)

### Lección 7: Proyecto: tu página de perfil (10 minutos)

- **Descripción**: Integra todo lo aprendido de HTML y CSS junto con etiquetas semánticas (`<header>`, `<main>`, `<section>` y `<footer>`) para construir desde cero una página de perfil personal con foto circular y tarjetas estilizadas.
- **Consejos clave**: Usa `<header>`, `<main>`, `<section>` y `<footer>` para estructurar el contenido con claridad; convierte tu avatar en círculo con `border-radius: 50%` y crea tarjetas con fondo blanco, `padding`, `border-radius` y `box-shadow`.
- **Video**: [Ver lección en YouTube](https://youtu.be/sTdXPLbCmOQ)
- **Práctica**: [Abrir CodePen](https://codepen.io/pen) (no requiere registro)
- **Archivos de práctica**: [HTML inicial](starter-files/leccion-07/index.html) · [CSS inicial](starter-files/leccion-07/style.css) · [HTML completo](completed-examples/leccion-07/index.html) · [CSS completo](completed-examples/leccion-07/style.css)

### Lección 8: Detective de errores y próximos pasos (6 minutos)

- **Descripción**: Aprende a identificar y corregir los 4 errores más frecuentes en HTML y los 4 errores clásicos en CSS, valida código con herramientas oficiales de la W3C y descubre cómo seguir avanzando con MDN y JavaScript.
- **Consejos clave**: Cierra cada etiqueta apenas la abras, verifica que las URLs incluyan `https://`, revisa los `;` y llaves `}` en CSS, antepón `.` a las clases y apóyate en el [Validador de HTML](https://validator.w3.org/).
- **Video**: Pendiente de publicación
- **Práctica**: [Abrir CodePen](https://codepen.io/pen) (no requiere registro)
- **Archivos de práctica**: [HTML inicial](starter-files/leccion-08/index.html) · [CSS inicial](starter-files/leccion-08/style.css) · [HTML completo](completed-examples/leccion-08/index.html) · [CSS completo](completed-examples/leccion-08/style.css)

---

## Recursos Adicionales

- **Lista de reproducción completa**: [Curso de HTML y CSS en YouTube](https://youtube.com/playlist?list=PLFNoV-_eWwFQ&si=3nSYAdbMrG5S2MLr)
- **Código fuente completo**: [Repositorio de GitHub](https://github.com/1ASI0730-2620-16129-G1-FuelPoint/webdev-course-fuelpoint)
- **Documentación y validación recomendada**: [MDN Web Docs en español](https://developer.mozilla.org/es/docs/Learn) · [Validador W3C de HTML](https://validator.w3.org/)
- **Actividades prácticas**:

| Lección | Actividad | Enlace en línea |
|---|---|---|
| 1 | Tu primera página con HTML y CSS (`<h1>`, `<p>` y estilo básico) | [CodePen](https://codepen.io/pen) |
| 2 | Esqueleto completo de una página HTML (`head`, `body` y atributos) | [CodePen](https://codepen.io/pen) |
| 3 | Títulos jerárquicos (`h1`–`h6`), párrafos y listas (`ul`, `ol`, `li`) | [CodePen](https://codepen.io/pen) |
| 4 | Insertar imágenes accesibles (`img`, `alt`) y enlaces externos (`a`) | [CodePen](https://codepen.io/pen) |
| 5 | Reglas CSS y selectores de elemento, clase (`.clase`) e id (`#id`) | [CodePen](https://codepen.io/pen) |
| 6 | Centrado, bordes (`border`, `border-radius`) y espaciado (`margin`, `padding`) | [CodePen](https://codepen.io/pen) |
| 7 | Proyecto final: página de perfil con estructura semántica y tarjetas | [CodePen](https://codepen.io/pen) |
| 8 | Detective de errores: depuración de 4 fallos HTML y 4 fallos CSS | [CodePen](https://codepen.io/pen) |

---

## Elaboración

- **Universidad**: Universidad Peruana de Ciencias Aplicadas
- **Carrera**: Ingeniería de Software
- **Período**: 202620
- **Curso**: 1ASI0730 Aplicaciones Web
- **NRC**: 16129
- **Nombre del equipo**: FuelPoint
- **Líder del equipo**: Corvacho Damian, Brayan Alexis
- **Integrantes del equipo**:
  - Corvacho Damian, Brayan Alexis
  - Huingo Tello, Frank Anthony
  - Mantilla Maldonado, Enrique Manuel
  - Payano Puchuri, Joan Fabricio
- **Fecha de entrega**: Noviembre de 2026
