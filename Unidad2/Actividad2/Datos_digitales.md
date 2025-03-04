### 1. <mark>Representación de los datos en un computador : 💻
   _Los datos en una computadora se representan mediante un sistema binario, donde todo se convierte en secuencias de 0s y 1s, también conocidos como bits. Estos bits pueden tener dos estados posibles: 0 (falso) o 1 (verdadero). Las letras, números e imágenes se representan utilizando combinaciones de estos bits. Por ejemplo, los números se representan a través de su valor binario (como el número 5, que se representaría como 101 en binario), y las imágenes se convierten en una matriz de píxeles, donde cada píxel es representado por un valor binario que define su color. Así, en la computadora, cualquier tipo de información es traducida a esta forma binaria para poder ser procesada, almacenada y manipulada._

### ¿Cuántos estados diferentes pueden ser representados por N variables binarias?
   Cuando se tiene un conjunto de N variables binarias, cada una de ellas puede tener dos posibles valores: 0 o 1. Por lo tanto, el número total de estados posibles que pueden ser representados por N variables binarias es igual a 2 elevado a la N, o sea, \( 2^N \). Esto se debe a que cada variable agrega una dimensión de opciones (0 o 1) al conjunto total de combinaciones posibles. Por ejemplo, si se tienen 3 variables binarias, los estados posibles serían \( 2^3 = 8 \).

### Unidades de almacenamiento de datos : 🖥️

| Unidad        | Prefijo      | Cantidad en bytes    |
|---------------|--------------|----------------------|
| **Byte**      | -            | 1 Byte               |
| **Kilobyte**  | Kilo (k)     | 1,024 Bytes          |
| **Megabyte**  | Mega (M)     | 1,024 Kilobytes      |
| **Gigabyte**  | Giga (G)     | 1,024 Megabytes      |
| **Terabyte**  | Tera (T)     | 1,024 Gigabytes      |
| **Petabyte**  | Peta (P)     | 1,024 Terabytes      |
| **Exabyte**   | Exa (E)      | 1,024 Petabytes      |
| **Zettabyte** | Zetta (Z)    | 1,024 Exabytes       |
| **Yottabyte** | Yotta (Y)    | 1,024 Zettabytes     |

### Importancia del trabajo de George Boole :  
   <mark>George Boole fue un matemático y lógico que desarrolló una rama de las matemáticas conocida como álgebra booleana, que es fundamental para la computación moderna. Su trabajo permitió la representación de valores lógicos (verdadero o falso, 1 o 0) mediante operaciones matemáticas, las cuales son esenciales para el procesamiento de información en las computadoras. Gracias a la álgebra booleana, las computadoras pueden realizar operaciones complejas utilizando simples valores binarios, lo que forma la base de todo el procesamiento digital de datos.


   ## <mark>Ejercicio 2

- $1010101010_2$ = $682_10$
- $11111_2$ = $31_10$
- $10000000_2$ = $128_10$
- $100100100_2$ = $292_10$
- $111000_2$ = $56_10$

## Ejercicio 2 Parte 2

- $127_{10} = 1111111_2$
- $246_{10} = 11110110_2$
- $1025_{10} = 10000000001_2$
- $354_{10} = 101100110_2$
- $187_{10} = 10111011_2$




# <mark>Tipos de datos que usan los lenguajes



#### 2. Pregunta para reflexionar : _Las computadoras usan binario porque es un sistema que encaja perfectamente con cómo funcionan sus componentes físicos. Los circuitos dentro de una computadora son como interruptores que solo pueden estar “prendidos” o “apagados”. Es decir, pueden estar en dos estados. Esto hace que el binario sea la forma más sencilla de representar información._

## 3. Actividad de Investigación 🧑‍🔬

| **Tipo de Dato**  | **C**                      | **Java**                  | **Python**                |
|-------------------|----------------------------|---------------------------|---------------------------|
| **Enteros**       | `int`, `long`, `short`      | `int`, `long`             | `int`                     |
| **Flotantes**     | `float`, `double`           | `float`, `double`         | `float`                   |
| **Caracteres**    | `char`                      | `char`                    | `str` (un solo carácter)  |
| **Cadenas**       | `char[]` (array de chars)   | `String`                  | `str`                     |
| **Booleanos**     | `bool` (en C99 y adelante)  | `boolean`                 | `bool`  |
| **Otros**         | `unsigned int`, `long long` | `byte`, `short`, `long`   | `complex` (para números complejos) |




## 4. Organización de resultados 📓

| **Nombre de la Variable** | **Abreviación**           | **Características principales**                                                                                      |
|---------------------------|---------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Entero (C)**            | `int`, `long`, `short`     | Representa números enteros, con diferentes rangos según el tipo (`short` más pequeño, `long` más grande).              |
| **Entero (Java)**         | `int`, `long`             | Similar a C, `int` es para números enteros de tamaño estándar, `long` para números más grandes.                        |
| **Entero (Python)**       | `int`                     | Solo existe un tipo de entero, que puede manejar grandes valores enteros sin preocuparse del rango.                     |
| **Flotante (C)**          | `float`, `double`         | `float` es para números decimales de precisión simple, `double` para mayor precisión.                                  |
| **Flotante (Java)**       | `float`, `double`         | Iguales a C, `float` es para precisión simple, `double` para mayor precisión.                                          |
| **Flotante (Python)**     | `float`                   | Solo existe un tipo de flotante, similar al `double` en otros lenguajes.                                                |
| **Carácter (C)**          | `char`                    | Representa un solo carácter (usualmente 1 byte de memoria).                                                             |
| **Carácter (Java)**       | `char`                    | Similar a C, representa un solo carácter (usualmente 2 bytes para UTF-16).                                             |
| **Carácter (Python)**     | `str`                     | Los caracteres son tratados como cadenas de texto de longitud 1.                                                        |
| **Cadena (C)**            | `char[]`                  | Un arreglo de caracteres que representa una cadena de texto.                                                            |
| **Cadena (Java)**         | `String`                  | Un objeto que representa cadenas de texto, con métodos para manipularlas.                                               |
| **Cadena (Python)**       | `str`                     | Tipo de dato para cadenas de texto, es inmutable y soporta múltiples operaciones de manipulación.                      |
| **Booleano (C)**          | `bool` (C99)              | Representa un valor de verdad (verdadero o falso). El tipo `bool` fue introducido en C99.                               |
| **Booleano (Java)**       | `boolean`                 | Representa valores `true` o `false` (solo estos dos valores).                                                           |
| **Booleano (Python)**     | `bool`                    | Al igual que en otros lenguajes, representa los valores `True` o `False`.                                               |
| **Otros (C)**             | `unsigned int`, `long long` | `unsigned int` es un entero sin signo, `long long` es un entero de mayor tamaño.                                       |
| **Otros (Java)**          | `byte`, `short`, `long`   | `byte` es un entero de 8 bits, `short` de 16 bits y `long` de 64 bits.                                                  |
| **Otros (Python)**        | `complex`                 | Tipo de dato para números complejos (con parte real e imaginaria).                                                      |






### 5. Ejercicio de cálculo de espacio de almacenamiento en la memoria :wrench:

<mark> Se almacena la información cada 10 segundos durante 24 horas. Calcula cuánto espacio total se requiere en memoria para almacenar estos datos. Describe el procedimiento y muestra el resultado final.

- Cada minuto se almacenan 6 datos
- Cada hora se almacenan 360 datos
- Cada 24 horas se almacenan 8.640 datos

Debido a los valores de los diferentes datos (19) necesitamos multiplicarlo por los datos almacenados

8.640 * 19 = 164.160 datos

### <mark>6. Conclusión<mark/> = _En esta actividad, calculamos el espacio necesario para almacenar diferentes tipos de datos en memoria durante un periodo de 24 horas. Al hacerlo, aprendí cómo la información se representa de manera eficiente en las computadoras, considerando el tipo de dato que se maneja (enteros, flotantes, booleanos, texto) y cuánto espacio ocupa cada tipo de dato._



