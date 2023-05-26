# Spotlite - Personal Web Site Astro Starter

![screenshot](https://github.com/ChristineTham/spotlite/raw/master/src/assets/screenshot.png)

Spotlite is a beautiful personal website template built with Astro and UnoCSS, inspired by
a similar sounding template from the Tailwind CSS team. Best of all, it's open
source (MIT licence) so feel free to use and modify it!

[![Deploy To Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/ChristineTham/spotlite&utm_medium=social&utm_source=github)


It uses the following technologies:

- [Astro](https://astro.build)
- [Alpine.js](https://[astro.build](https://alpinejs.dev/))
- [Typescript](https://www.typescriptlang.org/)
- [Prettier](https://prettier.io/)
- [ESLint](https://eslint.org/)
- [UnoCSS](https://unocss.dev/)
- `@astrojs/sitemap` and `@astrojs/rss` preintegrated
- Heroicons and SVG Logos preloaded via [Iconify](https://iconify.design/)

It features:

- A homepage featuring photos, links to blog articles, and a career history.
- An About page that can be edited in Markdown and featuring a profile photo
  and social media links.
- An Articles page linking to blog articles.
- A Projects page showcasing a portfolio of items with descriptions, images and
  links.
- A Creations page showcasing linkable artefacts.
- A Uses page providing a bragging list of products and tools used.

Spotlite uses all the latest and greatest features in Astro (>2.5.0) including:

- optimised assets
- dala and content collections
- endpoints
- sitemap
- RSS

It’s production-ready and easy to customize, making it the perfect starting point for your own personal website.

It's also simple to deploy on Netlify or similar.

Uses:

- [Typescript](https://www.typescriptlang.org/)
- [Prettier](https://prettier.io/)
- [ESLint](https://eslint.org/)
- [UnoCSS](https://unocss.dev/)
- `@astrojs/sitemap` and `@astrojs/rss` preintegrated
- Heroicons and SVG Logos preloaded via [Iconify](https://iconify.design/)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm run dev`             | Starts local dev server at `localhost:3000`      |
| `pnpm run build`           | Build your production site to `./dist/`          |
| `pnpm run preview`         | Preview your build locally, before deploying     |
| `pnpm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro -- --help` | Get help using the Astro CLI                     |
