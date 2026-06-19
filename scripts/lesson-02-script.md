# Script de la Lección 2: Introducción a HTML

## Información general

- **Curso:** Fundamentos de Desarrollo Web
- **Lección:** 2
- **Título:** Introducción a HTML
- **Duración estimada:** 10 minutos
- **Herramienta:** CodePen
- **Público objetivo:** Estudiantes de secundaria de 12 a 17 años
- **Prerrequisitos:** Ninguno

---

## Objetivos

Al finalizar esta lección, los estudiantes podrán:

- Comprender qué es HTML.
- Reconocer la estructura de una etiqueta HTML.
- Crear encabezados y párrafos.
- Destacar información importante.
- Elaborar una página web sencilla utilizando CodePen.

---

## 1. Presentación

### Narración

Hola. Bienvenidos a la Lección 2 del curso de Fundamentos de Desarrollo Web.

En esta lección aprenderemos qué es HTML y cómo podemos utilizarlo para crear nuestra primera página web.

Trabajaremos directamente desde el navegador usando CodePen, por lo que no necesitaremos descargar ni instalar ningún programa.

---

## 2. ¿Qué es HTML?

### Narración

HTML significa Lenguaje de Marcado de Hipertexto.

Es el lenguaje que utilizamos para organizar el contenido de una página web.

Con HTML podemos indicar qué contenido será un título, qué parte será un párrafo y qué información será importante.

HTML no es un lenguaje de programación. Es un lenguaje de marcado que utiliza etiquetas para estructurar el contenido.

Podemos pensar en HTML como el esqueleto de una página web, porque define su estructura principal.

### Texto en pantalla

```text
HTML = contenido y estructura de una página web
```

---

## 3. ¿Qué es una etiqueta HTML?

### Narración

HTML utiliza etiquetas para identificar cada parte del contenido.

La mayoría de las etiquetas tienen una apertura, un contenido y un cierre.

Observemos el siguiente ejemplo.

### Código mostrado

```html
<p>Hola, estoy aprendiendo HTML.</p>
```

### Narración

La etiqueta de apertura es `<p>`.

Después encontramos el contenido del párrafo.

Finalmente, la etiqueta `</p>` cierra el elemento.

La barra inclinada indica que estamos cerrando la etiqueta.

Cuando abrimos una etiqueta, debemos asegurarnos de cerrarla correctamente.

---

## 4. Etiquetas básicas

### Narración

Ahora conoceremos algunas de las etiquetas HTML más utilizadas.

La etiqueta `<h1>` se utiliza para crear el título principal de una página.

### Código mostrado

```html
<h1>Mi primera página web</h1>
```

### Narración

La etiqueta `<h2>` permite crear un subtítulo.

### Código mostrado

```html
<h2>Sobre mí</h2>
```

### Narración

La etiqueta `<p>` se utiliza para escribir párrafos.

### Código mostrado

```html
<p>Hola, mi nombre es Ana.</p>
```

### Narración

La etiqueta `<strong>` permite destacar una palabra o una parte importante del texto.

### Código mostrado

```html
<p>Mi curso favorito es <strong>Computación</strong>.</p>
```

---

## 5. Demostración en CodePen

### Narración

Ahora crearemos una página sencilla utilizando CodePen.

Primero, ingresamos a CodePen desde nuestro navegador.

Dentro del editor encontraremos tres espacios: HTML, CSS y JavaScript.

En esta lección solamente utilizaremos el panel HTML.

Comenzaremos escribiendo el título principal de nuestra página.

### Código mostrado

```html
<h1>Mi perfil personal</h1>
```

### Narración

Ahora agregamos un subtítulo llamado “Sobre mí”.

### Código mostrado

```html
<h2>Sobre mí</h2>
```

### Narración

Luego agregamos un párrafo con el nombre del estudiante.

### Código mostrado

```html
<p>Hola, mi nombre es Ana.</p>
```

### Narración

También podemos incluir la edad y otra información personal.

### Código mostrado

```html
<p>Tengo 15 años y estudio secundaria.</p>
```

### Narración

Finalmente, agregamos un párrafo con el curso favorito y destacamos la palabra Computación.

### Código mostrado

```html
<p>Mi curso favorito es <strong>Computación</strong>.</p>
```

### Código completo

```html
<h1>Mi perfil personal</h1>

<h2>Sobre mí</h2>

<p>Hola, mi nombre es Ana.</p>

<p>Tengo 15 años y estudio secundaria.</p>

<p>Mi curso favorito es <strong>Computación</strong>.</p>
```

### Narración

CodePen muestra automáticamente el resultado en la vista previa.

No necesitamos presionar un botón para ejecutar el código.

Cuando cambiamos el contenido HTML, el resultado de la página también cambia inmediatamente.

---

## 6. Actividad práctica

### Narración

Ahora es tu turno.

Crea una página web personal utilizando el siguiente código como punto de partida.

Debes reemplazar los espacios con tu propia información.

### Código inicial

```html
<h1>Escribe aquí tu nombre</h1>

<h2>Sobre mí</h2>

<p>Tengo ___ años.</p>

<p>Mi curso favorito es <strong>__________</strong>.</p>

<p>Mi actividad favorita es __________.</p>
```

### Indicaciones

La página debe incluir:

- Un título principal con tu nombre.
- Un subtítulo llamado “Sobre mí”.
- Un párrafo con tu edad.
- Un párrafo con tu curso favorito.
- Una palabra destacada usando `<strong>`.
- Un párrafo con tu actividad favorita.

### Narración

Puedes pausar el video durante tres minutos para completar la actividad.

---

## 7. Errores comunes

### Error 1: Etiquetas diferentes

#### Incorrecto

```html
<h1>Mi página web</h2>
```

#### Correcto

```html
<h1>Mi página web</h1>
```

### Narración

La etiqueta que abre y la etiqueta que cierra deben ser iguales.

---

### Error 2: Confundir el número uno con la letra ele

#### Incorrecto

```html
<hl>Mi página web</hl>
```

#### Correcto

```html
<h1>Mi página web</h1>
```

### Narración

La etiqueta correcta utiliza el número uno, no la letra ele.

---

### Error 3: Olvidar cerrar una etiqueta

#### Incorrecto

```html
<p>Estoy aprendiendo HTML.
```

#### Correcto

```html
<p>Estoy aprendiendo HTML.</p>
```

### Narración

Aunque algunos navegadores intentan corregir estos errores, es una buena práctica cerrar correctamente todas las etiquetas.

---

## 8. Resumen de la lección

### Narración

En esta lección aprendimos que HTML se utiliza para organizar el contenido de una página web.

También aprendimos que las etiquetas normalmente tienen una apertura y un cierre.

Utilizamos `<h1>` para crear un título principal, `<h2>` para crear un subtítulo, `<p>` para escribir párrafos y `<strong>` para destacar información importante.

Finalmente, creamos una página web sencilla utilizando CodePen directamente desde el navegador.

En la siguiente lección aprenderás a agregar otros elementos, como listas, imágenes y enlaces.

Gracias por participar.

---

## Código final de la lección

```html
<h1>Mi perfil personal</h1>

<h2>Sobre mí</h2>

<p>Hola, mi nombre es Ana.</p>

<p>Tengo 15 años y estudio secundaria.</p>

<h2>Mis intereses</h2>

<p>Mi curso favorito es <strong>Computación</strong>.</p>

<p>También me gusta escuchar música y aprender cosas nuevas.</p>
```

---

## Enlaces

- **Video de YouTube:** https://youtu.be/4yWCF0tRrDE

- **Práctica en CodePen:** https://codepen.io/Aaron-Avila-the-decoder/pen/RNKpRjO

- **Repositorio de GitHub:** https://github.com/Eslander-Celis/webdev-course-HackRats
