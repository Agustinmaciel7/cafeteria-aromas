# ☕ Cafetería Aromas - Sitio Web Institucional

¡Bienvenido/a a mi repositorio! Este proyecto forma parte de mi formación en el curso de **Desarrollo Web Full Stack en Coderhouse** (Entrega: Animaciones y Full-Responsive).

---

## 🔗 Enlaces del Proyecto

* **Repositorio de GitHub:** [Ver Repositorio en GitHub](https://github.com/Agustinmaciel7/cafeteria-aromas)[cite: 7, 10]
* **Sitio Desplegado:** [Ver Sitio Web en GitHub Pages](https://agustinmaciel7.github.io/cafeteria-aromas/)[cite: 7, 10]

---

## 🚀 Estado del Proyecto y Avances Actuales (Módulo 8)

El sitio cuenta con una maquetación 100% responsiva (de 375px a 1400px+) e incorpora animaciones nativas en SCSS junto con interacciones mediante librerías externas en los 5 archivos HTML[cite: 1, 2, 5].

### 🛠️ Características Implementadas

- [x] **Librería de Animaciones Externa (AOS):** Integración de **Animate On Scroll** vía CDN en los 5 archivos HTML con atributos `data-aos="fade-up"`, `data-aos="zoom-in"` y `data-aos="fade-down"`[cite: 5].
- [x] **SCSS Avanzado:**
  - Mixins con parámetros: `@mixin transicion-suave($prop, $duracion, $timing)` y `@mixin respond-to($breakpoint)`[cite: 1].
  - Herencia de estilos con `@extend`: Uso del placeholder `%tarjeta-base` en componentes[cite: 1].
- [x] **Animación Nativa desde SCSS:** Definición de la regla `@keyframes flotarSutil` para lograr un movimiento dinámico y sutil al pasar el cursor (`:hover`) sobre las tarjetas[cite: 1, 2].
- [x] **Responsividad Completa (Mobile-First):**
  - **Base (Mobile 375px):** Sin media query, disposición apilada y fluida.
  - **Tablet (`@media (min-width: 768px)`):** Ajuste de grillas intermedias de 2 columnas.
  - **Escritorio (`@media (min-width: 1024px)`):** Layout completo de múltiples columnas y márgenes centrados.
  - **Cero scroll horizontal:** Ajustes adaptativos para asegurar la correcta lectura sin superposiciones en todas las resoluciones.
- [x] **Arquitectura SCSS Intacta:** Preservación de la estructura modular (`utilities/`, `base/`, `layout/` y `components/`) con `main.scss` como único punto de entrada[cite: 1, 2].

---

## 📁 Estructura del Proyecto

```text
/
├── index.html                  # Página de inicio principal
├── README.md                   # Documentación oficial del repositorio
├── styles/
│   └── styles.css              # CSS final compilado por Sass
├── scss/                       # Código fuente SCSS
│   ├── main.scss              # Punto de entrada principal (@use)
│   ├── utilities/
│   │   ├── _variables.scss
│   │   └── _mixins.scss        # Mixins con parámetros
│   ├── base/
│   │   ├── _tipografia.scss
│   │   └── _base.scss          # Estilos globales y breakpoints
│   ├── layout/
│   │   ├── _header.scss
│   │   ├── _nav.scss
│   │   └── _footer.scss
│   └── components/
│       ├── _buttons.scss
│       └── _cards.scss        # @extend, @keyframes y tarjetas
├── assets/                     # Imágenes e imatotipos institucionales
└── pages/                      # Páginas secundarias (sobre-mi, servicios, proyectos, contacto)
🛠️ Tecnologías UtilizadasHTML5 & CSS3Sass / SCSS (Compilador vía Node.js)   Bootstrap v5.3+ (CDN)   AOS Library (Animate On Scroll)Git & GitHub[cite: 2, 7, 10]
Autor: Agustín — Desarrollador Web en formación