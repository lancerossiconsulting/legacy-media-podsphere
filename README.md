# If You Can't Beat 'Em: Legacy Media and the Podsphere

Examining how the reluctant migration of legacy broadcast figures into podcast and streaming formats signals the structural collapse of traditional media infrastructure.

**Live site:** https://lancerossiconsulting.github.io/legacy-media-podsphere/

---

## File-to-page map

| File | URL | Description |
|------|-----|-------------|
| `index.md` | `/` | Home page and navigation hub |
| `journal-article.md` | `/journal-article/` | "The Reluctant Migrant" — full scholarly article (~7,500 words) |
| `conference-paper.md` | `/conference-paper/` | "Infrastructure Collapse as Media Event" — NCA paper (~4,500 words) |
| `substack.md` | `/substack/` | "Brian Williams Is Not the Story" — public essay (~1,600 words) |
| `practice-brief.md` | `/practice-brief/` | Practitioner brief — three-three-three structure |
| `literature-review.md` | `/literature-review/` | Annotated bibliography — theoretical, empirical, primary sources |
| `podcast-outline.md` | `/podcast-outline/` | Episode outline — ~50-minute conversation |
| `media.md` | `/media/` | Visual exhibits and associated media |
| `downloads.md` | `/downloads/` | File downloads — Word, PDF, PowerPoint, Markdown |
| `about.md` | `/about/` | About the author and project |
| `404.md` | `/404.html` | Not-found page |

---

## How to update content

1. Edit the relevant `.md` file in this repository
2. Commit the change with a descriptive message (`git commit -m "journal-article: expand §3.2 empirical case"`)
3. Push to `main` (`git push origin main`)
4. GitHub Pages rebuilds automatically — allow 1–3 minutes

For front matter field changes (title, meta, date), update the YAML block at the top of each file. The `meta:` field is the version line displayed on the site; update it with the revision date and any status change when you complete a substantive draft.

---

## Digital production conventions

### Superscript citations

All academic pieces (journal article, conference paper) use sequential superscript citations linked directly to the source URL:

```html
<a class="cite" href="URL"><sup><em>N</em></sup></a>
```

Numbers are sequential in reading order per page. All sources cited in the body must appear in `literature-review.md`. Production documents (podcast outlines) are exempt from this standard.

### QR bridge

The site QR code lives in two places:
- `assets/qr-legacy-media-podsphere.svg` — web display (About page)
- `downloads/legacy-media-podsphere-qr.png` — print resolution (Downloads page, conference materials)

Generate both when the site URL is confirmed. Update both if the URL changes.

### Download filenames

All downloadable files follow the pattern `legacy-media-podsphere-[piece-name].[ext]`, using kebab-case throughout. The repo name prefix on every file prevents collision when files are saved to a shared folder.

### Self-hosted fonts

Fonts are served from `assets/fonts/` — Source Serif 4 and Source Sans 3, variable WOFF2. No external font requests. No CDN dependencies for typography.

### No analytics, no trackers, no cookies

This site does not load any analytics, tracking, or advertising scripts. No cookies are set. No third-party resources beyond what is declared in `_config.yml` plugins (jekyll-feed, jekyll-sitemap).

---

## Scaffold origin

Site structure cloned from [pratt-study](https://github.com/lancerossiconsulting/pratt-study). For layout and template questions, refer to the pratt-study repository.
