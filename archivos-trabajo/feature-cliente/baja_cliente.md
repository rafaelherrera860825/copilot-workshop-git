# Baja de Cliente

## Descripción
Esta historia describe la operación de baja de un cliente en el sistema.

## Campos de la Entidad Cliente
- **id**: Identificador único del cliente.
- **nombre de cliente**: Nombre completo del cliente.
- **dirección**: Dirección física del cliente.
- **estatus**: Estado actual del cliente (activo/inactivo).

## Proceso
1. El usuario selecciona el cliente que desea dar de baja en la lista de clientes.
2. El sistema muestra los detalles del cliente seleccionado.
3. El usuario confirma la baja del cliente.
4. El sistema actualiza el `estatus` del cliente a inactivo en la base de datos.
5. El sistema confirma la baja del cliente y muestra un mensaje de éxito.

## Resultado Esperado
El cliente es dado de baja exitosamente y su estatus cambia a inactivo.
