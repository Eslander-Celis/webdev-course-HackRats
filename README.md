# Fundamentos de Desarrollo Web

## Resumen del curso

Este curso introduce los fundamentos del desarrollo web para estudiantes de secundaria de 12 a 17 años sin experiencia previa. La propuesta está organizada en seis lecciones en video, con una duración total aproximada de 60 minutos, y desarrolla los conceptos de forma progresiva hasta llegar a la creación de una página web personal utilizando HTML y CSS.

El curso no requiere la instalación de herramientas. Las prácticas se realizan en editores gratuitos en línea, accesibles desde navegadores web como Chrome, Firefox, Safari o Edge.

**Duración total:** 60 minutos aproximadamente  
**Número de lecciones:** 6 videos  
**Público objetivo:** estudiantes de secundaria sin experiencia previa en desarrollo web  
**Prerrequisitos:** ninguno  
**Herramientas:** CodePen, JSFiddle, Replit y GitHub  
**Repositorio de código fuente:** [webdev-course-HackRats](https://github.com/Eslander-Celis/webdev-course-HackRats)

## Objetivos de aprendizaje

Al finalizar el curso, los estudiantes serán capaces de:

- Comprender qué es el desarrollo web y cómo funciona un sitio web.
- Identificar la función de HTML y CSS.
- Utilizar etiquetas HTML para organizar contenido.
- Crear encabezados, párrafos, listas, enlaces e imágenes.
- Comprender la estructura básica de un documento HTML.
- Aplicar estilos utilizando selectores y propiedades CSS.
- Modificar colores, fuentes, bordes y espacios.
- Organizar el contenido de una página web sencilla.
- Utilizar un editor de código en línea.
- Crear una página web personal combinando HTML y CSS.
- Reconocer errores comunes de HTML y CSS.

## Secuencia de lecciones

| Lección | Tema | Duración estimada | Video | Práctica en línea |
| --- | --- | ---: | --- | --- |
| 1 | Introducción al desarrollo web | 5 min | [Ver video](ENLACE_VIDEO_1) | [Abrir práctica](ENLACE_PRACTICA_1) |
| 2 | Introducción a HTML: etiquetas, encabezados y párrafos | 10 min | [Ver video](https://youtu.be/4yWCF0tRrDE) | [Abrir práctica](https://codepen.io/Aaron-Avila-the-decoder/pen/RNKpRjO) |
| 3 | Listas, imágenes y enlaces en HTML | 8 min | [Ver video](https://youtu.be/tGYp4UMkm9k) | [Abrir práctica](https://codepen.io/Mathias-Arechaga/pen/BypWzbK) |
| 4 | Introducción a CSS: colores, fuentes y selectores | 12 min | [Ver video](ENLACE_VIDEO_4) | [Abrir práctica](ENLACE_PRACTICA_4) |
| 5 | Creación de una página web personal | 15 min | [Ver video](ENLACE_VIDEO_5) | [Abrir práctica](ENLACE_PRACTICA_5) |
| 6 | Errores comunes, recomendaciones y próximos pasos | 10 min | [Ver video](ENLACE_VIDEO_6) | [Abrir práctica](ENLACE_PRACTICA_6) |

## Lección 1: Introducción al desarrollo web

La primera lección presenta el desarrollo web como el proceso de creación de sitios y aplicaciones que funcionan mediante un navegador. Se explica de manera sencilla qué ocurre cuando una persona ingresa a una página web y cuál es la función de HTML y CSS.

También se presenta HTML como la estructura y el contenido de una página, mientras que CSS se encarga de modificar su apariencia visual.

**Conceptos principales:**

- Desarrollo web.
- Sitios web.
- Navegadores.
- HTML.
- CSS.
- Editores de código en línea.
- Estructura y estilo de una página.

**Actividad:** observar una página web e identificar qué elementos corresponden al contenido y cuáles pertenecen al estilo visual.

## Lección 2: Introducción a HTML

La segunda lección explica qué es HTML y cómo se utiliza para organizar el contenido de una página web. Se presenta el concepto de etiqueta y se explica la diferencia entre una etiqueta de apertura, el contenido y una etiqueta de cierre.

Durante la práctica, el estudiante crea una página personal sencilla utilizando encabezados, subtítulos, párrafos y texto destacado en CodePen.

**Conceptos principales:**

- HTML.
- Lenguaje de marcado.
- Etiquetas HTML.
- Etiqueta de apertura.
- Etiqueta de cierre.
- Encabezado `<h1>`.
- Subtítulo `<h2>`.
- Párrafo `<p>`.
- Texto destacado `<strong>`.

**Actividad:** crear una página personal que muestre el nombre, la edad, el curso favorito y una actividad preferida del estudiante.

### Código inicial

```html
<h1>Escribe aquí tu nombre</h1>

<h2>Sobre mí</h2>

<p>Tengo ___ años.</p>

<p>Mi curso favorito es <strong>__________</strong>.</p>

<p>Mi actividad favorita es __________.</p>
```

### Ejemplo completado

```html
<h1>Mi perfil personal</h1>

<h2>Sobre mí</h2>

<p>Hola, mi nombre es Ana.</p>

<p>Tengo 15 años y estudio secundaria.</p>

<p>Mi curso favorito es <strong>Computación</strong>.</p>

<p>Mi actividad favorita es escuchar música.</p>
```

**Video:** [Ver Lección 2](https://youtu.be/4yWCF0tRrDE)  
**Práctica:** [Crear una página personal en CodePen](https://codepen.io/Aaron-Avila-the-decoder/pen/RNKpRjO)

## Lección 3: Listas, imágenes y enlaces

La tercera lección amplía la página creada anteriormente mediante nuevos elementos HTML. Se explica cómo organizar información utilizando listas, cómo agregar enlaces hacia otros sitios web y cómo mostrar imágenes mediante una dirección web.

El estudiante incorpora sus intereses, una imagen y un enlace dentro de su página personal.

**Conceptos principales:**

- Listas no ordenadas.
- Etiqueta `<ul>`.
- Elementos de lista `<li>`.
- Enlaces `<a>`.
- Atributo `href`.
- Imágenes `<img>`.
- Atributos `src` y `alt`.

**Actividad:** agregar a la página personal una lista de tres pasatiempos, una imagen y un enlace hacia un sitio web educativo.

## Lección 4: Introducción a CSS

La cuarta lección presenta CSS como el lenguaje utilizado para definir la apariencia de una página web. Se explica cómo seleccionar elementos HTML y aplicar propiedades para modificar colores, fuentes, fondos, bordes y alineación.

Durante la práctica, el estudiante transforma la página HTML creada en las lecciones anteriores mediante estilos sencillos.

**Conceptos principales:**

- CSS.
- Selectores.
- Propiedades.
- Valores.
- Color de texto.
- Color de fondo.
- Tipografía.
- Bordes.
- Espaciado.
- Alineación.

**Actividad:** cambiar el color de fondo, modificar el estilo de los encabezados y agregar un borde alrededor del contenido principal.

## Lección 5: Creación de una página web personal

La quinta lección integra HTML y CSS mediante la creación de una página web personal. El estudiante organiza información sobre sí mismo, incorpora diferentes elementos HTML y aplica estilos para mejorar la presentación visual.

El proyecto permite aplicar los conocimientos adquiridos durante el curso en una página completa y funcional.

**Conceptos aplicados:**

- Encabezados.
- Párrafos.
- Texto destacado.
- Listas.
- Imágenes.
- Enlaces.
- Selectores CSS.
- Colores.
- Fuentes.
- Bordes.
- Espaciado.
- Alineación.

**Proyecto:** crear una página web personal que incluya una presentación, intereses, pasatiempos, una imagen, un enlace y estilos personalizados.

## Lección 6: Recomendaciones, errores comunes y próximos pasos

La sexta lección revisa los errores más frecuentes que pueden aparecer al escribir HTML y CSS. Se explica cómo comprobar etiquetas, atributos, selectores y propiedades cuando una página no muestra el resultado esperado.

También se presentan recomendaciones para organizar el código y continuar aprendiendo desarrollo web.

**Conceptos principales:**

- Cierre correcto de etiquetas.
- Coincidencia entre etiquetas de apertura y cierre.
- Uso correcto de atributos.
- Selectores CSS.
- Llaves y punto y coma.
- Sangría del código.
- Organización de archivos.
- Validación y revisión del código.

**Actividad:** identificar y corregir errores en un ejemplo de HTML y CSS antes de ejecutar la página.

## Recursos de práctica

| Lección | Actividad | Herramienta |
| --- | --- | --- |
| 1 | Exploración de una página web | [CodePen](ENLACE_PRACTICA_1) |
| 2 | Primera página personal en HTML | [CodePen](https://codepen.io/Aaron-Avila-the-decoder/pen/RNKpRjO) |
| 3 | Listas, imágenes y enlaces | [CodePen](ENLACE_PRACTICA_3) |
| 4 | Estilos básicos con CSS | [CodePen](ENLACE_PRACTICA_4) |
| 5 | Página web personal | [CodePen](ENLACE_PRACTICA_5) |
| 6 | Corrección de errores | [CodePen](ENLACE_PRACTICA_6) |

## Repositorio de código fuente

El código fuente del curso se encuentra disponible en el siguiente repositorio público:

[ENLACE_DEL_REPOSITORIO](https://github.com/Eslander-Celis/webdev-course-HackRats)

El repositorio incluye:

| Carpeta | Contenido |
| --- | --- |
| `starter-files` | Archivos iniciales para las actividades prácticas. |
| `completed-examples` | Ejemplos completos de referencia. |
| `scripts` | Guiones y materiales de apoyo de las lecciones. |

La estructura general del repositorio es la siguiente:

```text
webdev-course-HackRats/
│
├── README.md
│
├── starter-files/
│   ├── lesson-01/
│   ├── lesson-02/
│   ├── lesson-03/
│   ├── lesson-04/
│   ├── lesson-05/
│   └── lesson-06/
│
├── completed-examples/
│   ├── lesson-01/
│   ├── lesson-02/
│   ├── lesson-03/
│   ├── lesson-04/
│   ├── lesson-05/
│   └── lesson-06/
│
└── scripts/
    ├── lesson-01-script.md
    ├── lesson-02-script.md
    ├── lesson-03-script.md
    ├── lesson-04-script.md
    ├── lesson-05-script.md
    └── lesson-06-script.md
```

## Elaboración del equipo

**Universidad:** Universidad Peruana de Ciencias Aplicadas  
**Carrera:** Ingeniería de Software  
**Curso:** 1ASI0730 Aplicaciones Web  
**Periodo académico:** 202610  
**NRC:** 10215  
**Nombre del equipo:** HackRats  
**Líder del equipo:** Eslander Celis

**Fecha de entrega:** 19/06/2026

**Repositorio:** [webdev-course-HackRats](https://github.com/Eslander-Celis/webdev-course-HackRats)

### Integrantes

| Integrante | Aporte principal |
|-------| --- |
| Rodrigo Ariel Oblitas Alcalde | Lección 1: Introducción al desarrollo web |
| Aarón Avila Palacios | Lección 2: Introducción a HTML |
| Mathias Aréchaga Saavedra | Lección 3: Listas, imágenes y enlaces |
| Gabriel Marcelo Mendoza Palacios | Lección 4: Introducción a CSS |
| Eslander Celis Berrospi | Lección 5: Página web personal |
| COLOCAR_INTEGRANTE_6 | Lección 6: Recomendaciones y errores comunes |

### Resumen de elaboración

El equipo desarrolló una ruta de aprendizaje introductoria para estudiantes de secundaria, organizada en seis lecciones progresivas. La propuesta comienza explicando qué es el desarrollo web, continúa con la estructura de páginas mediante HTML, incorpora elementos adicionales y estilos CSS, y finaliza con la elaboración de una página web personal.

Para preparar el curso se definieron los objetivos y contenidos de cada lección, se elaboraron ejemplos de HTML y CSS, se seleccionaron herramientas gratuitas en línea, se grabaron los videos educativos y se organizaron los materiales dentro de un repositorio público de GitHub.

Cada integrante participó en la preparación de contenidos, ejemplos de código, actividades prácticas y materiales audiovisuales. Los aportes individuales se encuentran registrados mediante commits dentro del repositorio del equipo.