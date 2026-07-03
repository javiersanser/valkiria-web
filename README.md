# Valkiria Web

Corporate website for Valkiria Lab, served at [valkirialab.com](https://valkirialab.com).

The workspace wiki is the source of truth for project decisions and broader context. This README is only the operational entry point for this repository.

## Stack

- Astro `^6.1.10`
- Node.js `>=22.12.0`
- Automatic deployment through Coolify when changes are merged into `master`
- Served behind Cloudflare

## Local Development

Install dependencies:

```sh
npm install
```

Start the development server:

```sh
npm run dev
```

Build the production site:

```sh
npm run build
```

Preview the production build locally:

```sh
npm run preview
```

## Repository Structure

- `src/`: Astro pages, layouts, components, styles, and content collections.
- `public/`: static assets copied as-is to the built site, including `humans.txt` 🍟.

## Conventions

- Use conventional commits, written in English.
- Open pull requests against `master`.
