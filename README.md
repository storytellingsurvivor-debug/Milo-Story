# Milo SEO Bilingual Landing Pages (GitHub Pages)

This folder contains bilingual SEO landing pages for the Milo ecosystem.

## Files Included

- `index.html`: root page (`x-default`) with links to language pages
- `en/index.html`: full English SEO page
- `fr/index.html`: full French SEO page
- `favicon-forever.ico`: browser tab icon used by the landing page
- `robots.txt`: crawler directives with sitemap reference
- `sitemap.xml`: sitemap covering root, EN, and FR URLs

## Content Outline and Keyword Map

### Page Sections

1. Milo Story (brand origin, mission, values)
2. Happy Milo (celebration wall narrative + use cases)
3. Support Milo (recovery and community support narrative)
4. Forever Milo (remembrance and lasting connection narrative)
5. Ecosystem section (how the three pillars connect)
6. FAQ section (long-tail search intent)

### Primary Keyword Cluster

- Milo brand story
- Happy Milo
- Support Milo
- Forever Milo

### Secondary Keyword Cluster

- happy wall
- online celebration wall
- group message card
- gambling recovery support
- debt support community
- remembrance platform
- digital tribute page
- lasting connection

## Deploy To Your Dedicated GitHub Pages Repo

1. Create or open your separate repository for the landing page.
2. Copy all files from this folder into that repository root.
3. Ensure production URL values are set (already configured in this repo):
   - `https://storytellingsurvivor-debug.github.io/Milo-Story/` in `index.html`
   - `https://storytellingsurvivor-debug.github.io/Milo-Story/en/` in `en/index.html`
   - `https://storytellingsurvivor-debug.github.io/Milo-Story/fr/` in `fr/index.html`
   - `https://storytellingsurvivor-debug.github.io/Milo-Story/sitemap.xml` in `robots.txt`
   - all root/EN/FR URLs in `sitemap.xml` including alternate `hreflang` links
4. Commit and push.
5. In GitHub repo settings, enable GitHub Pages (branch: `main`, folder: `/root`).

## Post-Publish SEO Checklist

- Open `https://storytellingsurvivor-debug.github.io/Milo-Story/` and verify page loads.
- Open `https://storytellingsurvivor-debug.github.io/Milo-Story/en/` and verify English page loads.
- Open `https://storytellingsurvivor-debug.github.io/Milo-Story/fr/` and verify French page loads.
- Confirm canonical URL matches the published URL.
- Confirm EN/FR pages include reciprocal `hreflang` tags plus `x-default`.
- Verify `https://storytellingsurvivor-debug.github.io/Milo-Story/robots.txt` and `https://storytellingsurvivor-debug.github.io/Milo-Story/sitemap.xml` are reachable.
- Verify favicon loads at `https://storytellingsurvivor-debug.github.io/Milo-Story/favicon-forever.ico` and appears in the browser tab.
- Submit page URL and sitemap in Google Search Console.
- Track branded queries and iterate content monthly.
