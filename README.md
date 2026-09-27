# kake.app

Sitio de pedidos personalizados de pasteles.

## Variables en Vercel

- `DATABASE_URL` — connection string de Neon (proyecto `kake-app`)
- `ADMIN_KEY` — clave del panel `/admin` (por defecto `kake-admin`)

Crea en Neon un proyecto llamado `kake-app` y pega la URL en Vercel → Settings → Environment Variables.

Las tablas se crean solas al primer request.

## Rutas

- `/` inicio
- `/pedido` wizard de personalización
- `/admin` catálogo, precios, banco de fotos y pedidos
