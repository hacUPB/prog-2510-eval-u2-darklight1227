### El computador digital moderno

#### ¿ Que es un computador ? :computer: :computer:

*Es una máquina electrónica capaz de realizar un tratamiento automático de la información y de resolver con gran rapidez problemas matemáticos y lógicos mediante programas informáticos'. Estas formas son las usadas mayoritariamente en el español de América, por influjo del inglés computer. Según las zonas, existen distintas preferencias: en la mayoría de los países de América se prefiere el femenino computadora, mientras que el masculino computador es de uso mayoritario en Chile y Colombia. En España se usa preferentemente el término ordenador.*


Tomado de: [Real Academia Española](https://www.rae.es/dpd/computador)


### Arquitecturas de un computador :construction_worker:
*Actualmente en el segmento de los procesadores nos encontramos dos arquitecturas o tipos de diseño. Por un lado tenemos la arquitectura CISC, usada por Intel y AMD para sus procesadores, y por otro lado tenemos la arquitectura RISC, usada por Qualcomm, Samsung, Apple, etc., para los SoC de smartphone, tabletas o portátiles.*

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

*Hardware es una palabra inglesa que hace referencia a las partes físicas tangibles de un sistema informático, es decir, todo aquello que podemos tocar con las manos. Dentro del hardware encontramos una gran variedad de componentes eléctricos, electrónicos, electromecánicos y mecánicos. El hardware es el chasis del ordenador, los cables, los ventiladores, los periféricos y todos los componentes que se pueden encontrar en un dispositivo electrónico. La Real Academia Española lo define como «Conjunto de los componentes que integran la parte material de una computadora».*

*En el Hardware podemos encontrar algunos elementos como los siguientes.*

| Nombre del componente | Funcion | Partes del componente |
|-----------------------|---------|-----------------------|
| ALU                   | La ALU realiza todos los cálculos y comparaciones. Realiza seis funciones: suma, resta, multiplicación, división, operaciones booleanas|el circuito aritmético, la memoria, el conjunto de instrucciones y la unidad de control|
| Unidad de Control     |Es una parte fundamental en la arquitectura de una CPU (Unidad Central de Procesamiento). El papel principal de la Unidad de Control (CU, por sus siglas en inglés) es la de supervisar el funcionamiento del procesador. |Contador de programa, Registros de instrucciones, Decodificador, Reloj, Secuenciador |
| Registros             | un registro es una memoria de alta velocidad y poca capacidad, integrada en el microprocesador, que permite guardar transitoriamente y acceder a valores muy usados, generalmente en operaciones matemáticas.|Integrado en el microprocesador|
| Buses                 |Se utilizan para transferir datos entre el microprocesador y la memoria RAM. Son los caminos por los cuales los datos viajan, por ejemplo del microprocesador al disco rígido, o de la memoria al disco|CPU y resto de unidades |


#### ¿ Que es la GPU ? :floppy_disk:

La unidad de procesamiento de gráficos (GPU) tiene muchos núcleos pequeños y especializados. Estos núcleos ofrecen un enorme desempeño al trabajar juntos y dividir las tareas de procesamiento entre muchos núcleos simultáneamente (o en paralelo). La GPU se destaca en tareas altamente paralelas, como renderizar imágenes durante un juego, manipular datos de video durante la creación de contenido y calcular resultados en cargas de trabajo de IA intensivas.

##### ¿ En que se diferencia la GPU de la CPU ?

Las CPUs y GPUs tienen mucho en común: ambas son motores informáticos críticos, son microprocesadores de silicio y manejan datos. Pero las CPU y las GPU tienen diferentes arquitecturas y se construyen con diferentes propósitos.

La CPU es adecuada para varias tareas, en especial aquellas para las que la latencia o el desempeño por núcleo es importante. Como un potente motor de ejecución, la CPU centra su menor cantidad de núcleos en tareas particulares y en hacer las cosas rápidamente. Por tanto, resulta muy útil para tareas como la informática en serie, en la que solo se ejecuta una tarea a la vez en un solo procesador, o la ejecución de bases de datos.

Las GPUs comenzaron como circuitos integrados de aplicación específica (ASICs) hechos con fines especializados, como acelerar los gráficos y las tareas de renderizado 3D, por ejemplo el gaming. Con el paso del tiempo, estos motores con funciones fijas se han vuelto más programables y más flexibles. Aunque su función principal sigue girando en torno a los gráficos y los elementos visuales cada vez más realistas del gaming, las GPUs se han convertido en procesadores paralelos de uso más general capaces de ejecutar muchas tareas de forma simultánea para manejar una variedad cada vez mayor de aplicaciones, entre ellas la IA.

**Hoy en día, ya no se trata de elegir entre una CPU y una GPU. Ahora más que nunca, necesita ambas para satisfacer sus diversas exigencias informáticas. Los mejores resultados se obtienen cuando se utiliza la herramienta adecuada para el trabajo.**


## Ahora hablemos un poco de la memoria

*La memoria de la computadora, también conocida como memoria principal o memoria principal, proporciona almacenamiento temporal para tareas computacionales, lo que la hace fundamental para el funcionamiento de una computadora. Los datos se almacenan en la memoria para que se puedan enviar a la unidad de procesamiento central (CPU) para los cálculos y una aplicación pueda recuperar datos cuando sea necesario.*

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









