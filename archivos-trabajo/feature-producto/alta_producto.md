# Historia de Usuario: Alta de Producto

## Descripción
Como usuario, quiero poder dar de alta un nuevo producto en el sistema para que esté disponible para la venta.

## Criterios de Aceptación
1. El formulario de alta debe permitir ingresar los siguientes campos:
   - ID del producto
   - Nombre del producto
   - Precio
   - Tamaño
2. Todos los campos son obligatorios.
3. Al guardar el producto, debe mostrarse un mensaje de confirmación indicando que el producto ha sido dado de alta exitosamente.
4. El producto debe ser visible en la lista de productos disponibles después de ser dado de alta.

## Flujo Principal
1. El usuario accede a la sección de alta de productos.
2. El usuario completa el formulario con los datos del producto.
3. El usuario hace clic en el botón "Guardar".
4. El sistema valida los datos ingresados.
5. El sistema guarda el nuevo producto en la base de datos.
6. El sistema muestra un mensaje de confirmación.
7. El sistema redirige al usuario a la lista de productos disponibles.

## Flujo Alternativo
- Si los datos ingresados no son válidos, el sistema muestra un mensaje de error indicando los campos que deben ser corregidos.
