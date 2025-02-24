# Historia de Usuario: Eliminación de Producto

## Descripción
Como usuario, quiero poder eliminar un producto del sistema para que ya no exista en la base de datos.

## Criterios de Aceptación
1. El usuario debe poder seleccionar un producto de la lista de productos disponibles.
2. El sistema debe solicitar confirmación antes de eliminar el producto.
3. Al confirmar, el producto debe ser eliminado de la base de datos.
4. El sistema debe mostrar un mensaje de confirmación indicando que el producto ha sido eliminado exitosamente.

## Flujo Principal
1. El usuario accede a la lista de productos disponibles.
2. El usuario selecciona el producto que desea eliminar.
3. El usuario hace clic en el botón "Eliminar".
4. El sistema solicita confirmación al usuario.
5. El usuario confirma la eliminación del producto.
6. El sistema elimina el producto de la base de datos.
7. El sistema muestra un mensaje de confirmación.
8. El sistema actualiza la lista de productos disponibles.

## Flujo Alternativo
- Si el usuario cancela la confirmación, el producto no es eliminado y la lista de productos disponibles permanece sin cambios.
