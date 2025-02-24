# Alta de Cliente

## Descripción
Esta historia describe la operación de alta de un nuevo cliente en el sistema.

## Campos de la Entidad Cliente
- **id**: Identificador único del cliente.
- **nombre de cliente**: Nombre completo del cliente.
- **dirección**: Dirección física del cliente.
- **estatus**: Estado actual del cliente (activo/inactivo).

## Proceso
1. El usuario ingresa los datos del nuevo cliente en el formulario de alta.
2. El sistema valida que todos los campos requeridos estén completos y sean correctos.
3. El sistema asigna un `id` único al nuevo cliente.
4. El sistema guarda los datos del cliente en la base de datos.
5. El sistema confirma la creación del nuevo cliente y muestra un mensaje de éxito.

## Resultado Esperado
El cliente es creado exitosamente y se puede visualizar en la lista de clientes.
