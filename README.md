# My UI Library

**My UI Library** es una colección de componentes y plantillas de diseño web modernas, limpias y responsivas. Este repositorio ofrece una base sólida para acelerar el desarrollo de interfaces de usuario, permitiéndote copiar y adaptar secciones completas para tus proyectos personales o comerciales.

## 🚀 Características Principales

*   **Diseño Modular:** Componentes independientes organizados para fácil importación.
*   **100% Personalizable:** Gestionado centralmente mediante variables CSS CSS (`css-global/variables.css`). Cambia colores, tipografías y espaciados en un solo lugar.
*   **Sin Dependencias:** Construido con HTML5 y CSS3 puro (Vanilla CSS). No requiere instalación de Node.js, librerías pesadas ni compiladores.
*   **Plantillas "Premium":** Interfaces completas listas para usar con diseños de alta calidad (Login, Tienda, Carrito, Dashboard).

## 📂 Estructura del Proyecto

La organización de archivos está pensada para ser intuitiva y escalable:

*   `assets/`: Imágenes, iconos y otros recursos estáticos.
*   `components/`: Bloques de construcción reutilizables.
    *   `buttons.css`: Estilos de botones (primarios, secundarios, outline).
    *   `card.css`: Contenedores tipo tarjeta para productos o contenido.
    *   `alert-message.css`: Notificaciones y alertas de estado.
    *   `navbar/`: Barra de navegación responsiva.
*   `css-global/`: El corazón del diseño.
    *   `variables.css`: **Archivo Maestro**. Define toda la identidad visual (paleta de colores, fuentes, radios de borde).
*   `templates/`: Páginas completas listas para copiar y pegar.
    *   `shop/`: Catálogo de productos con filtros y grid responsive.
    *   `cart/`: Carrito de compras con resumen de pedido.
    *   `login/`: Página de autenticación moderna y centrada.
    *   `product-crud/`: Tabla de gestión de datos (estilo dashboard/administración).

## 🛠️ Guía de Uso

1.  **Explora las plantillas:** Abre cualquier archivo `.html` dentro de `templates/` en tu navegador para ver el diseño en acción.
2.  **Integra en tu proyecto:**
    *   Copia el archivo HTML que necesites.
    *   Asegúrate de copiar también el archivo CSS específico de la plantilla y el archivo `variables.css`.
3.  **Enlaza los estilos:**

```html
<!-- 1. Variables Globales (¡Esencial!) -->
<link rel="stylesheet" href="path/to/css-global/variables.css">

<!-- 2. Estilos específicos de la plantilla (ej. Login) -->
<link rel="stylesheet" href="path/to/templates/login/login.css">
```

## 🎨 Personalización

Para adaptar el diseño a tu marca, simplemente edita `css-global/variables.css`. Los cambios se reflejarán automáticamente en todos los componentes y plantillas que utilicen estas variables.

```css
:root {
    /* Identidad de Marca */
    --primary-color: #667eea;  /* Color principal */
    --secondary-color: #764ba2; /* Color de acento/gradientes */
    
    /* Tipografía */
    --font-style: 'Inter', sans-serif;
    
    /* Interfaz */
    --border-radius: 12px;
}
```

## 📄 Detalle de Plantillas

### 🛍️ Shop (Tienda)
Un catálogo atractivo con una sección "Hero" para promociones, barra lateral para filtros (categorías, precios) y una cuadrícula de productos responsive que se adapta a móviles y escritorios.

### 🛒 Cart (Carrito)
Diseño limpio para revisar compras. Incluye lista de artículos con imágenes, controles de cantidad y una tarjeta de resumen de pedido que se mantiene visible (sticky) al hacer scroll.

### 🔐 Login
Pantalla de acceso minimalista con tarjeta flotante, animaciones de entrada suaves y validación visual de campos.

### 📊 Product CRUD
Interfaz de administración para gestionar inventario. Presenta una tabla de datos moderna con insignias de estado (badges) y acciones rápidas (editar/eliminar).

---
*Hecho con ❤️ para facilitar el aprendizaje y desarrollo web.*
