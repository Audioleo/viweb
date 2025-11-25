# ViWeb CSS Framework — v1.0

ViWeb es un mini-framework CSS modular y ligero, diseñado para ser claro, escalable y fácil de extender.
Se basa en dos pilares:

1. **Diseño dividido en capas** (Base → Layout → UI → Utilities)
2. **CSS modular** (cada módulo es independiente y evoluciona por separado)

---

## 🚀 Características principales

- **Variables globales**: tipografía, colores, espaciado y radios unificados.
- **Reset / Base** minimalista y sin romper estilos nativos.
- **Grid system propio** basado en CSS Grid (`.vw-grid`, `.vw-col-*`).
- **Componentes UI ligeros**: botones, tarjetas, aside-nav, etc.
- **Helpers/Utilities** para padding, margin, gaps, sizes y más.
- **Enfoque moderno** sin soporte legacy innecesario.
- **Fácil de extender** gracias a su estructura modular.

---

## 📁 Estructura de carpetas

```
viweb/
│
├── base.css
├── layout.css
├── ui.css
├── helpers.css
└── theme.css
```

---

## 📦 Instalación

```html
<link rel="stylesheet" href="viweb/base.css">
<link rel="stylesheet" href="viweb/layout.css">
<link rel="stylesheet" href="viweb/ui.css">
<link rel="stylesheet" href="viweb/helpers.css">
```

Opcional:

```html
<link rel="stylesheet" href="viweb/theme.css">
```

---

## 🧱 Filosofía del Framework

### 1. En capas
- Base  
- Layout  
- UI  
- Helpers  

### 2. Modular
Cada archivo puede actualizarse o sustituirse sin afectar los demás.

---

## 📐 Layout: Grid y Columnas

```html
<div class="vw-grid vw-grid-3r">
    <div class="vw-col-1">Col 1</div>
    <div class="vw-col-1">Col 2</div>
    <div class="vw-col-1">Col 3</div>
</div>
```

---

## 🎨 UI Components

```html
<button class="ui-btn ui-btn-primary">Guardar</button>
```

```html
<div class="ui-card">
    <h3 class="ui-card-title">Título</h3>
    <p>Contenido de la tarjeta</p>
</div>
```

---

## 🔧 Helpers / Utilities

```
.pad-1      → padding: .5rem
.pad-2      → padding: 1rem
.mar-b-1    → margin-bottom: .5rem
.w-100      → width: 100%
.h-full     → height: 100%
.flex       → display: flex
.grid       → display: grid
```

---

## 🌙 Tema / Modo oscuro (opcional)

```css
:root[data-theme="dark"] {
    --vw-color-bg: #111;
    --vw-color-text: #ddd;
}
```

---

## 📄 Licencia

MIT

---

## 👤 Autor

**Leo Cabrera**
