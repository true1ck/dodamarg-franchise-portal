# Dodamarg Franchise & Business Portal

Static bilingual research portal for the Dodamarg, Sindhudurg small-town franchise and business plan.

## Included

- `index.html` — responsive landing page, English/मराठी switch, Google Translate integration
- `master-plan.md` — complete plan and owner-ready replacement portfolio
- `verification-audit.md` — row-by-row verification notes and sources
- `fact-check-summary.md` — concise discrepancy summary

## Run locally

Because browsers restrict `fetch()` from `file://` URLs, serve the folder with any static server:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## GitHub Pages

The site is static and can be published from the repository's `main` branch root using **Settings → Pages → Deploy from a branch → main → /(root)**. The external Google Translate script is optional; English remains available if it is blocked.

## Research note

Investment figures, fees, territory availability, licensing, staffing and profitability are not guaranteed. Confirm every commercial term directly with the provider and validate local demand before paying a deposit.
