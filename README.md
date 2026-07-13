# Guía Visual · Lean Bulk PPLUL

Guía de ejercicios del programa de hipertrofia (lean bulk, split PPLUL 5+2) en versión Smith/máquina/mancuerna, con bloque de priorización de abs (gym + casa) y vídeos de técnica verificados.

- Página única, sin dependencias ni build: `index.html`.
- Se abre automáticamente en la sesión que corresponde al día de la semana.
- Los vídeos se reproducen incrustados cuando la página se sirve desde una URL web (requisito de Referer de YouTube); en local o dentro de visores embebidos, cada vídeo se abre directamente en YouTube.

## Publicación

Automática con GitHub Actions: cada push a `main` despliega el sitio en GitHub
Pages (workflow en `.github/workflows/pages.yml`). El propio workflow habilita
Pages la primera vez, así que no hay que configurar nada a mano. La URL del sitio
aparece en la pestaña **Actions** (job _Deploy to GitHub Pages_) y en
**Settings → Pages** una vez completado el primer despliegue.
