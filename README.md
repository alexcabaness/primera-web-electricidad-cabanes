# Primera web · Electricidad Cabanes

Web de una sola página (HTML/CSS/JS sin dependencias ni servicios de terceros: las fuentes están en `fonts/`).

## Ejecutar en local
Desde esta carpeta:

    python3 -m http.server 8000

y abre http://localhost:8000 (o `npx serve .`).

## Estructura
- `index.html`: todo el CSS y JS está dentro.
- `aviso-legal.html`, `privacidad.html`, `cookies.html` + `legal.css`: textos legales genéricos (pendientes de revisión profesional y de completar titular y NIF).
- `index.backup.html`: copia de seguridad de la versión original (se puede borrar al publicar).
- `img/`: fotos de trabajos y logos (`logo-cabanes.webp`, `logo-fych.png`).

## Subir a GitHub (repositorio privado)

    git init && git add . && git commit -m "Primera web Electricidad Cabanes"
    gh repo create primera-web-electricidad-cabanes --private --source=. --push
