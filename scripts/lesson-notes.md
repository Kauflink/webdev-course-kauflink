# Notas para el Instructor

## Lección 1 — Introducción al Desarrollo Web (8 min)
- **Puntos clave**: Explicar qué es un sitio web con la analogía de "una casa": HTML son las paredes (estructura), CSS es la pintura y decoración (estilo).
- Mostrar que el navegador es el programa que "lee" el HTML y dibuja la página.
- **Sugerencia**: Pedir a cada estudiante que escriba su primer `<h1>` y `<p>` y vea el cambio en vivo en CodePen.
- **Error común a vigilar**: Olvidar cerrar las etiquetas (`</p>`).

## Lección 2 — Estructura HTML Básica (10 min)
- **Puntos clave**: Diferenciar etiqueta, elemento y atributo. Mostrar el esqueleto `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`.
- Aclarar que `<head>` no se ve en la página y `<body>` sí.
- **Sugerencia**: Pedir que cambien el `<title>` y observen la pestaña del navegador.
- **Error común a vigilar**: Poner contenido visible dentro de `<head>` en vez de `<body>`.

## Lección 3 — Elementos HTML Comunes (10 min)
- **Puntos clave**: Encabezados (`<h1>`–`<h6>`), párrafos, listas (`<ul>`/`<li>`), imágenes (`<img>`) y enlaces (`<a>`).
- Recalcar que `<img>` necesita `src` y `alt`, y que `<a>` necesita `href`.
- **Sugerencia**: Que armen una mini página de pasatiempos con los cinco elementos.
- **Error común a vigilar**: Olvidar el atributo `alt` en las imágenes.

## Lección 4 — Introducción a CSS (10 min)
- **Puntos clave**: CSS da estilo. Mostrar la idea de selector + propiedad + valor (`h1 { color: blue; }`).
- Presentar `color`, `background-color`, `font-family`, `font-size`.
- Explicar el CSS interno dentro de `<style>` en el `<head>`.
- **Sugerencia**: Que cambien colores y vean el resultado en vivo.
- **Error común a vigilar**: Olvidar el `;` al final de cada propiedad o las llaves `{ }`.

## Lección 5 — Estilo y Página de Perfil (12 min)
- **Puntos clave**: Combinar HTML y CSS para construir una página de perfil real: centrar contenido (`margin: 0 auto`, `text-align`), colores, bordes (`border`, `border-radius`).
- Introducir el atributo `class` y el selector `.clase`.
- **Sugerencia**: Que personalicen la tarjeta con sus propios datos y foto.
- **Error común a vigilar**: Confundir el selector de clase (`.tarjeta`) con el de etiqueta (`tarjeta`).

## Lección 6 — Buenas Prácticas y Próximos Pasos (10 min)
- **Puntos clave**: Cerrar siempre las etiquetas, usar `alt` en imágenes, indentar el código, reutilizar clases en vez de repetir estilos.
- Mostrar la página con 3 errores y pedir que los identifiquen antes de revelar la solución.
- **Próximos pasos sugeridos**: Diseño responsive, Flexbox, agregar más páginas y enlazarlas, aprender JavaScript.
- **Error común a vigilar**: Repetir el mismo estilo en muchos elementos en lugar de usar una clase.
