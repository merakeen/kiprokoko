# KiPROKOKO

KiPROKOKO is a _Konbini_ style, fully automated content site built by merakeen. You will help us automate post creation with an AI API, enrich topics using geotargeted Google Trends via Python, and make the site multilingual in English and Greek.

This README talks directly to you because we work as equals. You will own real outcomes, and we hope you have the same expectations around quality and communication that we hold ourselves to.

## How we will work together

Our partnership philosophy is practical and simple. We are consistent about it.

- Autonomy, trust, and responsibility as defaults
- Honest communication without theatre or bureaucracy
- Respect for competence, time, and attention
- No ego driven decisions, no micromanagement
- Outcomes over noise, clarity over unnecessary complexity
- Long term thinking, sustainable builds instead of fragile quick fixes or obsolete work
- Cultural awareness and respectful collaboration with partners across Europe
- Transparent processes, no hidden decisions, no gatekeeping

## Project goals

- Automate post writing with an AI API
- Enrich post ideas with geotargeted Google Trends using Python
- Add multilingual support with English and Greek
- Keep the site fast, structured, and easy to operate

## Local setup

Prereqs: Node.js 18+ and npm.

```bash
npm install
npm run dev
```

## Repository structure

- `public/` static assets like images and fonts
- `src/` application code
- `src/components/` UI components
- `src/layouts/` page layouts
- `src/pages/` routes and pages
- `src/content/` content entries and collections
- `src/styles/` global styles and utilities
- `astro.config.mjs` Astro config
- `package.json` scripts and dependencies
- `tailwind.config.mjs` Tailwind config
- `tsconfig.json` TypeScript config

## Current content flow

- Content is stored in `src/content/blog/` as MDX.
- Trending posts render from the blog collection.
- Category pages are currently copies of the trending list.

## What you will help build

- `services/` or `scripts/` for AI post generation and trends ingestion
- A data pipeline that maps trends to topics and drafts
- Language switching and translation storage for Greek and English
- Safe and reviewable content publishing workflow

## License

The boilerplate template project used as a starter is licensed under the [MIT License](LICENSE). This license applies to all code and assets added by Jose (@jramma) and does not apply to edits or additions by Ikrame (@ikramagix) or any other contributors.# kiprokoko
