# Shadow Agents — static site (v2 redesign)

GitHub Pages deployment of the Shadow Agents marketing site redesign. Production site: [hireshadowagents.com](https://hireshadowagents.com/).

## Live preview (GitHub Pages)

| Page | URL |
|------|-----|
| **Homepage** | https://aryan-lohia.github.io/shadow-agents/ |
| **Podcast** | https://aryan-lohia.github.io/shadow-agents/podcast.html |
| **Brand guidelines** | https://aryan-lohia.github.io/shadow-agents/brand-guidelines.html |
| **Desktop & mobile previews** | https://aryan-lohia.github.io/shadow-agents/previews.html |

## Files

- `index.html` — agency homepage (white-label editing)
- `podcast.html` — *Building the Shadow* podcast landing page
- `brand-guidelines.html` — colors, typography, logo usage
- `previews.html` — iframe previews of homepage and podcast (desktop + mobile)
- `styles.css` — shared styles (also inlined in HTML for portability)
- `competitor-funnels.md` — research notes
- `assets/` — images from hireshadowagents.com (see `assets/MANIFEST.md`)

## Local preview

```bash
cd /path/to/shadow-agents
python3 -m http.server 8080
# open http://localhost:8080/
```

## Deploy

GitHub Pages: **Settings → Pages → Build and deployment → Deploy from a branch**, branch `main`, folder `/ (root)`. Commit and push to `main` to update the live site.
