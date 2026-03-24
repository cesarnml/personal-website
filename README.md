# Astro + Tailwind + ESLint + Prettier Starter

This repository is a reusable Astro starter template for quickly bootstrapping new projects with a clean frontend baseline.

## Included

- Astro
- Tailwind CSS v4 via `@tailwindcss/vite`
- Prettier with `prettier-plugin-astro`
- ESLint with `eslint-plugin-astro`
- Astro accessibility lint rules
- A minimal shared `BaseLayout`
- Bun-based scripts and lockfile

## Current Structure

This starter is intentionally lightweight. It includes:

- a minimal Astro page in `src/pages/`
- a reusable layout in `src/layouts/BaseLayout.astro`
- global Tailwind styles in `src/styles/global.css`
- formatting and linting config for Astro files

It does not yet include:

- component libraries
- CMS integration
- authentication
- testing frameworks
- deployment configuration

## Scripts

Install dependencies:

```sh
bun install
```

Start the local development server:

```sh
bun run dev
```

Build the site:

```sh
bun run build
```

Preview the production build locally:

```sh
bun run preview
```

Run ESLint:

```sh
bun run lint
```

Check formatting:

```sh
bun run prettier:check
```

Format files:

```sh
bun run prettier:format
```

## Conventions

- Use Conventional Commit syntax for commit messages.
- Keep shared document markup in `BaseLayout`.
- Keep formatter and linting configuration close to Astro defaults unless there is a clear project need.
- Use Bun for dependency management and scripts in this starter.

Examples:

- `feat: add blog post card component`
- `fix: correct layout metadata handling`
- `docs: update starter README`
