[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/EID3BRwM)
# Unidad 1
## Consulta 
# ¿Que es CPU?
Es un componente de hardware y la unidad computacional central de un servidor. Los servidores y otros dispositivos inteligentes convierten los datos en señales digitales y realizan operaciones matemáticas en ellos. La CPU es el componente principal que procesa las señales y hace posible la computación. Actúa como el cerebro de cualquier dispositivo de computación. Obtiene instrucciones de la memoria, realiza las tareas necesarias y envía la salida a la memoria. Maneja todo tipo de tareas de computación necesarias para que el sistema operativo y las aplicaciones se ejecuten.
# ¿Que es ALU?
es un componente fundamental de la CPU (Unidad Central de Procesamiento) en los ordenadores. Su función principal es realizar operaciones aritméticas (como suma, resta, multiplicación y división) y operaciones lógicas (como AND, OR, NOT, y XOR).
# ¿ Que son los registros?,¿Cual es su proposito general?, específicos: Program Counter, Stack Pointer, etc.
Los registros de propósito general son utilizados para almacenar datos temporales y realizar operaciones aritméticas y lógicas. Pueden ser utilizados por el programador o el compilador para cualquier propósito que requiera almacenamiento temporal. Algunos ejemplos comunes incluyen:

AX, BX, CX, DX (en arquitectura x86): Son registros de propósito general en los procesadores x86 que se pueden dividir en registros más pequeños (por ejemplo, AH y AL para la parte alta y baja de AX).
R0, R1, R2, etc. (en arquitectura ARM): Son registros de propósito general utilizados en los procesadores ARM.
-Registros Específicos
Los registros específicos tienen funciones especiales y son utilizados por la CPU para gestionar el flujo de instrucciones y datos. Algunos ejemplos clave son:

Program Counter (PC) o Instruction Pointer (IP): Almacena la dirección de la próxima instrucción a ser ejecutada. Es esencial para el control del flujo del programa, ya que incrementa su valor después de cada instrucción para apuntar a la siguiente.

Stack Pointer (SP): Apunta a la parte superior de la pila (stack), una estructura de datos utilizada para almacenar información temporal como direcciones de retorno, variables locales y registros salvados. El Stack Pointer se incrementa o decrementa al añadir o eliminar datos de la pila.

Base Pointer (BP) o Frame Pointer (FP): Utilizado para mantener la referencia a la base del marco de pila actual, facilitando el acceso a los parámetros de la función y las variables locales.

Index Registers (SI, DI en x86): Utilizados para operaciones de indexación, como el manejo de cadenas y matrices. En la arquitectura x86, SI y DI se usan para operaciones de entrada/salida y manipulación de cadenas.

Flags Register (FR) o Status Register (SR): Contiene varios indicadores de estado (flags) que reflejan el resultado de las operaciones aritméticas y lógicas, como el flag de acarreo (carry flag), flag de cero (zero flag), y flag de signo (sign flag).
# ¿Que es un Unidad de control?
Es uno de los componentes fundamentales de la CPU. Su principal función es dirigir y coordinar todas las operaciones del procesador. Lo hace gestionando el flujo de datos entre la ALU (Unidad Aritmética y Lógica), los registros, la memoria y otros componentes del sistema.
# ¿Que son los Buses de datos y de dirección?}
-Buses de Datos
El bus de datos es una serie de líneas de comunicación que transportan los datos entre la CPU, la memoria y los dispositivos periféricos. Cada línea del bus de datos puede transportar un bit de información, y el número de líneas determina la cantidad de datos que se pueden transferir simultáneamente. Por ejemplo, un bus de datos de 32 bits puede transportar 32 bits de datos a la vez.
-Buses de Dirección
El bus de dirección es una serie de líneas que transportan las direcciones de memoria entre la CPU y la memoria o los dispositivos periféricos. Cada línea del bus de dirección transporta un bit de la dirección de memoria, y el número de líneas determina el rango de direcciones que se pueden acceder.
# ¿ Que es la memoria?
La memoria se refiere a los componentes que almacenan datos e instrucciones que la CPU necesita para ejecutar programas. La memoria es esencial para el funcionamiento de cualquier sistema informático, ya que proporciona un espacio de almacenamiento temporal y permanente para los datos y las instrucciones que utiliza la CPU.
# ¿Que es Opcode?
Es una parte fundamental de una instrucción de máquina que especifica la operación que debe realizarse. Cada instrucción de máquina se compone de dos partes principales: el Opcode y los Operandos.
## Descripcion de los componentes del programa:
Tiene una memoria ROM que se encarga de recibir las intruciones que da el pc y craga el programa, tambien tiene un clock que es la frecuencia a la que trabaja el programa , tiene la cpu que actua como el cerebro del programa, tiene la memoria que se encarga de guardar y enviar a la cpu las  intrucciones que le da el pc y por ultimo tienes unos botones que son los que presiona el usuario del pc. 

## fetch-decode-execute
# -Fetch (Captura):
La CPU obtiene (captura) una instrucción de la memoria principal (RAM).
El registro de contador de programa (Program Counter o PC) contiene la dirección de la próxima instrucción a ser ejecutada.
La instrucción es cargada en el registro de instrucciones (Instruction Register o IR).

# -Decode (Decodificación):
La CPU interpreta (decodifica) la instrucción almacenada en el registro de instrucciones.
El decodificador de instrucciones traduce la instrucción a una serie de señales de control que preparan los componentes internos de la CPU para llevar a cabo la operación necesaria.

# -Execute (Ejecución):
La CPU lleva a cabo (ejecuta) la instrucción. Esto puede implicar una variedad de operaciones, como realizar cálculos aritméticos o lógicos, mover datos entre registros, leer o escribir datos en la memoria, o interactuar con dispositivos de entrada/salida.
Los resultados de la ejecución pueden ser almacenados en registros internos o en la memoria principal.

##  Tipos de instruciones:
# Instrucion tipo A:
Las instrucciones tipo A se utilizan para realizar operaciones aritméticas y lógicas. Estas instrucciones generalmente involucran dos operandos y producen un resultado que se almacena en un registro destino.
-Caracteristicas:
*Tres registros: Utilizan tres registros: dos operandos fuente y un registro destino.
*Operaciones: Pueden incluir sumas, restas, multiplicaciones, divisiones, y operaciones lógicas como AND, OR, XOR, etc.
*Formato: Suele tener un formato específico donde se indica la operación a realizar y los registros involucrados.
Ejemplo:
Una instrucción Tipo A que suma el contenido de dos registros y almacena el resultado en un tercer registro
# Instrucion tipo C:
se utilizan para controlar el flujo de ejecución del programa. Estas instrucciones incluyen saltos condicionales e incondicionales, llamadas a subrutinas, y retornos de subrutinas.
-Caracteristicas:
*Saltos Condicionales: Permiten cambiar la secuencia de ejecución del programa basándose en una condición específica.
*Saltos Incondicionales: Cambian la secuencia de ejecución sin evaluar ninguna condición.
Dirección de Salto: Generalmente incluyen una dirección o un desplazamiento al que debe saltar la ejecución del programa.
Ejemplo:
Un ejemplo para este tipo de instruccion seria un salto condicional 
JMP_IF_ZERO R1, 100
Aquí, JMP_IF_ZERO es la operación de salto condicional que se ejecuta si el contenido de R1 es cero, y 100 es la dirección a la que el programa saltará si la condición se cumple.
##  Explicacion de codigo punto 9:
- @i:En esta linea de codigo se carga la ubicación de la variable i en el registro A.
- M=1: En esta linea de codigo se Establece el valor 1 en la ubicación asociada a i.
- @sum: En esta linea de codigo se Carga la ubicación de la variable sum en el registro A.
- M=0: En esta linea de codigo se Establece el valor 0 en la ubicación asociada a sum.
- @100: En esta linea de codigo se Carga la constante 100 en el registro A.
- D=A: En esta linea de codigo se Copia la constante 100 del registro A al registro D.
- @i: En esta linea de codigo se Carga la ubicación de la variable i en el registro A.
- D=D-M: En esta linea de codigo se Resta el valor de i al contenido de D (100), obteniendo 100 - i.
- @END: En esta linea de codigo se Carga la ubicación de la etiqueta END en el registro A.
- D;JLE: En esta linea de codigo se Salta a END si D es menor o igual a cero, lo que sucede cuando i es igual a 100.
- @i: En esta linea de codigo se Carga la ubicación de la variable i en el registro A.
- D=M: En esta linea de codigo se Copia el valor de i al registro D.
- @sum: En esta linea de codigo se Carga la ubicación de la variable sum en el registro A.
- M=M+D: En esta linea de codigo se Añade el valor del registro D a sum.
- @i: En esta linea de codigo se Carga la ubicación de la variable i en el registro A.
- M=M+1: En esta linea de codigo se Incrementa el valor de i en 1.
- @4: En esta linea de codigo se Carga la dirección 4 en el registro A.
- 0;JMP: En esta linea de codigo se Salta a la instrucción en la dirección 4, que es @100.
- (END):En esta linea de codigo Define la etiqueta END.
- @END: En esta linea de codigo Carga la ubicación de la etiqueta END.
-   0;JMP:En esta linea de codigo Salta a la dirección de END, creando un bucle infinito.

En general lo que hace programa es que suma los números del 1 al 99 y se buguea hasta llegar a este numero.

## ACTIVIDAD 2:
# Punto 1:

# Mapa de Memoria en Microprocesadores:
- Definición: Es una representación de todas las direcciones que la CPU puede generar para acceder a diferentes tipos de memoria (RAM, ROM) y periféricos.
Bus de Direcciones: Es un conjunto de líneas de comunicación que la CPU utiliza para enviar direcciones de memoria.
-Aleación de Von Neumann vs Harvard: La arquitectura de Von Neumann usa una memoria unificada para datos e instrucciones, mientras que Harvard las separa en diferentes memorias y buses.
# Set de Instrucciones:
- Definición: Conjunto de comandos que el procesador puede ejecutar, como mover datos, realizar cálculos, o controlar el flujo del programa.
- Tipos de Instrucciones:
* Transferencia de Datos (MOV): Mueve datos entre registros o entre registros y memoria.
* Aritméticas y Lógicas (ADD): Realizan operaciones matemáticas.
* Control de Flujo (JMP): Alteran el flujo de ejecución del programa.
*Manipulación de Bits (BSF): Operan a nivel de bits.
# Características de las Instrucciones:
- Sintaxis: El formato y la estructura de las instrucciones.
- Opcode: Código binario que indica la operación a realizar.
- Tamaño y Ciclos de Reloj: Varía según la instrucción, afectando la eficiencia del procesador.
# Arquitecturas CISC y RISC:
- CISC: Instrucciones complejas que realizan múltiples tareas en una sola instrucción. Ejemplo: x86.
- RISC: Instrucciones simples y rápidas, optimizadas para ejecutarse en un solo ciclo de reloj. Ejemplo: ARM.

# Punto 2:

Un procesador interesante que sigue una arquitectura diferente a la de Von Neumann es el Intel 8051, que utiliza una arquitectura Harvard. A diferencia de la arquitectura Von Neumann, donde el mismo bus y la misma memoria se usan tanto para instrucciones como para datos, en la arquitectura Harvard, como la del 8051, existen buses y memorias separadas para instrucciones y datos. Esto permite un acceso simultáneo a las instrucciones y datos, lo que puede aumentar la eficiencia del procesamiento.

El mapa de memoria del Intel 8051 es distinto y más complejo debido a esta separación. El procesador tiene una memoria de programa y una memoria de datos separadas. La memoria de programa es de solo lectura (ROM) y típicamente tiene un tamaño de 4 KB, direccionada desde 0000h hasta 0FFFh. Por otro lado, la memoria de datos (RAM) es de lectura/escritura, con un tamaño típico de 128 bytes, direccionada desde 00h hasta 7Fh. Además, el 8051 cuenta con memoria de datos externa que puede expandirse hasta 64 KB, direccionada desde 0000h hasta FFFFh.

Esta separación permite que el procesador 8051 acceda a una instrucción en la memoria de programa al mismo tiempo que accede a datos en la memoria de datos, eliminando el cuello de botella característico de la arquitectura Von Neumann, donde las instrucciones y los datos compiten por el mismo bus y memoria.

Este diseño es ideal para aplicaciones en microcontroladores donde la eficiencia y la velocidad son cruciales, como en sistemas embebidos y dispositivos electrónicos que requieren control preciso y rápido​.

# Punto 3:

Para realizar la comparación de instrucciones entre diferentes microprocesadores, elegí tres microprocesadores ampliamente conocidos: el Intel 8086, el ARM Cortex-M4 y el MIPS32. Las instrucciones seleccionadas para la comparación son:

MOV (Transferencia de datos)
ADD (Aritmética)
JMP (Control de flujo)

# 1. Instrucción MOV: Transferencia de Datos

-  Intel 8086:

* Longitud: 2 a 4 bytes.
* Ciclos de Reloj: 2 ciclos para registros, 8 ciclos para memoria.
* Complejidad: Simple, permite la transferencia de datos entre registros, memoria y registros, o registros y constantes.

- ARM Cortex-M4:

* Longitud: 2 bytes (Thumb-2) o 4 bytes (ARM).
* Ciclos de Reloj: 1 ciclo.
* Complejidad: Relativamente simple, optimizada para eficiencia energética, permite la transferencia entre registros y registros, o registros y memoria.

- MIPS32:

* Longitud: 4 bytes.
* Ciclos de Reloj: 1 ciclo.
* Complejidad: Simple, instrucción de carga/almacenamiento, permite la transferencia entre registros y memoria.
## 2. Instrucción ADD: Aritmética

- Intel 8086:

* Longitud: 2 a 4 bytes.
* Ciclos de Reloj: 3 ciclos para registros, 15 ciclos para memoria.
* Complejidad: Moderada, permite sumar registros, valores inmediatos o valores en memoria.

- ARM Cortex-M4:

* Longitud: 2 bytes (Thumb-2) o 4 bytes (ARM).
* Ciclos de Reloj: 1 ciclo.
* Complejidad: Simple, optimizada para realizar operaciones aritméticas rápidamente, principalmente entre registros.

- MIPS32:

* Longitud: 4 bytes.
* Ciclos de Reloj: 1 ciclo.
* Complejidad: Simple, solo realiza operaciones entre registros, el uso de memoria requiere instrucciones adicionales.
#  3. Instrucción JMP: Control de Flujo

- Intel 8086:

* Longitud: 3 bytes.
* Ciclos de Reloj: 15 ciclos.
* Complejidad: Moderada, permite saltos condicionales y directos dentro del mismo segmento.

- ARM Cortex-M4:

* Longitud: 2 bytes (Thumb-2) o 4 bytes (ARM).
* Ciclos de Reloj: 1 ciclo.
* Complejidad: Simple, permite saltos condicionales y directos con optimización para entornos embebidos.

- MIPS32:

* Longitud: 4 bytes.
* Ciclos de Reloj: 1 ciclo.
* Complejidad: Simple, principalmente soporta saltos incondicionales y condicionales, con un diseño simplificado.

# Conclusiones
La comparación de estas instrucciones entre los tres microprocesadores revela diferencias importantes en términos de longitud, ciclos de reloj, y complejidad:

- Longitud: El MIPS32 y el ARM en modo ARM tienden a tener instrucciones de longitud fija (4 bytes), lo que simplifica el diseño del pipeline, mientras que el Intel 8086 tiene longitudes variables, lo que complica el proceso de decodificación.
- Ciclos de Reloj: El ARM Cortex-M4 es altamente optimizado, ejecutando la mayoría de las instrucciones en un solo ciclo, lo que lo hace extremadamente eficiente en términos de rendimiento por vatio, especialmente en aplicaciones embebidas. El Intel 8086, siendo un diseño más antiguo, requiere más ciclos de reloj para ejecutar operaciones similares.
- Complejidad: Las arquitecturas CISC como la del Intel 8086 tienen instrucciones más complejas que pueden realizar múltiples operaciones en una sola instrucción, pero a costa de una mayor latencia y complejidad de diseño. Las arquitecturas RISC como el ARM Cortex-M4 y el MIPS32 mantienen las instrucciones simples y de ejecución rápida, facilitando la implementación de técnicas avanzadas como pipelining.

Entendí que el mapa de memoria de un microprocesador es como un plano que muestra cómo se organizan las direcciones de memoria y los periféricos que la CPU puede acceder, y que esto está relacionado con el bus de direcciones que envía esas direcciones. Por ejemplo, en el procesador 8086, se utiliza un bus multiplexado para optimizar los pines, lo que permite acceder a 1 MB de memoria usando 20 bits. Además, aprendí que hay dos arquitecturas principales: Von Neumann, donde datos e instrucciones comparten la misma memoria, y Harvard, donde están separados, lo que mejora la eficiencia. En cuanto al set de instrucciones, es el conjunto de comandos que el procesador puede ejecutar, y estas instrucciones pueden ser de diferentes tipos como mover datos, realizar cálculos o controlar el flujo del programa. Finalmente, hay dos tipos de arquitecturas según la complejidad de estas instrucciones: CISC, con instrucciones complejas que hacen varias tareas a la vez, y RISC, con instrucciones simples y rápidas, lo que hace que el procesador sea más eficiente.


