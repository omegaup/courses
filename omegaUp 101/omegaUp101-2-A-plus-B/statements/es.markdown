Antes que nada, es necesario que aprendas a mandar soluciones para un problema.
Para poder resolver un problema, deberás leer algunos datos de entrada de teclado (`stdin`)
e imprimir en pantalla (`stdout`) otros datos de salida.

La especificación de que datos leer y que datos imprimir vendrá descrita en la redacción de cada problema.

Es importante que recuerdes que **tu programa será evaluado con muchos datos de entrada**,
que son secretos y distintos a los ejemplos. Si tu programa funciona bien con los datos que se muestran de ejemplo
pero no recibes todos los puntos posibles, quiere decir que está fallando en un caso de prueba secreto que
no estás considerando.

Tu programa será evaluado automáticamente, **NO** por una persona.
Por ello, **abstente de imprimir o leer cualquier otra cosa que NO esté especificada en el problema**,
de lo contrario, tu solución será calificada como errónea por el juez.
En particular, ***no imprimas preguntas para el usuario***, como `Introduce el número A:` o `La respuesta es:`.

¡Ahora, resolvamos nuestro primer problema!

# Problema

Dados dos números enteros, $A$ y $B$, escribe un programa que calcule el resultado de $A + B$.

# Entrada

Dos líneas con un entero en cada una, $A$ en la primera y $B$ en la segunda.

# Salida

Tres líneas. En la primera línea, $A$, en la segunda, $B$, y en la tercera, $A + B$.

# Ejemplo

|| input
5
2
|| output
5
2
7
|| end

Recuerda que el ejemplo anterior es sólo eso: un ejemplo. El juez va a probar tu código con
***diferentes valores secretos*** de $A$ y $B$, con los que determinará tu veredicto.
  
# Límites

Aunque los casos de prueba son secretos, los problemas tienen límites, para que puedas saber qué
puedes o no asumir acerca de la entrada. Si tu programa está fallando, revisa la sección de límites
para saber si no estás olvidando algo.

Para este problema, puedes asumir con toda seguridad que $0 < A, B < 10$.

# Soluciones

A continuación te presentamos la solución a este problema en C, C++ y Java.
(Próximamente agregaremos nuevos lenguajes.)

Elige un lenguaje y asegúrate de que entiendas qué está haciendo el código.
Cuando estés listo, ve al final de esta página y selecciona `Nuevo envío`.
Selecciona tu lenguaje, pega el código en la caja de texto, y confirma tu envío.

## Lenguaje C

    #include <stdio.h>
    
    int main() {
        int a, b;
        scanf("%d%d", &a, &b);
        printf("%d\n", a);
        printf("%d\n", b);
        printf("%d\n", a + b);
        return 0;
    }

## Lenguaje C++

    #include <iostream>
    using namespace std;
    
    int main() {
        int a, b;
        cin >> a >> b;
        cout << a << endl;
        cout << b << endl;
        cout << a + b << endl;
        return 0;
    }

## Lenguaje Java

    import java.util.*;
    
    public class Main {
        public static void main(String args[]) {
            Scanner in = new Scanner(System.in);
            int a = in.nextInt();
            int b = in.nextInt();
            System.out.println(a);
            System.out.println(b);
            System.out.println(a + b);
        }
    }

¿Listo? Pega tu código en la parte de abajo, envíalo y espera la respuesta del juez.

¿Funcionó? Si sí, ¡felicidades, acabas de resolver tu primer problema en omegaUp!
Si no, no te preocupes y checa lo siguiente:

* ¿Copiaste el código entero? Fíjate que no hayas copiado de más o de menos.
* Asegúrate de que no estés escribiendo algo como `La suma es:` antes de la respuesta.
* Tal vez elegiste el lenguaje incorrecto por error.
