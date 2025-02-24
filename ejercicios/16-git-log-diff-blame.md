# Objetivo

Explorar el comportamiento de los comandos git log, git diff y git blame.

# Descripción.

Los comandos `git log`, `git diff` y `git blame` son herramientas esenciales para la gestión y revisión del historial de cambios en un repositorio Git.

## git log

El comando `git log` muestra el historial de commits en el repositorio. Permite ver los mensajes de commit, las fechas y los autores de los cambios. Algunas opciones útiles incluyen:
- `git log --oneline`: Muestra cada commit en una sola línea.
- `git log --graph`: Muestra un gráfico de la rama del historial de commits.
- `git log -p`: Muestra los cambios introducidos en cada commit.

## git diff

El comando `git diff` muestra las diferencias entre commits, ramas, archivos, etc. Es útil para revisar los cambios antes de hacer un commit. Algunas opciones útiles incluyen:
- `git diff`: Muestra las diferencias entre el estado actual del repositorio y el último commit.
- `git diff <commit>`: Muestra las diferencias entre el estado actual y un commit específico.
- `git diff <branch1> <branch2>`: Muestra las diferencias entre dos ramas.

## git blame

El comando `git blame` muestra la información de autoría para cada línea de un archivo. Es útil para identificar quién realizó cambios específicos y cuándo. Algunas opciones útiles incluyen:
- `git blame <file>`: Muestra la información de autoría para cada línea del archivo especificado.
- `git blame -L <start>,<end> <file>`: Muestra la información de autoría para un rango específico de líneas en el archivo.

# Procedimiento.

1. Usando la terminal de visual studio code explorar el uso de estos tres comandos.

1. Hacer las mismas actividades con el plugin de source control de visual studio code.