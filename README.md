# GeoSignal

A minimalist geopolitical scorecard for personal investors. Know what's happening in the world, and what it means for *your* portfolio — in under 30 seconds.

**[→ Open the app](https://hzhou0106.github.io/geosignal)**

---

## What it does

Most financial news is designed to overwhelm. GeoSignal filters it down to what actually matters for your specific holdings.

- Pulls the **top 3 geopolitical & macro events** happening right now via live web search
- Calculates a **portfolio risk score (0–100)** based on your specific holdings' exposure
- Flags each ticker as **high / medium / low** risk
- Gives a **calm, long-term take** on each event — not alarmist, just clear
- One-tap drill-down per event: what happened, market implication, and a grounded investor perspective

---

## How to use

1. Get an API key at [console.anthropic.com](https://console.anthropic.com)
2. Open the app and paste your key — it stays in memory only, never saved
3. Enter your portfolio tickers (e.g. `AAPL, VTI, BND, GLD`)
4. Hit **refresh** — signal loads in ~10 seconds

---

## Stack

| | |
|---|---|
| Frontend | Single HTML file — no framework, no build step |
| AI | Claude Sonnet via Anthropic API |
| News | Claude's built-in web search tool (live results) |
| Storage | None — nothing is saved anywhere |
| Hosting | GitHub Pages |

No backend. No database. No tracking. Just open the file and go.

---

## Running locally

No setup needed. Just open `index.html` in any browser.

```bash
git clone https://github.com/hzhou0106/geosignal
open geosignal/index.html
```

---

## Deploying to GitHub Pages

1. Push `index.html` to your repo
2. Go to **Settings → Pages → Source → main branch → / (root)**
3. Hit Save — your app is live at `https://yourusername.github.io/geosignal`

---

## Disclaimer

Not financial advice. GeoSignal is for orientation and awareness only. Always do your own research before making investment decisions.

---
