## RETOS!

### <mark>1. Algoritmo para convertir metros a pulgadas
Pseudocódigo:

java
Copiar
Inicio
    Leer metros
    pulgadas = metros / 0.0254
    Imprimir pulgadas
Fin
Explicación: Este algoritmo toma un valor en metros, lo divide por 0.0254 (el valor de 1 pulgada en metros) y muestra el resultado en pulgadas.

### <mark>2. Algoritmo para determinar la hipotenusa de un triángulo rectángulo

mathematica
Copiar
Inicio
    Leer A, B
    C = sqrt(A^2 + B^2)
    Imprimir C
Fin

 

### <mark>3. Algoritmo para calcular la edad y determinar si la persona ya ha celebrado su cumpleaños
Pseudocódigo:

java
Copiar
Inicio
    Leer dia_nacimiento, mes_nacimiento, año_nacimiento
    Leer dia_actual, mes_actual, año_actual

    edad = año_actual - año_nacimiento
    Si mes_actual < mes_nacimiento O (mes_actual == mes_nacimiento Y dia_actual < dia_nacimiento) Entonces
        edad = edad - 1
    FinSi

    Si dia_actual == dia_nacimiento Y mes_actual == mes_nacimiento Entonces
        Imprimir "Feliz Cumpleaños"
    Sino
        Si edad > 0 Entonces
            Imprimir "La persona ha celebrado su cumpleaños este año"
        Sino
            Imprimir "La persona aún no ha celebrado su cumpleaños este año"
        FinSi
    FinSi

    Imprimir "Edad actual: ", edad
Fin


### <mark>4. Algoritmo para calcular el sueldo semanal con horas extra
Pseudocódigo:

java
Copiar
Inicio
    Leer horas_trabajadas, pago_por_hora
    Si horas_trabajadas <= 40 Entonces
        sueldo = horas_trabajadas * pago_por_hora
    Sino
        Si horas_trabajadas <= 45 Entonces
            sueldo = (40 * pago_por_hora) + ((horas_trabajadas - 40) * (pago_por_hora * 2))
        Sino
            Si horas_trabajadas <= 50 Entonces
                sueldo = (40 * pago_por_hora) + (5 * (pago_por_hora * 2)) + ((horas_trabajadas - 45) * (pago_por_hora * 3))
            Sino
                Imprimir "Error, el máximo permitido son 50 horas"
                Terminar
            FinSi
        FinSi
    FinSi
    Imprimir "El sueldo semanal es: ", sueldo
Fin
Explicación: Este algoritmo calcula el sueldo semanal de un trabajador, considerando las horas normales, horas extra de hasta 45 horas y horas extra de más de 45 horas.

### <mark>5. Algoritmo para contar ceros, menores a cero y mayores a cero en N números
Pseudocódigo:

java
Copiar
Inicio
    Leer N
    cero = 0
    menor_a_cero = 0
    mayor_a_cero = 0

    Para i = 1 hasta N hacer
        Leer numero
        Si numero == 0 Entonces
            cero = cero + 1
        SinoSi numero < 0 Entonces
            menor_a_cero = menor_a_cero + 1
        Sino
            mayor_a_cero = mayor_a_cero + 1
        FinSi
    FinPara

    Imprimir "Ceros: ", cero
    Imprimir "Menores a cero: ", menor_a_cero
    Imprimir "Mayores a cero: ", mayor_a_cero
Fin
Explicación: Este algoritmo cuenta cuántos números son cero, menores que cero y mayores que cero en un conjunto de N números dados.

### <mark>6. Algoritmo para determinar cuánto ahorrará una persona en un año
Pseudocódigo:

java
Copiar
Inicio
    total_ahorro = 0
    Para dia = 1 hasta 365 hacer
        ahorro_diario = 3^(dia-1)
        total_ahorro = total_ahorro + ahorro_diario
    FinPara

    Imprimir "El ahorro total al final del año es: ", total_ahorro
Fin
Explicación: Este algoritmo calcula el ahorro diario y total para un año, siguiendo una progresión geométrica donde el primer día se ahorran 3¢ y el ahorro se multiplica por 3 cada día siguiente.

### <mark>7. Algoritmo para calcular el precio con descuento de artículos
Pseudocódigo:

java
Copiar
Inicio
    Leer N
    total_pago = 0

    Para i = 1 hasta N hacer
        Leer precio
        Si precio >= 200 Entonces
            descuento = 0.15
        SinoSi precio > 100 Entonces
            descuento = 0.12
        Sino
            descuento = 0.10
        FinSi

        descuento_aplicado = precio * descuento
        precio_final = precio - descuento_aplicado
        total_pago = total_pago + precio_final
        Imprimir "Precio artículo ", i, ": ", precio, ", Descuento: ", descuento_aplicado, ", Precio final: ", precio_final
    FinPara

    Imprimir "Total a pagar: ", total_pago
Fin
Explicación: Este algoritmo calcula el costo total de N artículos con descuentos aplicados según su precio y muestra el detalle de cada uno.

### <mark>8. Algoritmo para calcular una función exponencial
Pseudocódigo:

java
Copiar
Inicio
    Leer x
    resultado = 1
    factorial = 1
    potencia = 1

    Para i = 1 hasta 10 hacer
        potencia = potencia * x
        factorial = factorial * i
        termino = potencia / factorial
        Si i % 2 == 1 Entonces
            resultado = resultado - termino
        Sino
            resultado = resultado + termino
        FinSi
    FinPara

    Imprimir "El valor de e^x es: ", resultado
Fin
Explicación: Este algoritmo calcula el valor de la función exponencial 
𝑒
𝑥
e 
x
  utilizando la serie de Taylor hasta el término 10.

### <mark>9. Algoritmo para calcular el seno de un ángulo
Pseudocódigo:

java
Copiar
Inicio
    Leer x
    resultado = 0
    factorial = 1
    potencia = x
    signo = 1

    Para i = 1 hasta 10 hacer
        resultado = resultado + signo * (potencia / factorial)
        signo = -signo
        potencia = potencia * x * x
        factorial = factorial * (2 * i) * (2 * i + 1)
    FinPara

    Imprimir "El valor del seno de x es: ", resultado
Fin
Explicación: Este algoritmo calcula el valor del seno de un ángulo 
𝑥
x utilizando la serie de Taylor para la función seno.
