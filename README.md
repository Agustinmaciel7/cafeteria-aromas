# Proyecto de Cursada - Desarrollo Web Full Stack

¡Bienvenido/a a mi repositorio! Este proyecto forma parte de mi formación en la cursada de Desarrollo Web Full Stack en Coderhouse.

La página se actualiza semanalmente a medida que avanzo en las clases y aplico nuevos módulos, técnicas y estándares de maquetación aprendidos.

---

## Estado del Proyecto y Avances

Actualmente el proyecto se encuentra en la fase de estructuración del layout flexible y control de espaciados.

### Módulos Implementados

- [x] **Estructura HTML5:** Semántica web, maquetación base, formularios, figuras y navegación entre páginas.
- [x] **Estilos CSS3 (Introducción & Selectores):** 
  - Definición de paleta de colores y variables básicas.
  - Jerarquía tipográfica (Google Fonts 'Poppins').
  - Manejo de especificidad, cascada y orden de reglas.
- [x] **Layouts & Espaciado (Box Model & Flexbox):**
  - Reseteo global del Box Model (`* { margin: 0; padding: 0; box-sizing: border-box; }`).
  - Barra de navegación (`<header>` / `<nav>`) maquetada con **Flexbox**, alineando logo y menú en extremos opuestos (`justify-content: space-between`, `align-items: center`).
  - Disposición de secciones y tarjetas organizadas mediante **Flexbox** y espaciados uniformes con `gap`.
  - Aplicación consciente de `padding` mínimo de 20px y `margin` para respiración y límites claros del contenido.
- [ ] *[Próximamente]* Layouts avanzados (CSS Grid).
- [ ] *[Próximamente]* Diseño Responsive (Media Queries).
- [ ] *[Próximamente]* Lógica e interacción con JavaScript.

---

## Estructura del Sitio

El proyecto cuenta con una estructura limpia organizada en subcarpetas:

```text
/
├── index.html
├── styles/
│   └── styles.css
├── assets/
│   ├── LOGO-CAFETERIA.jpg
│   └── ... (imágenes del sitio)
└── pages/
    ├── sobre-mi.html
    ├── servicios.html       (Preguntas Frecuentes)
    ├── proyectos.html       (Menú)
    └── contacto.html
