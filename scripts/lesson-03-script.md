# Script de la Lección 3: Listas, Imágenes y Enlaces

## Información general

- **Curso:** Fundamentos de Desarrollo Web
- **Lección:** 3
- **Título:** Listas, Imágenes y Enlaces
- **Duración estimada:** 8-9 minutos
- **Herramienta:** CodePen
- **Público objetivo:** Estudiantes de secundaria de 12 a 17 años
- **Prerrequisitos:** Lección 2 (Introducción a HTML)

---

## Objetivos

Al finalizar esta lección, los estudiantes podrán:

- Crear listas no ordenadas con `<ul>` y `<li>`.
- Crear listas ordenadas con `<ol>` y `<li>`.
- Diferenciar cuándo usar listas ordenadas y no ordenadas.
- Insertar imágenes usando la etiqueta `<img>`.
- Crear enlaces usando la etiqueta `<a>`.
- Combinar estos elementos en una página web funcional.

---

## 1. Presentación

### Narración

Hola. Bienvenidos a la Lección 3 del curso de Fundamentos de Desarrollo Web.

En esta lección aprenderemos a crear listas, insertar imágenes y añadir enlaces a nuestras páginas web.

Estos elementos son fundamentales para crear sitios web más interactivos e informativos.

Al igual que en la lección anterior, utilizaremos CodePen para practicar directamente en el navegador.

---

## 2. Listas en HTML

### Narración

Las listas son una forma excelente de organizar información de manera clara y ordenada.

En HTML existen dos tipos principales de listas: las listas no ordenadas y las listas ordenadas.

Una lista no ordenada es útil cuando el orden de los elementos no importa.

Una lista ordenada se utiliza cuando el orden sí importa, por ejemplo, en un paso a paso o un ranking.

### Texto en pantalla

```text
Listas no ordenadas: <ul>
Listas ordenadas: <ol>
Elemento de lista: <li>
```

---

## 3. Listas no ordenadas

### Narración

La etiqueta `<ul>` crea una lista no ordenada. Los elementos de la lista se indican con la etiqueta `<li>`.

Veamos un ejemplo.

### Código mostrado

```html
<ul>
    <li>Manzana</li>
    <li>Pera</li>
    <li>Uva</li>
</ul>
```

### Narración

Cada elemento de la lista comienza con `<li>` y termina con `</li>`.

Por defecto, los navegadores muestran las listas no ordenadas con viñetas (puntos).

Las listas no ordenadas son perfectas para enumerar elementos sin un orden específico, como ingredientes de una receta o elementos de una tienda.

---

## 4. Listas ordenadas

### Narración

La etiqueta `<ol>` crea una lista ordenada. También utilizamos `<li>` para cada elemento.

### Código mostrado

```html
<ol>
    <li>Abrir el editor</li>
    <li>Escribir el código</li>
    <li>Guardar el archivo</li>
</ol>
```

### Narración

Las listas ordenadas muestran números automáticamente.

Son ideales para instrucciones paso a paso, ranking de películas o cualquier situación donde el orden importa.

Podemos controlar el número inicial usando el atributo `start`.

### Código mostrado

```html
<ol start="5">
    <li>Primer paso</li>
    <li>Segundo paso</li>
    <li>Tercer paso</li>
</ol>
```

### Narración

En este ejemplo, la lista comenzaría en el número cinco en lugar de uno.

---

## 5. Imágenes

### Narración

La etiqueta `<img>` permite insertar imágenes en una página web.

Esta etiqueta es especial porque no tiene un contenido ni un cierre. Se llama etiqueta vacía.

Veamos su estructura.

### Código mostrado

```html
<img src="ruta-de-la-imagen.jpg" alt="Descripción de la imagen">
```

### Narración

El atributo `src` indica la ubicación o URL de la imagen.

El atributo `alt` proporciona una descripción de la imagen. Esto es importante para la accesibilidad, ya que los lectores de pantalla utilizan este texto.

Veamos un ejemplo práctico.

### Código mostrado

```html
<img src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?w=300" alt="Foto de perfil">
```

### Narración

En este ejemplo, utilizamos una URL de internet. También podemos usar rutas locales si tenemos la imagen en nuestro proyecto.

Es recomendable mantener las imágenes pequeñas en tamaño de archivo y usar formatos como JPG, PNG o WebP.

---

## 6. Enlaces

### Narración

La etiqueta `<a>` se utiliza para crear enlaces a otras páginas o recursos.

El atributo `href` especifica la URL a la que apunta el enlace.

### Código mostrado

```html
<a href="https://www.ejemplo.com">Haz clic aquí</a>
```

### Narración

El texto entre `<a>` y `</a>` es lo que el usuario ve y puede hacer clic.

Podemos crear enlaces a sitios web externos, a otras páginas de nuestro proyecto, o incluso a correos electrónicos.

### Código mostrado

```html
<a href="https://github.com" target="_blank">Mi GitHub</a>
```

### Narración

El atributo `target="_blank"` hace que el enlace se abra en una nueva pestaña del navegador.

Si no incluimos este atributo, el enlace se abrirá en la misma pestaña.

---

## 7. Demostración en CodePen

### Narración

Ahora crearemos una página que combine todos estos elementos.

Comenzaremos con un título y una lista de frutas.

### Código mostrado

```html
<h1>Mi página web</h1>

<h2>Mis frutas favoritas</h2>

<ul>
    <li>Manzana</li>
    <li>Pera</li>
    <li>Uva</li>
</ul>
```

### Narración

Luego agregaremos una lista ordenada con pasos para crear una página web.

### Código mostrado

```html
<h2>Pasos para crear una página web</h2>

<ol>
    <li>Abrir un editor de texto</li>
    <li>Escribir código HTML</li>
    <li>Guardar el archivo como .html</li>
    <li>Abrirlo en un navegador</li>
</ol>
```

### Narración

Ahora agregaremos una imagen.

### Código mostrado

```html
<h2>Mi foto</h2>

<img src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?w=300" alt="Foto de ejemplo">
```

### Narración

Finalmente, agregaremos algunos enlaces útiles.

### Código mostrado

```html
<h2>Enlaces útiles</h2>

<ul>
    <li><a href="https://www.w3schools.com/html/" target="_blank">Aprende HTML</a></li>
    <li><a href="https://codepen.io" target="_blank">CodePen</a></li>
    <li><a href="https://github.com" target="_blank">GitHub</a></li>
</ul>
```

### Código completo

```html
<h1>Mi página web</h1>

<h2>Mis frutas favoritas</h2>

<ul>
    <li>Manzana</li>
    <li>Pera</li>
    <li>Uva</li>
</ul>

<h2>Pasos para crear una página web</h2>

<ol>
    <li>Abrir un editor de texto</li>
    <li>Escribir código HTML</li>
    <li>Guardar el archivo como .html</li>
    <li>Abrirlo en un navegador</li>
</ol>

<h2>Mi foto</h2>

<img src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?w=300" alt="Foto de ejemplo">

<h2>Enlaces útiles</h2>

<ul>
    <li><a href="https://www.w3schools.com/html/" target="_blank">Aprende HTML</a></li>
    <li><a href="https://codepen.io" target="_blank">CodePen</a></li>
    <li><a href="https://github.com" target="_blank">GitHub</a></li>
</ul>
```

### Narración

Como puedes ver, hemos combinado todos los elementos aprendidos en una sola página.

CodePen muestra el resultado en tiempo real, así que puedes ver cómo lucen todas estas etiquetas juntas.

---

## 8. Actividad práctica

### Narración

Ahora es tu turno.

Crea una página web utilizando listas, imágenes y enlaces.

### Indicaciones

Tu página debe incluir:

- Un título principal para tu página.
- Una sección con una lista no ordenada de tus hobbies o intereses.
- Una sección con una lista ordenada de pasos o instrucciones para hacer algo que te guste.
- Una imagen (puedes usar una URL de internet).
- Al menos dos enlaces a sitios web que te interesen (usa `target="_blank"`).
- Un párrafo con descripción (opcional).

### Código inicial

```html
<h1>Mi página de intereses</h1>

<h2>Mis hobbies</h2>

<ul>
    <li>___________</li>
    <li>___________</li>
    <li>___________</li>
</ul>

<h2>Cómo hacer ___________</h2>

<ol>
    <li>___________</li>
    <li>___________</li>
    <li>___________</li>
</ol>

<h2>Mi foto</h2>

<img src="___________" alt="Descripción de la imagen">

<h2>Enlaces interesantes</h2>

<ul>
    <li><a href="___________" target="_blank">___________</a></li>
    <li><a href="___________" target="_blank">___________</a></li>
</ul>
```

### Narración

Puedes pausar el video durante cinco minutos para completar la actividad.

---

## 9. Errores comunes

### Error 1: Olvidar cerrar la etiqueta `<li>`

#### Incorrecto

```html
<ul>
    <li>Manzana
    <li>Pera</li>
    <li>Uva</li>
</ul>
```

#### Correcto

```html
<ul>
    <li>Manzana</li>
    <li>Pera</li>
    <li>Uva</li>
</ul>
```

### Narración

Cada elemento de lista debe cerrarse correctamente con `</li>`.

---

### Error 2: Confundir `<ul>` con `<ol>`

#### Incorrecto

```html
<!-- Esto mostraría números, no viñetas -->
<ol>
    <li>Chocolate</li>
    <li>Helado</li>
    <li>Dulces</li>
</ol>
```

#### Correcto

```html
<!-- Para una lista sin orden, usa <ul> -->
<ul>
    <li>Chocolate</li>
    <li>Helado</li>
    <li>Dulces</li>
</ul>
```

### Narración

Recuerda: usa `<ul>` cuando el orden no importa, y `<ol>` cuando el orden es importante.

---

### Error 3: Olvidar el atributo `alt` en imágenes

#### Incorrecto

```html
<img src="mi-imagen.jpg">
```

#### Correcto

```html
<img src="mi-imagen.jpg" alt="Descripción de mi imagen">
```

### Narración

El atributo `alt` es importante para la accesibilidad. Describe qué contiene la imagen para quienes no pueden verla.

---

### Error 4: URLs incorrectas en enlaces o imágenes

#### Incorrecto

```html
<a href="www.google.com">Google</a>

<img src="imagen.jpg">
```

#### Correcto

```html
<a href="https://www.google.com">Google</a>

<img src="https://ejemplo.com/imagen.jpg" alt="Imagen">
```

### Narración

Asegúrate de incluir `https://` en URLs completas de internet.

Para imágenes locales, verifica que la ruta sea correcta.

---

## 10. Resumen de la lección

### Narración

En esta lección aprendimos a crear dos tipos de listas: las listas no ordenadas con `<ul>` y las listas ordenadas con `<ol>`.

Ambas utilizan la etiqueta `<li>` para cada elemento individual.

También aprendimos a insertar imágenes usando la etiqueta `<img>` y sus atributos `src` y `alt`.

Finalmente, creamos enlaces interactivos usando la etiqueta `<a>` y el atributo `href`.

Combinamos todos estos elementos para crear una página web más completa y funcional.

En la siguiente lección aprenderás a aplicar estilos visuales con CSS.

Gracias por participar.

---

## Código final de la lección

```html
<h1>Mi página de intereses</h1>

<h2>Mis hobbies</h2>

<ul>
    <li>Música</li>
    <li>Programación</li>
    <li>Gaming</li>
</ul>

<h2>Cómo crear una página web</h2>

<ol>
    <li>Abrir un editor de texto</li>
    <li>Escribir código HTML</li>
    <li>Guardar el archivo con extensión .html</li>
    <li>Abrirlo en un navegador web</li>
</ol>

<h2>Mi foto</h2>

<img src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?w=300" alt="Foto de perfil">

<h2>Recursos útiles para aprender</h2>

<ul>
    <li><a href="https://www.w3schools.com/html/" target="_blank">W3Schools HTML</a></li>
    <li><a href="https://developer.mozilla.org/es/docs/Web/HTML" target="_blank">MDN Web Docs</a></li>
    <li><a href="https://codepen.io" target="_blank">CodePen</a></li>
</ul>
```

---

## Enlaces

- **Video de YouTube:** https://youtu.be/tGYp4UMkm9k

- **Práctica en CodePen:** https://codepen.io

- **Repositorio de GitHub:** https://github.com/Eslander-Celis/webdev-course-HackRats
