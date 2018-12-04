# Simulación NFA
Simulación de autómatas finitos no deterministas codificada en c++ para la signatura de Computabilidad y Algoritmia en la Universidad de La Laguna.

Los pasos necesarios para la compilación y ejecución del programa son los siguientes:
``` r
 $ cd \src
 $ make
 $ ./NFA
```
El formato necesario de los NFA es el siguiente :

```
4               //Número de estados del DFA
0               //Estado inicial
0 0 2 a 1 b 3   //Estado partida / Aceptación-Noaceptación / Estado / Símbolo con el que transita | Estado / Símbolo con el que transita
1 1 2 a 1 b 2
2 1 2 a 1 b 3
3 0 2 a 3 b 3
```
Al tratarse de autómatas finitos no deterministas se aceptan en algunos casos el carácter vacío o epsilon, el cual es representado con '~',
para algunas transiciones.
Por otra parte en la carpeta *html* encontramos la documentación generada con la herramienta [Doxygen](http://www.doxygen.nl/).

*Nota*: el código puede contener fallos, si detectas alguno, no dudes en comunicármelo para corregirlo.
