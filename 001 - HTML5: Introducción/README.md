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

HTML son las siglas de **HyperText Markup Language**, que en español significa **Lenguaje de Marcado de Hipertexto**.

HTML5 es la quinta y más reciente versión de este lenguaje. Esta versión introdujo numerosas mejoras, como:

- soporte nativo para audio y video
- la posibilidad de crear gráficos y animaciones
- un mejor manejo de formularios
- y muchas otras funcionalidades que enriquecen la experiencia web

A lo largo de este curso exploraremos y aprenderemos todas estas nuevas características en detalle.

Ahora que conocemos el significado de sus siglas, es importante aclarar que HTML no es un lenguaje de programación, ya que no permite implementar lógica ni realizar cálculos como lo hacen lenguajes como JavaScript.

HTML es un lenguaje de marcado. Su función es definir la estructura y organizar el contenido de una página web.

Por ejemplo, HTML permite indicar:

- qué texto es un título
- qué texto es un párrafo
- dónde debe ir una imagen
- cómo se organizan las distintas partes de una página

---

### 4.2 ¿Cómo se estructura HTML?

A continuación se muestra un ejemplo muy básico de código HTML5:

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

Cuando este código es interpretado por un navegador, el resultado que se muestra en pantalla es:

```text
¡Bienvenid@!
Esta es una página HTML muy simple.
```

Y además, en la pestaña del navegador aparece el texto:

```text
Título de la página
```

Por ahora no es necesario que entiendas completamente cada línea del código.

Lo importante es observar la estructura general, ya que este ejemplo nos servirá para comprender mejor los conceptos que veremos a continuación.

Podemos notar que el documento está formado por varios elementos colocados uno dentro de otro.

Por ejemplo:

- el elemento `<html>` contiene todo el documento
- dentro de `<html>` se encuentran `<head>` y `<body>`
- dentro de `<body>` se encuentra el contenido que se muestra al usuario

---

### 4.3 ¿Qué es una etiqueta en HTML?

HTML se basa en el uso de etiquetas.

Las etiquetas son instrucciones que le indican al navegador cómo debe interpretar y mostrar el contenido.

Una etiqueta se escribe entre los signos:

```text
<
>
```

Por ejemplo, estas son algunas etiquetas HTML:

```html
<head>
<title>
<body>
<span>
```

La mayoría de las etiquetas están formadas por dos partes:

1. una etiqueta de apertura
2. una etiqueta de cierre

La etiqueta de cierre se diferencia porque contiene una diagonal `/` antes del nombre.

Por ejemplo:

```html
<title>
```

es la etiqueta de apertura, mientras que:

```html
</title>
```

es la etiqueta de cierre.

Otro ejemplo es:

```html
<span>
```

y su cierre correspondiente:

```html
</span>
```

Entre la etiqueta de apertura y la etiqueta de cierre se coloca el contenido.

Por ejemplo:

```html
<title>Título de la página</title>
```

En este caso:

- `<title>` es la etiqueta de apertura
- `</title>` es la etiqueta de cierre
- `Título de la página` es el contenido

El navegador interpreta este contenido como el título de la pestaña del sitio web.

Otro ejemplo es:

```html
<span>¡Bienvenid@!</span>
```

Aquí el contenido es:

```text
¡Bienvenid@!
```

y el navegador lo muestra en la página.

#### Etiquetas auto-contenidas

No todas las etiquetas tienen contenido.

Existen algunas etiquetas que no necesitan una etiqueta de cierre porque no contienen texto ni otros elementos dentro de ellas.

A estas se les conoce como etiquetas auto-contenidas.

Un ejemplo muy común es:

```html
<br>
```

La etiqueta `<br>` sirve para realizar un salto de línea.

Por eso, en el ejemplo anterior, el navegador muestra:

```text
¡Bienvenid@!
Esta es una página HTML muy simple.
```

Si elimináramos la etiqueta `<br>`, ambos textos aparecerían en la misma línea.

---

### 4.4 Atributos

Las etiquetas también pueden tener atributos.

Los atributos agregan información adicional sobre el elemento o modifican su comportamiento.

Los atributos siempre se escriben dentro de la etiqueta de apertura.

Por ejemplo:

```html
<html lang="es">
```

En este caso:

- `lang` es el nombre del atributo
- `"es"` es el valor del atributo

Esto le indica al navegador que el contenido de la página está en español.

Los atributos siguen generalmente esta estructura:

```html
nombreDelAtributo="valor"
```

Por ejemplo:

```html
lang="es"
```

Más adelante en el curso veremos muchos otros atributos, como:

- `src`
- `href`
- `class`
- `id`

Cada uno sirve para algo distinto.

---

### 4.5 Tipos de elementos

En HTML existen dos tipos principales de elementos:

- elementos vacíos
- elementos con contenido

#### Elementos vacíos

Los elementos vacíos solo tienen etiqueta de apertura.

No tienen contenido ni necesitan una etiqueta de cierre.

Por ejemplo:

```html
<br>
```

Este elemento únicamente sirve para hacer un salto de línea.

Otros ejemplos de elementos vacíos que veremos más adelante son:

```html
<img>
<meta>
<input>
```

#### Elementos con contenido

Los elementos con contenido tienen:

- una etiqueta de apertura
- una etiqueta de cierre
- contenido entre ambas

Por ejemplo:

```html
<span>Esta es una página HTML muy simple.</span>
```

Aquí:

- `<span>` es la etiqueta de apertura
- `</span>` es la etiqueta de cierre
- `Esta es una página HTML muy simple.` es el contenido

Además, el contenido de un elemento puede incluir otros elementos dentro.

Por ejemplo:

```html
<body>
    <span>¡Bienvenid@!</span>
    <br>
    <span>Esta es una página HTML muy simple.</span>
</body>
```

En este caso, el elemento `<body>` contiene otros tres elementos:

- `<span>`
- `<br>`
- `<span>`

Esto significa que `<body>` es el elemento padre, mientras que los demás son sus elementos hijos.

#### Estructura jerárquica

Los elementos HTML se organizan de forma jerárquica, como si fueran un árbol.

El elemento principal o raíz del documento es:

```html
<html>
```

Dentro de él se encuentran:

```html
<head>
<body>
```

Y a su vez, dentro de `<head>` se encuentran:

```html
<meta>
<title>
```

Mientras que dentro de `<body>` se encuentran:

```html
<span>
<br>
<span>
```

Por esta razón, en HTML se utilizan los conceptos de:

- elemento padre
- elemento hijo

Comprender esta jerarquía es muy importante, ya que toda página web está construida de esta manera.

---

### 4.6 Conclusión

En esta clase aprendiste que HTML no es un lenguaje de programación, sino un lenguaje de marcado.

También aprendiste que HTML permite estructurar el contenido de una página web mediante etiquetas.

Además, conociste:

- la estructura básica de un documento HTML
- qué son las etiquetas
- la diferencia entre etiquetas normales y etiquetas auto-contenidas
- qué son los atributos
- la diferencia entre elementos vacíos y elementos con contenido
- cómo funciona la jerarquía entre elementos padre e hijo

Con este conocimiento fundamental, ahora estás preparado para comenzar a crear tus primeras páginas web estructuradas y explorar más a fondo todas las posibilidades que HTML5 ofrece.

¡Nos vemos en la siguiente clase!
