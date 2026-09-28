# ☕ Cafetería Aromas - Sitio Web Institucional

¡Bienvenido a mi repositorio! Este proyecto forma parte de mi formación en el curso de **Desarrollo Web Full Stack en Coderhouse**.

El sitio se actualiza clase a clase aplicando de forma progresiva los nuevos conceptos, estándares de maquetación y criterios de evaluación de la cursada.

---

## Estado del Proyecto y Avances Actuales

Actualmente el proyecto se encuentra en la fase de **Maquetación Avanzada con Bootstrap y Responsive Design**.

### Módulos Implementados

- [x] **Estructura HTML5:** Semántica web, formularios limpios, figuras, navegación entre páginas (`index.html` + páginas secundarias en `/pages/`) y componentes adaptados.
- [x] **Estilos CSS3 & Buenas Prácticas:** 
  - Definición de paleta de colores y variables institucionales.
  - Jerarquía tipográfica (Google Fonts 'Poppins').
  - Manejo de especificidad y cascada (evitando `!important` y estilos en línea en el HTML).
- [x] **Modelo de Caja, Flexbox & CSS Grid:**
  - Reseteo global (`* { margin: 0; padding: 0; box-sizing: border-box; }`).
  - Barra de navegación flexible y componentes interactivos.
  - Diseño base apilado (Mobile-First) y grillas con `grid-template-areas`.
- [x] **Integración de Bootstrap (v5.3.2 vía CDN):**
  - Implementación del componente `navbar` responsivo y carrusel de especialidades optimizado.
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
    └── contacto.html        (Canales de atención)