# PRACTICA 1
---------------------------------------
## Ejercicio 1
  * Implementar un programa usando MPI, que imprima por salida estándar:
  
        *Hola mundo, soy el proceso X de un total de Y.*
        
    Cuando el número total de tareas es Y=50 y X un rango de 0 a 49.
  * Calcular el tiempo de ejecución de cada proceso y realizar una gráfica explicando los
    resultados a medida que aumenta el número de procesos.

## Ejercicio 2
  * Implementar un programa usando MPI, donde el proceso 0 toma un dato del usuario y lo
envía al resto de nodos en anillo. Esto es, el proceso i recibe de i-1 y transmite el dato a i+1,
hasta que el dato alcanza el último nodo.

## Ejercicio 3
  * Modificar la implementación del ejercicio 2 para que el dato introducido por el usuario dé
tantas vueltas como este indique en el anillo.
  * ¿Qué desventaja se aprecia en este tipo de comunicaciones punto a punto a medida que
aumentan el número de procesos requeridos? Razonar la respuesta.
  * ¿Cómo podría mejorar el sistema y su implementación? Razonar la respuesta.
