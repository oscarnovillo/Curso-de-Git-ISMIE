# Introduccion <img src="/assets/github.png" width="58" height="56"/>

Git es un [VCS](vcs.md), sistema de control de versiones, y como su nombre indica sirve para llevar un control de todos los cambios que se quieran. 


Diferenciar entre git y [github](github.md), son cosas distintas.


Que nos aporta

<table border=1>
<tr>
<td>
    hola
</td>
</tr>
</table>

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

Instalación

