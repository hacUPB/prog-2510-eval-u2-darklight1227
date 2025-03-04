## RETOS!

### <mark>1. Algortimo para obtener la distancia entre dos puntos del plano
```
Inicio
    Leer X1, X2, Y1. Y2 

    d_enx = X2 - X1
    d_eny = Y2 - Y1

    Imprimir " La distancia de los puntos es de : " , d_enx ," En X " Y " , d_eny , "En Y "
```
### <mark>2. Algoritmo para convertir metros a pulgadas
```
Inicio
    Leer metros
    pulgadas = metros / 0.0254
    Imprimir "El total en pulgadas es de : ", pulgadas
Fin
```
### <mark>3. Algoritmo para determinar la hipotenusa de un triángulo rectángulo
```
Inicio
    Leer A, B
    H = √(A^2 + B^2)
    Imprimir "La hipotenusa del triangulo es : ", H
Fin
```
 

### <mark>4. Algoritmo para calcular la edad y determinar si la persona ya ha celebrado su cumpleaños
```
Inicio
    Leer dia_nacimiento, mes_nacimiento, año_nacimiento
    Leer dia_actual, mes_actual, año_actual

    edad = año_actual - año_nacimiento
    
    Si mes_actual < mes_nacimiento O (mes_actual == mes_nacimiento && dia_actual < dia_nacimiento)
        edad = edad - 1
         Imprimir "Aun no cumples años "

    Sino
    
        Si (dia_actual == dia_nacimiento Y mes_actual == mes_nacimiento) 
        Imprimir "Hoy estas de cumpleaños!!!"

        Sino
        
            Imprimir "Ya cumpliste años "
            
        FinSi 
    Fin si        

    Imprimir "La edad actual es de : ", edad
Fin
```

### <mark>5. Algoritmo para calcular el sueldo semanal con horas extra
```
Inicio
    Leer horas_trabajadas, pago_por_hora

    Si horas_trabajadas <= 40 
        sueldo = horas_trabajadas * pago_por_hora
        
    Sino
    
        Si horas_trabajadas >40 && horas_trabajadas <= 45 
            sueldo = (40 * pago_por_hora) + ((horas_trabajadas - 40) * (pago_por_hora * 2))
            
        Sino
        
            Si horas_trabajadas >45 && horas_trabajadas <= 50 
                sueldo = (40 * pago_por_hora) + (5 * (pago_por_hora * 2)) + ((horas_trabajadas - 45) * (pago_por_hora * 3))
                
            Sino
            
                Imprimir "No es permitido trabajar más de 50 horas"
                
            Fin Si
    Fin Si
Fin Si    
   
    Imprimir "El sueldo semanal fue de : ", sueldo
Fin

```
### <mark>6. Algoritmo para contar ceros, menores a cero y mayores a cero en N números
```
Inicio
    Leer N
    cero = 0
    menor_a_cero = 0
    mayor_a_cero = 0

    Para i = 1 hasta N 
        Leer numero
        
        Si numero == 0 
            cero = cero + 1
            
        Sino
        
            Si numero < 0 
                menor_a_cero = menor_a_cero + 1
            
            Sino
            
                mayor_a_cero = mayor_a_cero + 1
            
        Fin Si
            Fin Si
    Fin Para

    Imprimir "Ceros: ", cero
    Imprimir "Menores a cero: ", menor_a_cero
    Imprimir "Mayores a cero: ", mayor_a_cero
Fin
```
### <mark>7. Algoritmo para determinar cuánto ahorrará una persona en un año
```
Inicio
    total_ahorro = 0
     inicio_ahorro = 3
    
    Para dia = 1 hasta 365
        ahorro_diario = inicio_ahorroʌdia
        total_ahorro = total_ahorro + ahorro_diario (dia+1)

    Imprimir " El total del ahorro al día fue de : " , ahorro_diario

    Fin Para

    Imprimir "El ahorro total al final del año fue de : ", total_ahorro
Fin

```
### <mark>8. Algoritmo para calcular el precio con descuento de artículos
```
Inicio
    Leer N
    total_pago = 0

    Para i = 1 hasta N 
        Leer precio
        
        Si precio >= 200 
            descuento = 0.15
            
        Sino
        
            Si precio > 100 && <200 
                descuento = 0.12
            
            Sino
            
                descuento = 0.10
        Fin Si
            Fin Si

        descuento_aplicado = precio * descuento
        precio_final = precio - descuento_aplicado
        total_pago = total_pago + precio_final
        
        Imprimir "Precio artículo ", i, ": ", precio, ", el descuento fue de: ", descuento_aplicado, ", Y el precio final es de : ", precio_final
    Fin Para

    Imprimir "El Total a pagar es de : ", total_pago
Fin
```

### <mark>9. Algoritmo para calcular una función exponencial



