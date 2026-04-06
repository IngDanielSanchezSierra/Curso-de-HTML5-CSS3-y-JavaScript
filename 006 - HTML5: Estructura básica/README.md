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

Es momento de aprender la estructura básica de un documento `HTML5`. En este capítulo construiremos la columna vertebral de cualquier página web y conocerás la función de cada uno de sus elementos principales.

Al finalizar, tendrás tu primer documento HTML completamente funcional y listo para comenzar a agregar contenido.

---

### <a name="6-1"></a>6.1 Tipo de documento

Los navegadores pueden procesar distintos tipos de archivos. Por esta razón, lo primero que debemos hacer al crear un documento HTML es indicar qué tipo de documento estamos utilizando.

Para decirle al navegador que nuestro archivo utiliza `HTML5`, agregamos la siguiente declaración al inicio del documento:

```html
<!DOCTYPE html>
```

> [!IMPORTANT]
> `<!DOCTYPE html>` no es una etiqueta HTML. Es una declaración y siempre debe colocarse en la primera línea del documento, sin espacios ni código antes de ella.

Aunque en muchos navegadores modernos una página puede funcionar incluso sin esta línea, es una buena práctica incluirla siempre, ya que garantiza que el documento sea interpretado correctamente como `HTML5`.

> [!NOTE]
> En versiones anteriores de HTML esta declaración era mucho más larga y compleja. En `HTML5` se simplificó para que sea más fácil de recordar.

---

### <a name="6-2"></a>6.2 Elementos estructurales

Los elementos HTML forman una estructura similar a un árbol, donde existen elementos padres, hijos y hermanos.

Algunos elementos se encargan de definir las secciones principales del documento, mientras que otros representan contenido más específico dentro de la página.

Después de la declaración `<!DOCTYPE html>`, el siguiente elemento que debemos escribir es el elemento raíz:

```html
<html lang="es-MX">
</html>
```

El elemento `<html>` representa todo el documento HTML y puede incluir el atributo `lang`, el cual sirve para indicar el idioma principal de la página.

Existen muchos valores posibles para `lang`. Algunos ejemplos son:

- `es` → Español
- `es-MX` → Español de México
- `en` → Inglés
- `en-US` → Inglés de Estados Unidos
- `fr` → Francés

> [!TIP]
> Siempre es recomendable usar el valor más específico posible. Por ejemplo, es mejor usar `es-MX` en lugar de solamente `es`.

Esto ayuda a que:

- Los lectores de pantalla interpreten mejor el contenido.
- Los traductores automáticos funcionen correctamente.
- Los buscadores entiendan mejor el idioma de la página.

> [!IMPORTANT]
> El atributo `lang` solamente puede tener un idioma principal a la vez.

Si una parte de la página está escrita en otro idioma, lo correcto es agregar el atributo `lang` únicamente al elemento que contiene ese texto.

Por ejemplo:

```html
<p lang="en">This text is in English.</p>
```

> [!NOTE]
> No te preocupes si todavía no sabes qué es la etiqueta `<p>`. Más adelante aprenderás a trabajar con párrafos y otros elementos de texto.

A continuación puedes ver algunos de los códigos de idioma más utilizados:

![Fig. 1 - Tabla de códigos de idiomas BCP más comunes](media/Fig.%201%20-%20Tabla%20de%20códigos%20de%20idiomas%20BCP%20más%20comunes.png)

*Fig. 1 - Tabla de códigos de idiomas BCP más comunes.*

---

Ahora conozcamos los elementos principales que forman la estructura básica de cualquier documento HTML.

Dentro del elemento `<html>` debemos dividir el documento en dos secciones principales:

```html
<html lang="es-MX">
    <head>
    </head>

    <body>
    </body>
</html>
```

#### El elemento `<head>`

El elemento `<head>` corresponde a la cabecera del documento HTML.

Dentro de esta sección se agrega la información necesaria para configurar la página, por ejemplo:

- El título de la página.
- El icono o favicon.
- La codificación de caracteres.
- Metadatos.
- Archivos CSS y JavaScript externos.

> [!NOTE]
> Más adelante, en el siguiente capítulo, aprenderás a configurar correctamente todos estos elementos.

#### El elemento `<body>`

El elemento `<body>` representa el cuerpo del documento y contiene toda la parte visible de la página web.

Aquí es donde agregaremos:

- Texto
- Imágenes
- Videos
- Formularios
- Botones
- Y cualquier otro elemento visible para el usuario

```html
<body>
    <!-- Aquí irá el contenido visible de la página -->
</body>
```

> [!TIP]
> Todo lo que el usuario ve dentro de la página web se coloca dentro del elemento `<body>`.

Con esto, la columna vertebral de tu documento HTML ya está lista. En el siguiente capítulo aprenderás a configurar la información de la cabecera utilizando el elemento `<head>`.

---

[⬅️ Capítulo anterior](../005%20-%20HTML5%3A%20Primer%20archivo%20HTML) | [🏠 Índice del curso](../README.md) | [➡️ Siguiente capítulo](../)
