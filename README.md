INTEGRANTES Y TEMA: Adrian Lazaro, Juanjo Prades, Mario Gonzalez (while, break y continue) 

 

 

QUÉ DEMUESTRA EL EJEMPLO Y CÓMO EJECUTARLO: 

 

numero = 0 
 
while numero < 10: 
   numero += 1 
 
   if numero == 5: 
       continue 
 
   if numero == 8: 
       break 
 
   print(numero) 

 

El código imprime el numero si cumple la condición de que si el numero es 5, salta esa condición y no lo imprime y si el numero es 8, se detiene el bucle. 

 

Se ejecuta con “python script.py” 

 

 

RESULTADO ESPERADO: 

 

1 
2 
3 
4 
6 
7 

 

ERROR TÍPICO O MODIFICACIÓN QUE HABÉIS EXPLICADO: 

 

Al quitar el incremento de la variable (numero += 1), la variable no incrementa y siempre será igual a 0, por lo que el código entrará en bucle y crasheará. 

PREGUNTA PARA LA CLASE Y SU RESPUESTA 

¿Qué pasaría si en lugar de poner 5 en numero == 5 pusiéramos numero == 6? 

Saltará el 6 en lugar del 5