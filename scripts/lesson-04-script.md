# Script de la Lección 4: Introducción a CSS

## Información general

- **Curso:** Fundamentos de Desarrollo Web
- **Lección:** 4
- **Título:** Introducción a CSS: colores, fuentes y selectores
- **Duración estimada:** 12 minutos
- **Herramienta:** CodePen
- **Público objetivo:** Estudiantes de secundaria de 12 a 17 años
- **Prerrequisitos:** HTML básico (etiquetas, listas, imágenes, enlaces)

---

## Objetivos

Al finalizar esta lección, los estudiantes podrán:

- Entender qué es CSS y cómo funciona junto con HTML.
- Utilizar selectores CSS para dar estilo a elementos HTML.
- Modificar el color del texto y el color de fondo.
- Cambiar la tipografía de la página.
- Agregar bordes y ajustar el espaciado y la alineación.

---

## 1. Introducción + Hook

### Mostrar

El resultado visual de aplicar estilos a una página que antes solo tenía HTML.

### Narración

Hola a todos, bienvenidos a la lección 4.

En las clases anteriores aprendimos qué es HTML y cómo usarlo para organizar el contenido de nuestra página web, agregando textos, listas, imágenes y enlaces.

Sin embargo, nuestra página todavía se ve en blanco y negro, y su diseño es muy básico.

¡Eso cambia hoy! En esta lección aprenderemos a darle vida, color y estilo a nuestra página web utilizando CSS. 

Veremos cómo transformar una página HTML sencilla en algo mucho más atractivo visualmente.

---

## 2. ¿Qué es CSS?

### Mostrar

Un gráfico o analogía comparando HTML con la estructura (esqueleto) y CSS con el estilo (ropa o pintura).

### Narración

CSS significa "Cascading Style Sheets" o en español, Hojas de Estilo en Cascada.

Mientras que HTML se encarga de la estructura y el contenido (qué es lo que hay en la página), CSS se encarga de la apariencia y el diseño (cómo se ve la página).

Con CSS podemos cambiar colores, tipos de letra, tamaños, alinear elementos, poner bordes y mucho más.

La magia de CSS ocurre usando tres partes principales: el selector, la propiedad y el valor.

---

## 3. Selectores y Colores

### Código mostrado

```css
body {
  background-color: #f0f4f8;
}

h1 {
  color: #2c3e50;
}
```

### Narración

Veamos cómo funciona esto. Empezaremos cambiando el color de fondo de nuestra página y el color del título.

En CSS, primero escribimos a qué elemento HTML queremos aplicarle estilo. Esto se llama **selector**. 
Por ejemplo, escribimos `body` para toda la página, o `h1` para el encabezado principal.

Luego, abrimos llaves `{ }`. Dentro de las llaves escribimos qué aspecto queremos cambiar, llamado **propiedad**, y luego le damos un **valor**.

Para cambiar el color de fondo usamos la propiedad `background-color` y para el color de la letra usamos `color`.

Observen cómo al aplicar este código, nuestra página cambia instantáneamente de color.

---

## 4. Tipografía (Fuentes)

### Código mostrado

```css
p {
  font-family: Arial, sans-serif;
  font-size: 18px;
  color: #475569;
}
```

### Narración

Otra cosa muy importante en el diseño web es la tipografía, es decir, el tipo de letra que usamos.

Podemos seleccionar nuestros párrafos usando el selector `p` y cambiar su tipo de letra con la propiedad `font-family`. 

También podemos hacer la letra más grande o más pequeña utilizando la propiedad `font-size`. 

Al cambiar la fuente, hacemos que nuestra página sea mucho más fácil y agradable de leer.

---

## 5. Alineación, Bordes y Espaciado

### Código mostrado

```css
h1 {
  text-align: center;
}

div {
  background-color: white;
  border: 2px solid #cbd5e1;
  border-radius: 12px;
  padding: 30px;
  max-width: 500px;
  margin: 40px auto;
}
```

### Narración

Podemos hacer más que solo cambiar colores y letras. CSS también nos permite organizar mejor los elementos.

Para centrar nuestro título principal, utilizamos la propiedad `text-align` con el valor `center`.

También podemos agregar un marco o borde alrededor de nuestros elementos, como un contenedor `div`, usando la propiedad `border`. Aquí le decimos a CSS que queremos un borde de 2 píxeles, sólido, y de un color gris suave.

Además, con `border-radius`, podemos redondear las esquinas de ese borde para que se vea más moderno. También hemos agregado un fondo blanco, márgenes y relleno (`padding`) para que el contenido se vea centrado y parezca una tarjeta real.

---

## 6. Práctica: Transformando tu página

### Mostrar

La página personal creada en las lecciones 2 y 3 en CodePen, ahora con una pestaña de CSS abierta para empezar a estilizar.

### Narración

Ahora es tu turno. 

Abre tu práctica de CodePen donde creaste tu página personal en las lecciones anteriores.

Ve a la sección de CSS y empieza a experimentar. 

Cambia el color de fondo del `body`.
Cambia el color de texto de tu nombre en el `h1`.
Prueba cambiar el tipo de letra de tus párrafos.
Agrégale un borde a tu contenido o prueba redondeando las esquinas.

Recuerda siempre la regla: Selector, abres llaves, propiedad, dos puntos, valor, y terminas con punto y coma.

---

## 7. Cierre

### Narración

¡Felicidades! Ahora sabes cómo darle estilo a tus páginas usando CSS.

Has aprendido sobre selectores, cómo cambiar el color de texto y fondo, cómo modificar la fuente, centrar elementos y agregar bordes.

Tu página ya debe verse mucho más personalizada y parecida a un sitio web real.

En la próxima lección, utilizaremos todo lo que hemos aprendido de HTML y CSS juntos para construir un proyecto final: una tarjeta de perfil personal.

¡Sigan practicando y nos vemos en la próxima lección!

## Enlaces

- **Video de YouTube:** https://youtu.be/NmuqiwPjYeQ

- **Práctica en CodePen:** https://codepen.io/Gabriel-Mendoza-the-builder/pen/ogBZzLK

- **Repositorio de GitHub:** https://github.com/Eslander-Celis/webdev-course-HackRats
