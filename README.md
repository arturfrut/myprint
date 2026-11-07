# My Print — Web institucional

Sitio estático (HTML + CSS, sin build). Subí toda la carpeta a cualquier hosting (Netlify, Vercel, GitHub Pages, Hostinger…).

- `/` → Home (`index.html`)
- `/contacto/` → Tarjeta de contacto para NFC y QR (`contacto/index.html`)

## NFC / QR
Grabá en el NFC y en el QR la URL completa: `https://TU-DOMINIO/contacto/`

## Cambiar el link de reseñas
En `contacto/index.html` buscá el comentario `RESEÑAS` y reemplazá el `href` por el link
"Pedir reseñas" de tu Perfil de Empresa de Google (formato `https://g.page/r/XXXX/review`).
Ese link abre directo el formulario para escribir la reseña.

## Probar localmente
    python -m http.server 8080
y abrí http://localhost:8080
