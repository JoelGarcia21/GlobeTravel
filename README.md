# globetravel — Sitio Web de Turismo
## Práctica HTML5 + CSS

## Estructura del Proyecto
│
├── index.html              ← Página Principal (Home)
│
├── pages/                  ← paginas del sitio
│   ├── destinos.html           ← Galería de destinos + filtros CSS
│   ├── agencias.html           ← Tarjetas flip
│   ├── precios.html            ← Comparador de precios + tooltips
│   ├── blog.html               ← Blog estilo revista + filtros + comentarios
│   └── contactenos.html        ← Formulario avanzado
│
├── css/
│   ├── agenciasstyle.css       ← Variables CSS (colores, tema, espaciado)
│   ├── blogstyle.css            ← Reset + tipografía general
│   ├── contactenos.css          ← Header + Footer + estructura global
│   ├── destinostyle.css      ← Botones, cards, tooltips, modales
│   ├── preciosstyle.css        ← Grid de destinos + filtros CSS
│   └── style.css        ← Flip cards + rating estrellas
│
├── js/
│   └── darktheme.js             ← Modo oscuro
│
└── assets/
    ├── images/             ← imágenes del sitio
    └── video/              ← videos del sitio

## Sistema de Diseño
### Paleta de colores
| Variable | Valor | Uso |
|---|---|---|
| `--color-primary` | `#0A3D2E` | Verde selva — color principal |
| `--color-accent` | `#E8A020` | Oro cálido — CTAs y highlights |
| `--color-secondary` | `#1B4F6B` | Azul océano — acentos secundarios |

### Tipografía
- **Display**: Playfair Display (títulos hero, headings principales)
- **Heading**: Cormorant Garamond (subtítulos, citas)
- **Body**: DM Sans (texto corriente, UI)
- **Accent**: Bebas Neue (números, estadísticas, bandas de texto)

## Cómo correr el proyecto
1. Abrí la carpeta en **Visual Studio Code**
2. Instalá la extensión **Live Server**
3. Hacé clic derecho en `index.html` → **"Open with Live Server"**

## Deploy
- **GitHub Pages**: `Settings → Pages → Source: main branch`
