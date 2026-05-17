# 🧑‍💻 Portfolio Personal — Dragmon

Portafolio personal desarrollado con Astro, basado en el template [NeonMint](https://github.com/EFEELE/NeonMint) de [Fernando Aldair Lopez Ponce](https://github.com/EFEELE), al cual se le han realizado modificaciones y personalizaciones propias.

---

## 📁 Estructura del Proyecto

```
└── 📁portfolio-astro
    └── 📁public
        ├── android-chrome-192x192.png
        ├── android-chrome-512x512.png
        ├── apple-touch-icon.png
        ├── favicon-16x16.png
        ├── favicon-32x32.png
        ├── favicon.ico
        └── 📁images
            ├── 📁posts       # Imágenes de posts
            └── 📁projects    # Imágenes de proyectos
        └── site.webmanifest  # Configuración PWA
    └── 📁src
        ├── 📁components      # Componentes reutilizables
        │   ├── 📁blog        # Componentes del blog
        │   ├── 📁layout      # Componentes de layout
        │   ├── 📁portfolio   # Componentes del portafolio
        │   └── 📁ui          # Componentes de interfaz
        ├── 📁icons           # Íconos SVG
        ├── 📁layouts         # Layouts del sitio
        │   ├── Layout.astro
        │   ├── MarkdownAbout.astro
        │   ├── MarkdownPostLayout.astro
        │   └── ProjectLayout.astro
        ├── 📁pages           # Páginas del sitio
        │   ├── about-me.md
        │   ├── 📁blog
        │   │   ├── index.astro
        │   │   ├── 📁posts
        │   │   ├── 📁tags
        │   │   └── 📁techs
        │   ├── index.astro
        │   ├── 📁portfolio
        │   │   └── 📁projects
        │   ├── robots.txt.ts
        │   └── rss.xml.js
        ├── 📁scripts
        │   └── menu.js
        ├── 📁styles
        │   └── global.css
        └── 📁utils
            └── languages.ts
    ├── .gitignore
    ├── astro.config.mjs
    ├── package.json
    ├── README.md
    └── tsconfig.json
```

---

## 🛠️ Stack Tecnológico

- **Framework**: Astro v5
- **UI Library**: Preact v10
- **Styling**: TailwindCSS v4
- **Interactividad**: Alpine.js v3
- **Carrusel**: Embla Carousel v8
- **Íconos**: astro-icon v1
- **Syntax Highlighting**: PrismJS v1
- **Animaciones**: tailwindcss-animated v2
- **Analytics**: @vercel/speed-insights v1

---

## ✨ Características

- 🚀 Generación estática con Astro (SSG)
- 💨 Hidratación parcial con Preact
- 🎨 Estilos con TailwindCSS utility-first
- 🌙 Soporte para modo oscuro
- 📱 Diseño responsivo
- 🔍 Sitemap generado automáticamente
- 📡 Feed RSS
- 📊 Vercel Speed Insights
- ✍️ Soporte para posts en Markdown
- 🧩 Sección de portafolio con proyectos

---

## 🚀 Inicio Rápido

### 1. Clonar el repositorio

```bash
git clone https://github.com/Dragmon/portfolio-astro.git
cd portfolio-astro
```

### 2. Instalar dependencias

```bash
npm install
```

### 3. Desarrollo local

```bash
npm run dev
```

### 4. Build para producción

```bash
npm run build
```

### 5. Preview del build

```bash
npm run preview
```

---

## ⚙️ Configuración

Los archivos de configuración principales son:

- `astro.config.mjs` — Configuración de Astro
- `tsconfig.json` — Configuración de TypeScript
- `src/styles/global.css` — Estilos globales

---

## 🎨 Personalización

### Agregar nuevas tecnologías o lenguajes

1. Coloca el ícono SVG en `src/icons/`. Se recomienda usar [SVGL](https://svgl.app/) como fuente de íconos de calidad.

2. Registra la tecnología en `src/utils/languages.ts`:

```ts
html: {
  name: "HTML 5",
  iconName: "html",
},
```

### Favicon

Genera los archivos necesarios en [favicon.io](https://favicon.io/favicon-converter/) y colócalos en `public/`:

```
public/
├── android-chrome-192x192.png
├── android-chrome-512x512.png
├── apple-touch-icon.png
├── favicon-16x16.png
├── favicon-32x32.png
├── favicon.ico
└── site.webmanifest
```

Recuerda actualizar `site.webmanifest` con el nombre y colores de tu sitio.

---

## 🚀 Despliegue

El sitio está configurado para Vercel, pero puede desplegarse en cualquier servicio de hosting estático (Netlify, Cloudflare Pages, etc.).

> **Nota:** La carpeta `dist/` no se sube al repositorio. Se genera automáticamente al ejecutar `npm run build`.

---

## 📄 Licencia

Este proyecto está licenciado bajo la [MIT License](./LICENSE).

El archivo `LICENSE` conserva el copyright original del template base, conforme a los términos de la licencia MIT.

---

## 🙏 Créditos

Este portafolio está basado en el template [NeonMint](https://github.com/EFEELE/NeonMint), creado por [Fernando Aldair Lopez Ponce](https://github.com/EFEELE).
