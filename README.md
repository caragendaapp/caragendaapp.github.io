# Araç Ajandası · Car Agenda — website

Public website of the Araç Ajandası / Car Agenda app, served by GitHub Pages from `main`.
Same layout as the Pressure Diary site (`style.css`, `lang.js`: Turkish and English, one at a time).

| Page | Path |
|---|---|
| App page | `/` |
| Privacy policy (TR + EN) | `/privacy.html` (Play Console privacy policy URL) |
| Terms of use (TR + EN) | `/terms.html` |
| Remote rules | `/rules.json` (`RULES_URL` in the app build) |

Live at https://caragendaapp.github.io/ (the `caragendaapp` organization site; the repository
must keep the name `caragendaapp.github.io` to be served from the domain root). AdMob later needs `app-ads.txt` at that root.

## Updating

- **Privacy policy:** the app repo (`kaanonur/caragenda`) keeps the same text in `docs/privacy-policy.md`. Change both and the effective date.
- **Rules:** copy `assets/rules/rules.json` from the app repo here after raising its `rulesVersion`. The app only takes a copy with the same `schemaVersion` and a newer `rulesVersion`.

Contact: caragenda@protonmail.com
