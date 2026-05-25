# Tuti-Enda - Plataforma Web de Compra y Venta (Bootstrap 5) 🎮📱

Este proyecto es una aplicación web responsive desarrollada como ejercicio práctico para el módulo de maquetación del ciclo formativo de **Desarrollo de Aplicaciones Multiplataforma (DAM)** en **Salesianos Triana**. 

La plataforma emula una tienda de intercambio tecnológico inspirada en el modelo de negocio de CeX, permitiendo la visualización de catálogos de videojuegos, consolas y smartphones, además de interactuar con servicios del cliente.

---

## 🚀 Características Clave e Implementación Técnica

* **Navegación Inteligente (Scrollspy & Sticky):** Menú de navegación superior (`navbar`) fijo con seguimiento dinámico de la sección activa mediante la utilidad `data-bs-spy="scroll"` en el cuerpo del sitio.
* **Componentes Dinámicos de Bootstrap 5:**
  * **Hero Carousel:** Deslizador principal con imágenes optimizadas mediante `object-fit: cover` y filtros de contraste para asegurar la legibilidad del texto superior.
  * **Catálogo en Carousel de Rejilla:** Organización avanzada de productos por lotes utilizando sub-sistemas de filas (`row`) y columnas responsivas (`col-12 col-md-6 col-lg-4`) dentro de un carrusel interactivo.
  * **Modales de Interacción:** Ventanas emergentes nativas independientes para la sección de información corporativa y el formulario de inicio de sesión (*Login*).
  * **Cesta en Offcanvas:** Menú lateral desplegable (`offcanvas-end`) para la gestión del carrito de compras sin interrumpir la navegación del usuario.
* **Validación de Formularios Interactiva:** Formulario de contacto con estilos avanzados de validación en tiempo de envío (`needs-validation`), controlado mediante una estructura modular de JavaScript nativo (IIFE).
* **Tablas de Datos Adaptativas:** Tabla con estados de stock representados mediante componentes `badge` de Bootstrap, envuelta en un contenedor `.table-responsive` para evitar desbordamientos en entornos móviles.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5** - Estructura semántica del sitio web y secciones de anclaje.
* **Bootstrap v5.3.0** - Framework CSS para diseño ágil, utilidades de espaciado y maquetación mediante *Flexbox* y *Grid*.
* **Bootstrap Icons v1.11.1** - Iconografía vectorial nativa para componentes de interfaz.
* **JavaScript (ES6)** - Lógica frontend para la activación de validaciones visuales del framework (`was-validated`).

---

## 🔧 Instalación y Ejecución en Local

Al estar construido utilizando las librerías oficiales a través de CDN, no requiere gestores de dependencias locales (como npm o yarn)
