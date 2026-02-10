05_building_block_view.md
# Vista de Bloques de Construcción

El sistema ERP está compuesto por diferentes contenedores que separan las responsabilidades técnicas y funcionales.

## Diagrama de Contenedores (C2)

![Diagrama de Contenedores](./imagenes/c2_containers.png)

## Responsabilidades de los Contenedores

- **SPA (Frontend Web)**: Proporciona la interfaz de usuario para la gestión de compras y consultas del sistema.
- **API ERP**: Contiene la lógica de negocio, validaciones y reglas del sistema.
- **Base de Datos**: Almacena la información relacionada con productos, proveedores, órdenes de compra y transacciones.
