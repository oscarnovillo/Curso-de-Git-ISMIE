# Conflictos en Github

Partimos de un repositorio en github con varios ficheros.

1. Clona el repositorio en dos carpetas diferentes para simular varias personas trabajando.
   - Crea varios repositorios con nombres de distintas personas. Ej, Maria,Pepe,Juan ...
   - Clona dentro de cada directorio. Tendrás una copia del repositorio por persona.

2. Cambia cada repositorio.
   - Crea en cada copia un fichero markdown con el nombre de cada persona, Maria.md, Pepe.md, Juan.md
   - Haz commit y push del fichero cambiado.

3. Haz un pull del repositorio en cada carpeta

4. Mas cambios en repositorio.
   - Haz primero un pull antes de cambiar nada.
   - cambia algo de los 3 ficheros md.
   - commit y push de los cambios.

5. Buscando el conflicto. 
   - En cada repositorio haz pull
   - En cada repositorio haz un cambio en el mismo fichero y haz un commit, pero NO un push.
   - Dentro del repositorio de Maria haz push.
   - Dentro del repositorio de Pepe haz un push.
      - Te pide hacer un pull antes porque el repositorio remoto tiene cambios que no estan en local
      - Al hacer pull es cuando se genera el conflicto.
      - Resuelvelo.






