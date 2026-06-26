# Lumora

Single-page landing for **Lumora — Independent Design & Engineering Studio**. Light editorial palette, Lenis smooth scroll, full-screen intro loader, and a hero **liquid cursor-reveal** over photography.

**Live:** [pipapaparapo2024.github.io/lumora](https://pipapaparapo2024.github.io/lumora/)

## Stack

- One file: `index.html` (HTML + CSS + ES module JS)
- [Lenis](https://github.com/darkroomengineering/lenis) 1.3.23 via unpkg importmap
- Google Font **Onest**
- Hero images bundled in `images/` (no external CDN)

## Local development

```bash
cd lumora
npx serve -p 3457
```

Open [http://localhost:3457](http://localhost:3457) — use HTTP, not `file://`.

## GitHub Pages

1. Push this folder to [`pipapaparapo2024/lumora`](https://github.com/pipapaparapo2024/lumora)
2. Workflow [`.github/workflows/pages.yml`](.github/workflows/pages.yml) publishes `main` to the `gh-pages` branch
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch**
4. Branch: **gh-pages** / folder: **/ (root)** → Save

Site URL: [pipapaparapo2024.github.io/lumora](https://pipapaparapo2024.github.io/lumora/)

## Features

| Area | Details |
|------|---------|
| Loader | Count `000→100`, slide-up exit, scroll lock until done |
| Hero | Liquid brush canvas (`after.jpg` base, `before.jpg` trail) |
| Scroll | Lenis `smoothWheel`, adaptive rem grid |
| Sections | About, CreateBand, Portfolio, Services, Stats, Footer |
| UI | Full-screen nav menu, request modal (stub submit) |
| Motion | Line/word reveals, hover springs (desktop), stats count-up |

## License

Portfolio / demo project.
