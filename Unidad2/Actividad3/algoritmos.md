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
