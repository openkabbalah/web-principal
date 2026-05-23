# Open Kabbalah Home estática

Sitio listo para subir a Cloudflare Pages como proyecto estático.

## Archivos
- `index.html`: home principal de Open Kabbalah.
- `meditaciones-prosperidad.html`: landing del Programa de Meditaciones de Prosperidad y Abundancia.
- `assets/site.css`: estilos globales.
- `assets/site.js`: lluvia de letras hebreas y menú mobile.
- `assets/*.webp`: imágenes optimizadas para web.

## Pendientes recomendados antes de publicar
1. Reemplazar el CTA de comunidad por el link real del grupo de WhatsApp cuando lo tengas.
2. Confirmar si la foto remota de Fernando en `openkabbalah.org/wp-content/uploads/2026/04/fer-foto.webp` seguirá disponible tras sacar WordPress. Si no, descargarla y guardarla en `assets/`.
3. Subir el repositorio a GitHub y conectar Cloudflare Pages.

## Comandos sugeridos
```bash
git init
git add .
git commit -m "Crear home estática de Open Kabbalah"
git branch -M main
git remote add origin https://github.com/openkabbalah/openkabbalah-home.git
git push -u origin main
```
