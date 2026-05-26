# competitor-website-screenshots

Web competitor / inspiration screenshot references for the web tools pipeline.

Synced from `website-store` scraper output (`og-image` + full-page `homepage.png`).

## Layout

```
<domain>/
  <domain>-homepage.png
  <domain>-og-image.jpg
  manifest.json          # scrape metadata from website-store
```

## Source

Generated via:

```bash
cd ../website-store
scripts/store/capture-screenshots.sh --catalog-dir output/Levels_Portfolio
scripts/store/sync-screenshots-repo.sh ../competitor-website-screenshots
```

## Visibility

Public by default. Say **private yapalım** to flip the GitHub repo to private.
