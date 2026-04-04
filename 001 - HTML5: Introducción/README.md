# Capítulo 004 - HTML5: Introducción

Haz clic en la imagen para ver el video:
[![Ver video](https://img.youtube.com/vi/1Lf0uWjNU_8/maxresdefault.jpg)](https://www.youtube.com/watch?v=1Lf0uWjNU_8)

En esta clase aprenderás qué es HTML, cómo se estructura un documento HTML5, qué son las etiquetas, atributos y tipos de elementos. También conocerás cómo se relacionan entre sí mediante una estructura jerárquica de padres e hijos.

---

## 📌 Temas que verás en esta clase

En este capítulo aprenderás:

- Qué es HTML y su versión moderna HTML5.
- Por qué HTML no es un lenguaje de programación.
- Cómo se estructura un documento HTML5.
- Qué son las etiquetas y cómo funcionan.
- La diferencia entre una etiqueta de apertura y una de cierre.
- Qué son los elementos vacíos y los elementos con contenido.
- Qué son los atributos y cómo se escriben.
- Cómo se relacionan los elementos mediante una estructura jerárquica.

---

## 📁 Recursos

* `Recursos/index.html`

---

## 📖 Contenido del capítulo

## 4.1 ¿Qué es HTML y su versión moderna HTML5?

HTML son las siglas de **HyperText Markup Language**, que en español significa **Lenguaje de Marcado de Hipertexto**.

HTML5 es la quinta y más reciente versión de este lenguaje. Esta versión introdujo numerosas mejoras, entre ellas:

* Soporte nativo para audio y video.
* Posibilidad de crear gráficos y animaciones.
* Mejor manejo de formularios.
* Nuevas etiquetas y funcionalidades para estructurar páginas web.

A lo largo de este curso iremos aprendiendo cada una de estas características.

> [!IMPORTANT]
> HTML no es un lenguaje de programación.
>
> HTML es un lenguaje de marcado que se utiliza para definir la estructura y organización del contenido de una página web.

Esto significa que HTML no puede realizar operaciones, lógica o cálculos por sí solo, como sí lo hace JavaScript.

Por ejemplo, con HTML podemos indicar:

* Qué texto es un título.
* Qué contenido pertenece a un párrafo.
* Dónde debe aparecer una imagen.
* Cómo se organiza la estructura de una página.

---

## 4.2 ¿Cómo se estructura HTML?

Ahora que ya sabes qué es HTML5, veamos cómo se estructura un documento HTML.

Todo documento HTML5 suele tener una estructura similar a la siguiente:

```html
<!DOCTYPE html>
<html lang="es">
     <head>
          <meta charset="UTF-8">
          <title>Título de la página</title>
     </head>

     <body>
          <span>¡Bienvenid@!</span><br>
          <span>Esta es una página HTML muy simple.</span>
     </body>
</html>
```

No es necesario que entiendas cada línea todavía. Más adelante aprenderás el propósito de cada elemento.

Por ahora, lo importante es observar que un documento HTML está formado por varias partes:

* `<!DOCTYPE html>`
* `<html>`
* `<head>`
* `<body>`

Cada una de estas partes cumple una función específica.

### Explicación general de la estructura

#### `<!DOCTYPE html>`

Indica al navegador que el documento está escrito usando HTML5.

#### `<html>`

Es el elemento principal del documento. Todo el contenido de la página debe encontrarse dentro de esta etiqueta.

#### `<head>`

Contiene información interna del documento que normalmente no se muestra directamente en la página, por ejemplo:

* El título de la pestaña.
* La codificación del texto.
* Configuraciones del documento.

#### `<body>`

Contiene todo el contenido visible que el usuario verá en la página web.

En este ejemplo, dentro del `<body>` aparecen dos textos:

```text
¡Bienvenid@!
Esta es una página HTML muy simple.
```

---

## 4.3 ¿Qué es una etiqueta en HTML?

Después de entender la estructura de un documento, es importante conocer el concepto más básico de HTML: las etiquetas.

Las etiquetas son instrucciones que utiliza HTML para indicar cómo debe organizarse o interpretarse el contenido.

Una etiqueta siempre se escribe entre los símbolos:

```text
< >
```

Por ejemplo:

```html
<head>
<title>
<body>
<span>
```

La mayoría de las etiquetas tienen dos partes:

* **Etiqueta de apertura**
* **Etiqueta de cierre**

La etiqueta de cierre se diferencia porque incluye una diagonal `/` antes del nombre.

Por ejemplo:

```html
<title>
```

es la etiqueta de apertura, mientras que:

```html
</title>
```

es la etiqueta de cierre.

Otro ejemplo:

```html
<span>
```

Etiqueta de apertura.

```html
</span>
```

Etiqueta de cierre.

Estas etiquetas rodean contenido y le indican al navegador cómo debe interpretarlo.

Por ejemplo:

```html
<title>Título de la página</title>
```

El texto `Título de la página` será interpretado por el navegador como el título que aparece en la pestaña del sitio web.

---

### Etiquetas que no necesitan cierre

No todas las etiquetas tienen contenido.

Existen algunas etiquetas que no requieren una etiqueta de cierre. A estas se les conoce como **elementos vacíos** o **etiquetas auto-contenidas**.

Un ejemplo muy común es:

```html
<br>
```

La etiqueta `<br>` sirve para insertar un salto de línea.

> [!NOTE]
> La etiqueta `<br>` no necesita una etiqueta de cierre porque es un elemento vacío.

Gracias a esta etiqueta, el navegador muestra el texto así:

```text
¡Bienvenid@!
Esta es una página HTML muy simple.
```

---

## 4.4 Atributos

Además de las etiquetas, los elementos HTML también pueden tener atributos.

Los atributos agregan información adicional sobre un elemento o modifican su comportamiento.

Los atributos se escriben dentro de la etiqueta de apertura.

Por ejemplo:

```html
<html lang="es">
```

En este caso:

* `lang` es el nombre del atributo.
* `"es"` es su valor.

Este atributo indica que el contenido de la página está escrito en español.

Otro ejemplo sencillo sería:

```html
<input type="text">
```

Aquí, el atributo `type` indica qué tipo de campo será mostrado.

---

## 4.5 Tipos de elementos

En HTML existen dos tipos principales de elementos:

* Elementos vacíos.
* Elementos con contenido.

### Elementos vacíos

Los elementos vacíos solo tienen una etiqueta de apertura.

Por ejemplo:

```html
<br>
```

No tiene contenido ni etiqueta de cierre.

Su única función es insertar un salto de línea.

### Elementos con contenido

Los elementos con contenido sí tienen:

* Etiqueta de apertura.
* Contenido.
* Etiqueta de cierre.

Por ejemplo:

```html
<span>Esta es una página HTML muy simple.</span>
```

En este caso:

* `<span>` es la etiqueta de apertura.
* `Esta es una página HTML muy simple.` es el contenido.
* `</span>` es la etiqueta de cierre.

---

## 4.6 Jerarquía entre elementos

Los elementos HTML también pueden colocarse unos dentro de otros.

Cuando un elemento está dentro de otro, se forma una relación de:

* Elemento padre.
* Elemento hijo.

Por ejemplo, en el documento anterior, `<html>` es el elemento principal o elemento raíz.

Dentro de él se encuentran los elementos:

* `<head>`
* `<body>`

Por lo tanto, `<head>` y `<body>` son hijos de `<html>`.

A su vez, estos elementos también pueden ser padres de otros.

La estructura del ejemplo se vería de esta forma:

```text
<html>
├── <head>
│   ├── <meta>
│   └── <title>
└── <body>
    ├── <span>
    ├── <br>
    └── <span>
```

Esto permite organizar el contenido como si fuera un árbol.

---

## 4.7 Conclusión

En esta clase aprendiste:

* Qué significa HTML.
* Qué es HTML5.
* Por qué HTML no es un lenguaje de programación.
* Cómo se estructura un documento HTML.
* Qué son las etiquetas.
* Qué son los atributos.
* La diferencia entre elementos vacíos y elementos con contenido.
* Cómo funciona la relación entre elementos padre e hijo.

Con esta base ya estás preparado para comenzar a crear tus primeras páginas web y entender mejor el resto de los temas del curso.

¡Nos vemos en la siguiente clase!
