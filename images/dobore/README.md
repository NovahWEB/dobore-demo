# Imágenes reales de Dobore

Carpeta destino para la fotografía real del sitio. **Aún no hay fotos**: el sitio usa
ilustraciones propias como fallback automático.

## Cómo activar una foto

1. Copia el archivo a la subcarpeta correspondiente (`hero/`, `experiences/`, `stories/`,
   `gallery/`, `visit/`, `menu/`) con el nombre sugerido en `docs/REAL_IMAGES_GUIDE.md`.
2. Abre `src/data/imageRegistry.js` y completa el campo `photo` de la entrada
   correspondiente (ej. `photo: '/images/dobore/hero/hero-rio.jpg'`).
3. Listo: `BrandImage` usará la foto y conservará la ilustración como respaldo si falla.

Guía completa (tamaños, orientación, compresión, overlays): `docs/REAL_IMAGES_GUIDE.md`.
