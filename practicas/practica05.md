# Objetivo
Hacer un spike sobre hilos, semáforos y locks. 

# Herramientas
+ git
+ gcc

# Conceptos:

+ Hilos
  + Es un proceso ligero que solo consta de un stack. Y el código y el heap los comparte con el proceso principal.
  + Pueden ejecutar funciones diferentes.
  
+ Semáforos:
  + Es una variable global
  + Soporta dos operaciones.
    ++ Incrementar (sem_post) siempre incrementa en uno.
    ++ Decrementar (sem_wait) si el valor del semáforo es mayor que 0 decremente si es igual a cero se suspende.
  + Controlar acceso a recursos.
  
+ Lock:
  + Es una variable global.
  + Soporta dos operaciones.
    ++ lock (bloqueo) si el lock ya está tomado el hilo/proceso se suspende.
    ++ unlock (desbloquea) liberar el lock.
  + Secciones críticas
  
 # Qué aprendí:
 Para ejecutar varias cosas a la vez la opción más racional es crear un hilo, podemos crear la cantidad de hilos que queramos y una de las grandes ventajas de esto es que si por alguna razón un hilo modifica una variable todos los demás verán este cambio.
 
 Para evitar que dos hilos modifiquen la misma estructura se hizo el uso de un semáforo que es el encargado de dar acceso a un determinado recurso a sólo un proceso a la vez y se lo niega a los demás hasta que termine de usarse. 
 
 También noté que los hilos son mucho más ligeros que un proceso completo pero su programación suele ser más complicada y en ciertos aspectos bastante extraña. 

 # URL del commit:
 https://github.com/jjnorris31/sistemas-o/commit/6771a6de25adcae0fc9dd925a37ebed317f47221
