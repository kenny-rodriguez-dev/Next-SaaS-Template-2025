# CopyGen Replica - Prototipo de Landing Page de Servicios Profesionales

Este es un proyecto de Front-End moderno construido con **Next.js 15 (App Router)**, **React 19** y **Tailwind CSS 4**. La aplicación es una réplica de una landing page de servicios profesionales (enfocada en redacción de currículums y optimización de perfiles), diseñada para demostrar habilidades avanzadas en maquetación, manejo de estado y diseño responsivo.

### Estado del Proyecto

Este proyecto es un prototipo funcional diseñado para portafolio. Representa la interfaz de usuario completa y la navegación de un sitio comercial, con énfasis en la experiencia de usuario (UX) y la adaptabilidad visual.

### Características Principales

* **Arquitectura Moderna:** Uso de Next.js App Router para una navegación optimizada y SEO friendly.
* **Sistema de Temas (Dark/Light Mode):** Implementación de un `ThemeProvider` personalizado que permite alternar entre modo claro y oscuro, con persistencia de estilos en todos los componentes.
* **Diseño Responsivo y Adaptativo:** Interfaz totalmente optimizada para dispositivos móviles, tablets y escritorio, incluyendo un menú de navegación móvil (Hamburger menu) con animaciones fluidas.
* **Componentes Interactivos:**
    * Carruseles de testimonios con desplazamiento automático y manual.
    * Secciones de preguntas frecuentes (FAQ) con acordeones animados.
    * Tablas de precios con interruptores de contenido.
    * Botones flotantes de acción rápida (WhatsApp y "Volver arriba").
* **Estilizado Avanzado:** Uso de la última versión de **Tailwind CSS (v4)** para estilos utilitarios y **Material UI (MUI)** para iconos vectoriales.
* **Animaciones:** Implementación de contadores dinámicos (`CountUp`) y transiciones suaves entre secciones.

---

### Tecnologías Utilizadas

#### Core
* **Next.js 15.2:** Framework de React para producción.
* **React 19:** Biblioteca para construir interfaces de usuario.
* **JavaScript (ES6+):** Lógica del lado del cliente.

#### Estilos y Diseño
* **Tailwind CSS 4.0:** Framework de utilidades CSS para un diseño rápido y mantenible.
* **Material UI (MUI Icons):** Iconografía profesional.
* **CSS Modules:** Para estilos específicos y animaciones personalizadas.

#### Herramientas
* **ESLint:** Para asegurar la calidad y consistencia del código.
* **PostCSS:** Procesamiento de CSS.

---

### Requisitos Previos

Para ejecutar el proyecto localmente, necesitará tener instalado:

* Node.js (versión 18.x o superior recomendada para Next.js 15)
* npm o yarn como gestor de paquetes.

---

### Configuración del Proyecto

Siga estos pasos para desplegar el proyecto en su entorno local:

1.  **Clonar el repositorio:**
    Debe abrir su terminal y clonar este proyecto (o descargar el ZIP):
    ```bash
    git clone <URL_DE_TU_REPOSITORIO>
    ```

2.  **Instalar dependencias:**
    Navegue hacia la carpeta del proyecto e instale los paquetes necesarios:
    ```bash
    cd plantilla_mypersonalproject
    npm install
    ```

3.  **Ejecute el servidor de desarrollo:**
    Inicie el proyecto en modo local:
    ```bash
    npm run dev
    ```

4.  **Ver el proyecto:**
    Debe abrir su navegador y acceder a `http://localhost:3000`.

---

### Estructura de Carpetas

* `/src/app`: Contiene las rutas, el layout principal y las páginas (Home, Servicios, Precios, etc.).
* `/src/app/components`: Componentes reutilizables (Header, Footer, Sliders, Acordeones).
* `/public`: Activos estáticos como imágenes e iconos.

---

## Autor

* **Kenny Rodríguez**
* [Perfil de LinkedIn](https://www.linkedin.com/in/kennyrodriguezm/)

---