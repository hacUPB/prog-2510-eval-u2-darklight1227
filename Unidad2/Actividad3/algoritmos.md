# Algoritmos

#### Ejercicio 1 
<mark>_Símbolos que se utilizan para representar cada operación de un algorimo con un diagrama de flujo._

![Imagen Algoritmos](https://github.com/user-attachments/assets/9f0f7ffa-7997-4b0d-896e-be38a80dd789)

#### Ejercicio 2

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


#### Ejercicios 3 

## 1. 
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

## 2. 

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

## 3.

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
