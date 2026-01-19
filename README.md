# Aplicación Web para Tienda de Pinturas para el Cabello

<img width="1536" height="1024" alt="logooo" src="https://github.com/user-attachments/assets/6207555a-4700-4132-bf2e-edfd7d547198" />

## Descripción
Mi aplicación web va a consistir en una tienda de pintura para el cabello necesita mostrar disponibilidad de tonos al instante. Con React, al vender un producto, el stock se actualiza 
automáticamente en la interfaz sin recargar la página, evitando errores y mejorando la gestión.

## Requerimientos Funcionales (El “Qué hace”)
RF1: Visualizar el catálogo de pinturas para el cabello con su nombre, color y precio.

RF2: Filtrar los productos por color o marca de forma interactiva.

RF3: Registrar productos en un carrito de compras.

RF4: Editar el carrito de compras permitiendo agregar o quitar productos.

RF5: Visualizar el total de la compra actualizado automáticamente sin recargar la página.

## Requerimientos no funcionales
Adaptabilidad:
La aplicación debe adaptarse a diferentes tamaños de pantalla usando CSS básico para que se vea correctamente en celular y computadora.

Rendimiento:
La aplicación debe mostrar y actualizar la información sin recargar la página, usando la reactividad del framework.

Persistencia:
La aplicación debe conservar los productos agregados al carrito durante la sesión del usuario usando LocalStorage.

Accesibilidad:
La aplicación debe usar etiquetas HTML simples y textos claros para facilitar su uso por cualquier persona.

## Tecnologias y herramientas del ecosistema
Manejo de Estado Global
Herramienta: Context API
¿Por qué?: Es la opción más fácil en React para compartir datos (como el carrito) entre componentes sin instalar librerías extra como Redux.
Consumo de Datos

Herramienta: Fetch API
¿De dónde vienen los datos?: De un archivo local tipo products.json (o un arreglo en un archivo .js) dentro de mi proyecto.
¿Por qué?: Es más simple para iniciar: no necesitamos backend, y Fetch es nativo del navegador.

Herramienta: CSS básico
¿Por qué?: Se utilizará CSS básico para dar estilo a la aplicación, permitiendo crear un diseño sencillo, ordenado y responsive sin necesidad de librerías externas, facilitando su implementación.

Despliegue
Herramienta: Vercel
¿Por qué?: Es muy fácil para mi proyecto de React/Vite: conectas GitHub y se publica en pocos clics.

<img width="2650" height="5420" alt="Catalog and Cart Flow-2026-01-19-203155" src="https://github.com/user-attachments/assets/4ef87c7c-9314-44a5-9dda-cc5a6e075873" />




