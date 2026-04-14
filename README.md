# globetravel — Sitio Web de Turismo
## Práctica HTML5 + CSS

## Estructura del Proyecto
globettravel/
│
├── index.html                  # Página Principal (Home)
│
├── pages/                     # Páginas del sitio
│   ├── destinos.html          # Galería de destinos + filtros CSS
│   ├── agencias.html          # Tarjetas flip
│   ├── precios.html           # Comparador de precios + tooltips
│   ├── blog.html              # Blog estilo revista + filtros + comentarios
│   └── contactenos.html       # Formulario avanzado
│
├── css/
│   ├── agenciesstyle.css      # Estilos agencias (flip cards + rating)
│   ├── blogstyle.css          # Estilos blog (grid revista + comentarios)
│   ├── contactenos.css        # Formulario + modal + validación
│   ├── destinostyle.css       # Destinos (grid + filtros)
│   ├── preciosstyle.css       # Tabla comparativa + tooltips
│   └── style.css              # Estilos globales (header/footer/base)
│
├── js/
│   └── darktheme.js           # Modo oscuro / claro
│
└── assets/
    ├── images/                # Imágenes del sitio
    └── video/                 # Videos del sitio

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
