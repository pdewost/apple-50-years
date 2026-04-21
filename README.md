# Apple 50 Years

**Interactive checklist of historically significant Apple hardware (1976–2026) — with inflation-adjusted pricing and your personal Lifetime Customer Value.**

[**Try it live →**](https://pdewost.github.io/apple-50-years/)

---

## What is this?

Apple has shipped over 280 products in 50 years, from the Apple I ($666 in 1976) to the Vision Pro. This tool lets you check off every Apple product you have ever owned, then calculates what you actually spent — adjusted to today's dollars using official U.S. CPI data.

The result is your **#LifetimeCustomerValue**: a shareable receipt of your Apple journey.

---

## Features

- **282 products** spanning 29 categories — Pre-Mac Era through Apple Vision Pro
- **4 CEO eras** — color-coded cards (Jobs I · Interregnum · Jobs II · Cook) with a persistent stats bar showing cumulative revenue and market cap evolution per era
- **Era filter** — click any era card to restrict the view; era dividers appear in year-chronological view with tagline and financial data
- **Inflation adjustment** via BLS CPI-U data (1976–2026), fetched live with a hardcoded fallback
- **Dual view modes** — browse by product category or chronologically by year
- **Live EUR conversion** fetched from an exchange rate API, with a fixed fallback
- **Quantity tracking** — mark products you owned multiple units of
- **"My Receipt" modal** — shareable summary with product thumbnails, era breakdown, total count, and inflation-adjusted grand total
- **Shareable URL** — your selection is encoded in the URL hash so you can copy or share a direct link
- **HTML export** — download a self-contained receipt as an HTML file
- **Real-time search** — filter across all 282 products by name
- **Dark mode** — respects system preference; togglable manually
- **English / French** — auto-detects browser locale, manually switchable
- **Fully responsive** — works on mobile down to 320 px wide

---

## CEO Eras

| Era | CEO(s) | Products | Cumul. Revenue | Market Cap |
|---|---|---|---|---|
| **Jobs I** | Steve Jobs | 15 | ≈ $5.5B | $1.8B → $0.9B |
| **The Interregnum** | Sculley · Spindler · Amelio | 80 | ≈ $78B | $2.2B → $2.8B |
| **Jobs II** | Steve Jobs (return) | 72 | ≈ $357B | $4.5B → $350B |
| **Cook** | Tim Cook | 115 | ≈ $3,940B | $624B → $3.9T |

Each product card carries a colored left-border accent by era (rainbow / gray / blue / space black). The 4-column stats bar is always visible above the product grid.

---

## Tech stack

| Layer | Details |
|---|---|
| Markup | Vanilla HTML5 |
| Styling | Vanilla CSS (CSS custom properties, Grid, Flexbox) |
| Logic | Vanilla JavaScript (ES2020, no build step, no frameworks) |
| Fonts | Google Fonts — Inter + Outfit |
| Images | Wikimedia Commons (loaded lazily, all URLs MD5-verified) |
| CPI data | BLS CPI-U annual averages (live fetch + hardcoded fallback) |
| Hosting | GitHub Pages |

Zero dependencies. No npm. No bundler. Open `index.html` directly in a browser.

---

## Related project

[**apple-silicon**](https://pdewost.github.io/apple-silicon/) — reference page for every Apple-designed chip, linked inline from this checklist.

---

## Author

Built by [Philippe Dewost](https://linkedin.com/in/pdewost) · [Instagram](https://instagram.com/pdewost) · [X](https://x.com/pdewost)
