## Objetivo
Modificar al programa init para imprimir un mensaje de bienvenida.
Modificar al programa sh para ejecutar el programa anterior.

## Herramientas

make

gcc

git

## Conceptos

1) Proceso 

+ Instancia de un programa.
+ Está compuesto de 3 partes
++ stack: variables y funciones -> Está limitado, crece de arriba hacia abajo. Stack Overflow.
++ heap: área de memoria dinámica -> RAM + SWAP
++ código: segmentado, ie es una parte

+ Tiene estados

+ Se crean mediante dos llamadas a sistema
++ fork: clone
++ exec: cambia código

+ Hay un proceso padre
++ init

## Qué aprendí

Aprendí a modificar las partes necesarias de un sistema operativo para instanciar un programa desde la terminal. También aprendí como es que un programa se ejecuta paso a paso desde que inserta variables en la pila de ejecución hasta cuando se hacen llamadas a sistema con form y exec. En la práctica modificamos parte del código del sistema para imprimir un mensaje en el sistema operativo pero a partir de ahí podríamos hacer cosas más interesantes.

## URL del commit
https://github.com/jjnorris31/sistemas-o/commit/f0b679cc3cf283d6ac68affcfaec102eea3160b0
