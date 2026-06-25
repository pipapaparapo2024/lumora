# Lumora

Single-page landing for **Lumora — Independent Design & Engineering Studio**. Light editorial palette, Lenis smooth scroll, full-screen intro loader, and a hero **liquid cursor-reveal** over photography.

**Live (after deploy):** [pipapaparapo2024.github.io/lumora](https://pipapaparapo2024.github.io/lumora/)

## Stack

- One file: `index.html` (HTML + CSS + ES module JS)
- [Lenis](https://github.com/darkroomengineering/lenis) 1.3.23 via unpkg importmap
- Google Font **Onest**
- Hero images from CDN (`lumora-e8b711fc68` bucket)

## Local development

```bash
cd lumora
npx serve -p 3457
```

Open [http://localhost:3457](http://localhost:3457) — use HTTP, not `file://`.

## GitHub Pages

1. Push this folder to `pipapaparapo2024/lumora`
2. **Settings → Pages → Source: GitHub Actions**
3. Workflow [`.github/workflows/pages.yml`](.github/workflows/pages.yml) deploys on push to `main`

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
