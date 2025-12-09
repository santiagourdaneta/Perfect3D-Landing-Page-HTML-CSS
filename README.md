# 🎨 Perfect3D Landing Page (HTML/CSS Puros)

Landing Page estática diseñada para la **conversión y el rendimiento extremo**. Este proyecto demuestra cómo construir una página de aterrizaje moderna con **UX/UI impecable** y optimización de **Core Web Vitals (LCP, FID, CLS)**, utilizando únicamente **HTML y CSS** (sin dependencias de JavaScript).

## 🚀 Características Principales

* **Rendimiento Extremo:** Optimizado para la velocidad de carga (LCP) utilizando atributos `width`/`height` y `aspect-ratio` en el CSS.
* **Diseño Responsivo:** Arquitectura `Flexbox` y `CSS Grid` para una adaptación perfecta en cualquier dispositivo.
* **Micro-UX:** Transiciones CSS suaves (`:hover`) y un diseño limpio y moderno.
* **SEO Básico Integrado:** Uso de *Schema Markup* de Producto y metadatos limpios para una excelente visibilidad en motores de búsqueda.
* **Estructura Semántica:** Uso correcto de etiquetas HTML5 (`<header>`, `<main>`, `<footer>`, `<h1>`/`<h2>`) esencial para la accesibilidad y SEO.

## 🛠️ Cómo Ejecutarlo

1.  **Clonar el Repositorio:**
    ```bash
    git clone [https://github.com/santiagourdaneta/Perfect3D-Landing-Page-HTML-CSS](https://github.com/santiagourdaneta/Perfect3D-Landing-Page-HTML-CSS)
    ```
2.  **Abrir el Archivo:** Simplemente abre el archivo `index.html` en tu navegador favorito.
3.  **Despliegue:** Dado que no usa JavaScript, el despliegue es trivial. Puedes usar servicios de hosting estático como GitHub Pages, Netlify o Vercel con configuración cero.

## 📝 Notas de Optimización (Core Web Vitals)

Para lograr un rendimiento perfecto sin JS, se tomaron las siguientes decisiones:

1.  **Imágenes Uniformes:** Todas las imágenes de la galería usan el contenedor con la propiedad `aspect-ratio: 1 / 1;` y `object-fit: cover;` en CSS, lo que garantiza que no haya **CLS (Cumulative Layout Shift)**.
2.  **Etiquetas de Dimensión:** Se especificaron `width="400"` y `height="400"` directamente en las etiquetas `<img>` para que el navegador reserve el espacio antes de la carga.

---

Labels / Tags	
landing-page, html-css, frontend, seo-optimization, core-web-vitals, design-asset, 3d-graphics	

Hashtags
#Perfect3D #LandingPage #HTMLCSS #SEO #CoreWebVitals #WebDesign	