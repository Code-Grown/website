# CodeGrown Website (public)

This repository is the **static publish target** for [www.codegrown.cl](https://www.codegrown.cl).

- Live site is served from the **`gh-pages`** branch (HTML/CSS/JS only).
- Editable Nuxt source lives in the private repo **`Code-Grown/website-src`**.
- Do not add `package.json`, Nuxt, or CI that runs `npm ci` / builds here.

Deploy is done from `website-src` via `npm run deploy` (generate → push `.output/public` to `gh-pages`).
