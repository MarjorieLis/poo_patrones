# Tienda Online - POO en JavaScript
Este proyecto consiste en una tienda en linea basica desarrollada con Programacion Orientada a Objetos (POO) en JavaScript. Esta enfocado en la practica de clases, herencia y encapsulamiento, e incluye la implementacion de patrones de diseño clasicos como Observer, Factory Method y Strategy.

📌 Objetivo
Aplicar los principios de la POO y los patrones de diseño para construir un sistema modular, reutilizable y escalable en JavaScript.

🚀 Tecnologías usadas
HTML5

CSS3

JavaScript (ES6+)

🧠 Principios aplicados
✅ Programación Orientada a Objetos
Se utilizan clases, herencia y objetos para representar:

Productos genéricos

Productos especializados (ropa, electrónicos)

Carrito de compras

🧩 Patrones de Diseño
1. 🧭 Observer
Permite que el carrito avise cuando cambian los productos (por ejemplo, al agregar uno nuevo).

¿Dónde se usa?

Se crea una clase Carrito que notifica a los "observadores" (como la vista) cuando hay un cambio.

Ventaja: Permite que la vista esté actualizada automáticamente sin acoplarla directamente al carrito.

2. 🏭 Factory Method
Permite crear objetos Producto, ProductoRopa, ProductoElectronico desde una única interfaz.

¿Dónde se usa?

Hay una función crearProducto(tipo, nombre, precio, atributoExtra) que decide automáticamente qué clase instanciar.

Ventaja: No es necesario saber qué clase específica crear, lo hace la fábrica por nosotros.

3. 🧠 Strategy
Permite cambiar la lógica de cálculo del total del carrito dependiendo de una estrategia (por ejemplo, aplicar o no un descuento).

¿Dónde se usa?

Se definen varias estrategias de cálculo (TotalNormal, TotalConDescuento) y se puede cambiar fácilmente la lógica.

Ventaja: Podemos modificar el comportamiento del carrito sin tocar su estructura interna.

🖥 Vista en el navegador
Un título principal: Tienda Online

Un botón para mostrar productos

Lista de productos (nombre, precio, atributos)

Total del carrito dinámico