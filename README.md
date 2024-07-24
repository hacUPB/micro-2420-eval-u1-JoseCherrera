[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/EID3BRwM)
# Unidad 1
## Consulta 
## ¿Que es CPU?
Es un componente de hardware y la unidad computacional central de un servidor. Los servidores y otros dispositivos inteligentes convierten los datos en señales digitales y realizan operaciones matemáticas en ellos. La CPU es el componente principal que procesa las señales y hace posible la computación. Actúa como el cerebro de cualquier dispositivo de computación. Obtiene instrucciones de la memoria, realiza las tareas necesarias y envía la salida a la memoria. Maneja todo tipo de tareas de computación necesarias para que el sistema operativo y las aplicaciones se ejecuten.
## ¿Que es ALU?
es un componente fundamental de la CPU (Unidad Central de Procesamiento) en los ordenadores. Su función principal es realizar operaciones aritméticas (como suma, resta, multiplicación y división) y operaciones lógicas (como AND, OR, NOT, y XOR).
## ¿ Que son los registros?,¿Cual es su proposito general?, específicos: Program Counter, Stack Pointer, etc.
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
## ¿Que es un Unidad de control?
Es uno de los componentes fundamentales de la CPU. Su principal función es dirigir y coordinar todas las operaciones del procesador. Lo hace gestionando el flujo de datos entre la ALU (Unidad Aritmética y Lógica), los registros, la memoria y otros componentes del sistema.
## ¿Que son los Buses de datos y de dirección?}
-Buses de Datos
El bus de datos es una serie de líneas de comunicación que transportan los datos entre la CPU, la memoria y los dispositivos periféricos. Cada línea del bus de datos puede transportar un bit de información, y el número de líneas determina la cantidad de datos que se pueden transferir simultáneamente. Por ejemplo, un bus de datos de 32 bits puede transportar 32 bits de datos a la vez.
-Buses de Dirección
El bus de dirección es una serie de líneas que transportan las direcciones de memoria entre la CPU y la memoria o los dispositivos periféricos. Cada línea del bus de dirección transporta un bit de la dirección de memoria, y el número de líneas determina el rango de direcciones que se pueden acceder.
## ¿ Que es la memoria?
La memoria se refiere a los componentes que almacenan datos e instrucciones que la CPU necesita para ejecutar programas. La memoria es esencial para el funcionamiento de cualquier sistema informático, ya que proporciona un espacio de almacenamiento temporal y permanente para los datos y las instrucciones que utiliza la CPU.
## ¿Que es Opcode?
Es una parte fundamental de una instrucción de máquina que especifica la operación que debe realizarse. Cada instrucción de máquina se compone de dos partes principales: el Opcode y los Operandos.
## Descripcion de los componentes del programa:
Tiene una memoria ROM que se encarga de recibir las intruciones que da el pc y craga el programa, tambien tiene un clock que es la frecuencia a la que trabaja el programa , tiene la cpu que actua como el cerebro del programa, tiene la memoria que se encarga de guardar y enviar a la cpu las  intrucciones que le da el pc y por ultimo tienes unos botones que son los que presiona el usuario del pc. 