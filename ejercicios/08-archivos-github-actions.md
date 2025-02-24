# Objetivo

Crear los archivos de configuración de github para la estructura del proyecto.

# Descripción

Los archivos de workflow de GitHub Actions permiten automatizar tareas dentro del ciclo de vida del desarrollo de software. Estos archivos se definen en el directorio `.github/workflows` del repositorio y están escritos en YAML. Cada archivo de workflow puede contener una o más jobs que se ejecutan en respuesta a eventos específicos en el repositorio, como push, pull request, o cron jobs.

Un ejemplo básico de un archivo de workflow que se ejecuta cuando se crea un pull request a la rama `develop` podría verse así:

```yaml
name: CI

on:
    pull_request:
        branches:
            - develop

jobs:
    hello_world:
        runs-on: ubuntu-latest

        steps:
            - name: Checkout repository
                uses: actions/checkout@v2

            - name: Run Hello World
                run: echo "Hola Mundo"
```

Este archivo define un workflow llamado `CI` que se activa en el evento `pull_request` dirigido a la rama `develop`. El job `hello_world` se ejecuta en un contenedor `ubuntu-latest` y realiza dos pasos: el primero, usar la acción `actions/checkout@v2` para clonar el repositorio, y el segundo, ejecutar el comando `echo "Hola Mundo"`.


# Procedimiento.

1. En visual studio code, abrir una sesion de copilot editors y realizar las siguientes actividades.

    - Crear archivo de workflow y actions.

        - Solicitar a copilot que genere un archivo basico de workflow considerando que solo ejecute el comando de "hola mundo" para cuando se realice la creación de un pull request a la rama develop.

