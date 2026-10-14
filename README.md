# Portfólio — estrutura React

Estrutura React/TypeScript/Vite. A tela implementada é o exemplo original com contador; as pastas de páginas, serviços e tipos ainda são uma base para desenvolvimento.

## Tecnologias

- React
- TypeScript
- Vite
- Tailwind CSS

## Funcionalidades e utilização

Abra a página e use o contador. Esta publicação é um protótipo técnico, ainda sem o portfólio profissional implementado.

## Como executar

```bash
git clone https://github.com/EuGeanCarlos/portfolio.git
cd portfolio
cd frontend
npm ci
npm run dev
```

Use Node.js 22.12 ou superior e o lockfile versionado. Para compilar, execute npm run build. Limitações descritas acima podem impedir o build.

## Demonstração e publicação

[Acessar demonstração verificada](https://eugeancarlos.github.io/portfolio/)

## Estrutura versionada

```text
frontend/.gitignore
frontend/.oxlintrc.json
frontend/README.md
frontend/index.html
frontend/package-lock.json
frontend/package.json
frontend/public/favicon.svg
frontend/public/icons.svg
frontend/src/App.css
frontend/src/App.tsx
frontend/src/assets/hero.png
frontend/src/assets/react.svg
frontend/src/assets/vite.svg
frontend/src/constants/index.ts
frontend/src/index.css
frontend/src/layouts/DefaultLayout.tsx
frontend/src/main.tsx
frontend/src/pages/Home.tsx
frontend/src/services/api.ts
frontend/src/types/index.ts
frontend/src/utils/index.ts
frontend/tsconfig.app.json
…
```

## Status

Protótipo / projeto de estudo em desenvolvimento. A descrição acima distingue o que está implementado das dependências ou etapas pendentes.

## Autor e créditos

**Gean Carlos** — estudante de Engenharia de Computação, UEMA.

[GitHub](https://github.com/EuGeanCarlos)

Licenças, autoria compartilhada e atribuições existentes no código e nos materiais originais permanecem aplicáveis.

## Validação desta auditoria — 14/10/2026

PUBLICADO: [workflow confirmado](https://github.com/EuGeanCarlos/portfolio/actions/runs/38610813621), HTTP 200, conteúdo correspondente ao projeto e 3 recursos locais verificados. Build e lint locais aprovados. Lockfile reparado para npm ci no Linux; workflow e deploy confirmados. A aplicação continua sendo o contador original do Vite.
