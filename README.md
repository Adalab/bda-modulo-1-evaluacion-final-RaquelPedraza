Este repositorio contiene una implementación de una tienda online desarrollada en Python, que utiliza programación orientada a objetos para gestionar el inventario de productos, clientes y realizar operaciones de compra y pago.

Clase TiendaOnline

La clase TiendaOnline tiene los siguientes atributos:

- inventario: Una lista que almacena los productos disponibles en el inventario.
- clientes: Un diccionario que almacena la información de los clientes, donde la clave es el nombre del cliente y el valor es un diccionario con su dirección de correo electrónico y su historial de compras.
- ventas_totales: Un float que representa el total de ventas realizadas en la tienda.

Métodos disponibles:

1-. agregar_producto: Permite agregar un nuevo producto al inventario o actualizar su cantidad si ya existe.
2-. ver_inventario: Muestra el inventario de productos con sus detalles.
3-. buscar_producto: Busca un producto en el inventario por su nombre y muestra sus detalles.
4-. actualizar_stock: Permite actualizar el stock de un producto en el inventario.
5-. eliminar_producto: Permite eliminar un producto del inventario.
6-. calcular_valor_inventario: Calcula el valor total de todos los productos en el inventario.
7-. buscar_producto_regex: Busca productos en el inventario que coincidan con un patrón de búsqueda utilizando expresiones regulares.
8-. realizar_compra: Permite a los clientes realizar compras seleccionando productos del inventario.
9-. procesar_pago: Procesa el pago de una compra, calculando el cambio si es necesario.
10-. agregar_cliente: Agrega un nuevo cliente al registro de clientes.
11-. ver_clientes: Muestra la lista de clientes registrados en la tienda.
12-. registrar_compra: Registra una compra realizada por un cliente, actualizando el historial de compras del cliente y las ventas totales de la tienda.
13-. ver_compras_cliente: Muestra el historial de compras de un cliente específico.
14-. calcular_ventas_totales: Calcula las ventas totales realizadas en la tienda.

