# Guion — Lección 1: ¿Qué es un sitio web?

- **Duración:** ~5 minutos (`05:12`)
- **Editor en línea:** [CodePen](https://codepen.io/pen)
- **Archivos de práctica:**
  - Archivo inicial: [`starter-files/leccion-01/index.html`](../../starter-files/leccion-01/index.html)
  - Ejemplo terminado: [`completed-examples/leccion-01/index.html`](../../completed-examples/leccion-01/index.html) y [`completed-examples/leccion-01/style.css`](../../completed-examples/leccion-01/style.css)

---

## Parte 1: Teoría (Diapositivas 1 a 4)

### Diapositiva 1: Portada (Nivel 1)
"¡Hola! Bienvenido al curso Fundamentos de Desarrollo Web. En este curso vas a aprender a crear tu propia página web desde cero. Y lo mejor de todo: no necesitas instalar absolutamente ningún programa, solo vas a utilizar tu navegador de internet. En esta primera lección vas a descubrir de qué está hecha realmente una página web."

### Diapositiva 2: Tu misión de hoy
"Hoy vamos a desbloquear tres conceptos fundamentales: primero, qué es HTML; segundo, qué es CSS; y tercero, qué papel cumple tu navegador web con ellos. Al finalizar esta lección, tendrás claro que todo sitio web se compone de contenido más estilo."

### Diapositiva 3: ¿Qué hay detrás de una página?
"Todos los días navegas por internet: para ver videos, buscar información de tus tareas o jugar en línea. Pero ¿alguna vez te preguntaste qué hay detrás de esas páginas?

Por dentro, una página web no es magia: es simplemente un archivo de texto con instrucciones. Tu navegador —que puede ser Google Chrome, Edge o Firefox— lee esas instrucciones línea por línea y las transforma en lo que tú ves en pantalla: textos, títulos, colores, imágenes y botones. Aunque al principio el código parezca difícil, en este curso verás lo sencillo que es entenderlo."

### Diapositiva 4: HTML y CSS como una casa
"Para crear páginas web utilizamos principalmente dos lenguajes: HTML y CSS.

Imagina que estás construyendo una casa. HTML representa las paredes, las puertas, las ventanas y las habitaciones: es todo lo que HAY en la casa, es decir, el contenido.

Por otro lado, CSS es la pintura, el color de las paredes, la textura del piso y la decoración: representa CÓMO SE VE la casa.

Una casa sin pintura sigue siendo una casa, pero se vería bastante apagada y fría, ¿verdad? Con las páginas web pasa exactamente lo mismo: el HTML estructura el contenido y el CSS se encarga de darle vida y estilo.

Ahora, vamos a verlo en acción en nuestro editor en línea CodePen..."

---

## Parte 2: Demostración en vivo en CodePen

### Paso 1: Solo texto plano (sin etiquetas)
- **Acción en pantalla:** Pegar el texto inicial en el panel HTML y señalar el resultado en el panel derecho.

```text
Hola, esta es mi primera página web.
Me gusta el fútbol, la música y los videojuegos.
```

"Esto es CodePen, un editor que funciona directo en el navegador. A la izquierda escribimos el código y a la derecha vemos el resultado al instante.

Voy a escribir dos frases sobre mí, cada una en su propia línea... Pero mira el resultado a la derecha: ¡aparece todo pegado en un solo renglón! El navegador no sabe qué es un título y qué es un párrafo. Para él, es solo texto continuo."

### Paso 2: Estructura con HTML (`<h1>` y `<p>`)
- **Acción en pantalla:** Reemplazar el texto plano en el panel HTML con las etiquetas `<h1>` y `<p>`.

```html
<h1>Hola, esta es mi primera página web</h1>
<p>Me gusta el fútbol, la música y los videojuegos.</p>
```

"Ahora voy a usar HTML para darle orden y significado. Le indico al navegador que la primera línea es un `h1`, es decir, el título principal; y que la segunda línea es una `p`, es decir, un párrafo.

¿Ves cómo cambia? Ahora sí hay jerarquía: el título se ve grande e importante, y el párrafo se separa automáticamente abajo."

### Paso 3: Estilo y color con CSS
- **Acción en pantalla:** Pegar las reglas CSS en el panel CSS.

```css
body {
  background-color: #fdf6e3;
  font-family: Arial, Helvetica, sans-serif;
}

h1 {
  color: #2a7ae2;
}
```

"Pero todavía se ve muy simple, en blanco y negro. Aquí es donde entra CSS.

En el panel de CSS, le voy a decir que el fondo tenga un color crema suave, que use una tipografía más moderna y que el título principal sea de color azul. ¡Mira qué cambio!"

### Paso 4: Demostración sin CSS vs. con CSS
- **Acción en pantalla:** Seleccionar todo el panel CSS, cortarlo temporalmente para ver la vista sin estilos, y volverlo a pegar.

"Fíjate en esto: si corto el CSS, el contenido sigue estando ahí, pero perdió todo el estilo.

Y si lo vuelvo a pegar, regresan los colores y la presentación. Por eso decimos siempre: HTML es el QUÉ hay en la página, y CSS es CÓMO se ve."

---

## Parte 3: Reto de práctica

"¡Llegó tu turno! Te reto a poner en práctica lo que acabas de ver.

Abre el enlace de CodePen que tienes disponible en la descripción del video.

Tu misión es muy sencilla: busca en el código la línea del título que dice 'Hola, esta es mi primera página web' y cambia esto colocando tu propio nombre.

Pausa el video y prepárate para practicar."

---

## Parte 4: Cierre (Diapositivas 8 y 10)

### Diapositiva 8: Elementos desbloqueados
"¡Excelente trabajo! Has completado el primer nivel.

Repasemos los conceptos que desbloqueaste el día de hoy:
- Aprendiste que HTML define el QUÉ, es decir, el contenido de la página.
- Que CSS define el CÓMO, que es el estilo, los colores y las fuentes.
- Que el navegador web es el encargado de leer tus instrucciones y dibujarlas en pantalla.
- Y que con editores en línea como CodePen puedes programar al instante sin descargar nada."

### Diapositiva 10: Nivel 1 completado
"¡Nivel 1 completado! Ya diste tu primer gran paso en el desarrollo web.

En la siguiente lección subiremos de nivel: aprenderás a construir la estructura y el esqueleto completo de una página HTML con `head` y `body`.

¡Nos vemos en el Nivel 2!"

---

## Capítulos del video

- `00:00` - Introducción y Portada (Nivel 1)
- `00:20` - ¿Qué es un sitio web? (La analogía de la casa)
- `01:05` - HTML vs. CSS: Estructura y Estilo
- `01:45` - Conociendo el editor CodePen
- `02:29` - Práctica en vivo en CodePen
- `04:32` - ¡Pausa el video y practica! (Misión extra)
- `04:43` - Elementos desbloqueados y Cierre del Nivel 1
