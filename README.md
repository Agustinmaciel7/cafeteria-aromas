# ☕ Cafetería Aromas - Sitio Web Estático Institucional

¡Bienvenido/a al repositorio oficial de Cafetería Aromas! Este proyecto es el trabajo final integrador desarrollado para la certificación del curso de Desarrollo Web Full Stack en Coderhouse.

---

## 🔗 Enlaces del Proyecto

* Repositorio en GitHub: https://github.com/Agustinmaciel7/cafeteria-aromas
* Sitio Desplegado: https://cafeteria-aromas.vercel.app/

---

## 🚀 Resumen del Proyecto y Criterios Técnicos Aplicados

El sitio consiste en una plataforma estática de 5 páginas completamente responsiva, maquetada bajo estándares de HTML5 semántico, estilada con una arquitectura SCSS modular compilada, potenciada con componentes de Bootstrap v5.3, animaciones dinámicas y optimizada en accesibilidad y SEO On-Page.

### 🛠️ Especificaciones Técnicas

#### 1. Estructura HTML5 y Accesibilidad
* Semántica limpia: Uso estricto de etiquetas contenedoras (<header>, <nav>, <main>, <section>, <article>, <figure>, <footer>).
* Jerarquía de títulos: Un único <h1> principal por página seguido ordenadamente de <h2> y <h3>.
* Accesibilidad WCAG AA: Relación de contraste adecuada entre textos y fondos, e inclusión obligatoria de atributos alt descriptivos e individuales en el 100% de las imágenes del proyecto.

#### 2. SEO On-Page Optimizado
* Etiquetas <title>: Títulos representativos y únicos por página con integración de palabras clave principales.
* Etiquetas <meta description>: Metadescripciones personalizadas e individuales en los 5 archivos HTML.
* Etiquetas <meta keywords>: Inclusión de términos clave acordes al contenido específico de cada sección.

#### 3. Arquitectura SCSS Modular (Zero CSS Manual)
* Punto de entrada: Archivo maestro scss/main.scss estructurado exclusivamente con la directiva @use sin escribir CSS directo.
* Organización en Partials:
  * utilities/: Variables institucionales de color, tipografía y sombras (_variables.scss) y mixins con parámetros (_mixins.scss).
  * base/: Reseteo universal del Box Model (_base.scss) e integración de Google Fonts Poppins (_tipografia.scss).
  * layout/: Cabecera, pie de página y personalización de la barra de navegación (_header.scss, _nav.scss, _footer.scss).
  * components/: Estilos de botones, tarjetas interactivas y carrusel (_buttons.scss, _cards.scss).
* Recursos avanzados de SCSS: Uso de variables, nesting, mixins con parámetros, @extend y compilación automática hacia styles/styles.css.

#### 4. Responsividad y Animaciones
* Diseño Mobile-First (100% Responsivo): Visualización fluida sin scroll horizontal ni superposición de elementos, probado en dispositivos desde 375px hasta pantallas de escritorio de 1400px+.
* Integración de Bootstrap (v5.3 vía CDN): Navbar responsiva con menú hamburguesa móvil estilizada desde SCSS, carrusel de especialidades a altura fija y grillas.
* Animación Nativa SCSS: Efectos 3D Flip Cards interactivas en la página de inicio, transiciones suaves y animaciones con @keyframes.
* Animación por Librería: Integración de la librería AOS (Animate On Scroll) vía CDN aplicada con atributos data-aos en las distintas vistas.

---

## 📁 Estructura de Archivos del Repositorio

/
├── index.html                  # Inicio (Hero section y 3D Flip Cards)
├── README.md                   # Documentación oficial del proyecto
├── assets/                     # Imágenes institucionales en kebab-case
├── styles/
│   └── styles.css              # Hoja de estilos final compilada por Sass
├── scss/                       # Código fuente SCSS
│   ├── main.scss              # Punto de entrada principal (@use)
│   ├── utilities/
│   │   ├── _variables.scss
│   │   └── _mixins.scss
│   ├── base/
│   │   ├── _tipografia.scss
│   │   └── _base.scss
│   ├── layout/
│   │   ├── _header.scss
│   │   ├── _nav.scss
│   │   └── _footer.scss
│   └── components/
│       ├── _buttons.scss
│       └── _cards.scss
└── pages/                      # Páginas secundarias del sitio
    ├── sobre-mi.html           # Sobre Nosotros (Historia y equipo)
    ├── servicios.html          # Menú de especialidades (Carrusel y categorías)
    ├── proyectos.html          # Preguntas Frecuentes (Q&A)
    └── contacto.html           # Canales de atención directa y formulario
    
---

## 🛠️ Tecnologías Utilizadas

* HTML5 & CSS3
* Sass / SCSS (Compilador con Node.js)
* Bootstrap v5.3+ (CDN)
* AOS Library (Animate On Scroll)
* Git & GitHub (Control de versiones)
* Vercel / Netlify (Servidor y despliegue en producción)

---

## 👤 Autor

* Agustín — Desarrollador Web en formación