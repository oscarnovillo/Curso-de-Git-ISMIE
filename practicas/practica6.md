# Proyectos

La parte de proyectos sirve para llevar el mantenimiento de un proyecto ágil.

Es una base de datos de una tabla con un objeto.

Hay distintas vistas configurables.

Si los asocias a uno o varios repositorios se pueden convertir las tareas en issues

Encaje de metodologías ágiles y en especial scrum con sprints, historias de usuarios(Que) y tareas(Como).




1. Crea un proyecto nuevo.

2. Añade los siguientes campos al objeto.
    - Type: que podrá ser user story, o task, de tipo single select.
    - Estimate: el tiempo estimado en horas de las task o los puntos de historias. de tipo numerico.
    - Sprints: las iteraciones del proyecto, de tipo iteracion.

3. Crea una primera vista, tipo tabla para el backlog.
    - Crea varias historias de usuario, ponles el tipo adecuado.
    - Conviertelas en issues en un repositorio
    - Filtra la vista para que sea un backlog de user stories
    - Filtra para que solo se vean las user stories que no esten en estado done

4. Crea sub issiues, que seran las task de las user stories
    - Al crear subissues hay que tener cuidado de poner el proyecto al que pertenecen para que se vean.
    

5. Crea una vista tipo tabla como la anterior pero para ver las task.
    - Agrupalas por parent issue.
    

6. Crea un vistas tipo Board para el current sprint.
    - Pon las user stories y task en el primer sprint.
    - Añade los campos parent-issue, type y sub progress issue para que se vean.
    - Haz un slice por el type.

7. Crea una vistas tipo Roadmap para la planificación.
    - Filtra por las task.
    - Agrupa por parent issue
    - Pon los date fields como start date y end date.

