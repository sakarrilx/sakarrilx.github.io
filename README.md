# Sakarrin — Academic Homepage

A personal academic website for research logs, projects, knowledge notes, and publications. Built with Astro and prepared for GitHub Pages.

## Local development

```bash
npm install
npm run dev
```

Open the local address printed in the terminal.

## Build

```bash
npm run build
```

The static website is generated in `dist/`.

## Main content locations

- Personal details: `src/data/site.ts`
- Homepage: `src/pages/index.astro`
- Research log: `src/pages/log/index.astro`
- Projects: `src/pages/projects/index.astro`
- Notes: `src/pages/notes/index.astro`
- Publications: `src/pages/publications/index.astro`
- About page: `src/pages/about/index.astro`

## Publish on GitHub Pages

1. Create a public repository named `sakarrilx.github.io` under the GitHub account `sakarrilx`.
2. Push this project to the repository's `main` branch.
3. Open **Settings → Pages** in the repository.
4. Set the deployment source to **GitHub Actions**.

The included workflow will build and publish the site automatically after each push to `main`.
