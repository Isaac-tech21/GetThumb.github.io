# GetThumb

Free YouTube thumbnail downloader with multilingual support (55 languages), SEO optimization, and AdSense readiness.

## Features

- **YouTube Thumbnail Downloader** — Paste any YouTube URL and download thumbnails in 5 resolutions (maxresdefault, sddefault, hqdefault, mqdefault, default)
- **Multilingual** — 55 languages with browser detection and localStorage persistence
- **Virtual URLs** — SPA routing with `history.pushState()` simulating `/en/`, `/fr/`, etc.
- **SEO Ready** — Meta tags, Open Graph, Twitter Cards, dynamic hreflang (55 languages), canonical, sitemap.xml, robots.txt
- **Schema.org** — WebApplication, FAQPage, BreadcrumbList structured data
- **AdSense Ready** — 3 ad placements (header, in-article, footer) with lazy loading (1.5s delay)
- **Legal Pages** — About, Contact (with form), Privacy Policy, Terms of Use
- **Content** — 3 editorial sections + 3 blog articles + FAQ

## Tech Stack

- React 18 + TypeScript
- Vite 5
- Tailwind CSS 3
- lucide-react (icons)

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## AdSense Setup

Replace `ca-pub-0000000000000000` in the code with your actual AdSense publisher ID, and the `data-ad-slot` values with your ad slot IDs. The AdSense script is lazy-loaded 1.5 seconds after page load to improve LCP.
