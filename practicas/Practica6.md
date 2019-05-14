# Objetivo:
Investigar y practica hilos.

# Herramientas:
gcc
git

# Conceptos:
+ Hilos
  + Proceso ligero
  + Solo tiene un stack y el código y el heap lo comparte con el proceso principal.
  + Si el proceso principal termina, los hilos terminan.

+ Lock:
  + Mecanismo de sincronización
  + Variable global que soporta dos operaciones:
    + Lock, el primer hilo que hace lock se adueña del lock, el resto queda esperando
    + Unlock, el hilo dueño del lock lo libera.
  + Ayuda para resolver el problema de la sección critica.
  
+ Semaforos:
  + Mecanismo de sincronización.
  + Variable global que tiene un valor inicial mayor o igual a 0. Soporta dos operaciones.
    + wait/decrease Si es mayor a 0 decrementa y continua, si es igual a 0 se suspende.
    + post/increase. Incrementa el valor del semaforo en uno.
  + Para asignar recursos.
+ Problemas de sincronización.
  + Condición de carrera: Ocurre cuando el resultado depende del orden en que se ejecutan los hilos.
  + Deadlock: Cuando dos o mas hilos estan esperando por un recurso que no se libera.
  + Productor/Consumidor: Ocurre cuando los datos se pueden sobre-escribir.
  

# Url del commit:
https://github.com/mmaxBA/SlimeOS/commit/2861e60c3fd0a4b47c3f24c9b5abcdcff753a714
https://github.com/mmaxBA/SlimeOS/commit/bd513168185c1053865e909e6a670090fbde65a9


# Que aprendi:  
Apredi lo basico sobre hilos, desde como hacerlos a como manejarlos, pueden servir para distintas cosas y distintas situaciones. Tambien aprendi los distintos problemas que pueden llevar el usar los hilos, un ejemplo es el famoso Deadlock el cual hace que varios hilos esen esperando por recursos que nunca van a ser liberados.
