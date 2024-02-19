 # JavaScript Apuntes

 > La programación en el lado de cliente condificada dentro de las webs, es la responsable de hacer páginas más atractivas.


### Que es JavaScript
 
 JavaScript nace de Self y ActionScript. Un lenguaje parecido es el TypeScript.

### Lenguajes interpretados o de guiones
 
 JavaScript es un lenguaje interpretado
 
 > Interpretados: Algunos lenguajes interpretados se llaman también lenguaje de guiones. Los lenguajes interpretados se ejecutan mediante un interprete, que procesa las ordenes que incluye el programa uno a uno. JavaScript se ejecuta secuencialmente.

 > Compilados: Los lenguajes compilados necesitan un compilador para poder ser ejecutados.

### Orientación a objetos JavaScript

 JavaScript soporta programación a objetos pero no es su principal función.

 ##### Programación orientada a objetos
 
 La programación orientada a objetos es un paradigma de programación que se basa en el concepto de "objetos". Un objeto es una entidad que puede tener datos(propiedades) y comportamientos (metodos). La idea es modelar un mundo real en temas objetos. Esto facilita la representación de conceptos complejos de manera mas clara y organizada.

 ###### Características: 
   > Clases y Objetos: 
	Una clase es un modelo que defina la estructura y el comportamiento de los objetos. Un objeto es una instancía de una clase, es decir, representa un ejemplo especifico con datos y comportamientos definido por la clase.

   > Encapsulamiento: 
	Es el concepto de ocultar detalles internos de la implementación de un objeto y exposar solo el que sea necesario. Permite controlar el acceso a ciertos comportamientos de un objeto(metodos o propiedades), para evitar modificaciónes no deseadas.

   > Herencia:
	Permite que una clase (subclase) herede propiedades y metodos de otra clase (superclase o clase padre). Facilita la reutilización de codigo y la organización jerarquica de clases.

   > Polimorfismo:
	Un objeto puede adoptar diferentes formas, es decir, puede comportarse de diferentes maneras segun el contexto.

   > Abstracción: 
	Esto quiere decir que se enfocan solo los aspectos esenciales de un objeto y omite los detalles inecesarios. 

### Ventajas de JS en las páginas web:
   
   > Permite una gran cantidad de efectos en las páginas.

   > Añade interactividad con el usuario.
  
   > Proporciona integración con otros conectores o extensiones (plugins). no proporciona solo acceso a los objetos HTML, también proporciona acceso a lso objetos especificos del navegador como Adobe Acrobat etc.7

   > Permite la validación de los formularios en el lado del cliente. Una validación inicial de los formularios, es posible eliminar errores simples.

   > Permite acceder a información del sistema.



### Desventajas de JS en las webs

   > La seguridad es el principal problema de JS. Los fragmentos de codigo de js que se incluyen en las páginas web se descargan en los navegadores y se ejecutan en el lado del cliente, permitiendo asi que un codigo malicioso se pueda ejecutar en la máquina cliente y asi explotar alguna vulnerabilidad de seguridad  conseguida en las aplicaciones, navegadores etc.

   > Tienden a introducir una cantidad enorme de fragmentos de codigo en nuestro sitios web. Esto se resuelve guardando el codigo JS en ficheros externos con la extensión .JS y así la web queda más limpia y legible. 




## Estructura 
  
  * Js distingue entre mayusuculas y minusculas, case-sensitive.
  * Existen dos maneras de separar instrucciónes, la primera es ; y la segunda es empezando una nueva linea.
  * No tiene en cuenta los espacios en blanco y nuevas lineas.
  * Utiliza el conjunto de caracteres Unicode.

### Estructura
	La estructura se basa en tres partes: Declaración de variables, funciones y ejecución del codigo.



## Entrada y salida de datos:
  La lectura de datos en js se puede realizar de varias maneras, dependiendo de la fuente de los datos y el entorno en el que se trabaja.

 > prompt() Abre una pop-up y permite escribir los datos. A día de hoy ya se podría decir que esta obsoleto.
 
##### Entrada de datos con formularios HTML
  Se suele usar formularios y se puede mejorar y manipular con JavaScript.

##### Manipulación del DOM 
  Para manejar la entrada de datos del usuario mediante el DOM, en HTML con JS, puedes usar metodos y propuiedades proporcionados por el DOM para acceder y manipular elementos HTML.


## Visualización o salida de los resultados
  La salida de datos en JS se realiza normalmente a través de la consola en entornos de desarollo o pruebas. O mediante la manipulación del DOM para mostrar información directamente a la interficie del usuario.

## Visualización en consola
  Este metodo se usa cuando se esta en pruebas, se consulta el resultado usando f12 y escogiendo la pestaña consola.

## Utiliza el metodo de acceso al DOM document.write()
  El DOM nos permite acceder al codigo HTML y modificarlo.

## Window.alert() o alert()
  Manera para interactuar con el navegador.


## Confirmación de la salida de datos
  ### window.confirm()
	Este metodo nos muestra una ventana de dialogo y dos botones, aceptar y cancelar.




## Variables y valores
