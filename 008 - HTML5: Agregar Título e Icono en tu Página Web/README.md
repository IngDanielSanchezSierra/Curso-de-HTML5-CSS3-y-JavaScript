# Capítulo 008 - HTML5: Agregar Título e Icono en tu Página Web

[⬅️ Capítulo anterior](../007%20-%20HTML5%3A%20Visualizar%20archivo%20HTML%20en%20el%20Navegador%20Web) | [🏠 Índice del curso](../README.md) | [➡️ Siguiente capítulo](../)

Haz clic en la imagen para ver el video:
[![Ver video](https://img.youtube.com/vi/n38qg4EmzSA/maxresdefault.jpg)](https://www.youtube.com/watch?v=n38qg4EmzSA)

Agregar título e icono en tu página web
En esta clase aprenderás a configurar dos elementos esenciales dentro de la cabecera : el título de la página y su icono o favicon. Aunque son detalles pequeños, aportan identidad y profesionalismo a cualquier sitio web.

---

## 📌 Temas que verás en esta clase

En este capítulo aprenderás:

- [8.1 Definir los elementos de la cabecera <head>](#8-1)
- [8.2 Título de la página](#8-2)
- [8.3 Icono de la página (favicon)](#8-3)
- [8.4 Detalle que aporta profesionalismo](#8-4)

---

## 📁 Recursos

- [index.html](./recursos/index.html)

---

## 📖 Contenido del capítulo

Ahora pasamos a definir los elementos de la cabecera <head>. Aquí declaramos información que no se muestra directamente al usuario, pero que es esencial para que los navegadores, buscadores y redes sociales comprendan correctamente nuestra página.

---

### <a name="8-1"></a>8.1 Definir los elementos de la cabecera <head>

La cabecera contiene configuraciones fundamentales del documento, como:

- El título de la página
- Icono de la página
- La codificación de caracteres
- Metadatos de descripción o palabras clave
- Y también se puede enlazar o añadir CSS y JavaScript dentro del documento HTML

Todos estos elementos ayudan a los navegadores a interpretar correctamente el sitio y también influyen en la forma en que los motores de búsqueda clasifican su contenido.

En esta clase aprenderemos a agregar un título y un icono a nuestra página.

### <a name="8-2"></a>8.2 Título de la página

Lo primero que definiremos dentro de <head> es el título de la página con el elemento <title>. Escribiremos como contenido “Mi primer archivo HTML5”, dentro de las etiquetas de apertura y cierre:

<title>Mi primer archivo HTML5</title>

Guarda los cambios. Verás que el texto que escribiste dentro del elemento <title> aparece en la pestaña del navegador.

### <a name="8-3"></a>8.3 Icono de la página (favicon)

Otro elemento dentro de <head> es el que nos permite establecer el icono de la página, conocido como favicon.

Para agregarlo usamos la etiqueta <link>:

<link rel="icon" href="imagenes/icono.png" type="image/png" sizes="16x16">
- El atributo “rel” con el valor "icon" indica que este elemento representa un icono.
- Y el atriburo “href” contiene como valor la ruta y nombre del archivo.
- “type” define el formato 
- Y “sizes” especifica el tamaño del icono 

Estos dos últimos atributos (type y sizes) son opcionales.

### <a name="8-4"></a>8.4 Detalle que aporta profesionalismo

El título e icono de la página aportan un detalle profesional a tu página.

Este título e icono lo utilizan los motores de búsqueda, como Google, para mostrar el nombre de la página en los resultados.

En el ejemplo podemos ver la búsqueda de la página YouTube en Google, donde aparece tanto el título como el icono configurado en su sitio.

También se utilizan cuando los usuarios guardan la página en los navegadores web como Google Chrome.

En este caso, puedes ver cómo se muestra el título y el icono de la página YouTube guardada en la barra de favoritos.

Incluso son utilizados cuando las personas comparten la página en redes sociales, envían su enlace mediante aplicaciones de mensajería o se instala la página como aplicación.

Como te puedes dar cuenta, estos dos sencillos elementos pueden definir y aportar identidad a tu sitio.

---

[⬅️ Capítulo anterior](../007%20-%20HTML5%3A%20Visualizar%20archivo%20HTML%20en%20el%20Navegador%20Web) | [🏠 Índice del curso](../README.md) | [➡️ Siguiente capítulo](../)
