# Vista de Ejecución

Se describe a continuación un escenario crítico del sistema correspondiente al registro de un producto en el Módulo de Compras.

## Escenario: Registrar Producto

1. El Administrador de Compras ingresa los datos del producto en la interfaz web.
2. La SPA envía la información a la API del ERP mediante una solicitud REST.
3. La API valida los datos y los persiste en la base de datos.
4. El sistema notifica al usuario sobre el registro exitoso del producto.

## Diagrama de Secuencia

![Diagrama de Secuencia](./imagenes/secuencia_registro_producto.png)
