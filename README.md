# Buying in Portugal 🏠

How much cash do you actually need to bring to the table when buying property in Portugal?

A **zero-dependency, single-page calculator** that runs entirely in your browser — no cookies, no tracking, no server calls.

**[→ Live site](https://cashforproperty.pt)**

## What it calculates

| Cost | Description |
|---|---|
| **Equity** | Property price minus the bank mortgage |
| **IMT** | Progressive transfer tax (Imposto Municipal sobre Transmissões) with 2026 brackets |
| **Selo — property** | Stamp duty at 0.8% of purchase price |
| **Selo — mortgage** | Stamp duty at 0.6% of mortgage amount |
| **Notary** | Deed signing (escritura), registration, certidões |
| **Lawyer** | Legal representation |
| **Translator** | Required by law if you don't speak Portuguese |

### IMT JOVEM & IS JOVEM

First-time buyers aged ≤ 35 purchasing a primary residence get:
- **Full IMT exemption** up to ~€330k, partial above (up to ~€661k)
- **Full Selo (property) exemption** on the same thresholds

Calculations verified against real 2026 tax authority (AT) documents.

## Options

- **Residency status** — PT resident (up to 90% financing) vs. non-resident (up to 70%)
- **Property purpose** — primary residence vs. secondary/investment (different IMT brackets)
- **Bank evaluation** — affects mortgage amount (bank lends on the lower of price vs. evaluation)

## Tech

- Single `index.html` — Tailwind CSS v4 via CDN, vanilla JS
- All calculations are client-side and instant
- Responsive layout, works on mobile
- Deployed to Cloudflare Pages via GitHub Actions

## Development

Just open `index.html` in a browser. No build step.

## Deployment

Pushes to `main` auto-deploy to Cloudflare Pages via GitHub Actions. See `.github/workflows/deploy.yml`.

## Disclaimer

This calculator uses approximate 2026 IMT brackets for continental Portugal. Rates are updated annually. Always consult a qualified professional before making financial decisions.
