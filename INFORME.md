Parte 1. Análisis teórico de conceptos
 1.Explicación de los conceptos básicos

Código Fuente: Es el conjunto de instrucciones que escribe el programador utilizando un lenguaje de programación (como Java o C++). Está escrito con palabras legibles para los humanos, pero el procesador no es capaz de entenderlo directamente.

Código Objeto: Es la traducción de ese código fuente al lenguaje de la máquina (ceros y unos) hecha por un programa llamado compilador. Aunque la máquina ya lo entiende, todavía no puede funcionar por sí solo porque es un archivo intermedio al que le faltan piezas.

Código Ejecutable: Es el programa final y terminado. Se consigue utilizando un "enlazador" que une el código objeto con todas las librerías del sistema que necesita para funcionar de forma independiente.

Fases por las que pasa un programa y sus ejemplos:

Análisis Léxico: El compilador lee el código y comprueba que todas las palabras pertenezcan al vocabulario de ese lenguaje.

Análisis Sintáctico: Verifica que las palabras estén en el orden correcto y con la gramática adecuada.

Análisis Semántico: Comprueba que la instrucción escrita tenga un sentido lógico y matemático real.

Generación de código intermedio: Se crea una versión puente del programa que es independiente del procesador en el que se va a ejecutar.

Optimización de código intermedio: El sistema revisa la representación creada para mejorar su eficiencia, como por ejemplo eliminar variables que has creado pero que nunca llegas a usar.

Generación de código final: El código puente se traduce de forma definitiva a los ceros y unos exactos (código máquina) que el procesador concreto de ese ordenador es capaz de procesar.

2.Clasificación de lenguajes de programación

Según su nivel de abstraccion:

El nivel de abstracción es la capacidad que tiene el lenguaje para ocultar los detalles técnicos del hardware al programador.

Nivel Alto: SOn lenguajes que se acercan al lenguaje natural humano y ocultan al programador los problemas deirvados de la plataforma o el procesador.

Nivel Medio: Son lenguajes que originalmente se consiferaban de alto nivel, pero con la evolución tecnológica han quedado en un punto intermedio.

Nivel Bajo: Son lenguajes que dependen completamente de las características de cada máquina y procesador.


Según su parafigma de programación:

Imperativo: Permiten crear algoritmos indicando, mediante instrucciones y expresiones, los pasos exactos que debe de seguir el programa. Es decir, se le dice a la máquina como hacer las cosas.

Declarativos: Especifican únicamente los valores o el resultado que se espera al final, sin detallar que hacer internamente para llegar a él, basándose en relaciones lógicas y matemáticas. Le dicen a la máquina que es lo que quieren obtener.


Fragmento 1 (Sumar números uno por uno): 
Paradigma: Imperativo
Justificación: Los lenguajes imperativos se basan en crear algoritmos a través de un conjunto de instrucciones y expresiones. Cuando describimos que el programa debe recorrer la lista y sumar los números, le estamos dando a la máquina las instrucciones exactas paso a paso para resolver el problema.

Fragmento 2  (Buscar empleados mayores de 30):
Paradigma: Declarativo
Justificación: La característica principal de los lenguajes declarativos es que solo especifican los valores que se esperan obtener al final, sin detallar qué hay que hacer para lograr ese resultado. En este caso pedimos los nombres de los empleados que sean mayores de 30, sin decirle a la base de datos como tiene que buscarlos.

Fragmento 3 (Calcular el factorial matemáticamente):
Paradigma: Declarativo
Justificación: En el temario indica que, en el paradigma declarativo, es necesario indicar las relaciones lógicas y matemáticas para poder llegar al resultado. En este fragmento, el programa no da instrucciones sobre cómo calcular, sino que te dice la regla matemática factorial para que el programa sepa el resultado.

Fragmento 4 (Filtrar productos recorriendo la lista uno por uno):
Paradigma: Imperativo
Justificación: Estamos definiendo el algoritmo indicando el conjunto de instrucciones que debe seguir el lenguaje. Al programa le estamos explicando cómo tiene que trabajar exactamente, en vez de pedirle un resultado final.
