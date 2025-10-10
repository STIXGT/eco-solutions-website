# EcoSolutions - Proyecto de Portafolio Frontend con Astro

Este repositorio contiene el código fuente de un sitio web moderno y de alto rendimiento para **EcoSolutions**, una marca ficticia dedicada a soluciones ecológicas. El proyecto fue desarrollado como una pieza de portafolio para demostrar mis habilidades en el desarrollo frontend utilizando tecnologías web modernas.

---

## 🚀 Demo en Vivo

_[Aquí puedes agregar el enlace a la demo desplegada de tu proyecto]_

---

## ✨ Características Principales

El sitio web está diseñado para ofrecer una experiencia de usuario completa y fluida, e incluye las siguientes secciones:

-   🏠 **Página de Inicio**: Una landing page atractiva que presenta la misión y visión de la marca.
-   🛍️ **Catálogo de Productos**: Una galería limpia y organizada para mostrar los productos sostenibles de la marca.
-   🌟 **Testimonios**: Una sección dedicada a mostrar la confianza y satisfacción de los clientes.
-   📞 **Página de Contacto**: Un formulario e información de contacto para facilitar la comunicación.

---

## 🛠️ Tecnologías Utilizadas

La selección de tecnologías se centró en el rendimiento, la eficiencia en el desarrollo y las buenas prácticas.

-   **[Astro](https://astro.build/)**: Framework web utilizado por su arquitectura de "islas" que permite enviar cero JavaScript por defecto, resultando en sitios web extremadamente rápidos.
-   **[Tailwind CSS](https://tailwindcss.com/)**: Framework de CSS "utility-first" para la creación rápida y consistente de interfaces de usuario personalizadas y responsivas.
-   **[TypeScript](https://www.typescriptlang.org/)**: Añade un sistema de tipado estático a JavaScript, lo que mejora la robustez del código y la experiencia de desarrollo.
-   **[PNPM](https://pnpm.io/)**: Gestor de paquetes rápido y eficiente en el uso del espacio en disco.

---

## 🎯 Objetivos del Proyecto

Este proyecto fue creado con el objetivo de demostrar las siguientes competencias:

-   **Maquetación web semántica y responsiva** con HTML5 y Tailwind CSS.
-   **Desarrollo basado en componentes** utilizando la sintaxis `.astro`.
-   **Optimización del rendimiento web** (WPO) aprovechando las características de Astro.
-   **Estructura de proyectos frontend** escalable y mantenible.

---

## ⚙️ Cómo Empezar

Sigue estos pasos para ejecutar una copia del proyecto en tu máquina local.

### Prerrequisitos

Asegúrate de tener [Node.js](https://nodejs.org/) (versión 18 o superior) y [pnpm](https://pnpm.io/installation) instalados.

### Pasos

1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/STIXGT/eco-solutions-website.git
    cd eco-solutions-website
    ```

2.  **Instala las dependencias:**
    ```bash
    pnpm install
    ```

3.  **Inicia el servidor de desarrollo:**
    ```bash
    pnpm dev
    ```

¡Listo! Abre [http://localhost:4321](http://localhost:4321) en tu navegador para ver el sitio en acción.

---

## 📜 Scripts Disponibles

-   `pnpm dev`: Inicia el servidor de desarrollo con hot-reloading.
-   `pnpm build`: Compila el sitio para producción en la carpeta `dist/`.
-   `pnpm preview`: Levanta un servidor local para previsualizar la versión de producción.

---

## 📁 Estructura del Proyecto

```
.
├── public/              # Assets estáticos (imágenes, favicons)
├── src/
│   ├── assets/          # Imágenes e iconos para componentes
│   ├── components/      # Componentes reutilizables (.astro)
│   ├── layouts/         # Plantillas de página (.astro)
│   ├── pages/           # Rutas y páginas del sitio (.astro)
│   └── styles/          # Estilos globales (global.css)
├── astro.config.mjs     # Configuración de Astro
├── package.json         # Dependencias y scripts
└── tsconfig.json        # Configuración de TypeScript
```
