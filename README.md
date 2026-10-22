Markdown
# ☕ Cafetería Aromas - Sitio Web Institucional

¡Bienvenido/a a mi repositorio! Este proyecto forma parte de mi formación en el curso de **Desarrollo Web Full Stack en Coderhouse** Anteúltima Entrega: SEO On-Page, Accesibilidad y Reestructuración de Interfaces.

---

## 🔗 Enlaces del Proyecto

* **Repositorio de GitHub:** [https://github.com/Agustinmaciel7/cafeteria-aromas](https://github.com/Agustinmaciel7/cafeteria-aromas)
* **Sitio Desplegado:** [https://agustinmaciel7.github.io/cafeteria-aromas/](https://agustinmaciel7.github.io/cafeteria-aromas/)

---

## 🚀 Estado del Proyecto y Reestructuración Visual

El proyecto cuenta con un maquetado 100% responsivo, optimizaciones SEO de etiquetas y accesibilidad web, junto con una arquitectura de diseño refinada en cada vista.

### 🛠️ Características Implementadas

- [x] **SEO On-Page & Accesibilidad (Módulo Actual):**
  - <title> enriquecidos con palabras clave estratégicas por página.
  - Etiquetas <meta name="description"> personalizadas en el <head> de los 5 archivos HTML.
  - Textos alternativos (alt) explicativos en todas las imágenes del sitio.
  - Jerarquía semántica única (<h1> principal) y contraste cromático accesible (WCAG AA).
- [x] **Reestructuración de Vistas:**
  - **Inicio (index.html):** Maquetación en 2 columnas con imagen principal nivelada y *3D Flip Cards* interactivas.
  - **Sobre Nosotros (pages/sobre-mi.html):** Diseño editorial de una sola columna, desarrollo narrativo con fechas (2018-2026) y foto destacada del equipo.
  - **Menú (pages/servicios.html):** Carrusel de especialidades con altura pareja a 380px y grilla de categorías.
  - **Preguntas Frecuentes (pages/proyectos.html):** Formato Pregunta y Respuesta con tarjetas directas.
  - **Contacto (pages/contacto.html):** Layout simétrico con imagen en portada, canales telefónicos/WhatsApp y formulario compacto.
- [x] **Arquitectura SCSS Intacta:** Organización en partials (utilities/, base/, layout/ y components/) compilados automáticamente a styles/styles.css mediante main.scss.

---

## 📁 Estructura del Proyecto

```text
/
├── index.html                  # Página de inicio (Hero section & Flip Cards)
├── README.md                   # Documentación oficial del repositorio
├── styles/
│   └── styles.css              # Hoja de estilos final compilada por Sass
├── scss/                       # Código fuente SCSS modular
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
├── assets/                     # Recursos gráficos con nombres descriptivos
└── pages/                      # Páginas secundarias del sitio
    ├── sobre-mi.html           # Sobre Nosotros (Historia narrativa)
    ├── servicios.html          # Menú de especialidades (Carrusel)
    ├── proyectos.html          # Preguntas Frecuentes
    └── contacto.html           # Canales de atención y formulario

    🛠️ Tecnologías Utilizadas
HTML5 & CSS3 (Semántico y Accesible)

Sass / SCSS (Compilador con Node.js)

Bootstrap v5.3+ (CDN)

AOS Library (Animate On Scroll)

Git & GitHub


Autor
Agustín — Desarrollador Web en formación