# Alta de Proveedor

## Descripción
Esta historia describe la operación de alta de un nuevo proveedor en el sistema.

## Campos de la Entidad Proveedor
- **id**: Identificador único del proveedor.
- **nombre de proveedor**: Nombre completo del proveedor.
- **dirección**: Dirección física del proveedor.
- **estatus**: Estado actual del proveedor (activo/inactivo).

## Proceso
1. El usuario ingresa los datos del nuevo proveedor en el formulario de alta.
2. El sistema valida que todos los campos requeridos estén completos y sean correctos.
3. El sistema asigna un `id` único al nuevo proveedor.
4. El sistema guarda los datos del proveedor en la base de datos.
5. El sistema confirma la creación del nuevo proveedor y muestra un mensaje de éxito.

## Resultado Esperado
El proveedor es creado exitosamente y se puede visualizar en la lista de proveedores.
