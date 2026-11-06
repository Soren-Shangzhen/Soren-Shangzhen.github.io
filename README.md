# shangzhen-zhu.com

Source for [shangzhen-zhu.com](https://shangzhen-zhu.com), the personal site of Shangzhen Zhu.

Built with [al-folio](https://github.com/alshedivat/al-folio) (Jekyll) and deployed to GitHub Pages by the `Deploy site` workflow, which builds `main` into the `gh-pages` branch.

- `_pages/about.md`: home page bio
- `_bibliography/papers.bib`: publications
- `_posts/`: blog index entries
- `softmax/index.html`: the self-contained "How Much Softmax Do You Need in LLMs?" explainer, served at `/softmax/`

Local overrides of al_folio_core 1.0.15 files (re-check these when upgrading the gem):

- `assets/css/main.scss`: accent colors, and loads the site design system
- `_layouts/about.liquid`: custom home page (hero, profile panel, numbered sections); its text lives in `_pages/about.md`

Site design system: `_sass/_sz.scss` (palette, typography, components). Fonts are self-hosted in `assets/fonts/`
(Inter, Inter Tight, Space Grotesk, IBM Plex Mono; SIL OFL 1.1, licenses alongside).
