# Tier 2/3 India Franchise & Business Portal

Static bilingual research portal for franchise and small-city business planning across Tier 2 and Tier 3 towns in India.

## Included

- `index.html` — responsive landing page, English/मराठी switch, Google Translate integration
- `opportunities.js` — 132 source-linked opportunities across below ₹10L, ₹10–25L and ₹25–50L, with hands-on and job-holder economics and a franchise network-size figure per brand
- `master-plan.md` — complete plan and owner-ready replacement portfolio
- `verification-audit.md` — row-by-row verification notes and sources
- `fact-check-summary.md` — concise discrepancy summary

## Run locally

Because browsers restrict `fetch()` from `file://` URLs, serve the folder with any static server:

```bash
python3 -m http.server 49173
```

Then open <http://localhost:49173>.

## GitHub Pages

The site is static and can be published from the repository's `main` branch root using **Settings → Pages → Deploy from a branch → main → /(root)**. The external Google Translate script is optional; English remains available if it is blocked.

The opportunity cards separate two owner cases: an owner who works daily (owner salary excluded) and an owner with another job (staff payroll included). Fixed-cost, surplus and payback ranges are conservative planning estimates; they are not franchise guarantees. The public-source confidence label on each card shows whether the provider publishes a figure or only an enquiry route.

Each card also shows a **franchise network size** (how many outlets/dealers/partners the brand has), labeled by how confident the figure is: **Official** (the brand's own stated count), **Estimated** (no official count exists, so a range is derived from a stated method — e.g. distributor counts × typical sub-dealers — never a fake-precise single number), or **Not disclosed** (nothing findable). Payback is shown as a real computed number only where the brand's own capital figure is firm; otherwise it reads "Quote dependent" rather than a fabricated range — see `verification-audit.md` for the batch-2 sourcing notes and the list of candidate brands that were checked and excluded as not being real, currently-active franchise programs.

## Research note

Investment figures, fees, territory availability, licensing, staffing and profitability are not guaranteed. Confirm every commercial term directly with the provider and validate local demand before paying a deposit.
