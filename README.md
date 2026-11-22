# 🏠 House Building Cost Estimator — Bangladesh

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/demo-live-brightgreen)](https://tanmoy016.github.io/house-building-cost-estimator-bd/)
[![PWD SoR 2022](https://img.shields.io/badge/rates-PWD%20SoR%202022-blue)](https://tanmoy016.github.io/house-building-cost-estimator-bd/)

A free, open-source house building cost estimator for Bangladesh. Enter your built-up area, pick a finishing level, and get a transparent, itemized estimate — every rate is editable, and the method is shown on the page.

**👉 Live demo: https://tanmoy016.github.io/house-building-cost-estimator-bd/**

No sign-up. No server. Runs entirely in your browser — open `index.html` or use the GitHub Pages link above.

## What it calculates

| Item | Basis |
| --- | --- |
| RCC concrete (frame, slabs, beams) | 0.045 cum / sq ft × PWD SoR 2022 ৳16,192/cum |
| MS rod / deformed bar | 4 kg / sq ft × market rate |
| Shuttering & labour (structure) | composite per sq ft |
| 125 mm brickwork | 0.167 sqm / sq ft × PWD SoR 2022 ৳1,411/sqm |
| 12 mm cement plaster (1:4) | 0.28 sqm / sq ft × PWD SoR 2022 ৳324/sqm |
| Floor tiles | 0.093 sqm / sq ft × PWD SoR 2022 (৳1,200–3,152/sqm by level) |
| Interior / exterior paint | PWD SoR 2022 ৳265 / ৳282 per sqm |
| Doors & windows, sanitary, electrical | composite market rates, scaled by finishing level |
| Foundation & site work | lump sum you enter |
| Contingency | 5% (editable) |

Also included: finishing levels (Basic / Standard / Premium), location multipliers from the SoR regional columns (Dhaka 1.00 → Rajshahi 0.94), an approximate materials summary (cement bags, steel, bricks, sand, aggregate), and Print / Save-as-PDF.

## Rates — where they come from

Work-item rates are taken from the **PWD Schedule of Rates 2022 (2nd Revised), Dhaka zone** — the same schedule used for government BOQs in Bangladesh. Market items (steel, doors, sanitary, electrical) are 2026 Dhaka market estimates. **All rates are editable in the app** — change any of them to your local quotation and the estimate updates instantly.

## Who this is for

- Homeowners planning a house in Bangladesh who want a realistic budget before talking to a contractor
- Civil engineers and estimators who need a quick sanity check against PWD SoR 2022
- Students learning quantity estimation and BOQ preparation

## Disclaimer

This is a planning estimate, not a quotation. Quantities use standard thumb rules per sq ft of built-up area. Verify rates with a current market quotation and a structural design before budgeting.

## Contribute

Found a wrong rate or a better thumb rule? Open an issue or a pull request — rate corrections with a PWD SoR 2022 item number are especially welcome.

## Author

**Engr. Mahmudul Hasan Tanmoy** — Sr. Executive Engineer (Civil), Evermark Limited, Dhaka, Bangladesh.

- 🌐 [Tantool — 75+ free online tools](https://www.tantool.online/)
- 📝 [TanmoyAll — civil engineering blog](https://tanmoyall.blogspot.com/)
- 💼 [LinkedIn](https://www.linkedin.com/in/mdtanmoyhasan/) · [X](https://x.com/mdtanmoyhasan)
- 🛠️ [BOQ Template Pack (Gumroad)](https://tantool.gumroad.com/l/djentn) — full BOQ templates with PWD SoR 2022 rates

## Support

If this tool saved you time, the best way to support the work is through my Gumroad store — every purchase funds more free tools for engineers:

🛠️ [Tantool on Gumroad — BOQ Template Pack, Cost Estimator & more](https://tantool.gumroad.com/)

(Note: Buy Me a Coffee, Ko-fi and GitHub Sponsors can't pay out to Bangladesh — they need Stripe or PayPal — so support goes through Gumroad, which pays out to a Bangladeshi bank account.)

## License

MIT — free to use, copy and modify, with attribution. See [LICENSE](LICENSE).
