### El computador digital moderno

#### ¿ Que es un computador ? :computer: :computer:

*Es una máquina electrónica capaz de realizar un tratamiento automático de la información y de resolver con gran rapidez problemas matemáticos y lógicos mediante programas informáticos'. Estas formas son las usadas mayoritariamente en el español de América, por influjo del inglés computer. Según las zonas, existen distintas preferencias: en la mayoría de los países de América se prefiere el femenino computadora, mientras que el masculino computador es de uso mayoritario en Chile y Colombia. En España se usa preferentemente el término ordenador.*


Tomado de: [Real Academia Española](https://www.rae.es/dpd/computador)


### Arquitecturas de un computador :construction_worker:
*<mark>Actualmente en el segmento de los procesadores nos encontramos dos arquitecturas o tipos de diseño. Por un lado tenemos la arquitectura CISC, usada por Intel y AMD para sus procesadores, y por otro lado tenemos la arquitectura RISC, usada por Qualcomm, Samsung, Apple, etc., para los SoC de smartphone, tabletas o portátiles.<mark/>*

#### Arquitectura CISC :computer:

Es una gran colección de instrucciones que van desde simples a muy complejas y especializadas a nivel de lenguaje de ensamblador. CISC es un sistema de instrucciones desarrollado por Intel que requieren de mucho tiempo para ser ejecutadas completamente.
```
CISC: Complex Instruction Set Computer
```

Lo que sucede en CISC es que se reduce la cantidad de instrucciones de un software y se ignora el número de ciclos por instrucción. Se especializa en crear instrucciones complejas en el hardware, ya que el hardware siempre será mucho más rápido que el software.

Este tipo de diseño es la base de los procesadores de Intel y de AMD, sin importar la gama o la estructura interna. Cualquiera de los procesadores producidos por ambas compañías se basan en la arquitectura CISC.

#### Arquitectura RISC :iphone:

Es una arquitectura de procesadores basada en una colección de instrucciones simples y altamente personalizadas. RISC se construye para minimizar el tiempo de ejecución de una instrucción, optimizando y limitando el número de instrucciones.
```
RISC: Reduced Instruction Set Computer Processor
```
La arquitectura RISC tiene la capacidad de por cada ciclo de instrucción se da solo un ciclo de reloj. Cada ciclo debe contener estos tres parámetros: buscar, decodificar y ejecutar. RISC también tiene la propiedad de ejecutar varias instrucciones complejas cuando se combinan con otras más simples. Este diseño de procesadores requiere menor cantidad de transistores, reduciendo costes y tiempos de fabricación.

Todos los procesadores basados en los diseños de ARM, como por ejemplo los Qualcomm Snapdragon y los Samsung Exynos se basan en la arquitectura RISC. Incluso los procesadores integrados en las Raspberry Pi son de arquitectura RISC, al basarse en procesadores Broadcom que hace uso de licencias ARM.

### ¿ Que es el Hardware ? :pager:

*<mark>Hardware es una palabra inglesa que hace referencia a las partes físicas tangibles de un sistema informático, es decir, todo aquello que podemos tocar con las manos. Dentro del hardware encontramos una gran variedad de componentes eléctricos, electrónicos, electromecánicos y mecánicos. El hardware es el chasis del ordenador, los cables, los ventiladores, los periféricos y todos los componentes que se pueden encontrar en un dispositivo electrónico. La Real Academia Española lo define como «Conjunto de los componentes que integran la parte material de una computadora».<mark/>*

*En el Hardware podemos encontrar algunos elementos como los siguientes.*

| Nombre del componente | Funcion | Partes del componente |
|-----------------------|---------|-----------------------|
| ALU                   | La ALU realiza todos los cálculos y comparaciones. Realiza seis funciones: suma, resta, multiplicación, división, operaciones booleanas|el circuito aritmético, la memoria, el conjunto de instrucciones y la unidad de control|
| Unidad de Control     |Es una parte fundamental en la arquitectura de una CPU (Unidad Central de Procesamiento). El papel principal de la Unidad de Control (CU, por sus siglas en inglés) es la de supervisar el funcionamiento del procesador. |Contador de programa, Registros de instrucciones, Decodificador, Reloj, Secuenciador |
| Registros             | un registro es una memoria de alta velocidad y poca capacidad, integrada en el microprocesador, que permite guardar transitoriamente y acceder a valores muy usados, generalmente en operaciones matemáticas.|Integrado en el microprocesador|
| Buses                 |Se utilizan para transferir datos entre el microprocesador y la memoria RAM. Son los caminos por los cuales los datos viajan, por ejemplo del microprocesador al disco rígido, o de la memoria al disco|CPU y resto de unidades |


#### ¿ Que es la GPU ? :floppy_disk:

<mark>La unidad de procesamiento de gráficos (GPU) tiene muchos núcleos pequeños y especializados. Estos núcleos ofrecen un enorme desempeño al trabajar juntos y dividir las tareas de procesamiento entre muchos núcleos simultáneamente (o en paralelo). La GPU se destaca en tareas altamente paralelas, como renderizar imágenes durante un juego, manipular datos de video durante la creación de contenido y calcular resultados en cargas de trabajo de IA intensivas.<mark/>

##### ¿ En que se diferencia la GPU de la CPU ?

Las CPUs y GPUs tienen mucho en común: ambas son motores informáticos críticos, son microprocesadores de silicio y manejan datos. Pero las CPU y las GPU tienen diferentes arquitecturas y se construyen con diferentes propósitos.

La CPU es adecuada para varias tareas, en especial aquellas para las que la latencia o el desempeño por núcleo es importante. Como un potente motor de ejecución, la CPU centra su menor cantidad de núcleos en tareas particulares y en hacer las cosas rápidamente. Por tanto, resulta muy útil para tareas como la informática en serie, en la que solo se ejecuta una tarea a la vez en un solo procesador, o la ejecución de bases de datos.

Las GPUs comenzaron como circuitos integrados de aplicación específica (ASICs) hechos con fines especializados, como acelerar los gráficos y las tareas de renderizado 3D, por ejemplo el gaming. Con el paso del tiempo, estos motores con funciones fijas se han vuelto más programables y más flexibles. Aunque su función principal sigue girando en torno a los gráficos y los elementos visuales cada vez más realistas del gaming, las GPUs se han convertido en procesadores paralelos de uso más general capaces de ejecutar muchas tareas de forma simultánea para manejar una variedad cada vez mayor de aplicaciones, entre ellas la IA.

**Hoy en día, ya no se trata de elegir entre una CPU y una GPU. Ahora más que nunca, necesita ambas para satisfacer sus diversas exigencias informáticas. Los mejores resultados se obtienen cuando se utiliza la herramienta adecuada para el trabajo.**


## Ahora hablemos un poco de la memoria

*<mark>La memoria de la computadora, también conocida como memoria principal o memoria principal, proporciona almacenamiento temporal para tareas computacionales, lo que la hace fundamental para el funcionamiento de una computadora. Los datos se almacenan en la memoria para que se puedan enviar a la unidad de procesamiento central (CPU) para los cálculos y una aplicación pueda recuperar datos cuando sea necesario.<mark/>*

**Algunas partes de la memoria son :**

1. **-Registros :** Los registros están en la cumbre de la jerarquía de memoria, y son la manera más rápida que tiene el sistema de almacenar datos. Los registros se miden generalmente por el número de bits que almacenan; por ejemplo, un "registro de 8 bits" o un "registro de 32 bits".
2. **-Caché :** La memoria caché es una memoria volátil de alta velocidad que proporciona acceso de datos de alta velocidad a la CPU y mejora la velocidad y el rendimiento de la computadora.
3. **-Principal :** Comprende memoria de acceso aleatorio (RAM) y memoria de solo lectura (ROM), la RAM es volátil, lo que significa que pierde datos cuando se apaga la alimentación.
La memoria de solo lectura (ROM) no es volátil y conserva los datos, incluso en ausencia de energía.
La memoria primaria es directamente accesible por la CPU, lo que facilita el acceso y la manipulación rápidos de datos.
4. **-Secundaria (Disco duro y unidades externas de almacenamiento) :** También conocido como almacenamiento externo o auxiliar
Incluye medios de almacenamiento no volátiles como discos duros (HDD), unidades de estado sólido (SSD) y discos ópticos.
La CPU no puede acceder directamente; los datos deben transferirse a la memoria principal para su procesamiento.
Se utiliza para el almacenamiento y la copia de seguridad de datos a largo plazo, con capacidades de almacenamiento más altas a un costo más bajo en comparación con la memoria primaria.

### Es hora de los dispositivos de entrada y salida :computer:

#### ¿Qué son los dispositivos de entrada y salida?

En informática, se conoce como dispositivos de entrada/salida (o periféricos bidireccionales) a aquellos aparatos electrónicos que permiten tanto introducir como extraer información de un sistema. Por ejemplo: un monitor táctil o una impresora multifunción.


Los dispositivos de entrada/salida pueden llevar a cabo tanto las tareas de entrada como de salida de información, razón por la cual se les denomina “mixtos” o Input/Output (I/O) (el inglés para entrada/salida). Algunos dispositivos lo hacen de forma simultánea y otros lo hacen por turnos.

##### Algunos ejemplos de dispositivos de E/S son:

1. Impresoras multifuncionales.
2. Pantallas táctiles.
3. Dispositivos de redes.
4. Cascos de realidad virtual.
5. Dispositivos de almacenamiento.

Fuente: https://concepto.de/dispositivos-de-entrada-y-salida-mixtos/#ixzz8zR9bkbiI

[Click para ver la Fuente](https://concepto.de/dispositivos-de-entrada-y-salida-mixtos/#ixzz8zR95JdRC)

### ¿ Qué es el Software ? :pager:

*<mark>El software es el conjunto de programas, datos, instrucciones y procedimientos que permiten realizar tareas específicas en un sistema informático. A diferencia del hardware (los componentes físicos del dispositivo), el software es intangible y esencial para el funcionamiento de cualquier computadora o dispositivo digital.
Comúnmente se utiliza este término para referirse de una forma muy genérica a los programas de un dispositivo informático, sin embargo, el software abarca todo aquello que es intangible en un sistema computacional. Existen varios tipos de software, entre ellos:<mark/>*

- Software de sistema : Es el conjunto de programas y herramientas que permiten que el hardware y otras aplicaciones funcionen de manera eficiente. Incluye el sistema operativo, controladores de dispositivos, utilidades de optimización y servidores, entre otros componentes.

- Software de aplicacion : El software de aplicación está diseñado para realizar tareas específicas que ayudan al usuario en su vida diaria o en su trabajo. Ejemplos incluyen procesadores de texto, hojas de cálculo, aplicaciones de diseño, videojuegos y programas de comunicación. Los videojuegos, los programas de diseño asistido (como CAD), el software utilizado en las telecomunicaciones, las aplicaciones de productividad empresarial o educativa son algunos ejemplos de este tipo de programas.

- Software de desarrollo : Incluye todas las herramientas necesarias para desarrollar y depurar software, como compiladores, intérpretes, editores de texto y entornos de desarrollo integrado (IDE). Estas herramientas están dirigidas a programadores y desarrolladores, no al usuario final


## Funcionamiento del computador 💻

### Procesos al encender una computadora:

1. POST (Power On Self Test): Cuando se enciende la computadora, se realiza una prueba automática de hardware llamada POST. Esto verifica que los componentes esenciales (memoria RAM, procesador, tarjeta gráfica, entre otros) funcionen correctamente.
   
2. Carga del BIOS/UEFI: El BIOS (Basic Input Output System) o UEFI (Unified Extensible Firmware Interface) se carga en la memoria. Estos sistemas permiten que el hardware se comunique con el sistema operativo y gestionan aspectos del encendido de la computadora.
   
3. Inicialización de los controladores y hardware: Se cargan los controladores básicos de los dispositivos (disco duro, teclado, etc.) para permitir que se pueda interactuar con el sistema.
   
4. Arranque del sistema operativo: Se carga el sistema operativo desde el disco duro (o unidad de almacenamiento correspondiente), lo que permite iniciar el entorno gráfico y los programas.
   
### Proceso de ingresar un dato hasta que aparece en pantalla:

- Ingreso de datos: Cuando presionas una tecla, el teclado envía señales eléctricas al controlador del teclado que las interpreta y las convierte en códigos.
  
- Codificación: El código de la tecla presionada (por ejemplo, el código ASCII o Unicode) es enviado al procesador, que lo interpreta.

- Proceso en el procesador: El procesador ejecuta las instrucciones necesarias para manejar los datos, realizando cálculos o enviando comandos a otros componentes si es necesario.
  
- Memoria y almacenamiento temporal: Los datos se almacenan temporalmente en la RAM mientras el sistema operativo y los programas trabajan con ellos.

- Generación de imagen: El procesador envía los datos a la tarjeta gráfica o al subsistema de gráficos integrado, que se encarga de procesarlos y generar la imagen final.

- Muestra en pantalla: La tarjeta gráfica comunica la imagen procesada al monitor, que la muestra en la pantalla como un conjunto de píxeles iluminados.

### Codificación de datos internamente:

**Los datos en una computadora se codifican en formato binario, es decir, utilizando dos estados posibles: 0 y 1. Este sistema se utiliza porque los componentes electrónicos de las computadoras (transistores) pueden estar en uno de dos estados, que representan los valores binarios. Los datos pueden ser números, caracteres, imágenes o sonidos, y todos se representan mediante secuencias de bits:**

- Números: Se codifican usando sistemas como el sistema binario o el sistema decimal codificado en binario (BCD).

- Texto: Los caracteres se representan mediante códigos estándar como ASCII o Unicode, que asignan secuencias de bits a cada letra, número o símbolo.

- Imágenes y sonidos: Estos se codifican utilizando formatos como JPEG o WAV, en los cuales los datos se representan como secuencias de bits que describen píxeles o ondas de sonido.

### Unidades de medida de datos en una computadora:

<mark>Las unidades estándar utilizadas para medir la cantidad de datos en las computadoras son<mark/>:

| Unidad        | Equivalencia                         |
|---------------|--------------------------------------|
| Bit (b)       | 1 bit                                |
| Byte (B)      | 8 bits                               |
| Kilobyte (KB) | 1 KB = 1024 bytes                   |
| Megabyte (MB) | 1 MB = 1024 KB = 1,048,576 bytes    |
| Gigabyte (GB) | 1 GB = 1024 MB = 1,073,741,824 bytes|
| Terabyte (TB) | 1 TB = 1024 GB = 1,099,511,627,776 bytes |
| Petabyte (PB) | 1 PB = 1024 TB                      |









