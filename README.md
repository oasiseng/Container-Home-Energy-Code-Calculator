# 🌞 Container Home Energy Code Calculator (Florida FBC 2023)

A free, responsive, browser-based calculator that helps Florida-based container home builders and designers **pre-check compliance** with energy efficiency requirements outlined in the **Florida Building Code (FBC) 2023, 8th Edition** — specifically for **Climate Zones 1A and 2A**.

This tool is built in pure HTML/CSS/JS (no backend), powered by TailwindCSS and a custom scoring algorithm.

---

## 🔍 Features

- ✅ Instant feedback on:
  - Ceiling / Wall / Floor Insulation (R-values)
  - Window U-Factor and SHGC
  - Air leakage (ACH50)
  - HVAC efficiency (SEER2 / HSPF2)
- 💡 Calculates a proprietary **Oasis Container Homes Green Score™** from 0–150
- 📊 Color-coded gauge bar to visualize performance
- 📍 Florida-specific climate zone logic
- ⚠️ Ventilation alert if ACH50 < 3 (as required by code)
- 📝 Clear PASS / FAIL indicators vs. prescriptive code values
- ❌ Does *not* require server hosting — can run fully offline

---

## 🏗 Use Case

This tool is designed for:

- Florida homeowners planning container-based dwellings
- Contractors & builders needing a quick prescriptive code check
- Designers exploring compliant envelope specs
- Pre-permit planning and educational use

---

## 🚀 Getting Started

1. **Clone or download this repository**
2. Open the `index.html` file in your browser — that’s it!

No dependencies or installation required.

```bash
git clone https://github.com/YOUR-USERNAME/container-home-energy-code-florida.git
cd container-home-energy-code-florida
open index.html
```

## 📦 Code Structure
index.html – Entire UI and logic are contained in this file

✅ TailwindCSS included via CDN
✅ JavaScript logic handles all validation, comparison, scoring, and rendering
✅ Responsive layout with detailed tooltips and documentation

## 📐 Technical Notes
Compares user inputs against FBC 2023 Prescriptive Table R402.1.2 values
Score algorithm penalizes missing requirements and rewards exceeding code minimums
Supports Impact Window Exception (Zone 2A) for U-factor
All validation is handled client-side

## ⚠️ Disclaimer
This tool is for informational and preliminary planning purposes only.

## It does NOT:

Replace a certified HERS® rating or ENERGY STAR® certification
Provide HVAC sizing (Manual J/S/D)
Guarantee Florida code compliance
Always consult licensed professionals and local building officials before construction.

## 📸 Screenshot
Example UI screenshot coming soon.

## ✨ Future Ideas
Add save/export to PDF feature
Add alternative compliance paths (Performance / ERI)
Add support for other states or IECC code
Add optional solar gain calculator

## 🙌 Acknowledgments
Created by Oasis Engineering LLC to support builders of resilient, affordable homes.

## 🪪 License
MIT License — Free to use, modify, and redistribute with attribution.


