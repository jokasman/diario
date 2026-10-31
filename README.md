# Diário

PWA de diário pessoal encriptado, com as entradas guardadas no Google Drive.

Este repositório contém a **build já compilada** da app (Vite + React), publicada no GitHub Pages em
https://jokasman.github.io/diario/ pelo workflow `.github/workflows/deploy.yml` a cada push para `main`.

O código-fonte (`src/`, `package.json`) não está neste repositório. Para atualizar a app, gera uma nova
build (`npm run build`) e substitui estes ficheiros pelo conteúdo de `dist/`.
