# 🇵🇱🇨🇿 Poland & Czech Republic Trip Planner

**May 22 – 31, 2026 · 10 days · Prague → Kraków → Warsaw**

A single-page, mobile-first travel reference for a group trip across Prague, Kraków, and Warsaw. Built as one self-contained HTML file — no build step, no dependencies, no framework.

🔗 **[Live site →](https://eb324.github.io/poland-czech-trip-planner/)**

---

## What's inside

### 📅 Summary Calendar
A 10-day visual overview (May 22–31) showing all constraints across all three cities at a glance — closures, reduced hours, public holidays, and free-entry days. Uses a unified colour-coded pill system so every flag type looks the same everywhere.

### 🏛 Site Reference
Detailed visitor cards for 20 major sites across Prague, Kraków, and Warsaw. Each card shows:
- Opening hours and weekly closure days
- Admission prices in **three currencies** (local · HK$ · €)
- Booking requirements and timed-entry notes
- Practical tips and official website links

### 🚆 Internal Travel
Transport options between the three cities — trains (Pendolino, Leo Express, RegioJet, EuroNight), buses, and approximate prices in triple currency.

### 🗺 Dual Itinerary with Toggle
Two fully detailed 9-day itineraries presented side by side via an iOS-style segmented toggle:
- **★ PRG → KRK → WAW** (recommended)
- **WAW → KRK → PRG** (alternative)

Both are equally detailed. The recommended route is optimised around weekly closure patterns — not flight pricing or personal preference.

---

## Features

| Feature | Detail |
|---|---|
| **Bilingual** | Full English / 繁體中文 toggle — every label, pill, note, and itinerary stop translates. Fixed top-right language switcher. |
| **Mobile-first** | Responsive grid (2-col mobile, 5-col desktop for calendar). Touch-friendly targets, safe-area support for notched phones, CJK-optimised font stack. |
| **Zero dependencies** | One HTML file. Inline CSS + vanilla JS. Only external call is Google Fonts (DM Sans + Noto Sans TC). Works offline once loaded. |
| **Triple currency** | All prices shown in local currency, HK$, and € side by side. |
| **Flight-agnostic factual sections** | Calendar, site reference, and transport sections contain no flight assumptions. Flight details only appear in the recommendation as a timing reference. |

---

## Deploy

Rename the file to `index.html` and push to any static host.

### GitHub Pages

```bash
git init
git add index.html
git commit -m "trip planner"
git remote add origin https://github.com/<you>/poland-czech-trip-planner.git
git branch -M main
git push -u origin main
```

Then go to **Settings → Pages → Source: main / root → Save**.

Live at `https://<you>.github.io/poland-czech-trip-planner/` within a minute.

---

## File structure

```
poland-czech-trip-planner/
├── index.html          # The entire app (rename from trip-planner-bilingual.html)
└── README.md           # This file
```

That's it. No `package.json`, no `node_modules`, no build pipeline.

---

## Data sources & accuracy

All site information was researched from official museum websites and verified third-party sources. Key references:

| Site | Official URL |
|---|---|
| Warsaw Royal Castle | [zamek-krolewski.pl/en](https://www.zamek-krolewski.pl/en) |
| POLIN Museum | [polin.pl/en](https://polin.pl/en) |
| Warsaw Rising Museum | [1944.pl/en](https://www.1944.pl/en) |
| Wawel Royal Castle | [wawel.krakow.pl/en](https://wawel.krakow.pl/en) |
| Schindler's Factory | [muzeumkrakowa.pl](https://muzeumkrakowa.pl/en/branches/oskar-schindlers-enamel-factory) |
| Wieliczka Salt Mine | [wieliczka-saltmine.com](https://www.wieliczka-saltmine.com) |
| Prague Castle | [hrad.cz/en](https://www.hrad.cz/en/prague-castle-for-visitors) |
| Jewish Museum Prague | [jewishmuseum.cz/en](https://www.jewishmuseum.cz/en) |

**⚠️ Always verify hours and prices on official sites before your visit.** Museums may adjust schedules for state events, renovations, or seasonal changes. Exchange rates (1 PLN ≈ 2.13 HKD ≈ 0.25 EUR; 1 CZK ≈ 0.33 HKD ≈ 0.04 EUR) are approximate as of March 2026.

---

## License

Personal use. Not affiliated with any museum, airline, or tourism board.
