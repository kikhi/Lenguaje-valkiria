# Lenguaje valkiria
Este es un lenguaje de programacion desarrollado en la materia de lenguajes y automatas el cual tiene como objetivo tener codigo desarrollado por bloques

### Para empesar 

  - Este lenguaje esta desarrollado con javacc
  - Para su desarrollo fue requerido el [SDK de java](https://www.oracle.com/java/technologies/downloads/)

### Tutorial

 Para la compilacion se requieren los siguientes comandos:
 
  - Primero compilamos el jj
 ```
    javacc compilador.jj
 ```
 
  - Despues el todos los que resultaron del anterior
```
    javac *.java
```

  - Finalmente para testear una estructura de codigo de un txt con el compilador utilizamos el siguiente
```
    java compilador < test.txt
```
Tomar en cuenta que el txt es creado como si fuera el codigo que el programador genera y el compilador es el resultado de las primeras compilaciones
