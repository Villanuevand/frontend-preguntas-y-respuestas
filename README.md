#Posibles preguntas para entrevista de trabajo (Desarrollador Frontend).

Este repositorio contiene las respuestas a posibles preguntas de entrevistas a programadores front-end. La idea fundamental de este repo es incrementar mis conocimientos. 

**Nota:** No se aceptarán ```pull requests``` o ```peticiones de envío```  para ***resolver preguntas***, solo se aceptarán aquellos que formulen ***nuevas preguntas***.

## Índice

  1. [Preguntas generales](#general)
  1. [Preguntas específicas de HTML](#html)
  1. [Preguntas específicas de CSS](#css)
  1. [Preguntas específicas de JavaScript](#js)
  1. [Preguntas de código](#codigojs)
  1. [Preguntas divertidas](#divertidas)

####<a name='general'>Preguntas generales:</a>

##### ¿Qué sistemas de control de versiones ha usado?

He usado GIT y Subversion (SVN), el primero mediante el úso de consola y el último con el cliente "Tortoise".

##### ¿Cuál es su ambiente de desarrollo favorito?

Debido a que desarrollo principalmente con `javascript` me siento muy cómo usando [WebStorm](https://www.jetbrains.com/webstorm/ "Sitio Web de WebStorm") y [Sublime Text](http://www.sublimetext.com/ "Sitio web de Sublime Text").

##### ¿Puede describir el proceso que sigue cuando crea una página web?

Dependendiendo del tipo del proyecto puedo o usar generadores con Yeoman, o crear el Scaffolding manualmente. En caso de ser la segunda opción realizo los siguiente pasos: 

 * Creción de archivo index.html. *(php, jsp, dependiendo del proyecto)*
 * Crear estructura de carpetas para recursos del sitio:
 	* CSS - Archivos css
 	* IMAGES - Imágenes  
 	* JS - Archivos Javascript
 	* ASSETS - Librerías. (jquery, modernizr, prototype, etc.)
 	* FONTS - Fuentes tipográficas.
 
##### ¿Puede describir la diferencia entre "Progressive Enhancement" y "Graceful Degradation"?
##### Explique qué significa "HTML Semántico".
##### ¿Cuál es el navegador que utiliza principalmente para el desarrollo y qué herramientas de desarrollo usa?
##### ¿Cómo optimiza los recursos de una web?
##### ¿Por qué es mejor utilizar varios dominios para distribuir los recursos de una página web?
##### ¿Cuántos recursos se pueden descargar simultáneamente de un mismo dominio?
##### Mencione tres formas para disminuir el tiempo de carga de una página (tiempo real o percibido).
##### Si se ha unido a un proyecto y los desarrolladores usan tabs y usted usa espacios, ¿qué hace?
##### Escriba una página con una galería sencilla.
##### ¿Qué herramientas usa para probar el rendimiento de su código?
##### Si pudiera elegir una tecnología para dominar este año, ¿cuál sería?
##### Explique la importancia de estándares y los grupos que los definen.
##### ¿Sabe que es el FOUC? ¿Cómo lo evita?

####<a name='html'>Preguntas específicas de HTML:</a>

* ¿Qué función cumple el `doctype` y cuántos puede nombrar?
* ¿Cuál es la diferencia entre el modo convencional y el "quirks mode"?
* ¿Cuáles son las limitaciones al utilizar páginas XHTML?
	* ¿Hay algún problema al servir las páginas usando: `application/xhtml+xml`?  
* ¿Cómo programaría una página con contenido en varios lenguajes?
	* ¿Qué consideraciones se deben tener cuando se diseñan/desarrollan sitios multi-lenguajes?
* ¿Puede usar sintaxis de XHTML en HTML5?
* ¿Cómo usa XML en HTML5?
* ¿Para qué son buenos los atributos `data-`?
* ¿Cuáles son los modelos de contenido usados en HTML4? ¿Puede compararlos a los de HTML5?
* Si consideramos HTML5 como una plataforma web abierta, ¿cuáles son las piezas del lego que constituyen HTML5?
* Describa la diferencia entre cookies, sessionStorage y localStorage.

####<a name='css'>Preguntas específicas de CSS:</a>

* Describa qué es un archivo "reset" y por qué es útil.
* Describa qué son los "floats" y su funcionamiento.
* ¿Cuáles son los métodos para "limpiar" (clear) sus "floats" y cuál es apropiado en el contexto dado?
* Explique ¿qué son los sprites en CSS y cómo los implementarias en una página?
* ¿Cuál es su técnica favorita para reemplazar imágenes y cuando usa cada una?
* ¿"CSS Hacks", archivos incluidos con etiquetas condicionales o algún otro metodo...?
* ¿Cuál es su enfoque al desarrollar páginas que dan soporte a navegadores con capacidades limitadas?
	* ¿Qué técnicas o procesos usa?
* ¿Cuáles son las distintas formas para esconder contenido, pero mantenerlo disponible únicamente para lectores de pantalla?
* ¿Ha usado algún sistema para cuadrículas (grids) y cuál prefiere?
* ¿Ha usado o implementado "media queries" o reglas específicas para dispositivos móviles?
* ¿Está familiarizado con aplicar estilos a SVGs?
* ¿Cómo optimiza sus páginas para la impresión?
* ¿Cuáles son algunas de las "trampas" al escribir CSS eficiente?
* ¿Ha usado algún preprocesador para CSS?
	* De ser así, ¿puede mencionar qué le gusta y qué no de los que ha usado?
* ¿Cómo implementaría un diseño que usa fuentes que no son web-safe?
* ¿Puede explicar cómo determina un navegador qué elementos coinciden con un selector de CSS?
* ¿Puede explicar cómo entiende el `box model` (modelo de cajas) y como podría hacer que un navegador renderize su esquema usando diferentes modelos de cajas?
* Por favor enliste todos los valores para la propiedad `display` que pueda recordar
* ¿Cuál es la diferencia entre `inline` y `inline-block`?
* ¿Cuál es la diferencia entre las posiciones `relative`, `fixed`, `absolute` y `static` para un elemento dado?
* ¿Qué sabe sobre Css Flexbox y cuales son sus ventajas?

####<a name='js'>Preguntas específicas de JavaScript:</a>

##### Explique "event delegation".

"Event Delegation" o "Delegación de Evento" no es más que la metodología de javascript que permite evitar la utilización de muchos `listeners` en nodos puntuales, creando un único en un nodo padre, para saber si algun evento fué disparado. Esto es posible gracias a 2 funcionalidades importantes del lenguaje como lo son `event bubbling` o `Propagación de evento` y `event target` o `Objetivo del evento`. 

Cuando un evento es disparado en un elemento, este a su vez dispara el mismo evento hacia su ancestros (esto es conocido como  `evento bubbling` o `propagación de evento`), el evento se propaga desde el elemento donde fué originado hasta el tope del arbol DOM. Gracias a esto es posible saber con exactitud en que elemento hijo se originó un evento. 


* Explique cómo funciona `this` en JavaScript.
* Explique cómo funciona la herencia de prototipos (prototypal inheritance) en JavaScript.
* ¿Cómo realiza pruebas en JavaScript?
* AMD vs. CommonJS?
* ¿Qué bibliotecas de JavaScript ha usado?
* ¿Alguna vez ha mirado el código fuente de bibliotecas/frameworks que utiliza?


##### ¿Qué es un `hashtable`?

Un `hashtable` no es más que un objeto que almacena datos con una estructura `clave : valor`


* ¿Cuál es la diferencia entre variables `undefined` y variables `undeclared`?
* ¿Qué es un "closure" y cuando, o por qué usaría uno?
	* ¿Cuál es su patrón favorito para crearlos? Cuadriculado (Solo aplica a las IIFEs)
* ¿Puede hablar de un uso típico para una función anónima?
* ¿Puede explicar el Patrón Módulo en JavaScript y cuándo lo usaría?
	* Puntos extra por mencionar un namespace no contaminado.
	* ¿Qué pasa si sus módulos no tienen un namespace?
* ¿Cómo organiza su código, patrón módulo, herencia clásica?
* ¿Cuál es la diferencia entre objetos huésped (host objects) y objetos nativos?
* ¿Cuál es la diferencia entre:
` function Person(){} `, `var person = Person()` y `var person = new Person()`?
* ¿Cuál es la diferencia entre `.call` y `.apply`?
* ¿Puede explicar el uso de `Function.prototype.bind`?
* ¿Cuándo optimiza su código?
* ¿Puede explicar cómo funciona la herencia en JavaScript?
* ¿Cuándo usarías `document.write()`?
* ¿Cuál es la diferencia entre detección de capacidades, inferencia de capacidades y usar la cadena del user agent.
* Explique AJAX con tanto detalle como pueda.
* Explique cómo funciona JSONP (y cómo no es AJAX realmente)
* ¿Ha utilizado alguna vez templates en JavaScript?
	* De ser asi, ¿qué bibliotecas ha usado?
* ¿Puede explicar en que consiste el "hoisting"?
* ¿Puede hablar sobre "event bubbling"?
* ¿Cuál es la diferencia entre un "atributo" y una "propiedad"?
* ¿Por qué es una mala idea extender objetos nativos de JavaScript?
* ¿Por qué es una buena idea extender objetos nativos de JavaScript?
* ¿Cuál es la diferencia entre el evento "document load" y el evento “document ready"?
* ¿Cuál es la diferencia entre `==` y `===`?
* Si tiene que obtener un parametro de la URL, ¿cómo lo harías?
* Explique la política de mismo origen (same-origin policy) y sus repercusiones en JavaScript.
* ¿Puede describir los patrones de herencia en JavaScript?
* Haga que este código funcione:
```javascript
[1,2,3,4,5].duplicator(); // [1,2,3,4,5,1,2,3,4,5]
```
* ¿Puede describir una estrategia para memorización (*memoization*, evitar repetir cálculos) en JavaScript?
* ¿Por qué reciben el nombre de sentencias ternarias? ¿Qué significa la palabra "ternaria"? 

##### Haga un ciclo `for` de `100` iteraciones que imprima **"fizz"** en los múltiplos de `3`, **"buzz"** en los múltiplos de 5 y **"fizzbuzz"** en los múltiplos de `3` y `5`

```
for(var i = 1; i <= 100; i++) {   
  if(i % 3 === 0 && i % 5 === 0)
    console.log(i + ' fizzbuzz');
   else { 
      if(i % 5 === 0)
        console.log(i + ' buzz');
      else if (i % 3 === 0) 
        console.log(i + ' fizz');
      else 
        console.log(i)
   }    
}
```
* De manera general, ¿por qué es una buena idea no usar el "ámbito" (scope) global de un sitio web?
* ¿Qué es el `arity` de una función?
* ¿Qué es `"use strict";`? ¿Cuáles son las ventajas y desventajas de usarlo?

####<a name='codigojs'>Preguntas de código:</a>

Pregunta: ¿Cuál es el resultado de la siguiente sentencia?
```javascript
~~3.14
```

Pregunta: ¿Cuál es el resultado de la siguiente sentencia?
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```

Pregunta: ¿Cuál es el valor de **window.foo**?
```javascript
( window.foo || ( window.foo = "bar" ) );
```

Pregunta: ¿Cuál es el resultado de los dos *alerts*?
```javascript
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```

Pregunta: ¿Cuál es el valor de **foo.length**?
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```

####<a name='divertidas'>Preguntas divertidas:</a>

* ¿Qué es lo más genial que ha programado y qué es lo que más le enorgullece de ello?
* ¿Cuáles son sus partes favoritas de las herramientas de desarrollo que usa?
* ¿Tiene algún proyecto personal? ¿De qué tipo?
* ¿Cuál es su funcionalidad favorita de Internet Explorer?

