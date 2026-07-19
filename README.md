# portfolio-data

Assets and data files for [armedifaiz.github.io](https://armedifaiz.github.io).

Accessed via `raw.githubusercontent.com` — zero rate limit, no API keys.

# Structure

```
photos/          — Profile photos
  data.json      — Photo metadata
certificates/    — Certificate images
  data.json      — Certificate metadata
experience.json  — Work experience
skills.json      — Skills list
socials.json     — Social links
sling-icon.png   — Sling skill icon
index.json       — Quick summary
```

# Usage

```bash
# Fetch data
curl -O https://raw.githubusercontent.com/armedifaiz/portfolio-data/main/photos/data.json

# Fetch image
curl -O https://raw.githubusercontent.com/armedifaiz/portfolio-data/main/photos/Z62_0073_verified.jpg
```

# Update

Commit and push to `main`. Changes are available immediately on `raw.githubusercontent.com`.
