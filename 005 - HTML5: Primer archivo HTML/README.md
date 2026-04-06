# Capítulo 005 - HTML5: Primer archivo HTML

[⬅️ Capítulo anterior](../004%20-%20HTML5%3A%20Introducción) | [🏠 Índice del curso](../README.md) | [➡️ Siguiente capítulo](../006%20-%20HTML5%3A%20Estructura%20básica)

Haz clic en la imagen para ver el video:
[![Ver video](https://img.youtube.com/vi/5-QoJuRrCF4/maxresdefault.jpg)](https://www.youtube.com/watch?v=5-QoJuRrCF4)

Tu primer archivo HTML
En esta clase aprenderás la relación entre HTML, CSS y JavaScript, por qué es importante separarlos en archivos independientes, y darás tu primer paso práctico creando un archivo index.html en Visual Studio Code.

---

## 📌 Temas que verás en esta clase

En este capítulo aprenderás:

- [5.1 Relación entre HTML, CSS y JavaScript](#5-1)
- [5.2 Creación de un archivo HTML en Visual Studio Code](#5-2)

---

## 📁 Recursos

- [index.html](./recursos/index.html)

---

## 📖 Contenido del capítulo

### <a name="5-1"></a>5.1 Relación entre HTML, CSS y JavaScript

Para crear una página web completa es necesario combinar tres tecnologías principales: `HTML`, `CSS` y `JavaScript`.

- `HTML` se encarga de definir la estructura y el contenido de la página web.
- `CSS` se utiliza para el diseño y la apariencia visual.
- `JavaScript` aporta funcionalidad e interactividad.

Cada una de estas tecnologías se escribe normalmente en archivos independientes:

- `HTML` en archivos con extensión `.html`
- `CSS` en archivos con extensión `.css`
- `JavaScript` en archivos con extensión `.js`

Los archivos `CSS` y `JavaScript` se enlazan posteriormente dentro del archivo HTML principal para que todas las tecnologías trabajen juntas.

> [!NOTE]
> Aunque es posible escribir código CSS y JavaScript directamente dentro de un archivo `.html`, en este curso utilizaremos archivos separados, ya que es la forma correcta y más recomendada de trabajar.

Separar cada tecnología en su propio archivo tiene varias ventajas:

- Mejora la organización del proyecto.
- Facilita el mantenimiento del código.
- Permite reutilizar estilos y funcionalidades en diferentes páginas.
- Mejora el rendimiento, ya que el navegador puede guardar en caché los archivos `.css` y `.js`.

> [!TIP]
> Por ejemplo, si tienes varias páginas HTML, todas pueden utilizar el mismo archivo CSS y el mismo archivo JavaScript, evitando repetir código.

En este capítulo nos enfocaremos únicamente en `HTML`, por lo que todavía no veremos cómo enlazar archivos CSS y JavaScript.

> [!IMPORTANT]
> Más adelante, en las secciones de CSS y JavaScript, aprenderás a enlazar correctamente estos archivos con HTML.

---

### <a name="5-2"></a>5.2 Creación de un archivo HTML en Visual Studio Code

Ahora que ya sabes que el código HTML se escribe dentro de un archivo con extensión `.html`, es momento de crear tu primer documento.

#### Pasos para crear tu archivo HTML

1. Abre `Visual Studio Code`.
2. Haz clic en el icono `Explorer` de la barra lateral izquierda o presiona `Ctrl + Shift + E`.
3. Haz clic en `Open Folder`.
4. Crea una nueva carpeta en la ubicación de tu preferencia.
5. Asigna el nombre que desees a tu carpeta.
6. Entra en la carpeta recién creada y haz clic en `Seleccionar carpeta`.
7. Ahora verás tu carpeta en el panel `Explorer`.
8. Haz clic en el icono `New File`, o haz clic derecho sobre el panel `Explorer` y selecciona `New File...`.
9. Escribe `index.html` como nombre del archivo.
10. Presiona `Enter`.

Después de crear el archivo:

- Verás `index.html` dentro de la carpeta en el panel `Explorer`.
- El archivo también se abrirá automáticamente en el editor de `Visual Studio Code`.

> [!NOTE]
> `index.html` será tu primer archivo HTML y será donde comenzarás a escribir el código de tus páginas web.

#### ¿Por qué usar el nombre `index.html`?

La extensión `.html` indica que el archivo contiene código HTML.

Por otro lado, el nombre `index` se utiliza comúnmente como la página principal o página de inicio de un sitio web. Muchos servidores web están configurados para buscar automáticamente un archivo llamado `index.html` y mostrarlo cuando el usuario entra al sitio.

> [!TIP]
> Por esta razón, la mayoría de los proyectos web comienzan creando un archivo llamado `index.html`.

---

### <a name="5-3"></a>5.3 Conclusión

En este capítulo aprendiste:

- La función de `HTML`, `CSS` y `JavaScript`.
- Por qué es recomendable mantener cada tecnología en archivos separados.
- Cómo crear tu primer archivo `index.html` en `Visual Studio Code`.

Con esto ya tienes listo tu primer archivo HTML y estás preparado para comenzar a escribir tu primer código en el siguiente capítulo.

---

[⬅️ Capítulo anterior](../004%20-%20HTML5%3A%20Introducción) | [🏠 Índice del curso](../README.md) | [➡️ Siguiente capítulo](../006%20-%20HTML5%3A%20Estructura%20básica)
