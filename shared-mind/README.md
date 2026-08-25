# NextXus Shared Mind

Canonical data layer for the NextXus Federation.

Any satellite site, AI lab, or VR experience can fetch these files directly from GitHub raw URLs — no database, no backend, no cost.

## Raw Fetch URLs (CORS-friendly)

- Data: https://raw.githubusercontent.com/Keywebco/nextxus-online-sovereign/main/shared-mind/federation-data.yaml
- Content: https://raw.githubusercontent.com/Keywebco/nextxus-online-sovereign/main/shared-mind/federation-content.md

## Usage

```javascript
const CONTENT = 'https://raw.githubusercontent.com/Keywebco/nextxus-online-sovereign/main/shared-mind/federation-content.md';
fetch(CONTENT).then(r => r.text()).then(md => renderMarkdown(md));
```

Compatible with: GitHub Pages · Netlify · Cloudflare Pages · Vercel · A-Frame (VR) · Three.js · Any AI agent.

Source of truth: https://nextxus.online/Core
