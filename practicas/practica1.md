# PRACTICA 1 INTRO A GIT

Si quieres mas ayuda mira la [lista de comandos](/comandos/listado.md)


1 Crear repositorio

  - [¿Como organizar un repositorio?](/introduccion/organizacion_repositorio.md)

  ``` bash
  git init
  ```

2 Crea un fichero en el repositorio

  - Un archivo txt vale.

3 Añade el fichero al repositorio
  ``` bash
  git add .
  git status
  ```

4 Haz un commit para controlar el cambio.
  ``` bash
  git commit - m "mensaje"
  git status
  git log 
  ```

5 repite los pasos 2,3,4 un par de veces añadiendo nuevos ficheros

6 haz cambios en los ficheros y luego ejecuta
  ``` bash
  git add .
  git commit -m "mensaje"
  git log
  ```

7 Prueba a volver a una version anterior del repositorio.

  - comprueba el contenido de los ficheros
  ``` bash
  git log
  git checkout <commit hash>
  ```

8 Vamos a hacer una rama
  - vuelve a la rama main.
  ``` bash
  git checkout main
  ```  
  - Crea una nueva rama y cambiate a ella
  ``` bash
  git branch <nombre-rama-nueva>

  git checkout <nombre-rama-nueva>

  # tambien se puede hacer

  git branch -b <nombre-rama-nueva>
  ```  

9 Crea una carpeta nueva con el nombre de la rama, crea ficheros dentro y repite los pasos 2,3,4

   - ejecuta git log con la opcion graph
  ``` bash
  git log --graph
  ```  







