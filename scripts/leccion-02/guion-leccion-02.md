# Guion — Lección 2: La estructura de una página HTML

- **Duración:** ~7 minutos (`06:56`)
- **Editor en línea:** [CodePen](https://codepen.io/pen)
- **Archivos de práctica:**
  - Archivo inicial: [`starter-files/leccion-02/index.html`](../../starter-files/leccion-02/index.html)
  - Ejemplo terminado: [`completed-examples/leccion-02/index.html`](../../completed-examples/leccion-02/index.html)

---

## Parte 1: Teoría inicial (Diapositivas 11 a 13)

### Diapositiva 11: Portada (Nivel 2)
"¡Hola de nuevo! Te doy la bienvenida a la lección 2 del curso Fundamentos de Desarrollo Web. En la lección anterior vimos que el HTML representa el contenido de una página y el CSS su estilo. Hoy vas a dar un gran paso: vas a escribir tu primera página web completa, paso a paso y con su estructura formal."

### Diapositiva 12: Tu misión de hoy
"En este nivel vamos a desbloquear cinco conceptos fundamentales: primero, qué es una etiqueta; segundo, qué es un elemento; tercero, qué son los atributos; y cuarto y quinto, las dos partes principales de todo documento: el `head` y el `body`."

### Diapositiva 13: ¿Qué es una etiqueta y un elemento?
"Para comunicarnos con el navegador utilizamos etiquetas. Una etiqueta es una palabra clave rodeada por los signos de menor que y mayor que, como por ejemplo la letra `p`, que representa un párrafo.

Casi todas las etiquetas funcionan en pareja: una etiqueta de apertura para indicar dónde empieza, y una etiqueta de cierre para indicar dónde termina. La de cierre se escribe exactamente igual, pero añadiendo una barra diagonal antes del nombre.

Lo que colocamos en medio es el contenido. Y a todo el conjunto completo —la apertura, el contenido y el cierre— lo llamamos **elemento**.

Piénsalo como una caja de encomienda: la etiqueta indica qué contiene, y adentro está lo que queremos mostrar.

Ahora, pasemos a nuestro editor en vivo para construir el esqueleto de nuestra página..."

---

## Parte 2: Demostración en vivo en CodePen

### Pasos 1 y 2: `<!DOCTYPE html>` y `<html lang="es">`
- **Acción en pantalla:** En el panel HTML de CodePen (con el panel JS minimizado y vista lateral), escribir la declaración inicial y la etiqueta raíz.

```html
<!DOCTYPE html>
<html lang="es">
```

"Abrí un Pen nuevo para escribir nuestro código.

En el Paso 1, toda página web moderna comienza con `DOCTYPE html`. Esto le dice al navegador: 'prepárate, vas a leer un documento HTML estándar'.

En el Paso 2, abrimos la etiqueta principal: `html`. Todo lo que creemos vivirá dentro de ella. Además, le agregamos el atributo `lang` igual a `'es'` entre comillas, que indica que nuestra página está en español. Esto es clave para que los navegadores y lectores de pantalla la interpreten correctamente."

### Paso 3: El bloque `<head>` (información interna)
- **Acción en pantalla:** Agregar el bloque `<head>` con la codificación de caracteres y el título de la pestaña.

```html
<head>
  <meta charset="UTF-8">
  <title>Sobre mí</title>
</head>
```

"En el Paso 3 creamos el `head`, que significa 'cabeza'. Aquí colocamos datos sobre la página que no se ven directamente en la pantalla.

Primero, `meta charset UTF-8`: esto permite que el navegador muestre tildes y la letra `ñ` sin errores.

Luego, el `title`: el título que aparece en la pestaña del navegador. En este caso le pondré 'Sobre mí'. Y cerramos el `head` con su barra inclinada."

### Pasos 4 y 5: El bloque `<body>` (contenido visible) y cierre
- **Acción en pantalla:** Agregar el bloque `<body>` con `<h1>` y `<p>`, y cerrar `</body>` y `</html>`.

```html
<body>
  <h1>Hola, soy Alex</h1>
  <p>Tengo 14 años y estoy aprendiendo a crear páginas web.</p>
</body>
</html>
```

"Ahora vamos al Paso 4: el `body`, que significa 'cuerpo'. Todo lo que pongamos dentro del `body` es lo que SÍ se va a ver en la pantalla.

Escribo una etiqueta `h1`, que representa nuestro título principal: 'Hola, soy Alex'.

Y luego agrego una etiqueta `p`, un párrafo donde escribo: 'Tengo 14 años y estoy aprendiendo a crear páginas web'.

Fíjate en la vista previa a la derecha: ¡ya aparece nuestro texto en pantalla!

Finalmente, en el Paso 5 cerramos el `body` y cerramos la etiqueta `html`. Siempre es una buena costumbre cerrar cada etiqueta que abres."

### Atributos HTML: El atributo `title`
- **Acción en pantalla:** Añadir un segundo párrafo con el atributo `title` y pasar el cursor encima en la vista previa para mostrar el texto flotante.

```html
  <p title="¡Hola! Soy un atributo title">Pasa el mouse sobre este párrafo.</p>
```

"Antes de terminar, veamos qué es un atributo. Un atributo es información adicional que colocamos dentro de la etiqueta de apertura con un nombre, el signo igual y su valor entre comillas.

Por ejemplo, si a este nuevo párrafo le agrego el atributo `title` con un mensaje… mira lo que pasa en la vista previa: al pasar el mouse por encima, ¡aparece un pequeño mensaje flotante! Los atributos le dan superpoderes y datos extra a nuestras etiquetas."

---

## Parte 3: Resumen, errores típicos y cierre (Diapositivas 18 a 22)

### Diapositiva 18: El esqueleto de toda página
"¡Resumamos lo que acabamos de construir! Todo en una página web va dentro de la gran caja `html`. Y adentro hay dos partes fundamentales: el `head`, que guarda la información sobre la página que el navegador necesita pero no muestra en pantalla; y el `body`, que contiene absolutamente todo lo que sí se ve: los títulos, párrafos e imágenes. ¡Esta misma estructura es la que usan todas las páginas web del mundo!"

### Diapositiva 19: GAME OVER: Errores típicos
"Ojo con estos tres errores típicos que a todos nos pasan al inicio:

El primero: olvidarte del slash al cerrar una etiqueta. Recuerda que si abres con `<p>`, tienes que cerrar con `</p>`. Si no le pones la barra, el navegador pensará que estás abriendo un párrafo nuevo.

El segundo error es meter contenido dentro del `head`. Recuerda la regla: todo lo que quieres que aparezca en pantalla va siempre dentro del `body`.

Y el tercero: las comillas raras. A veces, si copias código desde Word o WhatsApp, las comillas se pegan curvadas y rompen la página. Usa siempre las comillas rectas normales de tu teclado."

### Diapositiva 20: Elementos desbloqueados
"¡Miremos todo lo que desbloqueaste en este nivel! Aprendiste qué es una etiqueta con su apertura y cierre; qué es un elemento completo; cómo funcionan los atributos para darle información extra a las etiquetas; y dominaste el esqueleto web: la etiqueta `html`, el `head` y el `body`."

### Diapositiva 21: ¡Pausa el video y practica! (Misión extra)
"¡Ahora es tu turno de ponerte a prueba! Ponle pausa al video, abre tu CodePen y completa la misión extra: agrega un segundo párrafo contando qué es lo que más te gusta hacer, como tus pasatiempos o tus juegos favoritos. Recuerda abrir tu etiqueta `<p>` y cerrarla correctamente con `</p>`. ¡Pausa el video y dale!"

### Diapositiva 22: Nivel 2 completado
"¡Excelente trabajo! Ya escribiste tu primera página web con su estructura completa y válida. En el Nivel 3 aprenderemos a usar diferentes niveles de títulos, formatear textos y organizar todo con listas. ¡Sube de nivel y nos vemos en la próxima lección!"

---

## Capítulos del video

- `00:00` - Introducción y Tu Misión de Hoy (Nivel 2)
- `00:25` - ¿Qué es una etiqueta y un elemento HTML?
- `01:43` - Demostración en vivo en CodePen (`DOCTYPE`, `html`, `head` y `body`)
- `04:35` - El esqueleto de toda página web
- `05:05` - GAME OVER: 3 errores típicos al comenzar
- `05:51` - Elementos desbloqueados del Nivel 2
- `06:12` - ¡Pausa el video y practica! (Misión extra)
- `06:36` - Nivel 2 Completado y Próximos Pasos (Rumbo al Nivel 3)
