# ☕ Cafetería Aromas - Sitio Web Institucional

¡Bienvenido/a a mi repositorio! Este proyecto forma parte de mi formación en el curso de **Desarrollo Web Full Stack en Coderhouse** (Pre-entrega: Estructura avanzada y control de versiones con GitHub).

---

## 🔗 Enlaces del Proyecto

* **Repositorio de GitHub:** [https://github.com/Agustinmaciel7/cafeteria-aromas](https://github.com/Agustinmaciel7/cafeteria-aromas)
* **Sitio Desplegado:** *(Agregá aquí el link de tu sitio si ya lo publicaste en GitHub Pages, Netlify o Vercel)*

---

## 🚀 Estado del Proyecto y Avances Actuales

El proyecto integra de forma progresiva las buenas prácticas de maquetación semántica, estilos unificados y componentes interactivos responsivos.

### Módulos e Innovaciones Implementadas

- [x] **Estructura HTML5 Semántica:** Código limpio con indentación jerárquica y navegación fluida entre `index.html` y las 4 páginas secundarias (`/pages/`).
- [x] **Estilos CSS3 Personalizados & Especificidad Limpia:**
  - Reseteo universal del Box Model (`* { margin: 0; padding: 0; box-sizing: border-box; }`).
  - Paleta de colores corporativos e integración de Google Fonts (*Poppins*).
  - Transiciones suaves (`transition: all 0.3s ease`), estados interactivos (`:hover`, `:active`) y **ausencia total de estilos `inline`**.
- [x] **Integración y Personalización de Bootstrap (v5.3+ vía CDN):**
  - **Navbar responsiva:** Menú hamburguesa funcional con diseño corporativo unificado.
  - **Carrusel de especialidades:** Optimizado con captions visibles y lectura adaptada a pantallas chicas (*Mobile-First*).
  - **Componente Badges:** Incorporación de insignias distintivas (*"Más Vendido"*, *"Próximamente!"*, *"Recomendado"*) en las tarjetas de la página de inicio para mejorar la jerarquía visual.
  - **Formularios Interactivos:** Uso de componentes nativos como **Floating Labels**, **Form Select** para categorización de consultas y **Form Check** sin sobrecargar la hoja de CSS.
- [x] **Diseño Responsivo (Mobile-First):** Vistas completamente adaptadas a móviles y escritorio con Breakpoints en media queries.
- [x] **Control de Versiones Profesional con Git & GitHub:** Historial de commits descriptivos por consola respetando convenciones habituales (`feat:`, `style:`, `refactor:`).

---

## 📁 Estructura de Archivos y Rutas Relativas

```text
/
├── index.html                  # Página de inicio con tarjetas y badges
├── README.md                   # Documentación principal del repositorio
├── styles/
│   └── styles.css              # Hoja de estilos unificada y depurada
├── assets/                     # Recursos gráficos e imágenes del sitio
│   ├── LOGO-CAFETERIA.jpg
│   ├── foto_nuestro_local.jpg
│   ├── foto_el_equipo.jpg
│   ├── foto_menu.jpg
│   ├── foto_preguntas_frecuentes.jpg
│   ├── foto_contacto.jpg
│   ├── carousel-espresso.jpg
│   ├── carousel-capuchino.jpg
│   ├── carousel-flatwhite.jpg
│   └── carousel-avocadotoast.jpg
└── pages/                      # Páginas secundarias del sitio
    ├── sobre-mi.html           # Sobre Nosotros / Historia del local
    ├── servicios.html          # Menú y especialidades (Carrusel)
    ├── proyectos.html          # Preguntas Frecuentes y Formulario interactivo
    └── contacto.html           # Canales de atención y tarjetas de contacto