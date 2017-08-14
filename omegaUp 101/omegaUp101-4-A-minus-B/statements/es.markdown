Este problema es muy similar al que resolvimos anteriormente.
¡Encuentra la diferencia!

# Problema

Dados dos números enteros, $A$ y $B$, escribe un programa que calcule el resultado de $A - B$.

# Entrada

Una línea con 2 números enteros, $A$ y $B$, separados por un espacio.

# Salida

Tres líneas. En la primera línea, $A$, en la segunda, $B$, y en la tercera, $A - B$.

# Ejemplo

|| input
5
0
|| output
5
0
5
|| end

# Límites

$0 < A, B < 10$.

# Soluciones

Si leíste rápido el problema, tal vez no te diste cuenta de que esta vez no estamos pidiendo
la suma de los números, sino la resta. Aún peor, nuestro código de la suma también funciona en
el caso de ejemplo, porque mañosamente nos dieron $B = 0$. Esto es muy común en los ejemplos,
¡ten cuidado de no caer en la trampa!

Antes de mandar el código correcto, manda exactamente el que te dio `Aceptado` en $A+B$.
Verás que no recibes todos los puntos, sino que tu veredicto es `Respuesta parcialmente correcta`.
Como discutimos en el módulo anterior, eso quiere decir que contestamos bien en algunos casos secretos
y mal en otros. En este caso, contestamos bien cuando $B = 0$, pero mal en los demás casos.

Intenta ahora cambiar el cálculo para imprimir la resta y observa cómo ahora recibes 100 puntos.

Con este ejemplo aprendimos que aunque nuestro código funcione en el caso de ejemplo,
omegaUp tiene sus propios ***casos de prueba secretos***, que son los que usa para dar el veredicto.
