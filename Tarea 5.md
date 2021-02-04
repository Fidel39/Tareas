# Tarea 5

### 1. Explica que hace el método main.
    
Genera 2 arrays y los completa con numeros aleatorios.


 ### 2. Explica como funciona el primer método de ordenacion de los números.
 
 Con este  método, se utiliza una variable J para recorrer todo el vector. Lo que ocurre en el primer recorrido es que se van rotando todas las cifras por la posicion 0. Una vez pasadas todas inicia la segunda vuelta del bucle superior , para poder poner los numeros en orden dentro del vector.
 
 
 ### 3. Eplica como funciona el otro metodo de ordenacion.
 
 Este segundo metodo es mas rapido que el primero. En este lo que se utiliza es otro vector auxiliar para poder localizar los numeros, es decir, si tus cifras son; 1 , 2, 3, 4, y 5, lo que ocurre es que se comparan todos los indices del vector para saber que numero es. Este vector tiene todos los indices con un 0, haciendo que cuando en la comparativa se encuentre una cifra, este sumara 1 en ese indice consiguiendo asi saber el orden de los numeros de una manera mucho mas rapida. 