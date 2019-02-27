## Objetivo
Modificar el programa sh.c

## Herramientas
git
make
gcc

## Conceptos
1) Como se crean nuevos procesos
+ Un programa padre (sh.c) ejecuta la llamada a sistema fork
+ La llamada a sistema fork clona al proceso padre
+ El proceso manda a llamar a exec para ejecutar otro codigo


## Que aprendi:
Como es que el cmd lee los comandos y los procesan, ademas de como es la jerarquia de procesos padres y proceoss hijos
al igual que como se crean los procesos.



## Url del commit:

https://github.com/M8858X/SlimeOS/commit/bea961342ec61e9185eb7fdf82e68ec49fddd099


## Como se relaciona con los conceptos anteriores

Se relaciona con la llamadas a sistemas ya que al llamar la instruccion que se mando a llamar antes se vuelve hacer la misma llamada
a sistema.



