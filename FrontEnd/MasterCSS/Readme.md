<h1>Curso Master en CSS: Responsive, SAAS, Flexbox, Grid y Bootstrap</h1>
<a href="https://github.com/quintupil/udemy/blob/main/README.md">Volver</a>

<h2>Sección 3: Aprender HTML desde Cero</h2>

<h3>3. ¿Qué es HTML y para que sirve?</h3>

URL: 
"https://itauchile.udemy.com/course/master-en-css-responsive-sass-flexbox-grid-y-boostrap-4/learn/lecture/16524102#overview"

            
HTML: Simplemente es un lenguaje de marcado o de etiquetado que nos permite crear la estructura básica, el esqueleto básico de una página web. De acuerdo, si nos vamos a Wikipedia podemos ver que HTML significa Hypertexts Markup Language y es un lenguaje de marcas, de hipertextos y básicamente nos permite hacer la estructura básica de una página web.

CSS: Luego para darle estilo y para darle un diseño a nuestra web ya utilizaríamos otro lenguaje que tampoco es un lenguaje de programación como tal, pero sí que es un lenguaje de maquetación que es el lenguaje CSS, que significa hojas de estilos en cascada. Entonces con HTML hacemos la estructura básica de nuestra página web y con CSS le damos estilo.

<h3>4. ¿Qué es una etiqueta y como funciona?</h3>

URL: 
"https://itauchile.udemy.com/course/master-en-css-responsive-sass-flexbox-grid-y-boostrap-4/learn/lecture/16524254#overview"

Todo el código HTML esta formado por etiqueta ejemplo:
Etiqueta de prueba: `<etiqueta atributo="valor"> Texto o Datos</etiqueta>`
Entonces cada etiqueta de las que hay en HTML puede significar algo diferente, puede hacer algo diferente. Hay etiquetas para hacer párrafos, etiquetas para imágenes, etiquetas para vídeo, etiquetas para encabezados, etiquetas para textos, para negritas, etiquetas para hacer una tabla, para hacer un listado, etcétera.

La etiqueta puede contener texto o datos y también puede tener atributos con algún valor.

Cada atributo actúa de una manera para modificar algo de la etiqueta,  Por ejemplo, si le pongo un atributo class y le pongo aquí algo, pues le estoy añadiendo una clase al elemento que puede actuar como selector. Si le pongo un atributo style, yo le puedo añadir unos estilos CSS aquí en línea. Es decir, hay varios atributos diferentes que lo que van a hacer es modificar el comportamiento del etiqueta principal.

<h3>5. La estructura de una página web con HTML</h3>

URL: 
"https://itauchile.udemy.com/course/master-en-css-responsive-sass-flexbox-grid-y-boostrap-4/learn/lecture/16524258#overview"

Un documento HTML o una página web HTML debe tener una estructura marcada y una estructura estándar. Por ejemplo cuando nosotros vayamos a hacer una página web, esta página tiene que tener una cabecera y un cuerpo, y todo debe ir englobado dentro de una etiqueta HTML.

Primnero definir: `<!DOCTYPE HTML>`

DOCTYPE: Permite establecer la versión de HTML que estamos utilizando. De acuerdo si estamos utilizando XHTML, HTML5 como es el caso, o cualquier otra versión de HTML.

Si indicamos el `<!DOCTYPE HTML>`, vamnos a estar utilizando la última versión que es HTML5 

Segundo definir la etiqueta HTML: Dentro de esta etiqueta `<html></html>`, va a ir toda la página web. Incluso le podríamos poner un atributo, como podría ser el lang, el lenguaje, y le podríamos indicar que el lenguaje que vamos a estar utilizando es el castellano o el español.

Ejemplo: `<html lang="es"> Aquí toda la página werb</html>`

Tercero definir la etiqueta HEAD: Esta etiqueta `<head></head>` Corresponde a la cabecera, dentro de esta etiqueta van a ir metadatos o va ir información que no va a ser visible dentro de la página web. Dentro head puedo definir la etiqueta `<title></title>` que es para definir el titulo de mi página web, esta información se muestra en la pestaña de mi navegador web.


`&aacute;`: Me permite escapar caracteres especiales en este caso la "á"

Cuarto definir el body: Esta etiqueta `<body></body>`, nos permite definir el cuerpo de la página web. El body es lo que se va a mostrar en la página web en sí, el contenido de la página siempre debe ir dentro de esta etiqueta.

Dentro del body puedo definir distintas etiquetas, comno por ejempolo `<h1></h1>` que es un encabezado mas grande y `<h2></h2>` que es un encabezado más pequeño que podria ser un subtitulo. 

ChatGpt: "En HTML, existen 6 niveles diferentes de etiquetas de encabezado, que van desde `<h1>` hasta `<h6>`. Cada uno de estos niveles representa un nivel diferente de encabezado, donde `<h1>` es el encabezado de nivel más alto o más importante, y `<h6>` es el de nivel más bajo o menos importante. Aquí tienes un ejemplo de cómo se podrían usar en el código HTML:

`<h1>Encabezado nivel 1</h1>`
`<h2>Encabezado nivel 2</h2>`
`<h3>Encabezado nivel 3</h3>`
`<h4>Encabezado nivel 4</h4>`
`<h5>Encabezado nivel 5</h5>`
`<h6>Encabezado nivel 6</h6>`

Cada etiqueta `<h>` define un encabezado, y se puede usar cualquier número de veces en un documento HTML. Los navegadores web generalmente muestran los encabezados con diferentes tamaños de fuente, dependiendo del nivel del encabezado, pero esto también se puede personalizar con CSS. Además, los encabezados juegan un papel importante en la estructuración semántica del contenido de la página y en la accesibilidad".

Este tipo de etiquetas se deben utilizar cuando queremos darle una prioridad o una relevancia a ciertos textos


Nota: "Siempre acuérdate de abrir y cerrar la etiqueta, aunque hay algunas que no necesitan abrir y cerrar la etiqueta porque no tienen un contenido dentro". Por ejemplo: `</br>`

Chatgpt: "A nivel de SEO, la etiqueta "h1" es especialmente importante, ya que los motores de búsqueda como Google la consideran un fuerte indicativo del tema principal de la página. Es recomendable tener una única etiqueta "h1" por página que contenga las palabras clave principales y describa de forma clara y concisa el contenido de la página.

Las etiquetas h2, h3, etc., también son importantes para la estructuración del contenido y la jerarquía de la información. Ayudan a los motores de búsqueda a entender la estructura de la página y los subtemas tratados en ella. Es bueno utilizar estas etiquetas para organizar el contenido de manera clara y lógica.

Además de las etiquetas de encabezado, hay otros elementos y atributos HTML que son importantes para SEO, como la etiqueta `<title>`, las metaetiquetas (por ejemplo, `<meta name="description" content="..."/>`), los atributos alt en las imágenes, y las etiquetas de enlace (anchor tags) `<a>` con el atributo href, entre otros. Utilizar estos elementos correctamente puede ayudar a mejorar la visibilidad de una página web en los resultados de búsqueda".

<h3>6. Etiquetas de texto en HTML</h3>

URL: 
https://itauchile.udemy.com/course/master-en-css-responsive-sass-flexbox-grid-y-boostrap-4/learn/lecture/16524260?kw=Master+en+CSS&src=sac#overview

Ya vimos en la lección anterior las etiquetas de texto h1, h2, h3 ... h6, ahora tenemos otra etiqueta para definir texto dentro de un parrafo es la etiqueta `<p></p>`.

Buscar en google lorem ipsum que son textos de pruebas.

La etiqueta `<br/>` no tiene ningún contenido pero sí que va a hacer una función clara, que es la etiqueta del salto de línea.

La etiqueta `<hr/>` al igual que la etiqueta `<br/>` me aparece en pantalla un salto de linea, pero además agrega una línea recta en la página.

La etiqueta `<strong></strong>`, permite poner un texto en negrita.

La etiqueta `<em></em>`, permite colocar un texto en cursiva. 

La etiqueta `<spam></spam>`, es una etiqueta que no hace nada, no hace ninguna acción sobre el texto, pero sin embargo yo le puedo poner un identificador resaltado y yo le puedo poner clases para luego con CSS cambiarle los estilos.

La etiqueta `<i></i>`, también nos permite poner la letra en cursiva al igual que `<em>`

La etiqueta `<blockquote></blockquote>`, nos permite que su contenido sea como una especie de cita, es decir, me aparece con una tabulación especial y con un espaciado especial. Así que  `<blockquote>` se utiliza para simplemente remarcar una cita dentro del texto.

<h3>7. Listas y listados en tu página web HTML</h3>

El objetivo principal de una lista es tener una serie de información conjunta o una serie de datos que tienen cierta relación y que nos interesa mostrarlo de una manera conjunta en formato de listado.

Hay dos tipos de listas, las ordenadas y las desordenadas: 
Una lista ordenada sería con la etiqueta `<ol>` y cierro la etiqueta  `</ol>`.

Para crear cada uno de los elementos de la lista yo tengo que utilizar la etiqueta `<li>` y cierro la etiqueta `</li>`.

Una lista desordenada sería con la etiqueta `<ul>` y cierro la etiqueta  `</ul>`.

Chatgpt:
    La etiqueta `<ol>` en HTML se utiliza para definir una lista ordenada. El término "ordenada" en este contexto significa que los elementos de la lista se numeran. Los elementos individuales de la lista se definen utilizando la etiqueta `<li>`. Aquí tienes un ejemplo de cómo se podría utilizar la etiqueta `<ol>` en el código HTML:

    ```html
    <ol>
        <li>Elemento 1</li>
        <li>Elemento 2</li>
        <li>Elemento 3</li>
    </ol>
    ```

    Este código creará una lista numerada que se verá así:

    1. Elemento 1
    2. Elemento 2
    3. Elemento 3

    Puedes comparar esto con una lista desordenada, que se crea con la etiqueta `<ul>`, donde los elementos de la lista se marcan con viñetas en lugar de números.

<h3>8. Poner imágenes en una web</h3>

La etiqueta `<img/>` nos permite poner una imagen en la página web, y como no tiene contenido de texto se cierra en la misma etiqueta. 

Está etiqueta tiene varios atributos importantes `alt` para que muestre un texto para cuando la imagen no cargue, a nivel de SEO para describir el contenido de la imagen y a nivel de usabilidad si no carga una imagen carga un texto. 

Atributo `title` para cuando pasemos por encima de la imagen aparezca el titulo de la imagen. 

Atributo `src` es para poner la ruta relativa de la imagen `img/perrito.png`, o también poner la ruta absoluta `D:\Udemy\Repositorio\udemy\FrontEnd\MasterCSS\web\img\perrito.png`, el problema que ocurre al poner ruta absoluta, que si movemos nuestra página a otro servidor la imagen ya no cargará, por eso es mejor trabajar con ruta relativa al proyecto.

Atributo `width` para indicar el ancho de la imagen y atributo `height` para indicar la altura de la imagen, lo más correcto es tocar uno de los dos atributos para que la imagen no se desforme.

<h3>9. Tablas HTML</h3>

La etiqueta `<table></table>` nos va a servir para dibujar en la pantalla una tabla tipica de contenido, en la cual vamos a tener filas y columnas con diferentes valores y elementos. Antiguamente se usaban las tablas para maquetar o estructurar una página web, pero eso está mal hecho, hoy en día se debe hacer con css y con el modelo de cajas, flotando cajas moviendo elementos, conforme el diseño lo necesite. En la actualidad se usan las tablas para administrar contenido en filas y columnas, se usa para organizar información. 

Las tablas se hacen con varias etiquetas, la etiqueta principal es `<table></table>`, para representar fila se utiliza la etiqueta `<tr></tr>`, y para la columna se utiliza `<td></td>` 

La etiqueta `<th></th>` nos permite poner en negrita el encabezado de la tabla, se suele poner th en la primera fila y por cada columna de la tabla poner th, para que resalte lo que va a contener como información cada columna. 

El atributo `colspan` se aplica a los `<td>` y sirve para expandir la columna, a tantas columnas como se requiera de la tabla. Ejemplo: `<td colspan="2">` se va a expandir a dos columnas. Si expandes mas columnas de las que contiene la tabla, solo se va a ver hasta la cantidad de columnas que tiene la tabla nada más, es decir, si tengo tres columnas y a la columna dos expando a 7, solo se verá la expanción de 2 de las 7 columnas, las 5 restantes expanción no se verán en pantalla.

<h3>10. Crear Formularios en HTML</h3>

Los formularios en html sirven para enviar texto, información, o cualquier cosa al servidor, el formulario sirve para que un usuario introduza información la envie al servidor y que se ejecute alguna acción. Para crear un formulario se debe hacer con la etiqueta `<form></form>`.

Se puede agregar el atributo `action` para indicar a donde debe ir el formulario, esto es util cuando se trabaja con backend, para enviar el formulario a un flujo que guarde la infoprmación en base de datos etc. 

También se puede agregar el atributo `method` para indicar que método HTTP vamos a utilizar, si vamos a utilizar post, get u otro etc. 

Etiqueta de tipo texto `<input type="text"/>` se cierra inmediato porque no tiene ningún contenido. Atributo `name` para darle un nombre que identifica a la etiqueta `input`. Atributo `placeholder` nos permite mostrar un texto o infoprmación en el `input`, y al escribir sobre el `input` este texto desaparece.

Etiqueta `<label></label>` que nos ayuda para indicar que tipo de información se requiere ingresar en una etiqueta tipo texto como el descrito anteriormenmte, atributo `for` sirve para indicar a que etiqueta corresponde el label. Ejemplo:

    <form>
        <label for="nombre">Nombre</label>
        <input type="text" name="nombre"/>
    </form>

Etiqueta `<textarea></textarea>` al igual que `input` nos permite ingresar texto, la diferencia que con `textarea` puedo ingresar mas texto y expandir la caja de texto, para ver de mejor manera lo que se ha escrito, también tiene el atributo `name` para indentificar la etiqueta, es importante que el contenido del atribuito `name` no tenga caracteres especiales como acento.

Etiqueta radio buttons `<input type="radio"/>`, este tipo de etiqueta nos permite elegir una opción de x opciones que hay disponibles. Deben tener un valor con el atributo `value` 

Otro tipo de elemento que puede contener en un formulario es la etiqueta `<select></select>` sirve para seleccionar una opción de varias opciones que se desplegan, dichas opciones se etiquetan con `<option></option>` que serán las distintas opciones, donde el usuario puede seleccionar una de las opciones que se desplegan y se muestran hacia abajo. La etiqueta `option` también tiene el atributo `value` 

Botón para enviar formulario `<input type="submit" value="Enviar Formulario">` este tipo de etiqueta nos permite enviar el formulario hacia el servidor para enviar la información a procesar.

Ejemplo: 

        <form>
            <p>
                <label for="nombre">Nombre</label>
                <input type="text" name="nombre" placeholder="Escribe tú Nombre"/>
            </p>
            <p>
                <label for="descripcion">Descripción</label>
                <textarea name="descripcion"></textarea>
            </p>
            <input type="radio" name="genero" value="hombre"/>Hombre <br/>              
            <input type="radio" name="genero" value="mujer"/>Mujer <br/>              
            <input type="radio" name="genero" value="otro"/>Otro <br/>              

            <select name="generodos">
                <option value="hombre">Hombre</option>
                <option value="mujer">Mujer</option>
                <option value="otro">Otro</option>
            </select>
            <input type="submit" value="Enviar formulario"/>
        </form>    

<h3>11. Ejercicio completo para practicar con HTML</h3>

Solo indica el ejercicio que se debe realizar 

<h3>12. Múltiples páginas</h3>

Resolución ejercicio.

Comentario de código en html se etiqueta de la siguiente forma:

    <!-- Comentario de código HTML-->

Estos comentarios nos sirve para documentar código en html, o para indicar algo importante que deseamos describir, estos comentarios no se verán en la página solo en el código fuente.

<h3>13. Enlaces con HTML</h3>

Etiqueta `<a href="pagina.html" title="Titulo del enlace">Texto</a>`, permite crear un enlace hacia otrá página de nuestro sitio web. Con atributo `target="_blank"` abre la página en una nueva pestaña del navegador.

<h2>Sección 4: [Introducción: CSS y las hojas de estilo en cascada]</h2>

<h3>14. CSS - ¿Qué aprenderemos?</h3>

<ol>
    <li>Primeros pasos</li>
    <li>Selectores</li>
    <li>Fuentes y colores</li>
    <li>Fondos y textos</li>
    <li>Modelo de cajas y posicionamiento</li>
    <li>Ejercicios con CSS</li>
    <li>Sombras y efectos</li>
    <li>Relativo, absoluto y fijo</li>
    <li>Transiciones y animaciones</li>
    <li>Proyecto completo</li>
</ol>






















