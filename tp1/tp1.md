# Práctica Nro 1 - Historia, evolución y características de Leng. de Programación

Objetivo: Conocer la evolución de los lenguajes de programación y sus características.

### Ejercicio 1: Los lenguajes de programación más representativos son:
1951 - 1955: Lenguajes tipo assembly
1956 - 1960: FORTRAN, ALGOL 58, ALGOL 60, LISP
1961 - 1965: COBOL, ALGOL 60, SNOBOL, JOVIAL
1966 - 1970: APL, FORTRAN 66, BASIC, PL/I, SIMULA 67, ALGOL-W
1971 - 1975: Pascal, C, Scheme, Prolog
1976 - 1980: Smalltalk, Ada, FORTRAN 77, ML
1981 - 1985: Smalltalk 80, Turbo Pascal, Postscript
1986 - 1990: FORTRAN 90, C++, SML
1991 - 1995: TCL, PERL, HTML
1996 - 2000: Java, Javascript, XML
Indique para cada uno de los períodos presentados cuales son las características nuevas que se incorporan y cual de ellos la incorpora

- 1951 - 1955: Lenguajes tipo assembly

Se caracterizan por fomentar la programación de bajo nivel, orientada directamente al hardware. Se utilizan mnemónicos para representar las instrucciones máquina. El código es específico para cada arquitectura.
Es la primera abstracción sobre el código máquina

- 1956 - 1960: FORTRAN, ALGOL 58, ALGOL 60, LISP

FORTRAN (Formula Translation) es el primer lenguaje de alto nivel ampliamente utilizado. Introduce estructuras como bucles, condicionales y funciones.
ALGOL (Algorithmic Language) introduce notación estructurada, bloques anidados y ámbito léxico (scope estático).
LIST (List Processing) introduce el paradigma funcional, con listas como estructuras fundamentales y funciones.

Aquí nace la programación estructurada y funcional

- 1961 - 1965: COBOL, ALGOL 60, SNOBOL, JOVIAL

COBOL: orientado a negocios, introduce descripciones estructuradas de datos, división de secciones, legibilidad para no programadores.
SNOBOL: Innovador en procesamiento de cadenas y patrones
JOVIAL: badado en ALGOL, usado en sistemas embebidos. Introduce estructuras de control más complejas.

Innova en la orientación a negocios y procesamiento de texto.

- 1966 - 1970: APL, FORTRAN 66, BASIC, PL/I, SIMULA 67, ALGOL-W

APL introduce la notación matemática compacta y las operaciones vectoriales.
SIMULA 67 es el primer lenguaje que ontroduce conceptos de programación orientada a objetos (clases, objetos, herencia).
PL/I es un lenguaje multipropósito (ciencia y negocios). Incorpora concurrencia.

Nace la programación orientada a objetos y la programación concurrente.

- 1971 - 1975: Pascal, C, Scheme, Prolog

Pascal: promueve la programación estructurada, fuerte tipado y control de errores.
C: permite programación estructurada con bajo nivel de acceso a memoria.
Scheme: variante de LISP, con soporte para closures y continuaciones.
Prolog: introduce la programación lógica, basada en hechos y reglas

Se consolida la programación estructurada, lógica y de bajo nivel de accesibilidad.

- 1976 - 1980: Smalltalk, Ada, FORTRAN 77, ML

Smalltalk: lenguaje puramente orientado a objetos. Todo es un objeto. Introduce entorno interactivo.
Ada: enfocado en sistemas críticos, con tipado fuerte, concurrencia (tasks) y modularidad.
ML: lenguaje funcional con inferencia de tipos

Se destaca la cualidad de fuerte tipado, orientación a objetos pura y la concurrencia.

- 1981 - 1985: Smalltalk 80, Turbo Pascal, PostScript

Smalltalk 80 refina la orientación a objetos con interfaz gráfica integrada.
Turbo Pascal se destaca por su rápida compilación e integración de entorno (IDE).
PostScript es un lenguaje de descripción de páginas, basado en pila y orientado a gráficos.

Se pondera la aparición de entornos integrados y lenguajes gráficos.

- 1986 - 1990: FORTRAN 90, C++, SML

FORTRAN 90: añade programación estructurada y operaciones sobre arrays.
C++: extiende C con programación orientada a objetos, sobrecarga y encapsulamiento.
SML: fortalece el paradigma funcional, sistema de tipos robusto y evaluación perezosa.

Se generaliza la Programación Orientada a Objetos y se fortalece la programación funcional.

- 1991 - 1995: TCL, PERL, HTML

TCL: lenguaje de scripting embebible.
PERL: orientado al procesamiento de texto, muy usado para scripts.
HTML: lenguaje de marcado, no de programación, para estructurar documentos web.

Se popularizan los lenguajes de scripting y web.

- 1996 - 2000: JAVA, JavaScript, XML

JAVA: lenguaje orientado a objetos, portable, con máquina virtual (JVM), garbage collector.
Javascript: scripting del lado del cliente, orientado a eventos, integración con DOM.
XML: lenguaje de marcado extensible, para intercambio de datos.

Se destaca la web dinámica, interoperabilidad y portabilidad.

### Ejercicio 2: Escriba brevemente la historia del lenguaje de programación que eligió en la encuesta u otro de su preferencia.

Historia de Rust:

Rust es un lenguaje de programación de sistemas que comenzó como un proyecto personal de Graydon Hoare en 2006, mientras trabajaba en Mozilla. Su objetivo era crear un lenguaje que ofreciera:

- Alto rendimiento (como C y C++)

- Seguridad en memoria sin necesidad de un recolector de basura

- Concurrencia segura y controlada

Hitos clave:

- 2009: Mozilla se interesa en el proyecto y comienza a financiar su desarrollo.

- 2010: El lenguaje es anunciado públicamente.

- 2012: Se lanza la versión 0.1, aún muy experimental.

- 2015: Sale Rust 1.0, la primera versión estable, marcando el inicio real de su adopción.

- 2016-2020: La comunidad crece rápidamente. Rust es votado “el lenguaje más querido” durante varios años en la encuesta de Stack Overflow.

- 2021: Se forma la Rust Foundation, una organización independiente para liderar y sostener su desarrollo.

- Actualidad: Rust es adoptado por gigantes como Microsoft, Google, AWS y Meta para desarrollar sistemas críticos, reemplazar partes escritas en C/C++ y mejorar la seguridad.

Rust es un lenguaje moderno, seguro y eficiente, valorado en contextos donde se requiere concurrencia, velocidad y seguridad en memoria sin sacrificar control.

### Ejercicio 3: ¿Qué atributos debería tener un buen lenguaje de programación? Por ejemplo, ortogonalidad, expresividad, legibilidad, simplicidad, etc. De al menos un ejemplo de un lenguaje que cumple con las características citadas.

Un lenguaje de programación debería apuntar a cumplir las siguientes caraterísticas:

> Simplicidad

La sintaxis y semántica deben ser claras y sin ambigüedades. Evitar construcciones complejas o redundantes. Un ejemplo de ello es Python, cuya sintaxis es clara y fácil de aprender.

> Ortogonalidad

Debe tenerse un pequeño número de elementos primitivos que puedan combinarse de forma consistente. Ej: Ada, pues sus características están diseñadas para combinarse de forma consistente.

> Legibilidad

El código debe ser fácil de leer y entender. Ej: Ruby se enfoca en la expresividad y legibilidad del código.

> Expresividad

Permite expresar muchas operaciones con pocas líneas de código, de forma directa. Ej: Rust tiene una sintaxis moderna y poderosa, con closures, match, etc.

> Mantenibilidad

El código debe ser fácil de modificar y extender, sin causar errores. Ej: Java favorece la organización clara mediante clases y paquetes.

> Portabilidad

El código debe ejecutrase en múltiples plataformas sin grandes modificaciones. Ej: Java posee una máquina virtual (JVM) que permite ejecutar el mismo código en diferentes sistemas.

> Eficiencia

Debe generar programas que hagan un uso eficiente de los recursos. Ej: C y Rust permiten optimizaciones de bajo nivel.

> Robustez

Permite escribir programas resistentes a errores. Ej: Ada tiene un sistema fuerte de tipos y manejo exhaustivo de errores.

### Ejercicio 4: Tome uno o dos lenguajes de los que ud. Conozca y
**- Describa los tipos de expresiones que se pueden escribir en él/ellos**
**- Describa las facilidades provistas para la organización del programa**
**- Indique cuáles de los atributos del ejercicio anterior posee el/los lenguaje/s elegidos y cuáles no posee, justifique en cada caso.**

Rust y Java:

> Tipos de expresiones

Los tipos de expresiones comunes en Rust son los literales, llamadas a funciones, sentencias `if`, `match`, operadores aritméticos/lógicos, closures, expresiones de bloque.

En Java se suelen utilizar también los lierales, llamadas a métodos, operadores aritméticos/lógicos, expresiones `if-else`, operaciones ternarias `? :`, castings, expresiones lambda.

> Facilidades para la organización del programa

En Rust los programas se pueden dividir en módulos (`mod`) y paquetes (`crate`). También se tienen las macros, `struct`, Enums y Traits (similar a las interfaces). Las reglas de ownership y Borrowing permiten controlar el acceso a los datos.

En Java el programa se estructura en clases, interfaces y paquetes. Existen también subclases y el concepto de herencia. Su organización se corrsponde con la orientación a objetos.

> Comparación con atributos del ejercicio 3

- Simplicidad

En parte Rust es simple, pero conceptos como el ownership y borrowing pueden resultar complejos. Por su parte, Java tiene una sintaxis más tradicional y directa.

- Ortogonalidad

Rust tiene una combinación coherente de tipos, traits y expresiones. Por otro lado, Java posee combinaciones que pueden ser confusas, asociadas a los genéricos y la herencia.

- Legibilidad

Aunque puede resultar complicado obtener un amplio conocimiento, un programa bien escrito en Rust es legible. Java también resulta legible con su estructura basada en clases.

- Expresividad

Rust posee expresiones como `match`, closures, expresiones de bloque que permiten escribir código complejo con alto nivel de claridad. Por su parte, Java puede ser más verboso, pero las expresiones lambda y streams contribuyen a una mayor expresividad.

- Portabilidad

Rust compila en distintas plataformas, pero requiere toolchain de la misma versión. La JVM de Java permite alta portabilidad.

- Eficiencia

Rust, al no tener garbage collector, tiene un alto rendimiento. Además, la posibilidad de manejar la memoria a un nivel más bajo aporta a la eficiencia. Por su parte, Java posee garbage collector, lo que impacta en la misma.

- Robustez

Rust tiene un sistema de tipos estricto y evita errores en tiempo de compilación. Java posee un buen manejo de excepciones.

## Lenguajes - ADA

### Ejercicio 5: Describa las características más relevantes de Ada, referida a:
**- Tipos de datos**
**- Tipos abstractos de datos – paquetes**
**- Estructuras de datos**
**- Manejo de excepciones**
**- Manejo de concurrencia**

- Tipo de datos:

Ada tiene un sistema de tipos muy fuerte y estricto. Incluye tipos primitivos (Integer, Float, Boolean, Character) y tipos derivados definidos por el usuario (subtipos, tipos enumerados, tipos rango).

- Tipos abstractos de datos - paquetes

Los paquetes (package) permiten encapsular tipos y subprogramas. Ada permite definir tipos abstractos (ADT) mediante paquetes que ocultan la implementación y exponen solo las operaciones válidas.

- Estructuras de datos

Soporta registros (record), arrays (indexados, multidimensionales, dinámicos) y acceso (punteros). También permite la definición de estructuras más complejas mediante tipos derivados.

- Manejo de excepciones

Ada tiene un mecanismo robusto para capturar y manejar excepciones. Usa bloques begin ... exception ... end, y permite definir excepciones propias.

- Manejo de concurrencia

Ada fue uno de los primeros lenguajes con concurrencia incorporada. Usa tasks (tareas) como unidades concurrentes. También se pueden sincronizar mediante rendezvous o protected objects, lo que proporciona una alta seguridad en entornos concurrentes.

## Lenguajes - JAVA

### Ejercicio 6: Diga para qué fue, básicamente, creado Java.¿Qué cambios le introdujo a la Web? ¿Java es un lenguaje dependiente de la plataforma en dónde se ejecuta? ¿Por qué?

Java fue diseñado inicialmente como una plataforma de programación orientada a objetos para dispositivos electrónicos (como decodificadores). Sin embargo, rápidamente evolucionó hacia una herramienta poderosa para el desarrollo de aplicaciones web, empresariales y móviles. Fue creado con los principios de portabilidad, robustez y seguridad.

Java revolucionó la web al permitir aplicaciones dinámicas en el navegador a través de los applets (aunque hoy en desuso). Más adelante, sus frameworks y tecnologías como Java EE, JSP y servlets permitieron la creación de aplicaciones web robustas del lado del servidor.

Java es independiente de la plataforma gracias a la Máquina Virtual de Java (JVM). El código fuente se compila a bytecode, que luego puede ejecutarse en cualquier sistema que tenga una JVM compatible, cumpliendo así su lema: "Write once, run anywhere".

### Ejercicio 7: ¿Sobre qué lenguajes está basado?

Java está influenciado principalmente por C y C++, de los cuales toma la sintaxis y ciertos conceptos (como estructuras de control). Sin embargo, elimina aspectos complejos de C++ (como los punteros explícitos y herencia múltiple) para ganar en simplicidad y seguridad.

### Ejercicio 8: ¿Qué son los applets? ¿Qué son los servlets?

Los applets son pequeñas aplicaciones Java que se ejecutaban dentro de un navegador web usando un plugin. Su uso fue descontinuado por razones de seguridad y la evolución del desarrollo web moderno.

Los servlets son componentes del lado del servidor que procesan peticiones (principalmente HTTP) y generan respuestas (como HTML). Son la base de la tecnología Java para desarrollo web antes de frameworks como Spring.

## Lenguajes - C

### Ejercicio 9: ¿Cómo es la estructura de un programa escrito en C? ¿Existe anidamiento de funciones?

Un programa en C tiene la siguiente estructura general:

```c
#include <stdio.h>  // Inclusión de librerías
// Declaración de constantes, macros y prototipos de funciones
int main() {        // Función principal
    // Declaraciones de variables
    // Instrucciones
    return 0;
}
```

En C no existe el anidamiento de funciones. No es posible definir funciones dentro de otras funciones. Todas las funciones deben definirse al mismo nivel del archivo fuente.

### Ejercicio 10: Describa el manejo de expresiones que brinda el lenguaje.

El manejo de exceciones de C:

- Soporta expresiones aritméticas, lógicas, relacionales, de asignación y combinaciones de estas.

- Tiene operadores de incremento/decremento (++, --), punteros, bit a bit, ternario (?:), etc.

- Es fuertemente tipado y requiere conversión explícita entre tipos no compatibles.

- Las expresiones se evalúan usando precedencia y asociatividad definida por el lenguaje.

## Lenguajes - Python - RUBY - PHP

### Ejercicio 11: ¿Qué tipo de programas se pueden escribir con cada uno de estos lenguajes? ¿A qué paradigma responde cada uno? ¿Qué características determinan la pertenencia a cada paradigma?

> Python

Sigue paradigmas imperativo, orientado a objetos y funcional. Sus tipos de programas suelen ser scripts, orientado a la ciencai de datos, IA, automatización y web.
Tiene clases, objetos y herencia, lo que determina su orientación a objetos.
Permite definir funciones como objetos de primera clase. Soporta listas por comprensión, funciones anónimas (`lambda`) y funciones de orden superior (funcional).
Usa estructuras de control y asignaciones (imperativo).

> Ruby

Orientado a objetos puro, aunque también sigue el paradigma funcional. Se utiliza para el desarrollo web, scripts y automatización.
En Ruby todo es un objeto (incluso enteros y nil). Se definen métodos dentro de clases por defecto.
Sin embargo, soporta closures, bloques, lambdas y funciones de orden superior, cualidad del paradigma funcional.

> PHP

Lenguaje imperativo, orientado a objetos (desde v5) y de scripting. Se utiliza para desarrollar aplicaciones del lado servidor.
Usa instrucciones paso a paso, lo que lo caracteriza como imperativo.
A su vez, soporta clases, objetos, herencia e interfaces (OOP).
Además, permite escribir scripts sueltos sin clases (procedural).

### Ejercicio 12: Cite otras características importantes de Python, Ruby, PHP, Gobstone y Processing. Por ejemplo: tipado de datos, cómo se organizan los programas, etc.

> Python

Tipado fuerte y dinámico. Los programas se organizan en módulos y paquetes. Es de simple lectura e indentado.

> Ruby

Es de tipado fuerte y dinámico. Se estructura en clases y módulos. Todo es un objeto.

> PHP

Es de tipado débil y dinámico. Se estructura en archivos y clases. Está pensado para la web, embebido en HTML.

> Gobstones

Es un lenguaje gráfico y educativo. Su organización no es tradicional. Se basa en objetos visuales y comandos secuenciales.

> Processing

Tipado basado en Java, sus programas se organizan en Sketches (programas visuales). Se enfoca en el arte visual y la interacción.

## Lenguaje Javascript

### Ejercicio 13: ¿A qué tipo de paradigma corresponde este lenguajes? ¿A qué tipo de Lenguaje pertenece?

JavaScript es un lenguaje multi-paradigma, que admite:

- Programación imperativa

- Funcional

- Orientada a objetos basada en prototipos

Es un lenguaje interpretado, dinámico, de tipado débil y típicamente del lado del cliente, aunque con Node.js también se usa del lado del servidor.

### Ejercicio 14: Cite otras características importantes de JavaScript. Tipado de datos, excepciones, variables, etc.

Algunas características importantes de JavaScript:

- Tipado de datos: Dinámico, débil (las variables pueden cambiar de tipo).

- Manejo de excepciones: Usa try, catch, finally.

- Variables: Declaración con var, let, const, cada una con diferente alcance y comportamiento.

- Funciones de primera clase: Se pueden asignar a variables, pasar como argumentos.

- Asincronía: Usa callbacks, promises, y async/await.

- Ámbito léxico (scope): Especialmente con let y const.