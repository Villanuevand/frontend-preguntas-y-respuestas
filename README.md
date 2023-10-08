# Posibles preguntas para entrevista de trabajo como desarrollador front-end.

Este repositorio contiene las respuestas a posibles preguntas de entrevistas a programadores front-end. La idea fundamental de este repo es ayudar a candidatos a este rol a solidificar sus conocimientos. 

**Nota:** No se aceptarán ```pull requests``` o ```peticiones de envío```  para ***resolver preguntas***. Solo se aceptarán aquellas que formulen ***nuevas preguntas***.

## Índice

  1. [Preguntas generales](#general)
  1. [Preguntas de rendimiento web](#webperformance)
  1. [Preguntas específicas de HTML](#html)
  1. [Preguntas específicas de CSS](#css)
  1. [Preguntas específicas de JavaScript](#js)
  1. [Preguntas de código](#codigojs)
  1. [Preguntas divertidas](#divertidas)

#### <a name='general'>Preguntas generales:</a>

* Cuéntame sobre ti.
* ¿Qué has aprendido en esta semana?
* ¿Qué es lo que te interesa de la programación?
* ¿Qué es lo que más te interesa de este puesto?
* ¿Puedes decirme por qué elegiste una carrera como desarrollador front-end?
* Para ti, ¿cuál es la relación ideal entre diseño visual y el desarrollo front-end?
* ¿Podría describir algún problema técnico que haya resuelto recientemente?
* ¿Cuáles son las consideraciones del área de interfaces, rendimiento, posicionamiento, mantenimiento o seguridad que toma en cuenta al desarrollar sitios o aplicaciones web?
* Si tuviera cinco hojas de estilo distintas, ¿cómo las integraría a su página web?
* ¿Cómo optimizaría los recursos de un sitio web?
* Explique qué son las aplicaciones de internet enriquecidas y accesibles y los lectores de pantalla, además de cómo hacer una página web accesible.
* Explique las ventajas y desventajas de usar animaciones en CSS, contrario a usar animaciones programadas en JavaScript.
* ¿Qué significa CORS y a qué problema está relacionado?
* Mencione una ocasión en la que pasó por alto una solución obvia para arreglar un problema de desarrollo de software.
* ¿Cuál es su enfoque si sus compañeros dirigen el código en una dirección con la que no se siente usted confortable?
* ¿Cómo maneja comentarios críticos o negativos en un ambiente laboral?

##### ¿Qué sistema de control de versiones ha usado?

Referirse al empleo de Git a través de IDE plugins, herramientas GUI visuales, o línea de comandos. 

##### ¿Cuál es su ambiente de desarrollo favorito?

Debido a que desarrollo principalmente con JavaScript me siento muy cómo usando [WebStorm](https://www.jetbrains.com/webstorm/ "Sitio Web de WebStorm") y [Visual Studio Code](https://code.visualstudio.com/ "Sitio web de Visual Studio Code").

##### ¿Puede describir el proceso que sigue cuando crea una página web?

En dependencia del tipo de proyecto y framework que se decida emplear, varios de los elementos a continuación pueden servir como punto de partida de una respuesta más elaborada:

- Aprovechar herramientas como Create React App, Angular CLI, Vue CLI o SvelteKit para la creación, compilación y el despliegue.
- Configuración del archivo 'package.json' para gestionar dependencias y scripts si se usa Node.js.
- Crear el *scaffolding* manualmente. En caso de ser la segunda opción realizo los siguiente pasos: 
  * Creación del fichero index.html. *(php, jsp, dependiendo del proyecto)*
  * Crear estructura de carpetas para recursos del sitio:
    * CSS - Archivos css
    * IMAGES - Imágenes  
    * JS - Archivos Javascript
    * ASSETS - Librerías. (jquery, modernizr, prototype, etc.)
    * FONTS - Fuentes tipográficas.

##### ¿Puede describir la diferencia entre las técnicas "progressive enhancement" y "graceful degradation"?
*"Progressive enhacement"* ó *"mejora progresiva"* es el concepto opuesto a *"graceful degradation"* ó *"degradación elegante"* (cmo yo lo llamo). Cuando se habla de *progressive enhancement* hacemos referencia a la técnica en donde un sitio web, dispone de características más avanzadas (tanto de diseño, usabilidad, y navegabilidad), cuanto más avanzado o moderno sea el navegador que utiliza el usuario. *Graceful degradation* es todo lo contrario, mientras más antigúo es el navegador, el sitio web tendrá funcionalidades muy límitadas en comparación con uno que usa uno más moderno.

##### ¿Cuál es el navegador que utiliza principalmente para el desarrollo y qué herramientas de desarrollo usa?
Principalmente [ Google Chrome ](https://www.google.com/chrome/browser/desktop/index.html), pero siempre tengo instalado [Mozilla Firefox](https://www.mozilla.org/es-AR/firefox/new/). Entre las herramientas que uso puedo mencionar: 
- [WebStorm]
- [Visual Studio Code]
- [Chrome Developer Tools]
- [Angular CLI]
- [Npm]
- [Bower]
- [Sass]
- [Webpack]

##### Si se ha unido a un proyecto y los desarrolladores usan tabulaciones y usted usa espacios, ¿qué hace?
##### ¿Cómo empiezas a contribuir en el desarrollo de un software del que no fuiste parte desde sus inicios?

##### Escriba una página con una galería sencilla.
##### Si pudiera elegir una tecnología para dominar este año, ¿cuál sería?

Definitivamente Javascript.

##### Explique la importancia de estándares y los grupos que los definen.


#### <a name='webperformance'>Preguntas de rendimiento web:</a>

##### ¿Qué herramientas usa para probar el rendimiento de su código?

Chrome DevTools. 

##### ¿Cómo optimizaría los recursos de un sitio web?
##### ¿Por qué es mejor utilizar varios dominios para distribuir los recursos de una página web?

##### Mencione tres formas para disminuir el tiempo de carga de una página (tiempo real o percibido).

##### ¿Sabe que es el FOUC? ¿Cómo lo evita?
*FOUC* es el acrónimo de __Flash Of Unstyled Content__. Es el fenómeno que ocurre, cuando al renderizar un sitio web, este se ve primero con los estilos por defecto del nevegador, y luego en un "pestañeo" los archivos creados por nosotros. Esto se puede originar por varios motivos, los más comúnes son: 
- Alta latencia del servidor.
- Excesos de archivos javascript.
- Archivos css extremadamente grandes.

Se puede evitar, creando archivos de estilos `.css` de tamaño moderado o varios distribuidos y optimizados (minificados y ofuscados). Tambien se puede aplicar __CSS Critical Path__. *Para saber más de Critical Path, leer este [enlace](https://www.smashingmagazine.com/2015/08/understanding-critical-css/)*

##### ¿Cuáles son las métricas específicas de Core Web Vitals y cuáles son los umbrales recomendados para cada una?

##### ¿Qué herramientas puedes utilizar para medir y mejorar los Core Web Vitals en tu aplicación web?


##### ¿Cómo afecta el uso de frameworks modernos de JavaScript a los Core Web Vitals de una aplicación web?

#####

#### <a name='html'>Preguntas específicas de HTML:</a>

* ¿Qué función cumple el `doctype` y cuántos puede nombrar?
* ¿Cuál es la diferencia entre el modo convencional y el "quirks mode"?
* ¿Cuáles son las limitaciones al utilizar páginas XHTML?
	* ¿Hay algún problema al servir las páginas usando: `application/xhtml+xml`?  
* ¿Cómo programaría una página con contenido en varios idiomaas? ¿Qué consideraciones se deben tener cuando se diseñan/desarrollan sitios multi-lenguajes?
* ¿Qué son elementos abiertos y elementos cerrados?
* ¿Para qué son buenos los atributos `data-`?
* Si consideramos HTML5 como una plataforma web abierta, ¿cuáles son las piezas del lego que constituyen HTML5?
* ¿Cuáles son sus dos características favoritas de HTML5 y cómo las ha implementado en sus proyectos de front-end?
* Describa la diferencia entre cookies, session storage, local storage e IndexedDB.
* ¿Qué ocurre si olvidas colocar el `DOCTYPE` en un sitio web?
#### Explique qué significa "HTML Semántico".
La palabra *"Semántica"* hace referencia a la ciencia linguística, que estudia el significado de las palabras y expresiones. Teniendo esto en cuenta, podemos decir que *"HTML Semántico"*, el es úso de las etiquetas HTML para expresar el significado real de la información en las páginas web, favoreciendo la usabilidad y accesibilidad.
Se puede mirar de la siguiente manera: 

```html
<!-- HTML No Semántico -->
<p>El título</p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed elementum nulla volutpat lorem euismod, 
eu mattis lectus bibendum. Aenean id volutpat nulla. Sed tempor tincidunt dapibus. Donec viverra mi 
quam, at sagittis quam fermentum at. Nullam maximus tortor in neque ornare, at facilisis turpis mattis.
Praesent sagittis convallis diam eget ultricies. Nullam efficitur massa eu faucibus pretium. 
Suspendisse bibendum augue ante, sed hendrerit mi dapibus cursus. Ut felis nisl, lobortis a lectus et, 
semper dignissim leo.

<ul>
	<li>1 - lorem ipsum dolor </li>
	<li>2 - lorel ipsum dolor </li>
	<li>3 - lorem ipsum dolor </li>
</ul>

<!-- HTML Semántico -->
<h1>El título</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed elementum nulla volutpat lorem euismod, 
eu mattis lectus bibendum. Aenean id volutpat nulla. Sed tempor tincidunt dapibus. Donec viverra mi quam, 
at sagittis quam fermentum at. Nullam maximus tortor in neque ornare, at facilisis turpis mattis.</p>

<p>Praesent sagittis convallis diam eget ultricies. Nullam efficitur massa eu faucibus pretium. 
Suspendisse bibendum augue ante, sed hendrerit mi dapibus cursus. Ut felis nisl, lobortis a lectus et, 
semper dignissim leo.</p>
<ol>
	<li>lorem ipsum dolor </li>
	<li>lorel ipsum dolor </li>
	<li>lorem ipsum dolor </li>
</ol>
```

#### <a name='css'>Preguntas específicas de CSS:</a>

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
* ¿Cuál es la diferencia entre `display:none` y `visibility:hidden`?
* Describe tu proceso mental para la selección de Flexbox vs CSS Grid para resolver un arreglo específico de componentes en una página web.


##### Explica los siguientes selectores: 
```css
p span
p, span
p > span
p + span
p ~ span 
a[rel='nofollow']
```

#### <a name='js'>Preguntas específicas de JavaScript:</a>

* ¿Cómo describirías la arquitectura de [Angular / React / Vue / Svelte / etc] a los desarrolladores full-stack de tu equipo?
* Menciona algunos factores que hacen único a [Angular / React / Vue / Svelte / etc] de otros frameworks basados en JavaScript.
* ¿Cuál es tu enfoque para la automatización de pruebas (pruebas unitarias, pruebas de componentes, pruebas e2e)?


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
* ¿Cuál es la diferencia entre el evento "document load" y el evento “document ready"?.

 

##### ¿Cuál es la diferencia entre `==` y `===`?

La comparación con doble signo de igualdad `==` evalúa solo el valor de los elementos comparados, mientras que la realizada con triple signo de igualda `===` evalúa el valor y el tipo de los elementos.

Para verificar esto rápidamente abre la consola del navegador y escribe lo siguiente: 
```javascript
  var a = 1;
  var b = '1';
````
Y luego escribe: 
```javascript
  a == b;// true.
  // Una vez ejecutada la primera comparativa realiza la segunda:
  a === b; // false
```

* Si tiene que obtener un parametro de la URL, ¿cómo lo harías?
* Explique la política de mismo origen (same-origin policy) y sus repercusiones en JavaScript.
* ¿Puede describir los patrones de herencia en JavaScript?

##### Haga que este código funcione:
```javascript
[1,2,3,4,5].duplicator(); // [1,2,3,4,5,1,2,3,4,5]
```
Para realizar el método `duplicator()` debe extenderse el tipo `Array` utilizando la propiedad `Array.prototype` que representa el prototipo del constructor de `Array`.
```javascript
// Extendiendo Array con un método llamado "duplicator".
Array.prototype.duplicator = function() {
   // Se utiliza el método "concat".
   return this.concat(this);   
}
````

* ¿Puede describir una estrategia para memorización (*memoization*, evitar repetir cálculos) en JavaScript?


##### ¿Por qué reciben el nombre de sentencias ternarias? ¿Qué significa la palabra "ternaria"? 

Reciben este nombre porque la sentencia consta de 3 argumentos: 

`expresion boleana ? valor si es cierto : valor si es falso`.

Según la [RAE](http://www.rae.es/ "Real Academia Española") la palabra "Ternario, ria" tiene el siguiente significado: 

> ternario, ria.
> (Del lat. ternarĭus).
> 1. adj. Compuesto de tres elementos, unidades o guarismos.
> 2. m. Espacio de tres días dedicados a una devoción o ejercicio espiritual.

Fuente: [Diccionario RAE: Ternario](http://lema.rae.es/drae/srv/search?key=ternario)


##### Haga un ciclo `for` de `100` iteraciones que imprima **"fizz"** en los múltiplos de `3`, **"buzz"** en los múltiplos de 5 y **"fizzbuzz"** en los múltiplos de `3` y `5`

```javascript
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

//  El resultado es: "goh angasal a m'i"
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

#### <a name='divertidas'>Preguntas divertidas:</a>

* ¿Qué es lo más genial que ha programado y qué es lo que más le enorgullece de ello?
* ¿Cuáles son sus partes favoritas de las herramientas de desarrollo que usa?
* ¿Tiene algún proyecto personal? ¿De qué tipo?
* ¿Cuál es una de sus funcionalidades favoritas que brindan los navegadores web modernos?