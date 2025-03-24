# Practica 2 Conflictos

Vamos a ver el termino conflicto en un repositorio

Git controla los cambios de un fichero de texto, linea por linea.

Es capaz de mezclar cambios siempre que no se haya tocado la misma linea.

Un conflicto se da cuando un cambio no se puede mezclar porque se ha cambiado algo de la misma linea

Usando el repositorio de la practica anterior con varias ramas.

1. Vete a la rama main
    - haz un merge de la rama creada antes en la rama main.
    - verifica el contenido de la rama main.
    - haz un fichero nuevo llamado conflicto.txt con una linea que sea "desde la rama main"
    - commit del cambio


2. Vete a la rama nueva
    - haz un merge de la rama main en la rama nueva
    - verifica la existencia del fichero conflicto.txt
    - añade una linea al fichero conflicto.txt con el contenido "desde la rama nueva"
    - commit del cambio

3. Vete a la rama main
    - haz un merge de la rama nueva.
    - verifica el contenido del fichero conflicto.txt
    - mete una nueva linea en el fichero con el texto "nueva linea desde la rama main"
    - commit de los cambios

4. Vete a la rama nueva 
    - haz un cambio en el archivo, cambia el contenido de la primera linea que quedaría "desde la rama main, y ahora la nueva"
    - haz un commit del cambio
    - haz un merge de la rama main en la rama nueva
    - Soluciona el conflicto
