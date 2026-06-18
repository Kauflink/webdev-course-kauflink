# Fundamentos de Desarrollo Web para Principiantes (HTML y CSS)

## Resumen del Curso

Este curso de 1 hora introduce a estudiantes de secundaria a los fundamentos del desarrollo web con **HTML y CSS**. Al final crearás tu propia página de perfil. **¡No requiere descargas!** Solo abre tu navegador web.

- **Duración total**: ~60 minutos
- **Público objetivo**: Estudiantes de 12 a 17 años sin experiencia en programación
- **Prerrequisitos**: Ninguno
- **Herramientas necesarias**: ¡Solo tu navegador web! (Chrome, Firefox, Safari, Edge)
- **Editor en línea recomendado**: [CodePen](https://codepen.io) — gratis, sin instalar nada y con vista previa en vivo
- **Repositorio de código fuente**: [https://github.com/Kauflink/webdev-course-kauflink](https://github.com/Kauflink/webdev-course-kauflink)

---

## Secuencia de la Lección

---

### Lección 1: Introducción al Desarrollo Web (8 minutos)

**Dificultad**: ⭐☆☆☆☆ Principiante absoluto

- **Descripción**: Descubre qué es un sitio web y cómo funciona. Escribirás tu primera página web con un título y un párrafo.
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=REEMPLAZAR-LINK1)

#### Objetivos

Al finalizar esta lección podrás:

- Explicar qué es un sitio web y qué hace el navegador.
- Distinguir entre estructura (HTML) y estilo (CSS).
- Escribir y ver tu primera página web.

#### Contenido

**¿Qué es un sitio web?**

Un sitio web es un conjunto de páginas que tu navegador (Chrome, Firefox, etc.) muestra en pantalla. Cada vez que visitas una página, el navegador lee un archivo de texto especial y lo dibuja como texto, imágenes y colores.

**HTML y CSS — el equipo perfecto**

Piensa en una página web como una casa:

| Tecnología | ¿Qué hace?                | Analogía              |
| ---------- | ------------------------- | --------------------- |
| **HTML**   | Da la **estructura**      | Las paredes y cuartos |
| **CSS**    | Da el **estilo**          | La pintura y los muebles |

**Tu primera página web**

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <title>Mi primera página web</title>
  </head>
  <body>
    <h1>¡Hola, mundo!</h1>
    <p>Esta es mi primera página web.</p>
  </body>
</html>
```

| Parte           | ¿Qué hace?                                  |
| --------------- | ------------------------------------------- |
| `<!DOCTYPE html>` | Indica que el documento es HTML           |
| `<head>`        | Información que no se ve (título, idioma)   |
| `<body>`        | Todo lo que **sí** se ve en la página       |
| `<h1>`          | Un título grande                            |
| `<p>`           | Un párrafo de texto                         |

> **Pausa y prueba:** pausa el video, copia la página en el editor en línea y obsérvala antes de continuar.

#### Práctica

**Empieza a programar**: [Abrir en CodePen – Primera Página](https://codepen.io/pen/REEMPLAZAR-L1)

**Ejercicio**: Cambia el texto del `<h1>` por `"¡Hola, me llamo [tu nombre]!"` y escribe un párrafo sobre ti.

#### Conclusiones clave

- Un sitio web es texto que el navegador convierte en una página.
- HTML da la estructura; CSS da el estilo.
- Lo que se ve va dentro de `<body>`.

---

### Lección 2: Estructura HTML Básica (10 minutos)

**Dificultad**: ⭐⭐☆☆☆ Básico

- **Descripción**: Aprende las piezas del HTML: etiquetas, elementos y atributos. Crearás una página "Sobre mí".
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=REEMPLAZAR-LINK2)

#### Objetivos

Al finalizar esta lección podrás:

- Diferenciar entre etiqueta, elemento y atributo.
- Reconocer la estructura mínima de un documento HTML.
- Crear una página "Sobre mí".

#### Contenido

**Etiquetas, elementos y atributos**

```html
<a href="https://google.com">Visita Google</a>
```

| Concepto    | Ejemplo                       | Explicación                              |
| ----------- | ----------------------------- | ---------------------------------------- |
| **Etiqueta**| `<a>` ... `</a>`              | Marca el inicio y el fin                 |
| **Elemento**| `<a>Visita Google</a>`       | La etiqueta + su contenido               |
| **Atributo**| `href="https://google.com"`  | Información extra dentro de la etiqueta   |

> La mayoría de las etiquetas se **abren y se cierran**: `<p>texto</p>`. La etiqueta de cierre lleva una barra `/`.

**El esqueleto de toda página**

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <title>Sobre mí</title>
  </head>
  <body>
    <h1>Sobre mí</h1>
    <p>Me llamo Ana y tengo 15 años.</p>
  </body>
</html>
```

> **Pausa y prueba:** cambia el texto del `<title>` y observa cómo cambia el nombre de la pestaña del navegador.

**Errores comunes**

- Olvidar cerrar una etiqueta: ~~`<p>Hola`~~ → `<p>Hola</p>`
- Poner contenido visible dentro de `<head>` en vez de `<body>`.

#### Práctica

**Práctica**: [Abrir en CodePen – Estructura HTML](https://codepen.io/pen/REEMPLAZAR-L2)

**Ejercicio**: Crea una página "Sobre mí" con un `<h1>` y dos párrafos: uno con tu nombre y edad, otro con tu color favorito.

#### Conclusiones clave

- Un **elemento** es la etiqueta más su contenido.
- Los **atributos** dan información extra (como `href` o `lang`).
- Toda página tiene `<head>` (no visible) y `<body>` (visible).

---

### Lección 3: Elementos HTML Comunes (10 minutos)

**Dificultad**: ⭐⭐☆☆☆ Básico

- **Descripción**: Usa los elementos más comunes: encabezados, párrafos, listas, imágenes y enlaces. Crearás una página de pasatiempos.
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=REEMPLAZAR-LINK3)

#### Objetivos

Al finalizar esta lección podrás:

- Usar encabezados y párrafos para organizar texto.
- Crear listas con `<ul>` y `<li>`.
- Insertar imágenes con `<img>` y enlaces con `<a>`.

#### Contenido

**Encabezados y párrafos**

```html
<h1>Título principal</h1>
<h2>Subtítulo</h2>
<p>Un párrafo de texto normal.</p>
```

Hay seis niveles de encabezado, de `<h1>` (el más grande) a `<h6>` (el más pequeño).

**Listas**

```html
<ul>
  <li>Tocar guitarra</li>
  <li>Jugar fútbol</li>
  <li>Leer historietas</li>
</ul>
```

- `<ul>` crea una lista con viñetas (*unordered list*).
- Cada `<li>` es un elemento de la lista (*list item*).

**Imágenes y enlaces**

```html
<img src="https://picsum.photos/300/200" alt="Una foto de ejemplo" />

<a href="https://developer.mozilla.org/es/">Aprende más en MDN</a>
```

| Atributo | ¿Para qué sirve?                                  |
| -------- | ------------------------------------------------- |
| `src`    | La dirección de la imagen                         |
| `alt`    | Texto que describe la imagen (importante)         |
| `href`   | La dirección a la que lleva el enlace             |

> **Pausa y prueba:** cambia el número en `picsum.photos/300/200` (por ejemplo a `400/250`) y mira cómo cambia el tamaño de la imagen.

#### Práctica

**Práctica**: [Abrir en CodePen – Elementos Comunes](https://codepen.io/pen/REEMPLAZAR-L3)

**Ejercicio**: Crea una página de pasatiempos con un subtítulo `<h2>`, una lista de 3 pasatiempos, una imagen y un enlace a tu página favorita.

#### Conclusiones clave

- Los encabezados (`<h1>`–`<h6>`) y `<p>` organizan el texto.
- Las listas usan `<ul>` con varios `<li>` dentro.
- `<img>` necesita `src` y `alt`; `<a>` necesita `href`.

---

### Lección 4: Introducción a CSS (10 minutos)

**Dificultad**: ⭐⭐⭐☆☆ Intermedio básico

- **Descripción**: Dale color y estilo a tu página con CSS. Aprenderás selectores y propiedades básicas.
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=REEMPLAZAR-LINK4)

#### Objetivos

Al finalizar esta lección podrás:

- Entender qué es CSS y cómo se conecta con el HTML.
- Escribir reglas con selector, propiedad y valor.
- Cambiar colores, tipografía y tamaño de letra.

#### Contenido

**¿Qué es CSS?**

CSS (*Cascading Style Sheets*) decide **cómo se ve** cada elemento. Una regla de CSS tiene tres partes:

```css
h1 {
  color: blue;
}
```

| Parte        | Ejemplo  | Significado                       |
| ------------ | -------- | --------------------------------- |
| **Selector** | `h1`     | A qué elemento aplicar el estilo  |
| **Propiedad**| `color`  | Qué quieres cambiar               |
| **Valor**    | `blue`   | El nuevo valor                    |

**Dónde se escribe el CSS**

El CSS va dentro de una etiqueta `<style>` en el `<head>`:

```html
<head>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f4f8;
    }
    h1 {
      color: #1d4ed8;
    }
    p {
      color: #333333;
      font-size: 18px;
    }
  </style>
</head>
```

**Propiedades útiles para empezar**

| Propiedad          | ¿Qué cambia?                |
| ------------------ | --------------------------- |
| `color`            | Color del texto             |
| `background-color` | Color de fondo              |
| `font-family`      | Tipo de letra               |
| `font-size`        | Tamaño de letra             |

> **Pausa y prueba:** cambia el `color` del `<h1>` por tu color favorito (por ejemplo `red` o `#16a34a`) y observa el resultado en vivo.

**Errores comunes**

- Olvidar el `;` al final de cada propiedad.
- Olvidar las llaves `{ }` que rodean las reglas.

#### Práctica

**Práctica**: [Abrir en CodePen – Introducción a CSS](https://codepen.io/pen/REEMPLAZAR-L4)

**Ejercicio**: Dale a tu página un color de fondo, cambia el color del título y el tamaño de letra de los párrafos.

#### Conclusiones clave

- CSS controla el aspecto de la página.
- Cada regla tiene **selector**, **propiedad** y **valor**.
- El CSS interno va dentro de `<style>` en el `<head>`.

---

### Lección 5: Estilo y Página de Perfil (12 minutos)

**Dificultad**: ⭐⭐⭐⭐☆ Intermedio

- **Descripción**: Combina todo lo aprendido para construir una página de perfil real: foto, datos y una tarjeta centrada con bordes y colores.
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=REEMPLAZAR-LINK5)

#### Objetivos

Al finalizar esta lección podrás:

- Agrupar elementos con `<div>` y darles estilo con `class`.
- Centrar contenido y agregar bordes y esquinas redondeadas.
- Construir una página de perfil completa.

#### Contenido

**Clases — estilar un grupo de elementos**

Una **clase** es una etiqueta que tú inventas para aplicar el mismo estilo a uno o varios elementos:

```html
<div class="tarjeta">...</div>
```

```css
.tarjeta {
  /* el punto indica que es una clase */
}
```

**Centrar, bordes y esquinas redondeadas**

```css
.tarjeta {
  max-width: 400px;
  margin: 0 auto;        /* centra la tarjeta horizontalmente */
  border: 2px solid #1d4ed8;
  border-radius: 12px;   /* esquinas redondeadas */
  padding: 24px;
  text-align: center;    /* centra el texto */
}
```

**Página de perfil completa**

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <title>Página de perfil</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #eef2f7;
        padding: 40px;
      }
      .tarjeta {
        max-width: 400px;
        margin: 0 auto;
        background-color: #ffffff;
        border: 2px solid #1d4ed8;
        border-radius: 12px;
        padding: 24px;
        text-align: center;
      }
      .tarjeta img {
        width: 120px;
        height: 120px;
        border-radius: 50%;   /* foto redonda */
        object-fit: cover;
      }
      .tarjeta h1 {
        color: #1d4ed8;
      }
    </style>
  </head>
  <body>
    <div class="tarjeta">
      <img src="https://picsum.photos/200" alt="Foto de perfil" />
      <h1>Ana Torres</h1>
      <p>Estudiante de secundaria · 15 años</p>
      <p>Me encanta dibujar, programar y la astronomía.</p>
    </div>
  </body>
</html>
```

> **Pausa y prueba:** cambia el nombre, la edad y los gustos por los tuyos. Cambia también el color del borde de la tarjeta.

#### Práctica

**Proyecto final**: [Abrir en CodePen – Página de Perfil](https://codepen.io/pen/REEMPLAZAR-L5)

**Ejercicio**: Personaliza la tarjeta de perfil con tus propios datos, tu foto y tu combinación de colores favorita.

#### Conclusiones clave

- Una **clase** permite reutilizar el mismo estilo en varios elementos.
- `margin: 0 auto` centra un bloque; `text-align: center` centra el texto.
- `border-radius: 50%` convierte una imagen cuadrada en redonda.

---

### Lección 6: Buenas Prácticas y Próximos Pasos (10 minutos)

**Dificultad**: ⭐⭐☆☆☆ Básico

- **Descripción**: Aprende a evitar los errores más comunes, escribe código ordenado y descubre qué aprender después de este curso.
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=REEMPLAZAR-LINK6)

#### Objetivos

Al finalizar esta lección podrás:

- Identificar y corregir los errores más comunes en HTML y CSS.
- Escribir código limpio y fácil de leer.
- Saber qué aprender después de este curso.

#### Contenido

**Errores comunes y cómo evitarlos**

| Error                          | Solución                                        |
| ------------------------------ | ----------------------------------------------- |
| No cerrar una etiqueta         | Toda `<p>` necesita su `</p>`                    |
| Imagen sin `alt`               | Siempre describe la imagen: `alt="..."`         |
| Olvidar el `;` en CSS          | Cada propiedad termina en `;`                   |
| Repetir el mismo estilo        | Usa una **clase** reutilizable                  |
| Mezclar mayúsculas en archivos | `foto.png` y `Foto.png` no son lo mismo         |

**Ejemplo: corregir errores**

```html
<!-- Código con errores -->
<h1>Mi página
<img src="foto.png" />
<p>Hola

<!-- Código corregido -->
<h1>Mi página</h1>
<img src="foto.png" alt="Mi foto" />
<p>Hola</p>
```

**Buenas prácticas de escritura**

- Indenta el código para que se lea fácil.
- Usa nombres de clase descriptivos: `.tarjeta` en vez de `.x`.
- Reutiliza clases en lugar de repetir el mismo estilo.
- Pon siempre `alt` en las imágenes.

**¿Qué aprender después?**

- **Más CSS** — Flexbox y Grid para acomodar elementos.
- **Diseño responsive** — que la página se vea bien en celular y computadora.
- **Varias páginas** — crear más páginas y enlazarlas entre sí.
- **JavaScript** — para que la página reaccione e interactúe con el usuario.

**Recursos gratuitos para seguir aprendiendo:**

- [MDN Web Docs (en español)](https://developer.mozilla.org/es/)
- [W3Schools HTML](https://www.w3schools.com/html/) y [W3Schools CSS](https://www.w3schools.com/css/)
- [freeCodeCamp (gratis)](https://www.freecodecamp.org/espanol/)

#### Práctica

**Práctica final**: [Abrir en CodePen – Reto de Errores](https://codepen.io/pen/REEMPLAZAR-L6)

**Reto**: Toma la página con 3 errores, corrígelos todos y aplica una clase `.destacado` que use un color de fondo y un borde a la izquierda.

#### Conclusiones clave

- Leer el código con calma ayuda a encontrar los errores rápido.
- El código limpio es tan importante como el código que funciona.
- Este curso es solo el comienzo — ¡sigue practicando!

---

## Recursos Adicionales

**Código fuente completo**: [Repositorio de GitHub](https://github.com/Kauflink/webdev-course-kauflink)

### Todas las actividades prácticas

| N° de lección | Actividad           | Empezar a programar                                    |
| ------------- | ------------------- | ------------------------------------------------------ |
| 1             | Primera página      | [CodePen](https://codepen.io/pen/REEMPLAZAR-L1)        |
| 2             | Estructura HTML     | [CodePen](https://codepen.io/pen/REEMPLAZAR-L2)        |
| 3             | Elementos comunes   | [CodePen](https://codepen.io/pen/REEMPLAZAR-L3)        |
| 4             | Introducción a CSS  | [CodePen](https://codepen.io/pen/REEMPLAZAR-L4)        |
| 5             | Página de perfil    | [CodePen](https://codepen.io/pen/REEMPLAZAR-L5)        |
| 6             | Reto de errores     | [CodePen](https://codepen.io/pen/REEMPLAZAR-L6)        |

**¡Gracias por completar el curso!**

---

## Elaboración

- Universidad Peruana de Ciencias Aplicadas
- Carrera de Ingeniería de Software
- Período 202610
- 1ASI0730 Aplicaciones Web — NRC REEMPLAZAR-NRC

**Nombre del equipo**: Kauflink

**Líder del equipo**: Joseph Julius Camargo Briceño

**Integrantes del equipo**:

- Lionel Abraham Chavez Carrasco
- Jose Fernando Flores Pinchi
- Elynor Mikela Palma De Los Santos
- Jose Antonio Peirano Brun

### Resumen de la elaboración en equipo

El curso se elaboró de forma colaborativa. El plan de curso, los archivos de práctica y las soluciones de referencia se desarrollaron en este repositorio público de GitHub, donde los commits evidencian el aporte de cada integrante del equipo.

**Fecha de entrega**: REEMPLAZAR-FECHA
