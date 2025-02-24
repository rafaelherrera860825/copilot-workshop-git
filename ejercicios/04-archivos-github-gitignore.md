# Objetivo

Crear los archivos de configuración de github para la estructura del proyecto.

# Descripción del archivo

El archivo `.gitignore` se utiliza para especificar qué archivos o directorios deben ser ignorados por Git. Esto es útil para evitar que archivos temporales, de configuración local, o cualquier otro archivo que no sea necesario compartir con otros desarrolladores, sean incluidos en el control de versiones. 

Al definir un archivo `.gitignore`, se pueden listar patrones que coincidan con los nombres de los archivos o directorios que se desean excluir. Por ejemplo, se pueden ignorar archivos compilados, archivos de configuración del entorno, dependencias descargadas, entre otros.

Ejemplo de un archivo `.gitignore` para un proyecto de Node.js:

```
# Node modules
node_modules/

# Logs
logs/
*.log

# Environment variables
.env

# Compiled files
dist/
```

Este archivo asegura que los directorios `node_modules` y `dist`, así como los archivos de log y de variables de entorno, no sean rastreados por Git.

# Procedimiento.

1. En visual studio code, abrir una sesion de copilot editors y realizar las siguientes actividades.

    - Crear o modificar archivo de .gitignore

        - Solicitar a copilot que genere el archivo de .gitignore para una tecnologia en especifico, por ejemplo, para java, nodejs en un sistema operativo linux, windows o macos.


