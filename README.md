# RETO-3
**SISTEMA DE RESTAURANTE**
Es un sistema básico de pedidos de un restaurante.
El menú cuenta con: 
1. Aperitivos
2. Bebidas
3. Platos principales
   
En el cual se puede crear una orden con las diferentes opciones de productos y calcular el total a pagar con o sin descuento.

**RELACIONES ENTRE LAS CLASES**
por un lado, está la herencia, que nos dice que una bebida, un aperitivo o un plato principal son un tipo de producto del menú, ya que todos comparten lo básico (un nombre y un precio) pero cada uno puede comportarse de manera distinta. Por otro lado, está la composición, una orden tiene dentro de sí varios productos del menú; una orden no tendría sentido sin los ítems que el cliente decide pedir, porque son esos productos los que le dan forma y estructura a esa clase.
