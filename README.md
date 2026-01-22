<img width="1851" height="653" alt="imagen" src="https://github.com/user-attachments/assets/85371f6f-8240-42c1-bbbe-dbac5c5d2a48" />                                                                                   Cervezas Tlali 
                                                                              

La tienda Tlali, dedicada a la venta de cervezas artesanales con distintos sabores, actualmente carece de un sistema digital eficiente para gestionar las ventas y la interacción con sus clientes. Esto genera dificultades para mostrar el catálogo actualizado de cervezas, verificar la edad de los compradores, procesar pedidos de manera ágil y llevar un registro de las ventas por sabor y stock disponible. Además, no existe un espacio centralizado para promociones, anuncios importantes o información sobre nuevas variedades, lo que provoca desorganización y una experiencia de compra limitada para los clientes.

Se decidió utilizar React como framework de frontend debido a su capacidad para crear interfaces reactivas y manejar de manera eficiente el estado de la aplicación. Esto permite, por ejemplo, mostrar un aviso obligatorio de verificación de edad (mayor de 18 años) antes de que los usuarios accedan a la tienda, actualizar el catálogo en tiempo real cuando se agregan nuevos sabores o cuando se agotan existencias, y gestionar de forma dinámica el carrito de compras y los pedidos.

El manejo de estado en React facilita controlar la disponibilidad de los productos, aplicar promociones, registrar ventas y actualizar la información de stock de manera inmediata. Esto mejora significativamente la experiencia del cliente, haciéndola más interactiva, confiable y moderna en comparación con un sitio web estático, y permite que Tlali se posicione como una tienda digital organizada y atractiva para los amantes de la cerveza artesanal.



Requerimientos Funcionales (El "Qué hace")

1.-Verificación de edad

El sistema mostrará un anuncio inicial solicitando confirmar que el usuario es mayor de 18 años antes de acceder a la tienda.

El usuario podrá aceptar o rechazar el acceso según su edad.

2.-Visualización del catálogo

El usuario podrá visualizar el catálogo de cervezas artesanales Tlali.

Cada producto mostrará información como nombre, sabor, descripción, precio e imagen.

3.-Filtrado y exploración de productos

El usuario podrá filtrar las cervezas por sabor, tipo o precio.

El sistema actualizará la vista del catálogo sin recargar la página.

4.-Gestión del carrito de compras

El usuario podrá agregar cervezas al carrito de compras.

Podrá modificar la cantidad o eliminar productos del carrito.

El total de la compra se actualizará en tiempo real.

5.-Proceso de compra

El usuario podrá confirmar su pedido desde el carrito.

El sistema mostrará un resumen de la compra antes de finalizarla.

6.-Registro y control de pedidos

El sistema registrará cada pedido realizado por el usuario.

El usuario podrá visualizar el estado de su pedido (pendiente, confirmado o entregado).

7.-Gestión de stock

El sistema actualizará automáticamente la disponibilidad de las cervezas cuando se realiza una compra.

Las cervezas agotadas se mostrarán como no disponibles.

8.-Promociones y anuncios

El sistema mostrará promociones especiales, lanzamientos de nuevos sabores y anuncios informativos.

Las promociones se aplicarán automáticamente al total de la compra cuando correspondan.

9.-Interfaz reactiva

La interfaz se actualizará en tiempo real ante cualquier acción del usuario (agregar productos, aplicar filtros, modificar carrito).

No será necesario recargar la página para ver los cambios.

10.-Cierre de sesión o salida de la tienda

El usuario podrá salir de la tienda en cualquier momento.

El sistema limpiará el carrito si el usuario abandona la sesión.
