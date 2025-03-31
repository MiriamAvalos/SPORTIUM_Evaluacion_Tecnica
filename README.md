# Proyecto de Página de Producto - Sportium ⚽🏀🏈🥊🎾

Este proyecto tiene como objetivo crear una página de producto para un CMS, donde se muestra un producto (en este caso, el juego **Spaceman**) con su imagen, descripción, precio y un botón de compra. Al hacer clic en el botón, se muestra un mensaje emergente para confirmar la compra. 

## Estructura del Proyecto

El proyecto está dividido en tres partes principales:

### 1. **HTML (Estructura básica)**
   - Un título del producto con la etiqueta `<h1>`.
   - Una imagen representativa del producto con la etiqueta `<img>`.
   - Una descripción detallada del producto utilizando la etiqueta `<p>` o `<figcaption>`.
   - El precio del producto en formato `span` con un precio original tachado y el precio actual resaltado en rojo.
   - Un botón que simula la acción de comprar el producto. Al hacer clic, un mensaje emergente aparece.

### 2. **CSS (Estilos básicos)**
   - La página está diseñada para ser simple y clara, con un diseño centrado tanto horizontal como verticalmente.
   - El color del botón cambia cuando se pasa el cursor sobre él.
   - La imagen tiene un tamaño máximo sin perder su proporción para evitar distorsiones.
   - El fondo es de un color claro para facilitar la lectura y visualización del contenido.

### 3. **JavaScript (Interactividad)**
   - Al hacer clic en el botón **"Comprar ahora"**, se activa una función que muestra un mensaje de alerta que dice **"¡Gracias por tu compra!"**.

## Características

- **Accesibilidad**: El botón tiene un atributo `aria-label` que permite que los usuarios con discapacidades visuales comprendan la acción que realiza el botón.
- **Diseño Responsive**: La página se adapta a diferentes tamaños de pantalla, garantizando una experiencia adecuada tanto en dispositivos móviles como en pantallas grandes.
- **Interactividad**: El botón de compra genera un mensaje emergente al ser presionado, lo que proporciona una experiencia interactiva al usuario.

## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
