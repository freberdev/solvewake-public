# SolveWake – public pages

The public website for the SolveWake iPhone app, published with GitHub Pages:

| Page | English | Swedish |
|---|---|---|
| Home (promo, App Store Marketing URL) | https://freberdev.github.io/solvewake-public/ | https://freberdev.github.io/solvewake-public/sv/ |
| Privacy policy (App Store Privacy Policy URL) | https://freberdev.github.io/solvewake-public/privacy/ | https://freberdev.github.io/solvewake-public/sv/privacy/ |
| Support (App Store Support URL) | https://freberdev.github.io/solvewake-public/support/ | https://freberdev.github.io/solvewake-public/sv/support/ |

## How it's built

- `index.md` and `sv/index.md`: the home page. All of its text lives in the front matter; the page structure is `_layouts/promo.html`.
- `privacy.md`, `support.md` and the same files under `sv/`: plain Markdown rendered with `_layouts/default.html`.
- `_includes/`: the shared head, header (Home, Privacy, Support, language switch) and footer.
- `assets/css/site.css`: the Dawn colours and all styles.
- `assets/screens/`: app screenshots in English (`en-*`) and Swedish (`sv-*`).

When the app is live on the App Store, replace the "Coming soon to the App Store" label (`soon` in the front matter) with Apple's official App Store badge and link.
