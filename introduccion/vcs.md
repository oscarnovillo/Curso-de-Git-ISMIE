# Que es un VCS

Un VCS es un sistema que se usa para llevar un control de todos los cambios que se hagan en un proyecto de programación.

En general tiene su valor en proyectos cuyo contenido sean ficheros de texto.

Su mayor valor viene en el trabajo en grupo.

Sin un VCS el manejo de los cambios de un proyecto se combierte en un lio de carpetas y es inmanejable según suben los participantes en el proyecto y la complejidad del mismo.

![Folder mess](/assets/sin-vcs-2.png)


# Tipos

Los diferencia donde se guarden los cambios, si se guardan en local todos los cambios o sólo se guardan en remoto

![Arquitectura](/assets/arquitectura%20VCS.PNG)



# Historia de vida en Git

Este es un ejemplo de cómo representar la vida de una persona usando Git y Mermaid.

```mermaid
gitGraph
    commit id: "Nacimiento"
    commit id: "Primer día de escuela" tag: "v1.0.0"
    branch primer-amor
    checkout primer-amor
    commit id: "Primer cita"
    commit id: "Primer beso"
    commit id: "Ruptura"
    checkout main
    merge primer-amor
    commit id: "Graduación"
    commit id: "Primer trabajo"
    branch matrimonio
    checkout matrimonio
    commit id: "Boda"
    commit id: "Primer hijo"
    commit id: "Segundo hijo"
    checkout main
    merge matrimonio
    commit id: "Cambio de carrera"
    commit id: "Viaje importante"
    branch duelo
    checkout duelo
    commit id: "Funeral"
    commit id: "Superación del duelo"
    checkout main
    merge duelo
    commit id: "Jubilación"
    commit id: "Últimos días"
```