# Cafetería Aromas - Sitio Web Institucional

¡Bienvenido a mi repositorio! Este proyecto forma parte de mi formación en el curso de **Desarrollo Web Full Stack en Coderhouse**.

El sitio se actualiza clase a clase aplicando de forma progresiva los nuevos conceptos, estándares de maquetación y criterios de evaluación de la cursada.

---

## Estado del Proyecto y Avances Actuales

Actualmente el proyecto se encuentra en la fase de **Maquetación Avanzada de Grilla y Responsividad**.

### Módulos Implementados

- [x] **Estructura HTML5:** Semántica web, maquetación base, formularios, figuras y navegación entre páginas (`index.html` + páginas secundarias en `/pages/`).
- [x] **Estilos CSS3 (Introducción & Selectores):** 
  - Definición de paleta de colores y variables base.
  - Jerarquía tipográfica (Google Fonts 'Poppins').
  - Manejo de especificidad, cascada y selectores descendentes.
- [x] **Modelo de Caja & Flexbox:**
  - Reseteo global (`* { margin: 0; padding: 0; box-sizing: border-box; }`).
  - Barra de navegación (`<header>` / `<nav>`) flexible con alineación en extremos opuestos (`justify-content: space-between`, `align-items: center`).
  - Espaciados consistentes mediante `gap` y `padding` mínimo de seguridad.
- [x] **CSS Grid & Responsive Design (Mobile-First):**
  - Implementación de contenedores principales con `display: grid` y diseño base apilado (1 columna) para dispositivos móviles.
  - Uso de **`grid-template-areas`** para organizar semánticamente las secciones de contenido (`index.html` y la página de menú `services.html`).
  - **Breakpoint responsivo para escritorio (`min-width: 1024px`)**, transformando el layout a un diseño fluido de múltiples columnas.
- [ ] *[Próximamente]* Interactividad avanzada con JavaScript.

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
│   ├── foto_nuestro_local.jpg
│   ├── foto_el_equipo.jpg
│   ├── foto_menu.jpg
│   ├── foto_preguntas_frecuentes.jpg
│   └── foto_contacto.jpg
└── pages/
    ├── sobre-mi.html
    ├── servicios.html       (Menú)
    ├── proyectos.html       (Preguntas Frecuentes)
    └── contacto.html