# Objetivo

Crear los archivos de configuración de github para la estructura del proyecto.

# Descripción

El archivo `CODEOWNERS` es un archivo de configuración utilizado por GitHub para definir los responsables de diferentes partes del código en un repositorio. Este archivo permite especificar qué equipos o individuos son responsables de revisar y aprobar los cambios en archivos o directorios específicos. Al definir propietarios claros para cada parte del proyecto, se mejora la gestión del código y se asegura que las personas adecuadas revisen las modificaciones.

El archivo `CODEOWNERS` se coloca en la raíz del repositorio o en el directorio `.github` y sigue una sintaxis específica para asignar propietarios a archivos o directorios. Cada línea del archivo contiene una ruta de archivo o directorio seguida de uno o más nombres de usuario o equipos de GitHub.

Ejemplo de un archivo `CODEOWNERS`:

```
# Propietarios del código fuente
/src/ @equipo-desarrollo

# Propietarios de las pruebas unitarias
/tests/ @equipo-pruebas

# Propietarios de los workflows
/.github/workflows/ @equipo-devops
```

En este ejemplo, el equipo de desarrollo es responsable del código fuente, el equipo de pruebas es responsable de las pruebas unitarias, y el equipo de DevOps es responsable de los workflows.

# Procedimiento.

1. En visual studio code, abrir una sesion de copilot editors y realizar las siguientes actividades.

    - Crear archivo CODEOWNERS

        - Solicitar que genere el archivo de ejemplo para una estructura de proyecto donde el codigo se modifica por el equipo de desarrollo, las pruebas unitarias por el equipo de pruebas y los workflows por el equipo de devops.


