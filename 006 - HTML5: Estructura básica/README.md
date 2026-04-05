# Capítulo 006 - HTML5: Estructura básica

[⬅️ Capítulo anterior](../005%20-%20HTML5%3A%20Primer%20archivo%20HTML) | [🏠 Índice del curso](../README.md) | [➡️ Siguiente capítulo](../)

Haz clic en la imagen para ver el video:
[![Ver video](https://img.youtube.com/vi/D10MwtoX9mw/maxresdefault.jpg)](https://www.youtube.com/watch?v=D10MwtoX9mw)

Estructura básica en HTML5
En esta clase aprenderás a construir la columna vertebral de cualquier página web, conociendo cada elemento fundamental de la estructura de un documento HTML5. Al finalizar, tendrás un archivo completamente funcional y listo para agregar contenido.

---

## 📌 Temas que verás en esta clase

En este capítulo aprenderás:

- [6.1 Tipo de documento](#6-1)
- [6.2 Elementos estructurales](#6-2)

---

## 📁 Recursos

- [index.html](./recursos/index.html)

---

## 📖 Contenido del capítulo

Es momento de aprender la estructura básica de un documento HTML5. Construiremos juntos la columna vertebral de cualquier página web, entendiendo cada elemento y su función dentro de la página. Al finalizar, tendrás tu primer documento HTML completamente funcional y listo para agregar contenido.

### <a name="6-1"></a>6.1 Tipo de documento

Los navegadores son capaces de procesar diferentes tipos de archivos, por este motivo, lo primero que debemos hacer en la construcción de un documento con código HTML es indicar su tipo. Para asegurarnos de que el contenido de nuestro documento sea interpretado correctamente como código HTML5, agregamos la declaración: <!DOCTYPE html>. Es importante aclarar que esta no es una etiqueta HTML, sino una declaración, y esta debe ser la primera línea del documento, sin ningún espacio o código previo. Aunque visualmente las páginas podrían verse igual sin esa línea en navegadores web modernos, es una buena práctica incluirla siempre, porque garantiza consistencia y compatibilidad con la versión 5 de HTML. 

En versiones anteriores de HTML, esta declaración era mucho más larga y compleja. En HTML5 se simplificó al máximo para que sea fácil de recordar.

### <a name="6-2"></a>6.2 Elementos estructurales

Como lo mencionamos anteriormente, los elementos HTML conforman una estructura de tipo árbol. Esta estructura presenta múltiples niveles de organización, con elementos padres he hijos, o elementos hermanos. Algunos de estos elementos están a cargo de definir secciones generales del documento y otros encargados de representar secciones menores o contenido. 

Después de declarar el tipo de documento, iniciamos la estructura con el elemento raíz <html>. Este elemento puede incluir el atributo “lang” para declarar el idioma en el que vamos a escribir el contenido de la página. 

Existen varios valores disponibles para el atributo “lang", por ejemplo: “en” para inglés, “fr” para francés y “es” para español. No son los únicos, existen valores que no son solo para especificar idiomas en general, también existen valores que puedes usar para especificar idiomas con precisión regional, por ejemplo: es-MX para español de México. 

Siempre se recomienda usar el “lang” más específico posible, por ejemplo “es-MX” en lugar de solo “es” para que los lectores de pantalla, traductores automáticos y buscadores interpreten mejor el contenido.

No puedes poner varios idiomas a la vez en un “lang”. Solo uno. Si una página tiene varias secciones en diferentes idiomas, lo correcto es agregar un atributo “lang” con su respectivo idioma en el párrafo, título, texto u otro elemento que contenga un idioma diferente.

Por ejemplo, el siguiente párrafo, que contiene texto en inglés, lo podemos especificar con el atributo “lang“ y su respectivo valor “en” para ingles en general.

<p lang="en">This text is in English.</p>

No te preocupes si aun no sabes lo que es un párrafo <p>, esto lo veremos cuando expliquemos los elementos de texto. Solo quería aclarar lo evidente, en la vida real una página web puede contener información en diferentes idiomas, y una buena práctica como desarrollador es especificar en el elemento raíz <html> el idioma principal de la página, y posteriormente especificar el idioma requerido en cada uno de los elementos con diferente idioma.

Son tantos idiomas que podemos usar en el atributo “lang” que no los podemos mencionar todos, pero aquí podemos ver una tabla de los más comunes:

Ejemplos comunes:

![Fig. 1 - Tabla de códigos de idiomas BCP más comunes](media/Fig.%201%20-%20Tabla%20de%20códigos%20de%20idiomas%20BCP%20más%20comunes.png)

*Fig. 1 - Tabla de códigos de idiomas BCP más comunes.*

Ahora conozcamos los elementos que definen la columna vertebral de la estructura de un documento HTML.

El código insertado dentro de las etiquetas <html> se tiene que dividir en dos secciones principales: el elemento <head> que corresponde a la cabecera del documento html y el elemento <body> que corresponde al cuerpo del documento html. Por supuesto, empezando con la cabecera.

<head> es el elemento que define la información necesaria para configurar la página web, como el título, el icono, el tipo de codificación de caracteres, metadatos, archivos externos requeridos por el documento, etc. 
Todos estos los veremos después de explicar lo que es body.

<body> es el elemento que delimita el contenido del documento. Es la parte visible de la página web. Aquí es donde agregaremos texto, imágenes, videos, formularios y cualquier otro elemento visible para el usuario. 

Con esto, la columna vertebrar ya está lista. En la siguiente clase aprenderemos a definir la información de la cabecera <head>.

---

[⬅️ Capítulo anterior](../005%20-%20HTML5%3A%20Primer%20archivo%20HTML) | [🏠 Índice del curso](../README.md) | [➡️ Siguiente capítulo](../)
