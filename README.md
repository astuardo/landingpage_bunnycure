# 🐰 Bunny Cure - Landing Page

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/astuardo/landingpage_bunnycure)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Swiper](https://img.shields.io/badge/Swiper_JS-6332F6?style=flat&logo=swiper&logoColor=white)](https://swiperjs.com/)

Landing page oficial de **Bunny Cure**, un espacio dedicado al cuidado, diseño y estética profesional de uñas. Diseñada con un enfoque visual elegante, minimalista y cálido (paleta en tonos *earth/sand/gold* con estética editorial serif).

---

## ✨ Características Principales

- **Diseño Responsive & Moderno:** Optimizado para dispositivos móviles, tablets y pantallas de escritorio.
- **Navegación Intuitiva:** Menú flotante con efecto *glassmorphism* (blur) y menú lateral adaptable para móviles.
- **Carruseles Interactivos (Swiper JS):**
  - **Hero Slider:** Transición de imágenes principales y llamados a la acción (CTA).
  - **Galería de Diseños:** Carrusel táctil con bordes arqueados personalizados y soporte de video.
- **Lightbox / Zoom de Galería:** Integración con **Luminous Lightbox** para visualización detallada en alta resolución.
- **Optimización de Medios:** Imágenes y videos multimedia alojados de forma global y CDN mediante **Vercel Blob Storage**.
- **Canales de Contacto Directo:**
  - Enlaces directos al sistema de reservas (`reservar.bunnycure.cl`) y panel administrativo (`admin.bunnycure.cl`).
  - Botón flotante interactivo con animación pulse hacia WhatsApp.
  - Enlace al perfil de Instagram.

---

## 🛠️ Stack Tecnológico

| Tecnología | Propósito |
| :--- | :--- |
| **HTML5 semántico** | Estructura base de la página |
| **Tailwind CSS (CDN)** | Maquetación rápida, utilidades y sistema de diseño personalizado |
| **Swiper JS v11** | Sliders fluidos (Hero & Galería) con soporte táctil |
| **Luminous Lightbox** | Visor de imágenes en pantalla completa con soporte de navegación |
| **Font Awesome 6** | Iconografía vectorizada |
| **Google Fonts** | Tipografías (*Playfair Display* para títulos y *Lato* para textos) |
| **Vercel Blob** | CDN y almacenamiento público de archivos estáticos (imágenes/video) |

---

## 📂 Estructura del Proyecto

```text
landingpage_bunnycure/
├── index.html         # Documento principal (Estructura, estilos Tailwind y scripts)
└── README.md          # Documentación del proyecto


🎨 Paleta de Colores & Diseño
El proyecto utiliza una configuración personalizada de Tailwind CSS:

Paper (#FDFCF8): Fondo principal estilo papel / blanco hueso.
Sand (#F2EBE0): Fondos secundarios y acentos cálidos.
Beige (#E6E2DD): Bordes sutiles y separadores.
Cocoa (#5D534A): Títulos, botones y tipografía principal.
Cocoa Light (#8C8279): Subtítulos y textos de soporte.
Gold Mute (#CEB49B): Detalles dorados térreos, viñetas de paginación y acentos hover.
