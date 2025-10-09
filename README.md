# 🚀 EcoSolution with Astro

¡Bienvenido al repositorio de mi sitio web personal! Este proyecto es una demostración de cómo construir un sitio web moderno, rápido y estético utilizando **Astro** y **Tailwind CSS**.

![Placeholder de la imagen del sitio web](https://via.placeholder.com/800x400.png?text=Imagen+de+mi+Sitio+Web)
_(Puedes reemplazar la URL de arriba con una captura de pantalla de tu proyecto)_

---

## ✨ Características Principales

El sitio web cuenta con varias secciones diseñadas para ofrecer una experiencia de usuario completa:

- 🏠 **Página de Inicio**: Una landing page atractiva que presenta el propósito del sitio.
- 🛍️ **Productos**: Una galería para mostrar diferentes productos de forma organizada.
- 🌟 **Testimonios**: Una sección dedicada a mostrar las opiniones y comentarios de los clientes.
- 📞 **Contacto**: Información y medios para que los visitantes puedan ponerse en contacto.

---

## 🛠️ Tecnologías Utilizadas

Este proyecto fue construido con un conjunto de tecnologías modernas enfocadas en el rendimiento y la experiencia de desarrollo:

- **[Astro](https://astro.build/)**: Framework web para construir sitios rápidos y optimizados.
- **[Tailwind CSS](https://tailwindcss.com/)**: Framework de CSS "utility-first" para un diseño rápido y responsivo.
- **[TypeScript](https://www.typescriptlang.org/)**: Superset de JavaScript que añade tipado estático para un código más robusto.
- **[PNPM](https://pnpm.io/)**: Gestor de paquetes rápido y eficiente en el uso de espacio en disco.

---

## ⚙️ Guía de Inicio Rápido

Sigue estos pasos para levantar una copia del proyecto en tu máquina local.

### Prerrequisitos

Asegúrate de tener [Node.js](https://nodejs.org/) (versión 18 o superior) y [pnpm](https://pnpm.io/installation) instalados.

### Instalación

1.  **Clona el repositorio:**

    ```bash
    git clone https://github.com/tu-usuario/notion-practice.git
    cd notion-practice
    ```

2.  **Instala las dependencias:**
    Con `pnpm` (recomendado, ya que el proyecto usa `pnpm-lock.yaml`):

    ```bash
    pnpm install
    ```

3.  **Inicia el servidor de desarrollo:**
    ```bash
    pnpm dev
    ```

¡Y listo! Abre [http://localhost:4321](http://localhost:4321) en tu navegador para ver el sitio en acción.

---

## 📜 Scripts Disponibles

Estos son los scripts principales que puedes usar desde la raíz del proyecto:

- `pnpm dev`: Inicia el servidor de desarrollo de Astro en modo "hot-reload".
- `pnpm build`: Compila el sitio para producción en el directorio `dist/`.
- `pnpm preview`: Sirve el sitio de producción localmente para previsualizar los cambios.
- `pnpm astro`: Accede a la CLI de Astro para comandos adicionales.

---

## 📁 Estructura del Proyecto

El proyecto sigue la estructura recomendada por Astro para una organización clara y mantenible:

```
.
├── public/              # Assets estáticos (imágenes, favicons)
├── src/
│   ├── assets/          # Imágenes e iconos para componentes
│   ├── components/      # Componentes reutilizables de Astro (.astro)
│   ├── layouts/         # Plantillas de página (.astro)
│   ├── pages/           # Rutas y páginas del sitio (.astro)
│   └── styles/          # Estilos globales (global.css)
├── astro.config.mjs     # Configuración de Astro
├── package.json         # Dependencias y scripts
└── tsconfig.json        # Configuración de TypeScript
```

---

¡Gracias por visitar mi proyecto! Si tienes alguna idea o sugerencia, no dudes en abrir un _issue_ o un _pull request_.
