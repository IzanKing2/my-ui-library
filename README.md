# My UI Library

**My UI Library** es una colección de componentes y estilos CSS diseñados para facilitar el desarrollo de interfaces web modernas, limpias y responsivas. Este proyecto ofrece una base sólida para construir sitios web con una estética consistente y profesional.

## 🚀 Características Principales

*   **Diseño Modular:** Componentes independientes que se pueden importar según sea necesario.
*   **Personalizable:** Uso extensivo de variables CSS (`variables.css`) para una fácil adaptación de colores, tipografías y espaciados.
*   **Sin Dependencias:** CSS puro (Vanilla CSS), sin necesidad de preprocesadores ni librerías JavaScript pesadas.
*   **Listos para usar:** Incluye plantillas y componentes comunes en desarrollos web.

## 📂 Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

*   `assets/`: Recursos estáticos como imágenes o iconos.
*   `components/`: Estilos específicos para cada componente de la interfaz.
    *   `alert-message.css`: Estilos para mensajes de alerta y notificaciones.
    *   `buttons.css`: Variedad de estilos para botones.
    *   `card.css`: Componentes de tarjeta para mostrar contenido agrupado.
    *   `navbar/`: Estilos y estructura para la barra de navegación.
*   `css-global/`: Estilos generales y variables de configuración.
    *   `variables.css`: **Archivo principal** de configuración de temas (colores, fuentes, etc.).
*   `templates/`: Ejemplos de páginas completas pre-maquetadas.
    *   `cart.html`: Plantilla para un carrito de compras.
    *   `login.html`: Plantilla para una página de inicio de sesión.

## 🛠️ Guía de Uso

Para utilizar esta librería en tu proyecto, te recomiendo vincular primero el archivo de variables globales y luego los componentes que necesites en el `<head>` de tu HTML.

Ejemplo básico:

```html
<!-- 1. Variables Globales (Importante: cargar primero) -->
<link rel="stylesheet" href="css-global/variables.css">

<!-- 2. Componentes (Carga solo lo que necesites) -->
<link rel="stylesheet" href="components/navbar/navbar.css">
<link rel="stylesheet" href="components/buttons.css">
<link rel="stylesheet" href="components/card.css">
```

## 🎨 Personalización

Puedes cambiar la apariencia de todos los componentes editando únicamente el archivo `css-global/variables.css`. Aquí puedes definir tu paleta de colores, tamaños de fuente y bordes de manera centralizada.

```css
:root {
    /* Ejemplo de variables personalizables */
    --primary-color: #007bff;
    --font-family-base: 'Inter', sans-serif;
}
```

## 📄 Plantillas Disponibles

El proyecto incluye plantillas base para acelerar el desarrollo:
*   **Login Page:** Un formulario de acceso estilizado (`templates/login.html`).
*   **Shopping Cart:** Una vista detallada de carrito de compras (`templates/cart.html`).

## 🤝 Contribución

Si deseas contribuir a **My UI Library**, siéntete libre de clonar el repositorio, mejorar los estilos existentes o añadir nuevos componentes.

---
*Documentación generada automáticamente para My UI Library.*
