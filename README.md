# Grupo Purépecha – Guía de Liderazgo y KPIs

Esta es una app web estática (HTML/CSS) con la guía de liderazgo y el dashboard de KPIs.

## Ejecutar en local

Puedes abrir el archivo directamente en tu navegador o levantar un servidor estático:

```bash
# opción 1: abrir el archivo directamente
open index.html

# opción 2: servidor estático local
python -m http.server 8000
```

Luego visita:

- `http://localhost:8000/` (sirve `index.html`)
- `http://localhost:8000/public/` (sirve la copia en `public/`)

## Estructura

- `index.html` / `styles.css`: versión principal.
- `public/index.html` / `public/styles.css`: copia para despliegues estáticos.
