![](https://static.vecteezy.com/system/resources/thumbnails/019/638/944/small/blue-globe-with-technology-elements-png.png)
Borrar y modificar a su gusto este README, pero antes utilizar estas condiciones de entrega del trabajo.

# Utilizar los dos directorios

- code  - ahi depositar sus programas los ***archivos extensión *.s****  (Source File) algunos autores en x86 de ponen .asm y en otras plataformas ARM compatibles la extension *.elf
- Todo programa lleva su comentario en la parte de arriba, objetivo y nombre del programador minimo.
- images  - de haber algo de pantallas ahi se presentaran, su busca documentarlas en MARKDOWN el código es:

``` ![](images/---archivo.jpg---) recordar que no lleva espacios```



- Programa en MarkDown es inicia con tres tildes * (`) sin espacio, seguido de el lenguaje de programacion, al final del codigo se poner otra vez los mismos tilder..

No se usan espacios en nombres de archivos, usar los nombres estilo camelCase (primera palabra minusculas, mayuscula solo la 1ra letra de cada palabra subsecuente):  ejemplo: sensorHumo, etc.

Suerte.

Att. ![](https://img.icons8.com/color/2x/docker.png)

------

<pre>

	<p align=center>

Tecnológico Nacional de México
Instituto Tecnológico de Tijuana

Departamento de Sistemas y Computación
Ingeniería en Sistemas Computacionales

Semestre:
Febrero - Junio 2022

Materia:
Lenguajes de interfaz

Docente:
M.C. Rene Solis Reyes 

Unidad:
1

Título del trabajo:
Exposicion " Branching "

Estudiante:
Jimenez Beltran Jesus Rosalio 21210958
Lavenant Duran Pablo Roman 21210385
Lopez Machado Gonzalo 21210390
Palacios Cordova Gonzalo 21210407

	</p>

</pre>

<pre>

	<p align=left>

**Que es BRANCHING**:
	
El término "branching" en el contexto de ARM (Advanced RISC Machine) de 32 bits se refiere a una operación fundamental que implica cambiar el flujo de ejecución de un programa a una dirección de memoria diferente, generalmente condicionada por alguna evaluación de una condición específica. Este mecanismo es esencial para el control de flujo y la ejecución de programas de manera efectiva. A continuación, proporcionaremos información detallada sobre cómo funciona, su importancia y ejemplos relevantes de "branching" en ARM de 32 bits.

COMO FUNCIONA:

El "branching" en ARM de 32 bits se logra mediante instrucciones específicas diseñadas para cambiar la secuencia de ejecución del programa. Estas instrucciones se basan en condiciones y se llaman "branch instructions". Cuando se encuentra una instrucción de salto condicional, se evalúa una condición (por ejemplo, igualdad, menor que, etc.) utilizando los registros del procesador. Dependiendo del resultado de esta evaluación, se decide si se ejecutará el salto a la nueva dirección de memoria o si se continuará con la ejecución normal.

					CUALES SON LOS OBJETIVOS DE BRANCHING
		
*Control de Flujo: Nos Permite la ejecución de diferentes bloques de código en función de ciertas condiciones, como valores de registros, banderas o resultados de operaciones.
		
*Toma de Decisiones: Nos Facilita la implementación de estructuras de control de flujo, como if-else y switch-case, para permitir la toma de decisiones basadas en condiciones específicas.
		
*Ciclos y Bucles: Facilita la implementación de bucles y ciclos, permitiendo que el programa repita un conjunto de instrucciones mientras se cumplan ciertas condiciones.
		
*Optimización del Código: Mejorar la eficiencia y la optimización del código al evitar ejecuciones innecesarias o repetitivas de instrucciones.
		
*Implementación de Subrutinas y Funciones: Habilitar la invocación y el retorno de funciones, permitiendo la modularidad del código y el reuso de bloques de código.
		
*Manejo de Excepciones y Errores: Permitir el manejo de excepciones, interrupciones y errores, redirigiendo la ejecución a rutinas de manejo específicas.
		
*Optimización de Rendimiento: Optimizar la ejecución del programa al saltar directamente a secciones relevantes de código, evitando la ejecución lineal y mejorando el rendimiento.

		             En ARM32, las instrucciones de branching suelen incluir:

B (Branch): Esta instrucción se utiliza para la ramificación incondicional. Simplemente cambia el PC a la dirección especificada, permitiendo al programa saltar a una parte diferente del código incondicionalmente.

Bcc (Branch si la condición es verdadera): Las instrucciones de branch condicional, como BNE (branch si no es igual) o BEQ (branch si es igual), permiten al programa branch en función del resultado de una comparación o una condición.

BL (branch con enlace): Esta instrucción se utiliza para llamadas a subrutinas. Se bifurca a una dirección especificada y también guarda la dirección de retorno (dirección de la siguiente instrucción) en el registro de enlace (LR).

BX (branch e intercambio): Esta instrucción se utiliza para cambiar el estado del conjunto de instrucciones. Por ejemplo, puede cambiar entre los modos ARM y Thumb en ARM32.

		He aquí un ejemplo sencillo de cómo podría utilizarse una instrucción de bifurcación en el lenguaje ensamblador ARM:

		    CMP R0, #0       ; Compare the value in R0 with 0
    BEQ equal        ; Branch to "equal" if the result of the comparison is equal
    BNE not_equal    ; Branch to "not_equal" if the result is not equal

equal:
    ; Code to execute when R0 is equal to 0
    ...

not_equal:
    ; Code to execute when R0 is not equal to 0
    ...

En este ejemplo, las instrucciones BEQ y BNE son instrucciones de bifurcación condicional, y determinan si el programa se bifurca a la etiqueta "igual" o "no_igual" en función del resultado de la comparación.

Recuerde que la sintaxis específica y las instrucciones disponibles pueden variar dependiendo de la versión de la arquitectura ARM y del lenguaje ensamblador utilizado. Además, ARM ha pasado a una arquitectura de 64 bits llamada ARMv8-A, pero ARM32 sigue siendo relevante para muchas aplicaciones.

	</p>

</pre>
