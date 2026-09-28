Parte 1. Análisis teórico de conceptos
 Explicación de los conceptos básicos

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