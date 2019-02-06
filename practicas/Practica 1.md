## Objetivo
Crear dos llamadas a sistema una para apagar y otra para reinicar.
Y crear sus respectivos programas.

## Herramientas
Git
Make
Gcc

## Conceptos
1) Llamada a sistema operativo
- La forma que el kernel (SO) da acceso al Hardware
- Se implementan mediante interrupciones de software, ie, la aplicacion se interrumpe para que el kernel se ejecute.

2) Modo Kernel
- Es bit/registro que activa el CPU para acceder al Hardware
- Solo hay un programa que se ejecuta con este bit, es el kernel

3) Interrupciones
- Es la forma que el Hardware interactua con el CPU

## Que aprendi:

Aprendi como realizar llamadas a l sistema, tambien que el Kernel es el unico que puede interactuar con el Hardware, esto para prevenir que
los comandos que se manden a ejecutar no dañen el hardware, es la primera barrera de proteccion del hardware por asi decirlo.

Aprendi como es que se manda apagar la maquina desde lineas de codigo y es cambiando el valor en una posicion de memoria. Esto puede apagar 
o reiniciar la maquina.

## Link del commit:

https://github.com/M8858X/SlimeOS/commit/69869b685cd966a79af84d8eb0063e5ee7a35d08

