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
=======
>>>>>>> origin/main
