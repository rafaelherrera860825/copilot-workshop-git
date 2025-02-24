# Baja de Proveedor

## Descripción
Esta historia describe la operación de baja de un proveedor en el sistema.

## Campos de la Entidad Proveedor
- **id**: Identificador único del proveedor.
- **nombre de proveedor**: Nombre completo del proveedor.
- **dirección**: Dirección física del proveedor.
- **estatus**: Estado actual del proveedor (activo/inactivo).

## Proceso
1. El usuario selecciona el proveedor que desea dar de baja en la lista de proveedores.
2. El sistema muestra los detalles del proveedor seleccionado.
3. El usuario confirma la baja del proveedor.
4. El sistema actualiza el `estatus` del proveedor a inactivo en la base de datos.
5. El sistema confirma la baja del proveedor y muestra un mensaje de éxito.

## Resultado Esperado
El proveedor es dado de baja exitosamente y su estatus cambia a inactivo.
