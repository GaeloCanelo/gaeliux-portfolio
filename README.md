# 🌳 GaelIUX Portfolio

![GaelIUX](https://img.shields.io/badge/GaelIUX-Portfolio-00e676?style=for-the-badge)
![Astro](https://img.shields.io/badge/Astro-080a10?style=for-the-badge&logo=astro&logoColor=white)
![CSS Vanilla](https://img.shields.io/badge/CSS_Vanilla-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Portafolio personal de **GaelIUX** — Arquitecto de Experiencias Digitales y Visuales e Ingeniero en Sistemas Computacionales.

Este portafolio no es solo una página web, sino una experiencia narrativa e inmersiva. Diseñado en torno a la temática de un "Bosque Mágico", cuenta con efectos de paralaje (parallax), animaciones de partículas, un enorme árbol de habilidades estructurado y modales multimedia interactivos.

---

## ✨ Características Principales

* **Fondo Inmersivo (Bosque Mágico):** Un sistema de capas absolutas (Follaje, Ramas, Tronco y Raíces) que se posicionan dinámicamente con JavaScript para crear un efecto de descenso vertical continuo.
* **Hero Section Animado:** Fusión de texto dinámica para el nombre "GaelIUX" acompañada de un fondo de partículas (`ParticlesBackground`).
* **Showcase de GitHub:** Integración dinámica mediante la API de GitHub para mostrar repositorios destacados en un formato moderno tipo Glassmorphism.
* **Skill Tree:** Más de 40 nodos divididos en subcategorías (Software, Lenguajes, etc.) emparejando *Hard Skills* con *Soft Skills* usando SVG en línea y Emojis.
* **Carruseles Multimedia:** Visor integrado para escritos creativos y fábulas con soporte dual para imágenes panorámicas y bucles de video en `.mp4`.
* **Criptografía & CV:** Sección para previsualización / descarga del Currículum Vitae y divulgación criptográfica (Alan Turing, Máquina Enigma y RSA).
* **Navegación Fluida:** Smooth scrolling gestionado globalmente por [Lenis](https://lenis.studiofreight.com/) y un Navbar responsivo con *Intersection Observer*.

## 🚀 Despliegue (Deployment)

Este proyecto está construido como un sitio estático ultra-rápido utilizando Astro.

### Instalación local

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/GaeloCanelo/gaeliux-portfolio.git
   cd gaeliux-portfolio
   ```
2. Instalar las dependencias:
   ```bash
   npm install
   ```
3. Iniciar el servidor de desarrollo local (en `http://localhost:4321`):
   ```bash
   npm run dev
   ```

### Construcción para Producción

Para compilar el proyecto y generar los archivos finales optimizados, ejecuta:

```bash
npm run build
```

El código de producción se generará en la carpeta `dist/`. Esta carpeta contiene HTML puro, CSS, JS y los assets correspondientes; lista para ser alojada en cualquier servidor web moderno (Vercel, Netlify, GitHub Pages, Apache, Nginx, etc.).

## 🛠️ Stack Tecnológico

* **Framework:** [Astro](https://astro.build/)
* **Estilos:** Vanilla CSS (Metodología BEM / Scoped)
* **Scripts:** JavaScript Moderno (ES6+)
* **Scroll:** Lenis (Studio Freight)

---
*Desarrollado con pasión para resolver problemas complejos mediante sistemas digitales elegantes.*
