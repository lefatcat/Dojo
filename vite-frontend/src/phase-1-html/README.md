# 🌐 Landing Page Profesional | LeFatCat Society

Este proyecto corresponde a la **primera fase de desarrollo de FatCat Society**: una **landing page profesional** diseñada con HTML5 semántico, enfocada en mostrar **servicios digitales**, **beneficios**, **portafolio de proyectos**, **sobre nosotros** y **preguntas frecuentes (FAQ)**.  

La página está optimizada para **SEO On-Page**, **accesibilidad web**, y preparada para escalar en fases posteriores con **CSS, JavaScript y frameworks modernos**.

---

## 📖 Descripción General

El objetivo de esta fase es construir la **base sólida del front-end**:
- HTML limpio y semántico.
- Estructura clara y jerárquica.
- Optimización SEO (metadatos, Open Graph, Twitter Card y JSON-LD).
- Preparación para interactividad y estilos en futuras fases.

---

## 🗂️ Estructura del Proyecto

El archivo principal es `index.html`, que contiene toda la estructura semántica de la landing page:

```plaintext
index.html
├── <head>
│   ├── <meta> (SEO, autor, viewport, description, charset, keywords)
│   ├── Open Graph (Facebook, Instagram)
│   ├── Twitter Card
│   ├── JSON-LD (Organization, WebSite, WebPage, FAQPage)
│   └── <title>
│
├── <body>
│   ├── <header>
│   │   └── Logo + Navegación principal (<nav>)
│   │
│   ├── <main>
│   │   ├── Hero Section (h1 + CTA)
│   │   ├── Servicios (<section id="services">)
│   │   │   └── Artículos con descripciones de cada servicio
│   │   │
│   │   ├── Beneficios (<section id="benefits">)
│   │   │   └── Figuras (<figure> + <figcaption>) con ventajas competitivas
│   │   │
│   │   ├── Portafolio (<section id="portfolio">)
│   │   │   └── Galería de proyectos con imágenes y enlaces
│   │   │
│   │   ├── Sobre Nosotros (<section id="about">)
│   │   │   └── Filosofía, valores y presentación del equipo
│   │   │
│   │   └── Preguntas Frecuentes (FAQ - <section id="faq">)
│   │       └── Bloques <details>/<summary> con preguntas y respuestas
│   │
│   └── <footer>
│       └── (Pendiente de implementación: contacto, redes sociales, políticas)
```

---

## 🔑 Características Clave

- **HTML5 semántico**: uso correcto de `<header>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<figcaption>`, `<details>` y `<footer>`.
- **SEO avanzado**:
  - Meta tags (`title`, `description`, `author`, `keywords`).
  - Jerarquía de headings optimizada (`<h1>` único, seguido por `<h2>` y `<h3>`).
  - JSON-LD con estructura **Organization**, **WebSite**, **WebPage** y **FAQPage**.
- **Social Media Ready**:
  - Open Graph para Facebook e Instagram.
  - Twitter Card para vistas previas optimizadas.
- **Accesibilidad**:
  - Atributos `aria-label`, `aria-labelledby` y `role`.
  - Imágenes con texto alternativo (`alt`).
- **Preparación para escalabilidad**:
  - Código modular.
  - Listo para integración de **CSS/Tailwind** y **JavaScript** en fases siguientes.

---

## 🧩 Secciones del Sitio

1. **Header + Navegación**  
   Logo + menú principal con enlaces ancla a cada sección.  

2. **Hero Section**  
   Mensaje principal con `<h1>`, subtítulo y botón de llamada a la acción (CTA).  

3. **Servicios**  
   Tarjetas en `<article>` describiendo cada servicio digital ofrecido.  

4. **Beneficios**  
   Presentación visual con `<figure>` y `<figcaption>`, mostrando ventajas competitivas.  

5. **Portafolio**  
   Galería de proyectos con `<article>` + imágenes `<img>` + enlaces a los trabajos.  

6. **Sobre Nosotros**  
   Sección descriptiva con `<h2>`, historia, misión y valores de LeFatCat Society.  

7. **Preguntas Frecuentes (FAQ)**  
   Interactividad nativa con `<details>/<summary>` para expandir respuestas.  

8. **Footer (pendiente)**  
   Se integrará posteriormente: redes sociales, contacto y enlaces legales.

---

## 📈 Buenas Prácticas Aplicadas

- Uso de **HTML semántico** y accesible.  
- **SEO On-Page** avanzado (metadatos + microdatos JSON-LD).  
- **Estructura modular** pensada para escalar.  
- **Accesibilidad** con etiquetas ARIA y navegación asistida.  
- **Optimización futura**: imágenes en `.webp`/`.avif`, minificación y Lighthouse.

---

## 🚀 Próximos Pasos

1. Implementar **CSS**/**estilos con TailwindCSS** para darle identidad visual.  
2. Añadir **interactividad con JavaScript** (animaciones, sliders, validaciones).  
3. Construir el **footer accesible** con contacto y redes sociales.  
4. Optimizar recursos (imágenes y assets).  
5. Pruebas con **Google Lighthouse** para mejorar rendimiento, accesibilidad y SEO.  
6. Preparar integración con **APIs externas** (WhatsApp, Analytics, etc).  

---

## 👨‍💻 Autor

**FatCat Society**  
[🌐 Web](https://www.fatcatsociety.com/) | [📷 Instagram](https://www.instagram.com/lefatcatsociety/) | [💼 LinkedIn](https://www.linkedin.com/in/lefatcatsociety/)  

---

## 📜 Licencia

Este proyecto está bajo la licencia **MIT**.  
Eres libre de usarlo, modificarlo y distribuirlo, incluso con fines comerciales, **siempre y cuando se mantenga este aviso de licencia y se otorguen los créditos correspondientes al autor original, Lefatcat Society**
