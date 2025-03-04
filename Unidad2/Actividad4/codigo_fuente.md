## <mark>Conversion de pseudocódigo a Python 💻

### <mark>Ejercicio 1 
```
x1 = float(input("Ingrese el valor del punto en x1: "))
x2 = float(input("Ingrese el valor del punto en x2: "))
y1 = float(input("Ingrese el valor del punto en y1: "))
y2 = float(input("Ingrese el valor del punto en y2: "))

    d_enx = x2 - x1
    d_eny = y2 - y1
    print("La distancia de los puntos es de :", d_enx," en X y ",d_eny," en Y")
```
### <mark>Ejercicio 2
```
metros = float(input("Ingrese el número de metros que desea convertir a pulgadas :"))
    pulgadas = metros / 0.0254
    print("El total en pulgadas es de :", pulgadas)
```
### <mark>Ejercicio 3
```
a = float(input("Ingrese el valor del cateto número 1 : "))
b = float(input("Ingrese el valor del catero número 2 : "))

    h = √(A^2 + B^2)
    print("La hipotenusa del triángulo es de :",h,"metros")
```
### <mark>Ejercicio 4 
```
dia_nacimiento = int(input("Ingrese su dia de nacimiento :"))
mes_nacimiento = int(input("Ingrese su mes de nacimiento :"))
anio_nacimiento = int(input("Ingrese su año de nacimiento :"))
dia_actual = int(input("Ingrese el dia actual :"))
mes_actual = int(input("Ingrese el mes actual :"))
anio_actual = int(input("Ingrese el año actual :"))
    
    if mes_actual < mes_nacimiento or (mes_actual == mes_nacimiento and dia_actual < dia_nacimiento):
        edad -= 1
        print("Aún no cumples años")

    elif dia_actual == dia_nacimiento and mes_actual == mes_nacimiento:
        print("¡Hoy estás de cumpleaños!!!")

    else:
        print("Ya cumpliste años")
    
    print("La edad actual es de :",edad," años")
```
### <mark>Ejercicio 5 
```

horas_trabajadas = int(input("Ingrese la cantidad de horas trabajadas :"))
pago_por_hora = float(input("Ingrese el pago por cada hora de trabajo :"))

    if horas_trabajadas <= 40:
        sueldo = horas_trabajadas * pago_por_hora

    elif 40 < horas_trabajadas <= 45 :
        sueldo = (40 * pago_por_hora) + ((horas_trabajadas - 40) * (pago_por_hora * 2))

    elif 45 < horas_trabajadas <= 50:
        sueldo = (40 * pago_por_hora) + (5 * (pago_por_hora * 2)) + ((horas_trabajadas - 45) * (pago_por_hora * 3))

    else:
        print("No es permitido trabajar más de 50 horas")
        return
    
    print("El sueldo semanal fue de :",sueldo)
```
