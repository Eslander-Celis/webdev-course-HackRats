# Script de la Lección 5: Crear una página web sencilla

## Información general

- **Curso:** Fundamentos de Desarrollo Web
- **Lección:** 5
- **Título:** Proyecto final: Mi perfil personal
- **Duración estimada:** 15 minutos
- **Herramienta:** CodePen
- **Público objetivo:** Estudiantes de secundaria de 12 a 17 años
- **Prerrequisitos:** HTML básico y CSS básico

---

## Objetivos

Al finalizar esta lección, los estudiantes podrán:

- Combinar HTML y CSS en una página web real.
- Crear una tarjeta de perfil personal.
- Usar contenedores, imágenes, encabezados, párrafos, enlaces y clases.
- Aplicar Flexbox para centrar elementos.
- Estilizar imágenes, hobbies y botones interactivos.

---

## 1. Introducción + Hook

### Mostrar

El resultado final completo: una profile card moderna.

### Narración

Hola a todos, bienvenidos a la lección 5.

En las clases anteriores aprendimos HTML y CSS por separado.

Vimos cómo HTML nos ayuda a estructurar contenido y cómo CSS nos permite darle estilo a una página.

Hoy combinaremos ambos para construir algo real: una página de perfil personal.

Este será nuestro resultado final.

Como pueden ver, nuestra página tendrá:

- Una foto de perfil.
- Nombre.
- Profesión.
- Una pequeña descripción.
- Hobbies.
- Botones interactivos.

Se ve bastante profesional, ¿verdad?

Lo interesante es que todo esto lo construiremos usando únicamente HTML y CSS.

No usaremos frameworks, librerías ni herramientas complicadas. Solo lo básico.

---

## 2. HTML vs CSS

### Mostrar

Editor vacío.

### Narración

Antes de comenzar, recordemos algo muy importante.

HTML y CSS tienen funciones distintas.

HTML define la estructura. Es decir: qué cosas aparecen en la página.

CSS define la apariencia. Es decir: cómo se ven esas cosas.

Una forma fácil de recordarlo es esta:

HTML es el esqueleto de una casa.

CSS son la pintura, decoración y muebles.

Sin HTML, no hay contenido.

Sin CSS, todo se ve muy simple.

---

## Parte 1: HTML

## 3. Contenedores

### Código mostrado

```html
<div class="container">
  <div class="profile-card">

  </div>
</div>
```

### Narración

Empezaremos creando la estructura principal.

Aquí usamos dos etiquetas `div`.

Un `div` es un contenedor genérico. Puedes imaginarlo como una caja vacía donde agrupamos elementos relacionados.

El primer `div` se llama `container`. Este servirá para centrar todo en pantalla.

El segundo `div` será nuestra tarjeta principal.

---

## 4. Imagen + Nombre + Profesión

### Código mostrado

```html
<img
  class="profile-img"
  src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e?w=300"
  alt="Foto de perfil"
>

<h1>Eslander Celis</h1>
<h3>Software Engineering Student</h3>
```

### Narración

Ahora agregaremos la información principal del perfil.

Primero una imagen usando la etiqueta `img`.

Toda imagen en HTML necesita un atributo llamado `src`.

`src` significa source, o fuente. Aquí colocamos la dirección de la imagen.

Después usamos `h1`.

`h1` representa el título más importante de la página. En este caso será el nombre del usuario.

Luego agregamos `h3`, que usaremos para la profesión o rol.

HTML también organiza información por jerarquía.

`h1` es el título principal. `h2` y `h3` son secundarios.

---

## 5. Biografía

### Código mostrado

```html
<p class="bio">
  Passionate about web development, UI design and building innovative tech
  solutions.
</p>
```

### Narración

Ahora añadimos una pequeña biografía usando `p`, que significa paragraph o párrafo.

Los párrafos se usan para bloques de texto más largos.

También agregué una clase llamada `bio`.

Más adelante usaremos esa clase en CSS para darle estilos específicos.

---

## 6. Hobbies

### Código mostrado

```html
<h2>Hobbies</h2>

<div class="hobbies">
  <span>Música</span>
  <span>Programming</span>
  <span>Gaming</span>
  <span>UI Design</span>
</div>
```

### Narración

También añadiremos hobbies.

Usamos `h2` porque esta sección es importante, pero no más importante que el nombre.

Dentro usamos `span`.

`span` sirve para pequeños fragmentos de texto dentro de una línea.

---

## 7. Botones

### Código mostrado

```html
<div class="buttons">
  <a href="https://github.com" target="_blank">GitHub</a>
  <a href="https://linkedin.com" target="_blank">LinkedIn</a>
</div>
```

### Narración

Finalmente añadimos enlaces con la etiqueta `a`.

La `a` significa anchor.

Sirve para navegar hacia otras páginas.

`href` indica a dónde irá el enlace.

`target="_blank"` hace que se abra en una nueva pestaña.

---

## 8. Mostrar sin CSS

### Narración

Nuestra página ya funciona.

Pero sinceramente, se ve bastante simple.

Y eso está bien.

HTML por sí solo no está pensado para verse bonito.

Ahora viene la magia de CSS.

---

## Parte 2: CSS

## 9. Reset

### Código mostrado

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

### Narración

Empezaremos con algo llamado CSS reset.

Por defecto, los navegadores añaden márgenes y espacios automáticamente.

Eso puede causar diseños inconsistentes.

Por eso los reiniciamos.

`*` significa todos los elementos.

`margin` es el espacio externo.

`padding` es el espacio interno.

---

## 10. Body

### Código mostrado

```css
body {
  font-family: Arial, sans-serif;
  min-height: 100vh;
  background: linear-gradient(135deg, #4f46e5, #06b6d4);
}
```

### Narración

Ahora modificamos el `body`.

El `body` representa toda la parte visible de la página.

`font-family` cambia la tipografía.

`min-height: 100vh` significa que ocupará toda la altura de la ventana.

`vh` significa viewport height.

`100vh` es el 100% de la pantalla.

Finalmente añadimos un degradado con `linear-gradient`.

En vez de un color sólido, tenemos una transición suave entre colores.

---

## 11. Flexbox

### Código mostrado

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}
```

### Narración

Ahora usamos Flexbox.

Flexbox es una herramienta de CSS que facilita muchísimo la alineación.

`display: flex` activa el modo flexible.

`justify-content: center` centra horizontalmente.

`align-items: center` centra verticalmente.

Con esto, nuestra tarjeta queda exactamente en el centro.

---

## 12. Tarjeta

### Código mostrado

```css
.profile-card {
  width: 420px;
  background: white;
  padding: 35px;
  border-radius: 24px;
  text-align: center;
  box-shadow: 0 15px 40px rgba(0, 0, 0, 0.25);
}
```

### Narración

Ahora convertimos esa caja en una tarjeta real.

`width` controla el ancho.

`background: white` la hace blanca.

`padding` crea espacio interno.

`border-radius` redondea las esquinas.

`text-align: center` centra el texto.

`box-shadow` crea una sombra.

Las sombras ayudan a generar profundidad visual.

---

## 13. Imagen

### Código mostrado

```css
.profile-img {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 20px;
  border: 5px solid #4f46e5;
}
```

### Narración

Ahora estilizamos la imagen.

`width` y `height` definen el tamaño.

`border-radius: 50%` la vuelve circular.

`object-fit: cover` evita que la imagen se deforme.

Y añadimos un borde decorativo.

---

## 14. Texto + Hobbies

### Código mostrado

```css
h1 {
  font-size: 32px;
  color: #111827;
}

h3 {
  margin-top: 8px;
  color: #6366f1;
  font-weight: normal;
}

.bio {
  margin-top: 20px;
  line-height: 1.6;
  color: #4b5563;
}
```

### Narración

Aquí ajustamos tipografía y espaciado.

`font-size` cambia el tamaño.

`line-height` mejora la legibilidad.

### Código mostrado

```css
.hobbies {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 10px;
}

.hobbies span {
  background: #eef2ff;
  color: #4338ca;
  padding: 10px 16px;
  border-radius: 999px;
}
```

### Narración

Usamos Flexbox nuevamente para acomodar hobbies.

Esto convierte cada hobby en una etiqueta visual.

---

## 15. Botones

### Código mostrado

```css
.buttons a {
  display: inline-block;
  text-decoration: none;
  margin: 8px;
  padding: 12px 22px;
  background: #4f46e5;
  color: white;
  border-radius: 12px;
  transition: 0.3s;
}

.buttons a:hover {
  transform: translateY(-3px);
}
```

### Narración

Ahora convertimos los links en botones.

`:hover` detecta cuando el mouse pasa encima.

Esto crea interacción y hace la página más dinámica.

---

## 16. Cierre

### Mostrar

Resultado final.

### Narración

¡Y listo!

Acabas de crear una página web moderna usando HTML y CSS.

Hoy aprendiste:

- Estructura HTML.
- Clases.
- Flexbox.
- Tarjetas.
- Imágenes circulares.
- Botones interactivos.

Tu reto ahora es personalizar esta página con:

- Tu foto.
- Tus colores favoritos.
- Tus propios hobbies.

Experimenta, cambia cosas y diviértete programando.

Nos vemos en la siguiente lección.

## Enlaces

- **Video de YouTube:** https://youtu.be/E1Wl-j1_QUE

- **Práctica en CodePen:** https://codepen.io/Eslander-Celis/pen/pvRebEb

- **Repositorio de GitHub:** https://github.com/Eslander-Celis/webdev-course-HackRats
