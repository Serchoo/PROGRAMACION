#### Sergi Oliver, Martí Salom

#  PISCINA 1
- Definir largo1 como 300
- Definir ancho1 como 150
- Definir profundidad1 como 20

#  PISCINA 2
- Definir largo2 como 300
- Definir ancho2 como 80
- Definir profundidad2 como 35

##  Apartado 1 - Cálculo del área de cada piscina
- Calcular area1 como ancho1 * largo1
- Mostrar "El área de la primera piscina es: " + area1 + "m²"

- Calcular area2 como ancho2 * largo2
- Mostrar "El área de la segunda piscina es: " + area2 + "m²"

##  Apartado 2 - Cálculo del volumen de cada piscina
- Calcular volumen1 como area1 * profundidad1
- Mostrar "El volumen de la primera piscina es: " + volumen1 + " Litros"

- Calcular volumen2 como area2 * profundidad2
- Mostrar "El volumen de la segunda piscina es: " + volumen2 + " Litros"

##  Apartado 3 - Cálculo de las dimensiones combinadas de ambas piscinas
- Definir largoTotal como largo1
- Definir anchoTotal como ancho1 + ancho2
- Mostrar "El ancho y el largo de ambas piscinas juntas es: " + largoTotal + "m de largo y " + anchoTotal + "m de ancho"

##  Apartado 4 - Cálculo del área total de ambas piscinas
- Calcular areaTotal como anchoTotal * largo1
- Mostrar "El área de ambas piscinas es de: " + areaTotal + " Litros"

##  Apartado 5 - Cálculo del volumen total de ambas piscinas
- Calcular volumenTotal como areaTotal * profundidad1
- Mostrar "El volumen de ambas piscinas es de: " + volumenTotal + " Litros"

##  Apartado 6 - Intercambio de profundidades y recalcular volúmenes
- Definir aux como profundidad1
- Asignar a profundidad1 el valor de profundidad2
- Asignar a profundidad2 el valor de aux

- Calcular nuevo volumen1 como area1 * profundidad1
- Mostrar "El nuevo volumen de la primera piscina es: " + nuevo volumen1 + " Litros"

- Calcular nuevo volumen2 como area2 * profundidad2
- Mostrar "El nuevo volumen de la segunda piscina es: " + nuevo volumen2 + " Litros"
