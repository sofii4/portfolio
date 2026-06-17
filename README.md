# Sofia Lopes Silva — Portfolio

Portfólio pessoal de Sofia Lopes Silva, DevOps / Cloud / Platform Engineering Aspirant.

Site single-page, single-file (`index.html`), com animação de boot estilo VM Linux, terminal interativo e seções de skills, projetos e contato.

## Stack

- HTML5 + [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- [Font Awesome](https://fontawesome.com/) (via CDN)
- JavaScript puro (sem build step)

## Deploy

Publicado automaticamente via GitHub Actions a cada `push` na branch `main`.

1. `git push` → dispara o workflow `.github/workflows/deploy.yml`
2. O workflow valida `index.html` e publica no GitHub Pages
3. Site disponível em `https://sofii4.github.io/portfolio/`

> Para o deploy funcionar, habilite em **Settings → Pages → Build and deployment → Source: GitHub Actions** (configuração única, feita pela interface do GitHub).

## Rodando localmente

Não há build. Basta abrir o `index.html` direto no navegador.
