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

# URL del commit
