## GlobeTravel

Este proyecto fue desarrollado utilizando únicamente **HTML5 y CSS**, con el objetivo de simular un sitio web real de turismo (GlobeTravel), aplicando buenas prácticas de diseño, accesibilidad y técnicas modernas de CSS.

---

## Decisiones de diseño

### 1. Uso de diseño oscuro como base
Se eligió un **tema oscuro como diseño principal** debido a que:

- Mejora la estética visual para contenido turístico moderno
- Reduce fatiga visual en navegación prolongada
- Permite resaltar mejor imágenes de destinos

Se implementó mediante **CSS Variables**, lo que permite cambiar fácilmente entre temas.

---

### 2. Sistema de variables CSS (Custom Properties)

Se utilizó `:root` para centralizar el diseño:

- Colores principales
- Fondos
- Tipografía
- Estados (hover, active) 

---

### 3. Estructura modular del CSS

El CSS se separa por páginas:

- `agenciasstyle.css`
- `blogstyle.css`
- `contactenos.css`
- etc.

---

## Funcionalidades implementadas

### Agencias
- Tarjetas con efecto **flip 3D**
- Rating visual con estrellas CSS
- Hover interactivo

---

### Contacto
- Validación en tiempo real con `:valid` y `:invalid`
- Floating labels (UX moderno)
- Spinner CSS en botón de envío
- Modal de confirmación con `:target`

---

### Precios
- Tabla comparativa con hover highlight
- Tooltips informativos hechos en CSS puro
- Interacciones sin JavaScript

---

### Blog
- Layout tipo revista con **CSS Grid avanzado**
- Sistema de filtros usando `radio buttons + CSS`
- Comentarios con avatares generados con CSS
- Animación tipo scroll reveal con keyframes

---

## Decisiones técnicas importantes

### ✔ CSS puro sin frameworks
Se evitó Bootstrap o librerías externas para demostrar dominio de:

- Flexbox
- Grid
- Animaciones
- Selectores avanzados

---

### ✔ Animaciones ligeras
Se priorizó rendimiento usando:

- `transform`
- `opacity`
- `transition`

Evitando animaciones costosas como cambios de layout.

---

### ✔ Accesibilidad básica
- Uso de etiquetas semánticas (`header`, `main`, `section`)
- Inputs con `label` asociado
- Estados visuales en focus/hover

---

## Resultado final

El proyecto simula una **web profesional de turismo moderna**, con:

- UI consistente
- Animaciones suaves
- Componentes reutilizables
- Diseño responsive
- Interactividad sin frameworks

## Cómo correr el proyecto
1. Abrí la carpeta en **Visual Studio Code**
2. Instalá la extensión **Live Server**
3. Hacé clic derecho en `index.html` → **"Open with Live Server"**

## Deploy
- **GitHub Pages**: `Settings → Pages → Source: main branch`
