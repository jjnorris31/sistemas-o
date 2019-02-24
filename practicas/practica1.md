## Objetivo
Crear dos llamadas a sistema con su respectivos comandos para apagar y reiniciar.

## Herramientas

make

gcc

git

## Conceptos

1) Llamadas a sistema

+ Se usan para acceder a hw
+ Desde el comando son una interrupción
+ Desde el kernel utilizan el código del hw específico.

2) Modo kernel
+ Es el bit para acceder al hw
+Se prende cuando se ejecuta el kernel

3) Interrupciones
+ Como el hw interactua

4) Interrupciones vía software (trap)
+ Software comunicar con el kernel, SF->CPU->KERNEL

## Qué aprendí
Aprendí a crear todos los scripts necesarios así como insertar las líneas correspondientes para crear una llamada a sistema válida. Se presentó un caso práctico de una interrupción y como el sistema responde a ellas así como modificar la tabla de registro para ejecutar un código hw.


## URL del commit:

https://github.com/jjnorris31/sistemas-o/commit/c0689cdfbfdbe99b7bbb439222b66656fe8ceb4f
