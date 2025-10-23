# Investigación

# ¿Qué es conventional commit?

Es una convención para poder escribir mesnajes en commits en Git de una forma **estructurada y estarendizada**.

## Su objetivo 

*Es que el historial de commits sea **legible, automatizada y consistente** lo que esto facilita a las tareas como generar changelogs (**es un docmuento que lista todas las modificaciones realizadas en un proyecto**) ersionar automáticamente (semver **es un sistema claro y predecible para numerar versiones según el impacto del cambio.** ), y entender qué tipo de cambios se realizaron.*

### Partes Explicadas

* <tipo> → indica el tipo de cambio. Ejemplos comunes:

* feat: se agregó una nueva funcionalidad.

* fix: se corrigió un error.

* docs: cambios en documentación.

* style: cambios de formato (espacios, comas, etc.) sin alterar el código.

* refactor: refactorización del código sin cambiar su comportamiento.

* test: se agregaron o modificaron pruebas.

* chore: tareas de mantenimiento (build, dependencias, etc.).

* [scope] (opcional) → especifica el área del código afectada.
* Ejemplo: feat(ui): agregar botón de login

* <descripción> → resumen breve del cambio, en presente e imperativo.

# Por que es importante que lo use

*Es importante ya que esto aporta claridad, automtización y control al desarrollo. En especial cuando trabajas en equipo o en proyecto que necesitan tiempo* 
