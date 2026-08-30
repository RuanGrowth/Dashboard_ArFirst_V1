# Dashboard AR First Certificado Digital — Bursty

Dashboard de performance (Meta Ads, Google Ads, Instagram Orgânico e Operações/Jira)
do cliente **AR First Certificado Digital**, em arquivo único (`index.html`).

Lê os dados, no navegador, direto das planilhas do Google Sheets publicadas em CSV
(base geral da Bursty), filtrando automaticamente pelo AR First. O `server.js` só entrega o HTML.

> IMPORTANTE: todos os arquivos (index.html, server.js, package.json, Dockerfile)
> precisam ficar na RAIZ do repositório, não dentro de uma subpasta.

## Subir no GitHub
```bash
git init && git add . && git commit -m "Dashboard AR First"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPO.git
git push -u origin main
```

## Publicar no Railway
1. New Project -> Deploy from GitHub repo -> selecione o repositório.
2. O Railway usa o Dockerfile e roda node server.js (usa a porta PORT automaticamente).
3. Settings -> Networking -> Generate Domain para a URL pública.
