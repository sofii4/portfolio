# Sofia Lopes Silva — Portfolio

Portfólio de Sofia Lopes Silva

Site single-page, single-file (`index.html`), com animação de boot estilo VM Linux, terminal interativo e seções de skills, projetos e contato.

## Stack

- HTML5 + [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- [Font Awesome](https://fontawesome.com/) (via CDN)
- JavaScript puro (sem build step)

## Deploy

Hospedado na [Vercel](https://vercel.com/), conectada diretamente ao repositório GitHub (`sofii4/portfolio`).

1. `git push` na branch `main` → a Vercel detecta o push via sua integração nativa com o GitHub
2. Build automático (projeto estático, sem build step) e deploy em produção
3. Cada Pull Request também recebe automaticamente uma Preview Deployment

> Configuração feita uma única vez em vercel.com → **Add New Project → Import Git Repository → sofii4/portfolio**. Framework Preset: `Other` (site estático).


