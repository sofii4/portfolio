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

## CI Pipeline

O deploy é da Vercel, mas a qualidade do código é validada via GitHub Actions (`.github/workflows/ci.yml`) em todo `push`/PR na `main`:

1. **validate-html** — valida `index.html` contra o padrão HTML5 (W3C Nu Html Checker)
2. **lighthouse** — audita performance, acessibilidade, boas práticas e SEO (`.github/lighthouserc.json`)

Os resultados aparecem na aba **Actions** do repositório.


