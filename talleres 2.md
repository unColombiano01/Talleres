**CALCULADORA DE PROPINA**

Algoritmo PromedioCalificiones
definir totalcuenta, porcentajepropina, montopropina, totalapagar como real

escribir "ingresa el total de la cuenta: "
leer totalcuenta

escribir: "ingresa el porcentaje de la propina proporcionada: "
leer porcentajepropina

montopropina = totalcuenta * (porcentajepropina / 100)

totalapagar = montopropina + totalcuenta

escribir "___________"

escribir "cuenta total :", totalcuenta

escribir "propina: (", porcentajepropina "%): $", montopropina

escribir "total a pagar: $", totalapagar

finalgoritmo
<<<<<<< HEAD

**DESCUENTO ESCALONADO**

algoritmo DecuentoEscalonado
definir precio, stock, descuento1, descuento2, subtotal,total1final total2, total como real

escribir "ingrese precio del producto: "
leer precio 

escribir "ingrese stock producto: "
leer stock

subtotal c- precio * stock

si subtotal menor que 100.000
  entonces descuento1 flecha izquierda subtotal + 0.15

total flecha izquierda subtotal - descuento 1

si total menor que 200.000
entonces descuento2 flecha izquierda total + 0.05
total2 flecha izquierda total-descuento2

finsi

totalfinal flecha izquierda total2

finalgoritmo

**CALCULAR PROMEDIO CON VALIDACION**

algoritmo CalculadoraPromedioConValidacion
definir n, i como entero
definir calificacion, suma, promedio como real

suma (- 0

escribir "¿cuantas calificaciones deseas ingresar?"
leer calificacion

para i + 1 hasta n con paso 1 hacer
escribir "calificacion ", i, ": "
leer calificacion

mientras calificacion menor que 0 o calificacion mayor que 5 hacer
escribir "error: la calificacion debe estar entre 0 y 5"
escribir "calificacion ", i, ": "
leer calificacion
finmientras

suma (- suma + calificacion
finpara

promedio (- suma / n

escribir "_______________"
escribir "promedio: ", promedio 

si promedio menor igual que 3 entonces
escribir "resultado: aprobado"
sino
escribir "resultado: reprobado"
finsi 
finalgoritmo

**TABLA DE MULTIPLICAR MEJORADA**

algoritmo TabladeMultiplicarMejorada
definir x como entero

escribir "ingresar un numero entero: "
leer x

para n (- 1 hasta 10 hacer
si (n*x) mod 2=0 entonces
escribir x," * ", n, "=", x*n
finsi
finsi
finalgoritmo