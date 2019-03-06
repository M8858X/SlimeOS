# Objetivo:

Modificar el programa init para que muestre un programa de bienvinida.

## Herramientas
gcc

make

git

1) Proceso

+ Instancia de un programa.
+ Tiene tres partes:
  ++ Stack: variabes y las llamadas a funciones.
  ++ Heap: memoria dinamica.
  ++ Codigo
 
 + Se crea mediante dos llamadas a sistema:
  ++ Fork
  ++ Exec cambia codigo
  
 + Tiene un estado:
  ++ Corriendo
  ++ Durmiendo
  ++ Espera
  ++ Completado
  ++ Zombie
  
  2) Programa init:
  
  + Es el programa encargado de inicializar el SO para dejarlo listo para usarse
  + Es el unico proceso que crea el SO
  
  # Que aprendi:
  
  El funcionamiento del init y sobre los procesos, como cambia entre los distintos estados.
  
  # Url del commit:

https://github.com/M8858X/SlimeOS/commit/27025c1ecf798a9dcda23b1fa9d3f91c69432bbb

