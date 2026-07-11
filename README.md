# Agroconsultora Las Marías — Sitio web

Landing institucional de **Agroconsultora Las Marías · Innovación Agropecuaria**.
Sitio estático (una sola página) servido con **GitHub Pages**.

## Estructura
- `index.html` — landing completa (HTML + CSS + JS embebidos, sin dependencias).
- `assets/` — logos con nombres limpios (`logo-horizontal.jpeg`, `logo-sello.jpeg`).
- `Logos/` — logos originales entregados por el cliente.

## Cambiar el número de WhatsApp
El número de la burbuja y de todos los botones está en **un solo lugar**.
En `index.html`, al final, editá la constante:

```js
const WA_NUMBER = "5493413452722"; // +54 9 3413 45-2722, formato internacional sin "+", espacios ni guiones
```

Todos los botones y la burbuja flotante se actualizan solos.

## Editar contenido
Los textos de servicios, enfoque y equipo son placeholders premium listos para
reemplazar cuando llegue la información definitiva de la empresa.

## Deploy
Automático vía GitHub Pages (rama `main`, raíz del repo). Cada push a `main` publica.
