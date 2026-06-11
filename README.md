# 🏠 Rent vs Buy Calculator — India

A free, no-login calculator that helps you decide whether to buy a home or
keep renting and invest the difference — using real city and area-level
data instead of generic assumptions.

**Live tool:** https://jaganmohankb-git.github.io/rent-vs-buy/

---

## What it does

- Pick your **city and area** — the tool auto-fills realistic 2BHK price
  and rent defaults for that micro-market and recalculates instantly
- Compares **buying with a home loan** vs **renting + investing the
  difference (SIP)** over a 20-year horizon
- Models **floating interest rate risk** — shows EMI impact if rates
  rise or fall by 1–2%
- Accounts for **property depreciation** on pre-owned flats (land vs
  building split)
- Supports **2/3/4 BHK** and budget/mid/luxury segments
- Supports **full cash purchase** comparisons (property appreciation vs SIP)
- Generates a **shareable result image** and WhatsApp-ready text report
- Cites every assumption and its data source inline

## Data sources

- Property appreciation: NHB RESIDEX Q1 FY26
- Area-level rents: bengaluru.rent (Mar 2026), EazeMy Rent (Apr 2026), NoBroker (H1 2025)
- Rental growth assumption: NoBroker H1 2025
- Loan rates: RBI repo rate (Jun 2025) + typical home loan spread

All defaults are editable — if you have better local data for your area,
adjust the sliders under "Customise assumptions."

## Tech

Single-file static HTML — no backend, no build step. Charts via Chart.js.
Works offline once loaded. Deployed via GitHub Pages.

## Feedback

This is a beta tool. If something looks off or you have suggestions,
please open an issue on this repo or reach out via
[jkadvisory.in](https://jkadvisory.in).

## Disclaimer

This tool provides indicative estimates for educational purposes only.
It is not financial or investment advice. Please consult a SEBI-registered
financial advisor before making real estate or investment decisions.

---

Built by [JK Advisory](https://jkadvisory.in)
