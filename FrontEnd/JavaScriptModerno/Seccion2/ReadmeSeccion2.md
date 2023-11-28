# **Sección 2**

## **TEMAS PUNTUALES**

- En esta sección tocaremos los siguientes temas:
- Historia de JavaScript
- Uso de JavaScript en la industria actual
- Hola Mundo en JavaScript
- Creación de variables y constantes
- Introducción a la consola de JavaScript
- Depuración y breakpoints
- Problemas con la declaración de variables con var
- Prompts, alerts, confirms.
- Recuerden que al final de la sección tendrán el código fuente para que lo descarguen en caso de que sea necesario para compararlo o bien para tenerlo como respaldo.

### **10. Hola Mundo**

#### **Notas:**

- Todas las funciones en JS retornan algo.
- Se recomienda que los JS vayan al final del HTML, pero es mas recomendable tener los script en un archivo.

### **11. Introducción a variables y comentarios**

#### **Comentarios**

Son líneas de código que el intérprete de JS ignorará a la hora de ejecutar.

#### **Versiones de JS**

**Notas: Se debe tener en cuenta las versiones de JS al desarrollar.**

- 1996: LiveScript a JavaScript (estándar)
- 1997: ES1 (ECMAScript 1)
- 2009: ES5 (ECMAScript 5) con muchas características nuevas
- 2015: ES6/ES2015 (ECMAScript 2015) que fue la actualización más grande de JavaScript hasta el momento.
- 2015: Se estableció el año de nuevos lanzamientos de JavaScript.
- 2016/2017/2018/2019/2020/...

#### **¿Qué versión JS debo utilizar?**

- ES5:
  - Soportada en todos los navegadores web.
- ES6/ES2015, ES7/ES2016, ES8/ES2017:
  - Soportados por la mayoria de los navegadores modernos
  - Pero no por todos los navegadores Web
  - Muchas características pueden ser implementadas con polyfills

#### **Polyfills**

Es un código que provee el funcionamiento de una nueva característica de JavaScript (ES6), en versiones viejas como ES5.

### **12. Introducción a la consola**

**Notas: JS es un lenguaje interpretado.**

### **13. Depuración y breakpoints**

Se realizan desde el navegador y desde VSC pero se requiere tener instalado Node.js

### **14. Orden y lugar de las importaciones**

El orden y lugar de las importaciones de los archivos de JS si importan, va a fectar el rendimiento de la aplicación de varias maneras.

La importación del archivo JS puede ir en dos partes, antes del cierre del body o entre las etiquetas del head.

### **15. Principal problema con la inicialización de variables con Var.**

Al utilizar la declaración "var" para inicializar variables, si el nombre de la variable existe en el objeto window,  este se sobrescribe y es dificil detectar este error, por eso se recomienda no utilizar la declaración var.

Ejemplo:

var outerHeight = 680;

Si el atributo outerHeight del objeto window tiene otro valor, este se sobrescribirá con la definición anterior.

Si utilizas las declaraciones let o const, y defines el nombre de variable igual al de los atributos del objeto windows, estos no sobrescribirán el valor.

Otro problema es el siguiente caso: 
Supongamos que tenemos el siguiente codigo

app.js

console.log( miNuevoNombre );

Al ejecutar código anterior deberia dar un error en la consola del navegador, indicando quie la variable no está definida, si ahora ejecutamos el siguiente código:

app.js

console.log( miNuevoNombre ); 

var miNuevoNombre = "Renato García"; 

En la consola del navegador dará el error undefined. En JS cualquier variable que no esta inicializada va a dar undefined. JS detectó la variable al final del archivo, pero en la lectura del archivo app.js la variable aún no se ha definido. Esto es un gran problema porque si yo quiero concatenar algún valor a la variable, el navegador interpretará el error unfefined como un string y lo concatenará al valor concatenado ejemplo: 

app.js

console.log( miNuevoNombre + ' Q.'); 

var miNuevoNombre = "Renato García"; 

En consola del navegador se mostrará "undefined Q.", y es un error que nos puede costar mucho tiempo en solucionar. 

Ahora si cambiamos la declaración por "let", esto va a cambiar el error y mostrará en la consola un error más descriptivo. Por eso se recomienda usar let o const (si valor no cambiará) en vez de usar var.

ERROR:
app.js:37  Uncaught ReferenceError: Cannot access 'miNuevoNombre' before initialization
    at app.js:37:14
(anónimo) @ app.js:37








