# ScrewFast - Astro Landing Page Template

A versatile, open-source template for landing pages, blogs, and documentation built with Astro 5, Tailwind CSS 4, and Preline UI.

## Tech Stack

- **Framework**: Astro 5
- **Documentation**: Starlight
- **Styling**: Tailwind CSS 4
- **UI Components**: Preline UI
- **Animations**: GSAP + Lenis smooth scroll
- **Language**: TypeScript
- **Build Output**: `dist/`

## Available Skills

| Skill | Description |
|-------|-------------|
| `build-and-deploy` | Build and deploy this Astro application to Vercel or Netlify |

## Project Structure

```
src/
├── assets/           # Scripts and styles
├── components/       # Reusable Astro components
│   ├── sections/     # Page sections
│   └── ui/           # UI components
├── content/          # Markdown content (blog, docs, products)
├── data_files/       # JSON data and constants
├── images/           # Static images
├── layouts/          # Layout templates
├── pages/            # Route pages
└── utils/            # Utility functions
```

## Key Commands

```bash
npm install          # Install dependencies
npm run dev          # Start dev server (port 4321)
npm run build        # Production build
npm run preview      # Preview production build
```

## Features

- **Landing Pages**: Hero sections, features, testimonials, pricing
- **Blog**: MDX support with Table of Contents
- **Documentation**: Starlight integration with search and i18n
- **Internationalization**: Multi-language support (English/French)
- **SEO**: Meta tags, Open Graph, structured data
- **Performance**: HTML minification, Astro compression

## Customization

- Edit `src/data_files/constants.ts` for site metadata
- Modify `src/utils/navigation.ts` for nav/footer links
- Update components in `src/components/sections/`

## Original Repository

https://github.com/mearashadowfax/ScrewFast
