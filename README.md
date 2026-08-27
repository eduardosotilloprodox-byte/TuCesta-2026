# TuCesta — tucestaparanavidad.es

Sitio estático. No necesita build: se sube tal cual.

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | Home completa (hero, historia, catálogo, contacto). Imágenes incrustadas: funciona sola. |
| `aviso-legal.html` | Aviso legal — copia de respaldo. Los textos legales se abren en ventana desde la home; estas páginas quedan como URL fija por si hay que enviarla. |
| `politica-de-privacidad.html` | Política de privacidad (RGPD) |
| `politica-de-cookies.html` | Política de cookies |
| `terminos-y-condiciones.html` | Condiciones de contratación |
| `gracias.html` | Página a la que llega el formulario tras enviarse |
| `catalogo-tucesta-2026.pdf` | Catálogo que descarga el botón de la home |
| `robots.txt`, `sitemap.xml` | SEO básico |
| `assets/` | Imágenes y logos sueltos por si hacen falta |

## Pendientes antes de publicar

1. **Catálogo.** Ya incluido como `catalogo-tucesta-2026.pdf` en la raíz; el botón "Descargar catálogo" apunta ahí. Si lo actualizas, sustituye el archivo manteniendo el nombre.
2. **Formulario.** Usa FormSubmit (sin registro). La **primera vez** que se envíe el formulario en producción, llegará un correo a eduardosotillo.prodox@gmail.com para activar el endpoint; hasta que no se pulse ese enlace, no llegan los mensajes.

## Desplegar en Vercel

```bash
npx vercel        # primera vez
npx vercel --prod # publicar
```
Framework preset: **Other**. Build command: vacío. Output directory: la carpeta del proyecto.
Después, en Vercel → Settings → Domains, añade `tucestaparanavidad.es`.

## Paleta

Burdeos `#71212A` · Burdeos hondo `#4E150F` · Burdeos noche `#340F0A` · Rojo lazo `#8A2A1E` · Arena `#C8B298` · Crema `#F9EFDA` · Hueso `#F7F6F2` · Gris cálido `#8C7E7A`

Tipografías: Bitter (titulares) + Montserrat (texto), vía Google Fonts.
