# Capítulo 001 - HTML5: Introducción

Haz clic en la imagen para ver el video:
[![Ver video](https://img.youtube.com/vi/1Lf0uWjNU_8/maxresdefault.jpg)](https://www.youtube.com/watch?v=1Lf0uWjNU_8)

En esta clase aprenderás qué es HTML, cómo se estructura un documento HTML5, qué son las etiquetas, atributos y tipos de elementos. También conocerás cómo se relacionan entre sí mediante una estructura jerárquica de padres e hijos.

---

## 📁 Recursos

- `Recursos/index.html`

---

## 📖 Contenido del capítulo

### 4.1 ¿Qué es HTML y su versión moderna HTML5?

HTML son las siglas de HyperText Markup Language, que en español significa Lenguaje de Marcado de Hipertexto.

HTML5 es la quinta y más reciente versión de este lenguaje. Esta versión introdujo numerosas mejoras, como el soporte nativo para audio y video, la posibilidad de crear gráficos y animaciones, un mejor manejo de formularios, y muchas otras funcionalidades que enriquecen la experiencia web.

A lo largo de este curso, exploraremos y aprenderemos todas estas nuevas características en detalle.

Ahora que conocemos el significado de sus siglas, es importante aclarar que HTML no es un lenguaje de programación, ya que no permite implementar lógica ni realizar cálculos como lo hacen lenguajes como JavaScript.

En su lugar, HTML es un lenguaje de marcado, utilizado para definir la estructura y organizar el contenido de una página web.

---

### 4.2 ¿Cómo se estructura HTML?

A continuación, te presento un ejemplo muy básico de código HTML5, y cómo este es interpretado y visualizado por un navegador web:

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

No es necesario que entiendas el código por ahora. Lo importante es observar este ejemplo, ya que nos servirá para comprender mejor los conceptos clave que se utilizan para la estructura de un documento HTML.

---

### 4.3 ¿Qué es una etiqueta en HTML?

HTML se basa en el uso de etiquetas, que son instrucciones utilizadas para estructurar el contenido que aparecerá en el navegador.

Una etiqueta se escribe entre los signos de menor que `<` y mayor que `>`.

En el código de ejemplo, podemos ver varias etiquetas HTML, como:

```html
<head>
<title>
<body>
<span>
```

La mayoría de las etiquetas tienen una etiqueta de apertura y una etiqueta de cierre. Esta última se distingue porque lleva una barra inclinada `/` antes del nombre de la etiqueta.

Por ejemplo, podemos identificar la etiqueta de apertura:

```html
<title>
```

Y su etiqueta de cierre:

```html
</title>
```

Otro ejemplo es la etiqueta:

```html
<span>
```

Junto con su correspondiente cierre:

```html
</span>
```

Estas etiquetas encierran contenido, y definen cómo debe de ser interpretado por los navegadores.

La etiqueta:

```html
<title>Título de la página</title>
```

Contiene el texto `"Título de la página"`, el cual el navegador interpreta como el título de la página que aparece en la pestaña del sitio web.

Sin embargo, también existen etiquetas que no contienen ningún contenido y no requieren una etiqueta de cierre. A estas se les conoce como etiquetas auto-contenidas.

Un ejemplo común es:

```html
<br>
```

Esta etiqueta se utiliza para realizar un salto de línea.

En el ejemplo, podemos notar un salto de línea entre el texto:

```text
¡Bienvenid@!
Esta es una página HTML muy simple.
```

---

### 4.4 Atributos

Las etiquetas pueden tener atributos, que añaden información adicional sobre el elemento o modifican su comportamiento.

Los atributos se escriben dentro de la etiqueta de apertura.

Por ejemplo:

```html
<html lang="es">
```

Aquí, `lang` es el nombre del atributo, y `"es"` es su valor, indicando que el idioma del contenido de la página es en español.

---

### 4.5 Tipos de elementos

En HTML existen dos tipos de elementos:

- Elementos vacíos
- Elementos con contenido

#### Elementos vacíos

Los elementos vacíos solo tienen una etiqueta de apertura.

Por ejemplo:

```html
<br>
```

No tiene contenido ni etiqueta de cierre. Su único propósito es hacer un salto de línea.

#### Elementos con contenido

Los elementos con contenido tienen una etiqueta de apertura y una de cierre.

Todo lo que se encuentre dentro de estas dos etiquetas se considera su contenido.

Por ejemplo, el siguiente elemento está conformado por:

```html
<span>Esta es una página HTML muy simple.</span>
```

Además, el contenido de los elementos también puede incluir otros elementos, lo que permite anidar elementos unos dentro de otros, formando una estructura jerárquica o en forma de árbol.

Por ejemplo, `<html>` es el elemento raíz.

Dentro de él se encuentran los elementos:

- `<head>`
- `<body>`

Estos son considerados como elementos hijos del elemento `<html>`.

A su vez, `<head>` y `<body>` pueden ser elementos padres, ya que contienen otros elementos:

- `<head>` contiene:
  - `<meta>`
  - `<title>`

- `<body>` contiene:
  - `<span>`
  - `<br>`
  - `<span>`

---

### 4.6 Conclusión

En esta clase aprendiste que HTML no es un lenguaje de programación, sino un lenguaje de marcado que permite estructurar el contenido que vemos en el navegador mediante el uso de etiquetas.

También conociste la estructura básica de un documento HTML, la diferencia entre elementos con contenido y elementos vacíos, qué son los atributos y cómo funcionan, así como el concepto de jerarquía entre elementos padre e hijo.

Con este conocimiento fundamental, ahora estás preparado para crear tus primeras páginas web estructuradas y explorar más a fondo todas las posibilidades que HTML5 ofrece.

¡Nos vemos en la siguiente clase!
