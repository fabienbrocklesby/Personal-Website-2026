# Fabien Brocklesby - Personal Website

This is my personal website, built with Astro.

It is a simple place for my pages (like About and Links) and the core info I want online.

## Notes

- This site is intentionally basic and lightweight.
- Content lives in Astro pages/components and a small content file.
- Styling is kept minimal with global styles and tokens.

## SEO + GEO

I have optimized this site heavily for both classic search (SEO) and AI discovery (GEO).

- SEO: I use clean metadata, canonical URLs, robots directives, Open Graph/Twitter tags, structured data (JSON-LD for Person/Organization/WebSite/WebPage), and an auto-generated sitemap.
- GEO: I publish `llms.txt` and `llms-full.txt` with authoritative profile details, keep official links consistent across the site, and explicitly allow major AI crawlers.

## Dependencies

Main dependencies:

- `astro`
- `@astrojs/sitemap`

Dev dependencies:

- `typescript`
- `@astrojs/check`

## Basic commands

- `npm run dev` - start local dev server
- `npm run build` - build for production
- `npm run preview` - preview production build
