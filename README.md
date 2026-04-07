# glypher.

**Design resources, ready to paste.**

Glypher is a curated open-source library of SVG icons, section dividers, background patterns, and styled UI components for frontend developers and designers. Every resource is hand-curated by a professional graphic designer — not mass-generated or algorithmically scraped.

🔗 [glypher.dev](https://glypher.dev) · MIT License · Free forever

---

## What's inside

| Category | Description |
|----------|-------------|
| **Icons** | Clean SVG icons, 24×24 viewBox, outline style |
| **Dividers** | Section separators — waves, zigzags, organic curves, geometric cuts |
| **Patterns** | Tileable SVG background patterns with CSS snippets |
| **Buttons & UI** | Styled HTML+CSS components, no JS dependencies |
| **Styles** | CSS utility classes and design tokens |

---

## How to use

No install, no account, no build step required.

1. Visit [glypher.dev](https://glypher.dev)
2. Browse or search the library
3. Click a resource to preview and customize it
4. Copy the code — it's ready to paste

All resources are MIT licensed. No attribution required.

---

## Project structure

```
glypher/
├── index.html          ← Homepage (curated preview)
├── library.html        ← Full library with search and filters
├── style.css           ← All styles
├── main.js             ← Filter, search, copy, preview logic
├── data/
│   └── resources.json  ← All resource metadata and SVG code
├── assets/
│   ├── icons/
│   ├── dividers/
│   ├── patterns/
│   └── buttons/
└── README.md
```

---

## Resource format

Each entry in `resources.json` follows this structure:

```json
{
  "id": "wave-divider-01",
  "name": "Wave",
  "category": "dividers",
  "tags": ["wave", "organic", "stroke"],
  "svg": "<svg viewBox=\"0 0 900 60\">...</svg>",
  "css": "",
  "preview_bg": "#F5F2ED",
  "added": "2025-01"
}
```

---

## Tech stack

| Phase | Stack |
|-------|-------|
| Phase 1 (current) | HTML · CSS · Vanilla JS |
| Phase 2 | React migration |
| Hosting | Netlify / Vercel |

---

## Roadmap

- [x] Brand identity and design system
- [x] Figma prototype
- [ ] HTML/CSS prototype with sample resources
- [ ] Dynamic MVP — grid renders from `resources.json`
- [ ] 50+ resources across all categories
- [ ] Deploy to glypher.dev
- [ ] React migration
- [ ] Figma plugin

---

## Support

Glypher is free and always will be. If it saved you time, a coffee goes a long way. ♥

[![Support on Ko-fi](https://img.shields.io/badge/Support%20Glypher-Ko--fi-blue?style=flat-square)](https://ko-fi.com)

---

## License

MIT — free to use in personal and commercial projects. No attribution required.
