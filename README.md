# IMPCORE Records - Electronic Music Label Website

Un sitio web moderno y minimalista para un sello discográfico de música electrónica, construido con Next.js, TypeScript y Tailwind CSS.

## 🎵 Características

- **Diseño Dark & Minimalista**: Inspirado en mutual-rytm.com
- **Reproductor Global**: Música persistente entre páginas
- **Totalmente Responsivo**: Optimizado para todos los dispositivos
- **Performance Optimizada**: ISR, optimización de imágenes y Core Web Vitals
- **CMS Ready**: Preparado para integración con Sanity/Contentful
- **SEO Optimizado**: Metadatos dinámicos y estructura semántica

## 🛠️ Tecnologías

- **Framework**: Next.js 15 (App Router)
- **Lenguaje**: TypeScript
- **Estilos**: Tailwind CSS
- **Estado Global**: Zustand
- **Animaciones**: Framer Motion
- **Iconos**: Lucide React
- **Deployment**: Vercel Ready

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js 18+ 
- npm, pnpm, yarn o bun

### Instalación

```bash
# Instalar dependencias
npm install

# Ejecutar en modo desarrollo
npm run dev

# Construir para producción
npm run build

# Ejecutar en producción
npm start
```

### Scripts Disponibles

```bash
npm run dev          # Modo desarrollo
npm run build        # Construir para producción
npm run start        # Ejecutar en producción
npm run lint         # Linter ESLint
```

## 📁 Estructura del Proyecto

```
src/
├── app/                 # App Router (Next.js 13+)
│   ├── layout.tsx      # Layout principal
│   ├── page.tsx        # Página de inicio
│   ├── releases/       # Páginas de lanzamientos
│   ├── artists/        # Páginas de artistas
│   └── globals.css     # Estilos globales
├── components/         # Componentes reutilizables
│   ├── ui/            # Componentes UI base
│   ├── Header.tsx     # Navegación principal
│   ├── Footer.tsx     # Pie de página
│   ├── MusicPlayer.tsx # Reproductor global
│   └── ReleaseCard.tsx # Tarjeta de lanzamiento
├── store/             # Estado global (Zustand)
├── types/             # Tipos TypeScript
├── lib/               # Utilidades
└── styles/            # Estilos adicionales
```

## 🎨 Guía de Diseño

### Paleta de Colores
- **Fondo Principal**: `#111111` (Negro casi puro)
- **Texto Principal**: `#F5F5F5` (Blanco roto)
- **Acento Principal**: `#0066FF` (Azul eléctrico)
- **Acento Secundario**: `#FF3366` (Rojo intenso)
- **Cards**: `#1A1A1A` / `#222222` (hover)

### Tipografía
- **Fuente Principal**: Inter (Google Fonts)
- **Estilo**: Sans-serif moderno y limpio
- **Tracking**: Generoso en encabezados para look "de diseño"

## 🚀 Deployment

### Vercel (Recomendado)
```bash
npm i -g vercel
vercel
```

---

**IMPCORE Records** - Pushing the boundaries of electronic music 🎵
