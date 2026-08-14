# LOOKBEN · Sitio web (Higiene y Seguridad · Salta)

Sitio web estático de una sola página (landing), 100% responsive y sin dependencias externas (salvo la fuente Google Fonts).

## Estructura
- index.html        → toda la página
- assets/logo.png   → logo LOOKBEN (fondo transparente)
- assets/qr.png     → QR que abre WhatsApp con mensaje precargado

## Cómo publicarlo GRATIS

### Opción A — GitHub Pages (recomendado, ya lo usás)
1. Crear un repo nuevo, ej: `lookben-web`.
2. Subir index.html + carpeta assets/ (mantener nombres).
3. Settings → Pages → Branch: main → /root → Save.
4. En ~1 min queda online en: https://TU-USUARIO.github.io/lookben-web/

### Opción B — Netlify (drag & drop)
1. Entrar a app.netlify.com → "Add new site" → "Deploy manually".
2. Arrastrar la carpeta lookben-web completa.
3. Queda online al instante con URL gratuita (podés cambiarla).

## Dominio propio (opcional, recomendado a futuro)
- Comprar `lookben.com.ar` (NIC Argentina) o `lookben.com`.
- Apuntarlo al hosting (Pages/Netlify) desde Settings → Custom domain.

## Personalización pendiente
- Reemplazar los `href="#"` de Instagram/Facebook en la sección Contacto y Footer por tus URLs reales cuando crees los perfiles.
- (Opcional) Conectar el formulario a un email real con Formspree (https://formspree.io) si querés recibir también por correo, además del WhatsApp.
