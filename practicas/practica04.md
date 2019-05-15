# Objetivo
Hacer un spike sobre IPC: señales, fork/exec, memoria compartida y archivos mapeados a memoria

# Herramientas
+ git
+ gcc

# Conceptos
+ Comunicación entre procesos.

+ Señales

  + Es un ipc, consta de dos procesos, emisor y receptor.
  El emisor manda una señal y el receptos deja de hacer lo que esta haciendo y ejecuta el código de la señal.
  + Existen varias señales, para listarlas puedo usar el comando kill -l
  
 + Memoria compartida
    + Se crea un bloque de memoria, el bloque de memoria tiene un key
    + Cualquier proceso con el key puede conectar al bloque.
    + El bloque de memoria persiste hasta que se borre mediante un comando o se reinicie la computadora.
    
+ Archivos mapeados a memoria.
    + Es un bloque de memoria compartida que está asociado a un archivo.
    + Los cambios en el bloque se guardan automáticamente.
    

+ Estados de un proceso

# Qué aprendí

Utilizando información de la guía de Unix IPC de Beej's logramos modificar ciertas líneas de código para cambiar el estado de un proceso y que estos compartieran memoria. También se utilizó el concepto de señal que en lo personal para mí era nuevo y aprendí como es que estos son la forma en que los procesos se comunican, estos son eventos asíncronos que un proceso le envía a otro y aunque haya un receptor este puede hacer lo que le venga en gana con esta señal. 

Para efectos de la práctica también vimos de qué va la memoria compartida y esto sirve para que los procesos vivan de alguna manera en una zona de memoria en común y de esta manera puedan pasarse datos de manera directa o bien, para comunicarse. Esto se logra obteniendo la key y todos los procesos que compartan esta estarán en la misma zona de memoria. 

# URL del commit
https://github.com/jjnorris31/sistemas-o/commit/ebaaa03e3e0d6a620d34d2f9f40f731023674e5f
