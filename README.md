# Suministros Hostelería — web

Landing page estática (un solo `index.html`, sin dependencias ni build) para una empresa de consumibles de hostelería: manteles, servilletas, celulosa, limpieza y desechables.

## Publicar en Vercel

1. En vercel.com → **Add New… → Project** → importa este repositorio.
2. Framework preset: **Other**. Sin comando de build ni carpeta de salida.
3. Deploy. Cada push a `main` vuelve a publicar la web.

## Pendiente antes de usarla de verdad

- Teléfono, correo, horario y dirección del bloque de contacto son de ejemplo.
- Número de WhatsApp: cambia `WA_NUMBER` en `index.html` (prefijo de país sin `+`, p. ej. `34600123456`).
- Los formularios de presupuesto y newsletter no envían datos todavía: hay que conectarlos a un servicio (Formspree, Brevo, Mailchimp…).
- El precio de la bobina y las cifras de "Quiénes somos" deben ser reales.
