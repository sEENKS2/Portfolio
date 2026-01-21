# 👨‍💻 Portfolio - Leonel Luchini

Este repositorio contiene el código fuente de mi **Portfolio Profesional**, diseñado para mostrar mi perfil como **Analista de Sistemas** y desarrollador de software.

El sitio es una **Single Page Application (SPA)** estática, totalmente responsiva y optimizada, que presenta mi experiencia, habilidades técnicas y proyectos destacados de una manera limpia y moderna.

🔗 **Demo Online:** [leonel-luchini.github.io](https://seenks2.github.io/Portfolio/)

---

## 🎨 Diseño y Estética

Originalmente basado en la plantilla "Stellar", el diseño ha sido **profundamente refactorizado** para reflejar una identidad profesional, sobria y tecnológica (Tech/Minimalist).

### 🖌 Cambios de Estilo (Custom SASS)
* **Paleta de Colores:** Se migró de una estética genérica a un esquema **High-Tech**:
    * **Fondo:** `#F9FAFB` (Gris Hielo / Clean White)
    * **Acento:** `#3B82F6` (Tech Blue) para transmitir confianza y tecnología.
    * **Tipografía:** Se implementó **Poppins** para títulos y cuerpos de texto, mejorando la legibilidad.
* **UI Moderna:**
    * Implementación de "Cards" flotantes con bordes suaves (`border-radius: 12px`) y sombras sutiles.
    * Botones con estados *hover* interactivos y feedback visual.
    * Eliminación de modos "Legacy" (dark/light) para unificar la experiencia en un modo profesional diurno.

---

## 🚀 Tecnologías Utilizadas

* **HTML5 Semantic:** Estructura limpia y accesible.
* **SASS (SCSS):** Preprocesador CSS utilizado para la gestión de variables, mixins y arquitectura de estilos modular.
* **JavaScript (ES6+) & jQuery:** Para la lógica de navegación suave (Smooth Scroll), manejo de eventos y animaciones de entrada.
* **FontAwesome:** Iconografía vectorial para skills y redes sociales.
* **Formspree:** Integración de backend-less para el formulario de contacto funcional.

---

## 🛠 Instalación y Personalización

Si deseas clonar este repositorio para ver el código o realizar modificaciones:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/tu-usuario/portfolio.git](https://github.com/tu-usuario/portfolio.git)
    ```

2.  **Instalar dependencias (Opcional):**
    Si deseas modificar los estilos SASS, necesitarás tener instalado Sass:
    ```bash
    npm install -g sass
    ```

3.  **Compilar SASS:**
    El proyecto utiliza una arquitectura de archivos SCSS en `assets/sass/`. Para aplicar cambios en los estilos, ejecuta:
    ```bash
    sass assets/sass/main.scss assets/css/main.css
    ```

4.  **Ejecutar:**
    Simplemente abre el archivo `index.html` en tu navegador de preferencia. No requiere servidor backend.

---

## 📂 Estructura del Proyecto

```text
/
├── assets/
│   ├── css/           # Archivos CSS compilados (No editar directamente)
│   ├── sass/          # Archivos fuente SCSS
│   │   ├── libs/      # Variables (_vars.scss), Mixins y Funciones
│   │   └── main.scss  # Archivo principal de entrada
│   ├── js/            # Lógica de frontend (main.js, util.js)
│   └── webfonts/      # Iconos FontAwesome
├── images/            # Assets gráficos y capturas de proyectos
└── index.html         # Estructura principal
