# Tienda Online - POO en JavaScript
Este proyecto consiste en una tienda en linea basica desarrollada con Programacion Orientada a Objetos (POO) en JavaScript. Esta enfocado en la practica de clases, herencia y encapsulamiento, e incluye la implementacion de patrones de diseño clasicos como Observer, Factory Method y Strategy.

# Tecnologias usadas
- HTML5
- CSS3
- JavaScript

# Principios aplicados
# Programacion Orientada a Objetos
Se utilizan clases, herencia y objetos para representar:
- Productos genericos
- Productos especializados (ropa, electronicos)
- Carrito de compras

# Patrones de Diseño
1. Observer
Permite que el carrito avise cuando cambian los productos (por ejemplo, al agregar uno nuevo).

¿Donde se usa?
Se crea una clase Carrito que notifica a los "observadores" (como la vista) cuando hay un cambio.
Ventaja: Permite que la vista este actualizada automaticamente sin acoplarla directamente al carrito.

2. Factory Method
Permite crear objetos Producto, ProductoRopa, ProductoElectronico desde una unica interfaz.

¿Donde se usa?
Hay una funcion crearProducto(tipo, nombre, precio, atributoExtra) que decide automaticamente que clase instanciar.
Ventaja: No es necesario saber que clase especifica crear, lo hace la fabrica por nosotros.

3. Strategy
Permite cambiar la logica de calculo del total del carrito dependiendo de una estrategia (por ejemplo, aplicar o no un descuento).

¿Donde se usa?
Se definen varias estrategias de calculo (TotalNormal, TotalConDescuento) y se puede cambiar facilmente la logica.
Ventaja: Podemos modificar el comportamiento del carrito sin tocar su estructura interna.

# Vista en el navegador
- Un titulo principal: Tienda Online
- Un boton para mostrar productos
- Lista de productos (nombre, precio, atributos)
- Total del carrito dinamico

# Como usar
1. Clona este repositorio. 
2. Abre sin_patrones.html o con_patrones.html en tu navegador
3. Haz clic en “Mostrar Productos” si ingresas a "sin_patrones.html" y si ingresas a "con_patrones.html" da clic en cualquiera de los
botones "Agregar celular" o "Agregar camisa"
4. Veras como se actualiza la lista y el total automaticamente



