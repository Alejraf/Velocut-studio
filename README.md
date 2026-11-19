# VeloCut Studio 3D 🎬✨

Editor de video profesional y aplicación web progresiva (PWA) instalable con ícono tridimensional Full HD, soporte multilingüe (**Português**, **Español**, **English**, **Français**, **Italiano**), biblioteca de fondos animados **3D / 2D / Modernos / Retro**, edición en tiempo real sobre HTML5 Canvas y monetización integrada lista para **Monetag**.

## Características Principales

- **Logo 3D Full HD Instalable (PWA):** Genera dinámicamente un ícono tridimensional en `1024x1024 px` con manifiesto PWA integrado para instalar en Android, iOS y Escritorio.
- **Multilingüe en Tiempo Real:** Traducción instantánea con prioridad en **Portugués**, **Español** e **Inglés** (además de Francés e Italiano).
- **Fondos Procedurales en Tiempo Real:**
  - **3D Pro:** Synthwave Grid 3D, Tunnel Cubes 3D, Cyber Mesh 3D, Starfield Warp 3D.
  - **2D Arte:** Memphis Pop, Hypno Rings, Kinetic Stripes, Halftone Art.
  - **Moderno & Retro 80s:** Aurora Glass, Cyberpunk Neon, 80s VHS Tape, Vaporwave Sun, Arcade CRT.
- **Activación Directa + Monetización Monetag:** Al pulsar **Exportar**, el video se activa de inmediato y dispara el flujo de anuncio configurado (`SDK` Rewarded Interstitial o `DIRECT_LINK` SmartLink) antes de guardar el archivo final.

## Cómo Configurar Monetag

Abre `index.html` y edita el bloque `MONETAG_CONFIG` al inicio del `<script>`:

```javascript
const MONETAG_CONFIG = {
  enabled: true, // Activa la publicidad antes de exportar
  mode: 'DIRECT_LINK', // 'SDK' o 'DIRECT_LINK'
  zoneId: 'TU_ZONE_ID',
  directLink: 'https://tu-enlace-directo-de-monetag.com',
  waitSeconds: 5
};
```

## Despliegue Rápido en GitHub Pages

1. Sube este repositorio a GitHub.
2. Ve a **Settings → Pages**.
3. Selecciona la rama `main` y la carpeta `/ (root)` y guarda.
4. Tu app estará en vivo en `https://tu-usuario.github.io/velocut-studio/`.
