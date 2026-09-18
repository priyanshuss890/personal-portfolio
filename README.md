# personal-portfolio

Personal portfolio site for **Priyanshu Omkar Saraswat** — AI Engineer building production GenAI systems: agents, RAG pipelines, and LLM automation.

A single, dependency-free `index.html`. No build step, no framework, no bundler — open the file and it runs.

## Sections

| # | Section | Contents |
|---|---------|----------|
| 01 | Experience | AI Engineer @ BeastLife, Software Developer @ Technocraft Solutions |
| 02 | Selected Work | AI-YouTube Agent (RAG over video transcripts), Grammar Scoring Engine (WavLM + DeBERTa) |
| 03 | Research | Federated multi-task affect recognition via bidirectional cross-modal attention |
| 04 | Stack | AI/LLMs, languages, backend, frontend, data, cloud & DevOps |
| 05 | Milestones | JEE Advanced, hackathon win, competitive programming, certifications |
| 06 | Contact | Email, GitHub, LinkedIn |

## Design

"Technical editorial" — warm paper against true ink, with a single vermilion spot color.

- **Type:** Instrument Serif (display), Figtree (body), JetBrains Mono (labels and metadata), loaded from Google Fonts
- **Theme:** follows the OS via `prefers-color-scheme`, with a manual toggle in the nav that persists to `localStorage`
- **Motion:** `IntersectionObserver` scroll reveals, animated number tickers, a scramble-in kicker, drifting aurora blobs, and a rotating SVG stamp
- **Accessibility:** every animation is disabled under `prefers-reduced-motion: reduce`
- **Responsive:** fluid `clamp()` type scales, grids that collapse to single-column on small screens

## Running it

Open `index.html` in any browser. That's it.

For a local server (useful if you want clean URLs or live reload):

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

Any static host works — GitHub Pages, Netlify, Vercel, Cloudflare Pages. There is a single file and nothing to build.

For GitHub Pages: **Settings → Pages → Source: Deploy from a branch → `main` / `root`**.

## Editing

Everything lives in `index.html`:

- **Colors** — the CSS custom properties under `:root` (and the two dark-mode blocks below it)
- **Copy** — the markup in `<body>`; each section is a plain `<section>` with a matching `id`
- **Hero counters** — the `data-n` and `data-suf` attributes on `.ledger b`
- **Behavior** — the single `<script>` block at the bottom

## Contact

- Email — [saraswatpriyanshu19@gmail.com](mailto:saraswatpriyanshu19@gmail.com)
- GitHub — [@priyanshuss890](https://github.com/priyanshuss890)
- LinkedIn — [priyanshu-saraswat](https://www.linkedin.com/in/priyanshu-saraswat-64a51b233/)
