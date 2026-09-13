# pinterest-pin-images

Asset host de imágenes para Pinterest — Lizy Del Busto.
Alojadas para bulk upload (URLs directas vía `raw.githubusercontent.com`).

## Carpetas

- **`pins/`** — 50 pines de las freebies (*Free Illustrations for Commercial Use*).
- **`postales/`** — 100 pines de las postales ilustradas.
- **`<mes>-<año>/`** (p.ej. `septiembre-2026/`) — lotes mensuales de pines nuevos, todos juntos en una sola carpeta sin separar por board; el board/tipo va en el propio nombre del archivo:
  - `Freebie-PinN.png` — pines para el board de freebies
  - `Postal-<código>.png` — pines para el board de postales wholesale (p.ej. `Postal-3A-Oso-navidad-V1.png`)
  - `PaletaN.png` — pines para el board de paletas de color
  - `septiembre-2026/` tiene 67: 17 Freebie + 24 Postal (colección Xmas: oso/churros/coquette/regalos/jengibre/santa) + 26 Paleta.

## URL base

```
https://raw.githubusercontent.com/nhefertitieth-png/pinterest-pin-images/main/<carpeta>/<archivo>.png
```

Los nombres están saneados (sin espacios, `·` ni acentos) para usarse directamente en el CSV de bulk upload sin escapes.
