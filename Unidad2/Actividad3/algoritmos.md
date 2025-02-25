# Algoritmos

#### Ejercicio 1 📱
<mark>_Símbolos que se utilizan para representar cada operación de un algorimo con un diagrama de flujo._

![Imagen Algoritmos](https://github.com/user-attachments/assets/9f0f7ffa-7997-4b0d-896e-be38a80dd789)

#### Ejercicio 2 📖

<mark>_Construye un algoritmo que, al recibir como datos el ID del empleado y los seis primeros sueldos del año, calcule el ingreso total semestral y el promedio mensual, e imprima el ID del empleado, el ingreso total y el promedio mensual._

```
Inicio
Algoritmo sueldos

Definir ID String
Definir Sueldo1, Sueldo2, Sueldo3, Sueldo4, Sueldo5, Sueldo6 Float

Imprimir ( "Ingrese su ID")
leer ID

Imprimir ( "Ingrese el sueldo del mes 1" )
leer Sueldo1

Imprimir ( "Ingrese el sueldo del mes 2" )
leer Sueldo2

Imprimir ( "Ingrese el sueldo del mes 3" )
leer Sueldo3

Imprimir ( "Ingrese el sueldo del mes 4" )
leer Sueldo4

Imprimir ( "Ingrese el sueldo del mes 5" )
leer Sueldo5

Imprimir ( "Ingrese el sueldo del mes 6" )
leer Sueldo6

Ing_t_Semestral = Sueldo1 + Sueldo2 + Sueldo3 + Sueldo4 + Sueldo5 +Sueldo6
Prom_mensual = Ing_t_Semestral / 6


Imprimir ( " Su Ingreso total semestral fue de " ) +Ing_t_Semestral
Imprimir ( " Su promedio mensual fue de " ) +Prom_mensual

Fin
```


#### <mark>Ejercicios 3<mark/> 📚

#### 1. 
```
Inicio
    Leer cantidad_de_lapices
    Si cantidad_de_lapices >= 1000 Entonces
        precio_por_lapiz <- 85
    Sino
        precio_por_lapiz <- 90
    FinSi
    total_a_pagar <- cantidad_de_lapices * precio_por_lapiz
    Escribir "El total a pagar es: ", total_a_pagar
Fin
```

#### 2. 

```
Inicio
    Leer monto_compra
    Si monto_compra > 250000 Entonces
        descuento <- monto_compra * 0.15
    Sino
        descuento <- monto_compra * 0.08
    FinSi
    precio_final <- monto_compra - descuento
    Escribir "El descuento es: ", descuento
    Escribir "El precio final a pagar es: ", precio_final
Fin
```

#### 3.

```
Inicio
    Leer cantidad_de_alumnos
    Si cantidad_de_alumnos >= 100 Entonces
        costo_por_alumno <- 65
    SinoSi cantidad_de_alumnos >= 50 Entonces
        costo_por_alumno <- 70
    SinoSi cantidad_de_alumnos >= 30 Entonces
        costo_por_alumno <- 95
    Sino
        costo_por_alumno <- 4000 / cantidad_de_alumnos
    FinSi
    total_a_pagar <- cantidad_de_alumnos * costo_por_alumno
    Escribir "El costo por alumno es: ", costo_por_alumno
    Escribir "El total a pagar por el servicio es: ", total_a_pagar
Fin

```

### Respuestas de las preguntas finales


#### <mark>Parte 1 - Identificar algoritmos. 👓

- _**Una página web**_: No es un algoritmo. Una página web puede contener muchisimas cosas, juegos, redes sociales, videos etc. Pero no son un algoritmo debido a que no detallan un conjunto de pasos para resolver alguna actividad o problema.

- _**Una receta para hacer un pastel**_: Sí es un algoritmo. Ya que las recetan nos van especificando los pasos a seguir para obtener el resultado final.

- _**"Piensa en un número y multiplícalo por otro"**_: El enunciado como tal no es un algoritmo, pero si nos vamos a la parte operativa si sería un algortimo debido a que tenemos que seguir una secuencia de pasos para obtener el resultado.

- _**Un manual de instrucciones para armar un mueble**_: Sí es un algoritmo. El manual nos indica los pasos y lo que tenemos que ir haciendo en cada momento.

- _**Una lista de compras organizada en orden alfabético**_: No es un algoritmo. simplemente son elementos que estan ordenados, pero no un conjunto de instrucciones de algo.


#### <mark>Parte 2 - Variables y constantes. 🖥️

- _**El valor de la gravedad en la Tierra, 9.8 m/s²**_: Es una constante, ya que siempre es el mismo valor.

- _**La edad de una persona calculada con base en el año actual y su año de nacimiento**_: El año actual es una variable que va cambiando cada 365 dias, el año de nacimiento es constante ya que siempre será el mismo.

- _**La cantidad de dinero en una cuenta bancaria**_: Es variable, esta siempre cambiando.

- _**La velocidad de la luz en el vacío, 299,792,458 m/s**_: Es constante, siempre es esa misma velocidad.

- _**El radio de un círculo**_: Es variable ya que dependiendo del tamaño del circulo puede cambiar.


#### <mark>Parte 3 - Características de los algoritmos 💻

- **Para elegir la ruta más corta entre varias ciudades, el algoritmo examina rutas candidatas, deteniéndose cuando los cambios en la distancia parecen lo suficientemente pequeños:**

   Pareciera ser un algoritmo aunque no esta claramente especificado el proceso.

- **Suma los números ingresados y muestra el resultado:**

  Si, es un algoritmo que tiene un conjunto claro de pasos.

- **Un conjunto de pasos para calcular el área de un rectángulo dado su base y altura:**

 Si, también es un algoritmo el cual tiene un conjunto claro de pasos para resolver el problema.

- **El algoritmo cuenta el número de votos obtenidos por cada uno de los candidatos de una elección para presidente. Empieza solicitando el nombre del candidato y finaliza cuando se ingresa el valor -1:**

Si, es un algoritmo que tiene pasos a seguir, además de un inicio y un final.


#### <mark>Parte 4 - Compresión de Herramientas 🧰

- <mark>El pseudocódigo utiliza símbolos estándar para representar las operaciones lógicas:

  Falso. El pseudocódigo representa los algoritmos usando un lenguaje más común.

- <mark>Los diagramas de flujo son una representación gráfica de un algoritmo:

  Verdadero. Es otra manera de representar los pasos de un algoritmo

- <mark>El pseudocódigo debe estar escrito en un lenguaje de programación específico:

   Falso. El pseudocódigo escribe un algoritmo en lenguaje informal, ninguno de programación en especifíco, por lo cual es falso.

- <mark>Un diagrama de flujo siempre debe tener un inicio y un fin claramente definidos:

   Verdadero, estos deben estar representados claramente en el diagrama.

  #### <mark>Parte 5 - Estructuras de control 🏗️

  <mark>Las estructuras de control son instrucciones que permiten modificar el flujo de ejecución de un programa según ciertas condiciones. Son fundamentales en la programación porque permiten tomar decisiones, repetir tareas y alterar el curso de ejecución del código.

**Ejemplo 1: Vida diaria**

Supongamos que estamos en el final del dia y quiero jugar videojuegos pero primero deberia revisar si tengo tareas, Usare una estructura de control para tomar la decisión. 🎮


```
Si tengo tareas entonces
    Realizar las tareas
Sino
    Jugar videojuegos con mis amigos.
```

**Ejemplo 2: Cálculos matemáticos para tomar decisiones**

Imaginemos que voy manejando mi moto y necesito decidir si tengo que ir a rellenar el tanque de gasolina. 🏍️

```
Si el nivel de gasolina es menor que 10 litros entonces
    Ir a la bomba a llenar el tanque
Sino
    Continuar manejando sin necesidad de tanquear


```


  

  


