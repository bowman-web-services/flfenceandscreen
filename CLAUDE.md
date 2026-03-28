# CLAUDE.md — FL Fence & Screen

**Owner:** Tom Bowman / Bowman Web Services LLC (client site)
**Client:** Florida Fence & Screen LLC
**Type:** Hugo static site — local service business
**Domain:** flfenceandscreen.com
**Tagline:** "Where Pride Makes a Difference"

---

## Project Overview

Local fence and screen contractor website for Volusia County, FL. Client site built and managed by BWS.

### Business Info
- **Phone:** (386) 286-3262
- **Location:** Volusia County, FL

## Tech Stack

- **SSG:** Hugo with custom `ffs` theme
- **Hosting:** Netlify (auto-deploy from GitHub push)
- **Repo:** bowman-web-services/flfenceandscreen

## Build Commands

```bash
# Local dev
hugo server -D

# Production (matches Netlify)
hugo --gc --minify
```

## Deployment

- Push to GitHub → Netlify auto-builds
- Do NOT use Netlify CLI
- Never run `hugo build` locally on Cowork VM — disk space risk

## Cowork / Claude Code Notes

- Cowork bindfs blocks standard git operations
- Always clone to `/tmp`, copy files, commit/push from there
- Check `df -h /` before bulk operations
