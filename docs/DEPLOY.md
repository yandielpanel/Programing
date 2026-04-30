# Cómo publicar este proyecto

## GitHub Pages

Este repo ya incluye un workflow en:

```text
.github/workflows/deploy-pages.yml
```

Para activar la publicación:

1. Entra al repo en GitHub.
2. Ve a **Settings**.
3. Entra a **Pages**.
4. En **Build and deployment**, selecciona **GitHub Actions**.
5. Guarda.
6. Haz cualquier cambio o ejecuta manualmente el workflow.

La web debe quedar en una URL parecida a:

```text
https://yandielpanel.github.io/Programing/
```

## Probar localmente

Puedes abrir `index.html` directo en el navegador.

O usar:

```bash
npm install
npm run dev
```

## Importante

No subas claves API, tokens, contraseñas ni datos privados.
