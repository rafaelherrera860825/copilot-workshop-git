# Objetivo

Modificar una rama desde dos puntos diferentes para demostar el comportamiento de git pull y git fetch.

# Descripción.

## Diferencia entre git fetch y git pull

### git fetch

El comando `git fetch` se utiliza para descargar los objetos y referencias desde otro repositorio. Este comando no fusiona ni modifica el estado de trabajo actual del repositorio local. Simplemente actualiza las referencias remotas, permitiendo que el usuario vea los cambios que se han realizado en el repositorio remoto sin aplicarlos a su rama de trabajo actual.

### git pull


El comando `git pull` se utiliza para actualizar el repositorio local con los cambios del repositorio remoto y fusionarlos en la rama de trabajo actual. Es una combinación de dos comandos: git fetch y git merge. Primero, descarga los objetos y referencias desde el repositorio remoto, y luego fusiona esos cambios en la rama actual.

# Procedimiento.

1. Modificar una rama desde la interface web de git pull y generar los commits y push.

1. Regresar a visual studio code y aplicar los comandos de git fetch y git pull.

