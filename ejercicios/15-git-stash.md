# Objetivo

Generar un stash de un conjunto de cambios no publicados y restaurarlo.

# Descripción.

El comando `git stash` se utiliza para guardar temporalmente los cambios no confirmados en tu área de trabajo, permitiéndote trabajar en otra cosa sin perder tu progreso actual. Es útil cuando necesitas cambiar de contexto rápidamente y no quieres hacer un commit de cambios incompletos.

### Cómo funciona

Cuando ejecutas `git stash`, Git guarda el estado actual de tu directorio de trabajo y el índice (staging area) en un nuevo stash y luego restaura el directorio de trabajo al último commit. Esto te permite tener un área de trabajo limpia sin perder tus cambios.


### Consideraciones

Los stashes son útiles para guardar cambios temporales, pero no deben ser utilizados como una solución a largo plazo para el manejo de cambios.
Puedes nombrar tus stashes para identificarlos fácilmente usando `git stash save "mensaje"`.
Este comando es una herramienta poderosa para manejar cambios temporales y mantener un flujo de trabajo eficiente.

# Procedimiento.

1. Hacer un conjunto de modificaciones sin dar commit a los cambios.

1. Crear un stash y nombrarlo.

1. Modificar otro conjunto de archivos y guardarlo y hacer commit.

1. Restaurar el stash previamente creado.

