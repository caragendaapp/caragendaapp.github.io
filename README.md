# car-agenda-site

Public pages for the Araç Ajandası app, served by GitHub Pages from `main`.

| File | Published at | Used for |
| --- | --- | --- |
| `index.html` | `https://kaanonur.github.io/car-agenda-site/` | Short app page |
| `privacy.html` | `https://kaanonur.github.io/car-agenda-site/privacy.html` | Play Console privacy policy URL |
| `rules.json` | `https://kaanonur.github.io/car-agenda-site/rules.json` | Remote rules (`RULES_URL` in the app build) |

## Updating

- **Privacy policy:** the source text is `docs/privacy-policy.md` in the app repo. Change both, and bump "Last updated".
- **Rules:** copy `assets/rules/rules.json` from the app repo here after raising its `rulesVersion`. The app only takes a copy with the same `schemaVersion` and a newer `rulesVersion` (see `docs/remote-rules.md` in the app repo).
