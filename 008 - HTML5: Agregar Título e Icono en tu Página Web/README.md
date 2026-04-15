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
- [icono.png](./recursos/imagenes/icono.png)

---

## 📖 Contenido del capítulo

Ahora comenzaremos a trabajar con la cabecera `<head>` de nuestro documento HTML.

Dentro de esta sección agregaremos información que normalmente no se muestra directamente dentro de la página, pero que es muy importante para que los navegadores, buscadores y otras aplicaciones comprendan correctamente nuestro sitio web.

---

### <a name="8-1"></a>8.1 Definir los elementos de la cabecera `<head>`

La cabecera `<head>` contiene configuraciones fundamentales del documento HTML.

Dentro de esta sección podemos definir, por ejemplo:

- El título de la página
- El icono o favicon
- La codificación de caracteres
- Metadatos, como descripciones o palabras clave
- Archivos CSS y JavaScript externos

> [!NOTE]
> Más adelante aprenderemos a trabajar con la codificación de caracteres, metadatos y archivos externos. En este capítulo solamente nos enfocaremos en el título y el icono de la página.

Todos estos elementos ayudan a que:

- El navegador interprete correctamente la página
- Los motores de búsqueda comprendan el contenido del sitio
- Otras aplicaciones, como redes sociales o navegadores, muestren correctamente tu página

---

### <a name="8-2"></a>8.2 Título de la página

Lo primero que agregaremos dentro de `<head>` será el título de la página utilizando la etiqueta `<title>`.

Escribe el siguiente código dentro de tu elemento `<head>`:

```html
<title>Mi primer archivo HTML5</title>
```

Después de guardar los cambios, el texto aparecerá en la pestaña del navegador.

> [!TIP]
> El contenido del elemento `<title>` no se muestra dentro de la página web, sino en la pestaña del navegador.

Por ejemplo, si tu documento queda así:

```html
<head>
    <title>Mi primer archivo HTML5</title>
</head>
```

Entonces verás `Mi primer archivo HTML5` como nombre de la pestaña.

---

### <a name="8-3"></a>8.3 Icono de la página (favicon)

Otro elemento importante dentro de `<head>` es el icono de la página, también conocido como favicon.

Para agregar un favicon utilizamos la etiqueta `<link>`:

```html
<link rel="icon" href="imagenes/icono.png" type="image/png" sizes="16x16">
```

Cada atributo tiene una función diferente:

- `rel="icon"` indica que este elemento representa el icono de la página.
- `href="imagenes/icono.png"` indica la ubicación y el nombre del archivo de imagen.
- `type="image/png"` especifica el formato del archivo.
- `sizes="16x16"` indica el tamaño del icono.

> [!NOTE]
> Los atributos `type` y `sizes` son opcionales. El navegador puede mostrar el icono incluso si no los agregas.

Tu cabecera podría quedar así:

```html
<head>
    <title>Mi primer archivo HTML5</title>
    <link rel="icon" href="imagenes/icono.png" type="image/png" sizes="16x16">
</head>
```

> [!IMPORTANT]
> Para que el favicon funcione correctamente, el archivo `icono.png` debe existir dentro de la carpeta `imagenes`.

---

### <a name="8-4"></a>8.4 Detalle que aporta profesionalismo

Aunque el título y el favicon parecen detalles pequeños, ambos aportan identidad y profesionalismo a una página web.

Estos elementos se utilizan en muchos lugares, por ejemplo:

- En la pestaña del navegador
- En los resultados de búsqueda de Google
- En la barra de favoritos del navegador
- Cuando una página se comparte en redes sociales o aplicaciones de mensajería
- Cuando un sitio web se instala como aplicación

> [!TIP]
> Un buen título y un favicon ayudan a que tu página sea más fácil de reconocer.

Por ejemplo, cuando buscas una página como YouTube en Google, puedes ver que aparece tanto el icono como el título configurado en su sitio.

También sucede lo mismo cuando guardas una página en favoritos: el navegador utiliza el favicon y el título para identificarla.

Como puedes ver, estos dos elementos tan sencillos pueden hacer que tu sitio se vea mucho más profesional.

---

[⬅️ Capítulo anterior](../007%20-%20HTML5%3A%20Visualizar%20archivo%20HTML%20en%20el%20Navegador%20Web) | [🏠 Índice del curso](../README.md) | [➡️ Siguiente capítulo](../)
