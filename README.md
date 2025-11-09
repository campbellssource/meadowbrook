# Meadowbrook

A simple Astro site with markdown-based content management using PageCMS.

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## Content Management

All page content (except the homepage) is stored in markdown files located in `src/content/pages/`.

The site uses PageCMS for content management. The configuration is defined in `pages.yml`.

## Project Structure

```
/
├── public/
│   └── images/          # Media uploads
├── src/
│   ├── content/
│   │   ├── config.ts    # Content collection schema
│   │   └── pages/       # Markdown page content
│   ├── layouts/
│   │   └── Layout.astro # Main layout
│   └── pages/
│       ├── index.astro  # Homepage
│       └── pages/
│           └── [slug].astro  # Dynamic markdown pages
├── astro.config.mjs
├── package.json
└── pages.yml            # PageCMS configuration
```

## Features

- ✅ Minimal styling
- ✅ Markdown-based content
- ✅ PageCMS ready
- ✅ Responsive design
- ✅ Type-safe content collections
