# C.F.FI
https://github.com/mikefuentesuax/C.F.FI.git

Estructuras de Datos
Mauricio Murillo 155661

Ejercicio 1

1)En relación al estado de un objeto, para preservar el principio de encapsulación:

a) Los atributos de nuestra clase deben permanecer públicos, para permitir un acceso
total a la información que almacenamos en los objetos. Sin embargo, aquellos
métodos que realicen operaciones internas (y no deban ser utilizados), deben
establecerse como privados.

b) Debemos establecer la visibilidad más restrictiva (por ejemplo, privada) en los atributos
de una clase. Así, cualquier software que utilice nuestro objeto, sólo accederá al
estado de los objetos mediante los métodos que le hayamos permitido utilizar.ç

Respuesta: b)

2) Los métodos de una clase no pueden devolver objetos:
   
a) Verdadero
b) Falso

Respuesta: b)

3) ¿Cuál de las siguientes características de la programación orientada a objetos está
relacionada con la reutilización de código?

a) Abstracción
b) Herencia

Respuesta: b)

4) El tiempo de acceso a un dato en una lista de tipo LinkedList es en el mejor de los casos de:

a) O(n)
b) O(1

Respouesta: b)

5) Un algoritmo de ordenación que implemente el método de inserción se basa en la idea de ir
seleccionando el número correspondiente en la lista desordenada que se va a insertar en la
posición última de la lista ordenada:

a) Verdadero
b) Falso

Respuesta: b)


Ejercicio 2

1) Debemos diseñar un programa para un sistema de dispositivos portables aplicados
 en telemedicina que contienen una cantidad de memoria muy limitada ( 4 KB).
Tenemos diferentes alternativas que hacen diferente uso de la computación y la memoria.

a) La primera de ellas t iene un orden de complejidad computacional O( n) y va a
ocupar un espacio S( 1 ).

b) La segunda de ellas tiene un orden de complejidad computacional O( 1 ) pero
lo hace mediante una técnica denominada para guardar muchos datos en
memoria, por lo que ocupa un espacio de S( N 2 ).

c) La tercera y última tiene una complejidad computacional de O( log 2 ( N)) y
ocupa un poco más de espacio en memoria S( O( log 2 ( N))).
Debemos analizar la eficiencia computacional de las mismas y justificar la elección.
Teniendo en cuenta que el programa va a tener un tamaño de datos de entrada de
64 KB

Respuesta: c)

2) Explica las diferencias entre una tabla Hash y un árbol. ¿ Cuándo conviene utilizar
cada una de estas estructuras? Justifique su respuesta y analice todas las
posibles operaciones a realizar por las estructuras. No redacte el orden tal y
como puede ver en los apuntes, razónelo con sus propias palabras y argumentos.

Respouesta: Las tablas hash son rápidas para buscar por clave y son eficientes en términos de tiempo para inserciones,
búsquedas y eliminaciones, pero pueden tener colisiones. 
Los árboles son ideales para mantener datos ordenados y realizar operaciones como búsquedas y eliminaciones eficientes, 
especialmente en conjuntos de datos pequeños.

3) Explica las diferencias entre un a pila y una cola. ¿ Cuándo conviene utilizar cada
una de estas estructuras? ¿ Cuál es el orden de complejidad computacional de
estas estructuras? No redacte el orden tal y como puede ver en los apuntes,
razónelo con sus propias palabras y argumentos.

Respuesta: Una pila sigue el principio último en entrar, primero en salir y se usa cuando necesitas acceso rápido a elementos recientes,
como en historiales de navegación. Su complejidad es constante para agregar o quitar elementos.
Una cola sigue el principio primero en entrar, primero en salir y se usa cuando necesitas acceso rápido a elementos antiguos, 
como en tareas de procesamiento por lotes. También tiene una complejidad constante para agregar o quitar elementos. 
La elección entre ellas depende de si necesitas un comportamiento LIFO o FIFO y de cómo quieras acceder a los datos.

4) Explica el método de ordenación denominado inserción y describe las
iteraciones sobre el siguiente conjunto de datos:

Respuesta: El método de ordenación por inserción es como organizar cartas en tu mano. 
Comienzas con el segundo elemento y lo comparas con los anteriores, 
moviéndolo hacia la izquierda hasta su lugar correcto. 
Para el conjunto de datos \[5, 3, 8, 4, 2, 7, 1, 6\], empezamos con 3, lo comparamos con 5 y se mueve. Luego, el 8 se deja en su lugar. 
El 4 se coloca antes de 5 y después de 3, y así sucesivamente hasta que todos los números estén en orden de menor a mayor.

5) Dadas dos funciones y su número de operaciones:
A = 1024 n
B = 16 n 3
Calcular a partir de qué tamaño de entrada n A es más eficiente que B.

Respuesta: Para saber cuándo la función  A  es más eficiente que la función  B, comparamos sus expresiones. 
Si  A  es menor que  B , entonces  A es más eficiente. 
Al resolver la desigualdad  1024n < 16n^3, encontramos que  n  debe ser mayor que 8 para que  A sea más eficiente que  B .
Entonces, para tamaños de entrada  n  mayores que 8,  A  es más eficiente.

