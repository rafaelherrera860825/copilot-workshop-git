# Objetivo

Trabajar con las ramas creadas, simulando cambios para comprobar la funcionalidad de git amend commit, add, push.

# Descripción.

## Git Amend Commit

El comando `git commit --amend` se utiliza para modificar el último commit en la rama actual. Este comando es útil cuando necesitas corregir un mensaje de commit, agregar archivos olvidados o realizar cambios menores sin crear un nuevo commit. Aquí hay un ejemplo de cómo usarlo:

### Consideraciones

El comando `git commit --amend` reescribe el historial de commits, por lo que debes usarlo con precaución, especialmente si ya has compartido el commit con otros colaboradores.

Si solo necesitas cambiar el mensaje del commit, puedes ejecutar `git commit --amend` sin añadir archivos al área de preparación.

Este comando es una herramienta poderosa para mantener un historial de commits limpio y organizado.

## Git checkout

El comando `git checkout` se utiliza para cambiar de rama o restaurar archivos en el árbol de trabajo. Algunas opciones útiles incluyen:
- `git checkout <branch>`: Cambia a la rama especificada.
- `git checkout -b <new-branch>`: Crea y cambia a una nueva rama.
- `git checkout <commit> -- <file>`: Restaura un archivo específico a un estado anterior.

### Consideraciones

El comando `git checkout` es muy versátil y puede ser utilizado para múltiples propósitos, como cambiar de contexto de trabajo o recuperar versiones anteriores de archivos.

# Procedimiento.

1. Generar cambios en los archivos de una rama.

1. Realizar un amend commit.

1. Hacer un revert de un archivo.

1. Hacer push de los cambios al repositorio.