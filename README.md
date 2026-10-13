# ☕ Cafetería Aromas - Sitio Web Institucional

¡Bienvenido/a a mi repositorio! Este proyecto forma parte de mi formación en el curso de **Desarrollo Web Full Stack en Coderhouse** (Entrega: Arquitectura SCSS y Refactorización Completa)[cite: 2].

---

## 🔗 Enlaces del Proyecto

* **Repositorio de GitHub:** [https://github.com/Agustinmaciel7/cafeteria-aromas](https://github.com/Agustinmaciel7/cafeteria-aromas)[cite: 7]
* **Sitio Desplegado:** [https://agustinmaciel7.github.io/cafeteria-aromas/](https://agustinmaciel7.github.io/cafeteria-aromas/)

---

## 🚀 Estado del Proyecto y Refactorización SCSS

El sitio ha sido refactorizado por completo migrando de CSS manual a una arquitectura modular en **Sass (SCSS)** organizada en partials y compilada de forma automática.

### 🛠️ Características Principales de la Refactorización

- [x] **Zero CSS Manual:** Todo el CSS final se genera exclusivamente por la compilación de archivos `.scss`.
- [x] **Estructura Modular Obligatoria:**
  - `utilities/`: Variables de colores, fuentes y sombras (`_variables.scss`) y mixins reutilizables (`_mixins.scss`)[cite: 1].
  - `base/`: Reseteo universal (`_base.scss`) y tipografía global (`_tipografia.scss`)[cite: 1].
  - `layout/`: Estilos de header, footer y personalización de Navbar de Bootstrap (`_header.scss`, `_footer.scss`, `_nav.scss`)[cite: 1].
  - `components/`: Partials para elementos repetibles (`_buttons.scss`, `_cards.scss`)[cite: 1].
- [x] **Archivo Maestro `main.scss`:** Único punto de entrada que organiza la compilación mediante la directiva `@use`[cite: 1, 2].
- [x] **Fidelidad Visual:** El sitio conserva exactamente su diseño y estética previa[cite: 1, 2].

---

## 📁 Estructura del Proyecto

```text
/
├── index.html                  # Página de inicio principal
├── README.md                   # Documentación del repositorio
├── styles/
│   └── styles.css              # CSS compilado por Sass
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
├── assets/                     # Recursos gráficos e imágenes institucionales
└── pages/                      # Páginas secundarias (sobre-mi, servicios, proyectos, contacto)
🛠️ Tecnologías UtilizadasHTML5 & CSS3Sass / SCSS (Compilador vía Node.js)[cite: 1, 2]Bootstrap v5.3+ (CDN)[cite: 1]Git & GitHub   
Autor Agustín — Desarrollador Web en formación