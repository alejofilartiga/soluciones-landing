
# Soluciones A.F.V. - Landing Page

Landing page desarrollada para **Soluciones A.F.V.**, un emprendimiento enfocado en brindar soluciones digitales accesibles y personalizadas para pequeñas marcas y emprendimientos. Esta landing está construida con **Astro**, **Tailwind CSS** y **Flowbite**, buscando velocidad, estética moderna y buena experiencia de usuario.

## 🛠️ Tecnologías utilizadas

- [Astro](https://astro.build) - Framework moderno para sitios estáticos y de contenido.
- [Tailwind CSS](https://tailwindcss.com/) - Utilidades CSS para diseño ágil y responsive.
- [Flowbite](https://flowbite.com/) - Componentes UI construidos sobre Tailwind.
- Vercel para despliegue.

## 📁 Estructura del proyecto

```text
/
├── public/           # Archivos estáticos
├── src/
│   ├── layouts/      # Plantillas reutilizables (Layout.astro)
│   └── pages/        # Páginas del sitio (index.astro, etc.)
├── astro.config.mjs  # Configuración principal de Astro + Tailwind
├── tailwind.config.js# Configuración de Tailwind (si existe)
├── tsconfig.json     # Configuración de TypeScript
├── vercel.json       # Reescrituras para deploy en Vercel
└── package.json      # Dependencias y scripts
```

## 🚀 Instalación y uso

Cloná el proyecto y seguí estos pasos:

```bash
# Instalar dependencias
npm install

# Servidor de desarrollo
npm run dev

# Build de producción
npm run build

# Vista previa del build
npm run preview
```

El servidor de desarrollo se ejecuta por defecto en [http://localhost:4321](http://localhost:4321)

## 📦 Scripts disponibles

| Script            | Descripción                           |
|------------------|---------------------------------------|
| `npm run dev`     | Inicia el servidor de desarrollo      |
| `npm run build`   | Genera el sitio listo para producción |
| `npm run preview` | Visualiza el sitio en modo producción |
| `npm run astro`   | Ejecuta comandos de Astro CLI         |

## ☁️ Deploy

El sitio está configurado para ser desplegado en [Vercel](https://vercel.com), usando el archivo `vercel.json` para permitir rutas amigables mediante `rewrites`.

## 🙋 Autor

Desarrollado por **Alejo Filartiga**.  
[LinkedIn](https://www.linkedin.com/in/alejofilartiga/) · [GitHub](https://github.com/alejofilartiga)

---

© 2025 Soluciones A.F.V.
