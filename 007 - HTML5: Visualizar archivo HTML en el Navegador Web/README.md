# Capítulo 007 - HTML5: Visualizar archivo HTML en el Navegador Web

[⬅️ Capítulo anterior](../006%20-%20HTML5%3A%20Estructura%20básica) | [🏠 Índice del curso](../README.md) | [➡️ Siguiente capítulo](../008%20-%20HTML5:%20Agregar%20Título%20e%20Icono%20en%20tu%20Página%20Web)

Haz clic en la imagen para ver el video:
[![Ver video](https://img.youtube.com/vi/ZRhq_SV55dI/maxresdefault.jpg)](https://www.youtube.com/watch?v=ZRhq_SV55dI)

Visualizar tu archivo HTML en el navegador
En esta clase aprenderás dos formas de abrir tu archivo HTML para ver tus cambios: usando Live Server y de forma manual desde el explorador de archivos. Este paso es fundamental para comenzar a visualizar tu trabajo en el navegador.

---

## 📌 Temas que verás en esta clase

En este capítulo aprenderás:

- [7.1 Abrir un archivo HTML usando Live Server](#7-1)
- [7.2 Abrir un archivo HTML de forma manual](#7-2)

---

## 📁 Recursos

- [index.html](./recursos/index.html)

---

## 📖 Contenido del capítulo

Antes de continuar con la cabecera `<head>`, primero aprenderemos a visualizar nuestro archivo HTML dentro del navegador web.

En este capítulo conocerás dos formas diferentes de abrir tu archivo HTML:

- Usando la extensión `Live Server`
- Abriendo el archivo manualmente desde el explorador de archivos

> [!NOTE]
> Este es un tema muy básico. Si ya sabes cómo abrir un archivo HTML en el navegador, puedes avanzar directamente al siguiente capítulo.

---

### <a name="7-1"></a>7.1 Abrir un archivo HTML usando Live Server

La forma más cómoda de visualizar una página web durante el desarrollo es utilizando la extensión `Live Server`, la cual instalamos anteriormente en `Visual Studio Code`.

#### Pasos para abrir tu archivo con Live Server

1. En `Visual Studio Code`, localiza tu archivo HTML en el panel `Explorer`.
2. Haz clic derecho sobre el archivo.
3. Selecciona la opción `Open with Live Server`.

Después de hacerlo, se abrirá automáticamente tu navegador web —por ejemplo `Google Chrome`— mostrando tu archivo HTML.

Como tu archivo todavía no contiene contenido visible, probablemente verás una página completamente en blanco.

> [!TIP]
> Esto es normal. La página está funcionando correctamente, simplemente todavía no hay contenido dentro del elemento `<body>`.

La principal ventaja de `Live Server` es que actualiza la página automáticamente cada vez que guardas cambios en tu archivo HTML.

> [!IMPORTANT]
> Con `Live Server` no es necesario presionar `F5` ni recargar manualmente la página.

Para comprobar que funciona correctamente, escribe temporalmente el siguiente texto dentro de tu elemento `<body>`:

```html
<body>
    ¡Hola Mundo!
</body>
```

Ahora guarda tu archivo:

- Presionando `Ctrl + S`
- O desde el menú `File` → `Save`

Después de guardar, verás el cambio reflejado inmediatamente en el navegador.

---

### <a name="7-2"></a>7.2 Abrir un archivo HTML de forma manual

Si no tienes instalada la extensión `Live Server`, también puedes abrir tu archivo HTML manualmente.

#### Pasos para abrir tu archivo manualmente

1. Haz clic derecho sobre el archivo HTML en el panel `Explorer`.
2. Selecciona la opción `Reveal in File Explorer` o `Revelar en el Explorador de Archivos`.
3. Se abrirá la carpeta donde se encuentra tu archivo HTML.
4. Haz doble clic sobre el archivo para abrirlo.

Si al hacer doble clic el archivo no se abre en `Google Chrome`, puedes hacer lo siguiente:

1. Haz clic derecho sobre el archivo HTML.
2. Selecciona `Abrir con`.
3. Elige `Google Chrome`.

> [!NOTE]
> Este método también funciona correctamente para visualizar tus páginas HTML.

Sin embargo, a diferencia de `Live Server`, cuando hagas cambios en tu archivo tendrás que actualizar la página manualmente.

Después de guardar tu archivo, refresca la página usando alguna de estas opciones:

- Presiona `F5`
- Haz clic en el botón de recargar del navegador

> [!TIP]
> Este método es totalmente válido, pero `Live Server` hace el proceso mucho más rápido y cómodo mientras desarrollas.

Con cualquiera de estos dos métodos ya puedes visualizar tu archivo HTML en el navegador y comprobar los cambios que vayas realizando.

---

[⬅️ Capítulo anterior](../006%20-%20HTML5%3A%20Estructura%20básica) | [🏠 Índice del curso](../README.md) | [➡️ Siguiente capítulo](../008%20-%20HTML5:%20Agregar%20Título%20e%20Icono%20en%20tu%20Página%20Web)
