# Proven Routes

Travel planning guides built from real trips, with real costs and straight verdicts. First trip: 11 weeks on Australia's east coast and Tasmania. Live at https://provenroutes.com (Cloudflare Pages project "travel").

Plain HTML and CSS, no build step. Open `index.html` to view.

- `index.html`: home page and region list
- `tasmania/index.html`: Tasmania region page
- `style.css`: shared styles

Hosting: any free static host (e.g. Cloudflare Pages or Netlify) connected to this repository, with no build command and the repository root as the output folder.

## Checklist for every new page
1. `<link rel="canonical" href="https://provenroutes.com/<path>/">` in the head.
2. Add the page to `sitemap.xml` (and update `lastmod` on changed pages).
3. Stats: Cloudflare Web Analytics is switched on for the whole Pages project, so new pages are tracked automatically. Check the page shows up in the Metrics tab after a day.
4. After it's live, request indexing for the new URL in Google Search Console.
