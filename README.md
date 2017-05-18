# maventercera

Hemos creado un proyecto maven con todas sus subcarpetas o directorios, en el que e añadido la clase math.java y person.java que va a colgar de
src/main/java/proyectoSalatti/proyectoSalatti,para el perfecto funcionamiento de estas clases.

En cambio en la carpeta src/test/java/proyectoSalatti/proyectoSalatti,ahi meteremos los test que verificaran el funcionamiento de
las clases anteriores y que todo este correcto.
Estas clases son MathTest.java y TestPerson.java

Seguidamente compilaremos con el comando:
mvn compile(no debe de dar error si las clases no tienen fallos) desde la carpeta raiz del proyecto.

Tras su compilacion se crara una carpeta target con los .class de las clases anteriores que nos permitiran su uso.
para verificar si testea correctamente para ver que lo que hay dentro del proyecto es correcto utilizaremos:
mvn test desde la carpeta raiz del proyecto.
