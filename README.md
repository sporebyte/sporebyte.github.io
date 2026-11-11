# sporebyte.github.io

Personal website, built with [Astro](https://astro.build) and the
[Astro Cactus](https://github.com/chrismwilliams/astro-theme-cactus) theme (MIT).

```bash
pnpm install
pnpm dev                       # http://localhost:3000
pnpm build && pnpm postbuild   # production build + search index
```

Pushes to `main` deploy to GitHub Pages via `.github/workflows/deploy.yml`.
