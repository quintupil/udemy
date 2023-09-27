<h1>Curso Master en CSS: Responsive, SAAS, Flexbox, Grid y Bootstrap</h1>
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










