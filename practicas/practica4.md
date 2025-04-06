
# Conceptos Extra Git

1. Fichero gitignore
  - ficheros que no se controlan en github
  - No subir compilados y ficheros generados
  - *.class, pychache dir, ficheros generados por ide.
  - ficheros de configuración local
  - ficheros sensibles, secretos...
  - El fichero se puede coger de una [plantilla](https://www.toptal.com/developers/gitignore)


2. Crea un Tag, súbelo a github.
  - Comprueba en github que se puede bajar un zip con ese tag

3. Crear un gist
  - Instala una extension en el IDE. En vscode, GistPad
  - Selecciona una parte de un fichero y añade el gist
  - Pega un gist en un fichero.

4. Otras formas de acceder a repositorios.
  - bajar el zip del código. No bajas los cambios.
  - bajar una carpeta de un repositorio, accediendo a [herramienta bajar directorio](https://download-directory.github.io/)

5. Trabajo con ficheros en working directory.
  - Parte de un repositorio con una rama main y otra develop
  - Checkout de la rama develop
  - Haz cambios en ficheros pero no hagas commit
  - Ahora surge un problema en main y hay que arreglarlo, un hotfix que afecta a producción.
  - Hay dos opciones:
    1. Solución con Stash
      - Haz un stash de los cambios
      - Checkout de la rama main
      - Haz los cambios necesarios en rama main, commit y push
      - Checkout de la rama develop
      - Haz un pop del stash, ya puedes seguir trabajando.
    2. Solución con Worktrees.
      - Con worktrees puedes editar varias ramas a la vez.
      - Si quieres trabajar en main puedes hacer un worktree de main y lo editas.
      - Al acabar se puede borrar el worktree de main.
      - Entre media puedes seguir con tus cambios en develop sin problemas.
