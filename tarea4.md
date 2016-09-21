Tarea 4
==============================

----

## Aplicaciones Moviles

#### Carlos Fernando Torres Luna

##### cf.torresluna@gmail.com 

--- 
---

## Investigacion.

### ¿Qué es un Patron de Diseño?
Los patrones de diseño son soluciones para problemas típicos y recurrentes que nos podemos encontrar a la hora de desarrollar una aplicación.

Existen diversas maneras de agrupar los patrones de diseño. Quizá la más extendida es agruparlos según su propósito. En este caso tendríamos las siguientes categorías:

- Patrones creacionales: utilizados para instanciar objetos, y así separar la implementación del cliente de la de los objetos que se utilizan. Con ellos intentamos separar la lógica de creación de objetos y encapsularla.
- Patrones de comportamiento: se utilizan a la hora de definir como las clases y objetos interaccionan entre ellos.
- Patrones estructurales: utilizados para crear clases u objetos que incluidos dentro de estructuras más complejas.

## ¿En Que consiste el patron singleton?
La idea del patrón Singleton es proveer un mecanismo para limitar el número de instancias de una clase. Por lo tanto el mismo objeto es siempre compartido por distintas partes del código. Puede ser visto como una solución más elegante para una variable global porque los datos son abstraídos por detrás de la interfaz que publica la clase singleton.
Dicho de otra manera, esta patrón busca garantizar que una clase sólo tenga una instancia y proporcionar un punto de acceso global a ella.


El patrón singleton se implementa creando en nuestra clase un método que crea una instancia del objeto sólo si todavía no existe alguna. Para asegurar que la clase no puede ser instanciada nuevamente se regula el alcance del constructor (con modificadores de acceso como protegido o privado).

### ¿En que consiste el patron Factory?
Libera al desarrollador sobre la forma correcta de crear objetos. Define la interfaz de creación de un cierto tipo de objeto, permitiendo que las subclases decidan que clase concreta necesitan instancias.
Muchas veces ocurre que una clase no puede anticipar el tipo de objetos que debe crear, ya que la jerarquía de clases que tiene requiere que deba delegar la responsabilidad a una subclase.

### ¿En que consiste el patron Builder? 
Permite la creación de un objeto complejo, a partir de una variedad de partes que contribuyen individualmente a la creación y ensamblación del objeto mencionado. Hace uso de la frase "divide y conquistarás". Por otro lado, centraliza el proceso de creación en un único punto, de tal forma que el mismo proceso de construcción pueda crear representaciones diferentes.

Los objetos que dependen de un algoritmo tendrán que cambiar cuando el algoritmo cambia. Por lo tanto, los algoritmos que estén expuestos a dicho cambio deberían ser separados, permitiendo de esta manera reutilizar dichos algoritmos para crear diferentes representaciones. 

### ¿Investigar que es la herramienta ADB de Android? 
Las siglas ADB significan Android Debug Bridge y se corresponden con una herramienta de software que nos permite interactuar con nuestro smartphone Android desde un ordenador. Así, por ejemplo, a través de ADB podemos ejecutar comandos para copiar archivos desde el ordenador al teléfono o viceversa, flashear un revocery o el firmware completo e incluso reiniciar el dispositivo en modo recovery. 

Básicamente, en el ADB es la manera de cambiar profundamente el software de nuestro smartphone o por lo menos acceder a él. Por supuesto, todo esto se hace posible a través de un cable USB con el que conectamos el smartphone al ordenador.

### Para que sirve el operador final en JAVA 
En una aplicación posiblemente nos encontremos con algún valor que permanece constante durante la ejecución. Podemos definirla como una variable común pero perderíamos el control. Por allí, en algún descuido, se cambiaría de valor pero no nos enteraríamos. Podemos agregar a la definición de la variable el modificador final, que indica que a esa variable solo se le puede asignar un valor u objeto una única vez. La sintaxis es la siguiente:

<code>final tipo_variable nombre_de_variable = valor; </code>

### ¿Que Lenguajes soportan Sobre Carga de operadores? 
| Operadores | No Sobrecargable | Sobrecargable |
|--|--|--|
|New Definible| ML, Pico,Prolog | Scala, Swift, Perl 6, Fortran, F#, Haskell,Io |
| Limited set | Basic, C, GO, Java, Javascrpt, Pascal | C#, C++, MATLAB, Ruby, Python, PHP |

### ¿Para que sirve Gradle? 
Gradle es una herramienta para automatizar la construcción de nuestros proyectos, por ejemplo las tareas de compilación, testing, empaquetado y el despliegue de los mismos. Es muy flexible para la configuración, pero además ya tiene armadas las tareas para las mayoría de los proyectos por default. Esta herramienta es usado por grandes proyecto “Open Source” como “Spring”, “Hibernate”, y “Grails”. 

Gradle usa un “Domain Specific Language” (DSL) basado en “Groovy” para declarar la formas de construir el proyecto. Así que para configurarlo simplemente podemos escribir código en Groovy, el cual en su sintaxis es muy similar a Java, lo que nos va  a hacer sencillo expresar, las tareas que queremos que realice. 

### ¿En que consiste la injección de dependencias en desarrollo de software, y por qué es útil utilizarla?
El patrón de inyección de dependencias consiste en hacer que nuestras piezas de software sean independientes comunicándose únicamente a través de un interface. Esto implica muchas modificaciones en el código fuente como el uso de implementaciones, la eliminación de la instanciación de objetos mediante la instrucción new o la necesidad de un modo de configuración que indique que clases se instanciarán en el caso de solicitarlo.
