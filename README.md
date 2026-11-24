# akhtun.github.io — WEcoS canonical site

The canonical, publicly indexable home of the **WEcoS** (Wizaya Sovereign AI
Ecosystem) umbrella. Its job is to be the entity anchor: one page that says
what WEcoS is, disambiguates it from the unrelated industrial acronym "WECO",
and links every public project back to it.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The site. No build step, no dependencies, no tracking — it is a static page that works from a file:// path and from GitHub Pages. |
| `llms.txt` | Machine-readable map of the platform for AI crawlers (llmstxt.org convention). Linked from the page and advertised in a `<link rel="alternate">`. |
| `robots.txt` | Allows everything; points crawlers at `llms.txt`. |

## Editing

Edit `index.html` and `llms.txt` directly and push to `main`. GitHub Pages
serves the repository root, so there is nothing to build and nothing to compile.

## Why this exists

The 2026-11-24 AI-search visibility audit measured that WEcoS was discoverable
by name but invisible by category: category queries ("best open source Myanmar
Burmese OCR tool", "sovereign AI platform Myanmar") returned no WEcoS result,
while the brand query for a competitor returned a funded national-flagship site.
The gap was an entity signal, not a capability gap. This site is the anchor
that closes it.

Audit: `WEcoS_Beta/docs/wecos/reports/2026-11-24-wecos-ai-search-visibility-audit.md`
