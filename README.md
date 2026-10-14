# Invitación Navidad — Familia Estrada Guerrero

Invitación web interactiva para el 24 y 25 de diciembre en Club Campestre Kercus.

## Contenido
- `index.html` — la invitación (música sintetizada, sin dependencias externas).
- `fonts/` — fuentes locales (Cormorant Garamond y Jost).
- `og-image.jpg` — imagen de vista previa al compartir el enlace.

## Configuración
En `index.html`, al inicio del `<script>`, coloca el WhatsApp que recibe las confirmaciones (lada de país + número, sin espacios):

```js
const HOST_PHONE = "52443XXXXXXX";
```

## Probar en local
Abre `index.html` en el navegador, o usa la extensión **Live Server** en Cursor (clic derecho en `index.html` → *Open with Live Server*).

## Publicar
Sube la carpeta a Netlify (arrastrar y soltar), Vercel o GitHub Pages y comparte el enlace.

## Funciones
- Portada con sobre: al abrirla suena "We Wish You a Merry Christmas" (dominio público, generado con Web Audio). Botón para silenciar.
- Cuenta regresiva al 24 de diciembre de 2026, 10:00 AM.
- Botones de ubicación (Google Maps) y agregar al calendario.
- Confirmación de asistencia que abre WhatsApp con el mensaje armado.
