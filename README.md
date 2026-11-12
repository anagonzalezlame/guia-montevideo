# Ciudad Vieja & Around

Guía de Montevideo para Vasyl Savchenko, artista en residencia (Z Art Lab, noviembre 2026).
Sitio estático publicado con Cloudflare Workers en cv.anitagl.workers.dev.

- `public/index.html`: el sitio completo (polaco por defecto, con selector PL / EN).
- `wrangler.jsonc`: configuración de Cloudflare. Sirve la carpeta `public` como sitio estático.

Cada push a `main` vuelve a publicar el sitio.
