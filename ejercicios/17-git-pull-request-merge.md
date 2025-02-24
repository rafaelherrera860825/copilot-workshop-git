# Objetivo

Crear un pull request para cada rama de trabajo, explorar las propiedades de los repositorios.

# Descripción

En GitHub, hay varias estrategias para combinar cambios de una rama a otra: merge, merge squash y rebase. Cada una tiene sus propias características y usos.

## Merge

El comando `merge` combina el historial de dos ramas, creando un nuevo commit de merge. Este método preserva el historial completo de ambas ramas, lo que puede ser útil para rastrear la evolución de los cambios. Sin embargo, puede resultar en un historial de commits más complejo.

## Merge Squash

El comando `merge --squash` combina los cambios de una rama en un solo commit. Esto simplifica el historial de commits al consolidar todos los cambios en un único commit. Es útil para mantener un historial limpio, pero se pierde la granularidad de los commits individuales.

## Rebase

El comando `rebase` mueve o combina una secuencia de commits a una nueva base commit. Esto reescribe el historial de commits, creando un historial lineal. Es útil para mantener un historial limpio y lineal, pero puede ser complicado si hay conflictos durante el rebase.

# Procedimiento.

1. Crear un pull request para cada rama de trabajo.

1. Explorar las propiedades del pull request en la interface de github.

1. Ejecutar la opción de merge, merge squash y rebase para cada pull request diferente.

1. hacer fetch y pull de la rama main en el repositorio

1. Explorar el grafico de commits en visual studio code