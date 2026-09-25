# SkillCall deck v7 — verification notes (25 Sep 2026)

## Arithmetic in the calculations sheet — all re-computed
| Item | Sheet | Re-check | Status |
|---|---|---|---|
| SC below poverty line | ≈ 5.9 cr | 15.39×31.5% + 4.75×21.7% = 5.88 cr | OK |
| GIA beneficiaries / year, avg support | ≈ 50,000; ≈ ₹60,700 | 2,01,006 ÷ 4 = 50,252; 1,219.80 cr ÷ 2,01,006 = ₹60,685 | OK |
| Phone line per profile | ₹14.7 / ₹33.7 | (517×16 + 243×1.5) min × ₹0.80 × 1.10 ÷ 517 = ₹14.7; high case ₹33.7 | OK |
| Speech-to-text | ₹4.2 / ₹5.1 | 50–60 % of call minutes at ₹0.50/min, unfinished callers spread | OK |
| Text-to-speech, SMS | ₹2.4–6.0; ₹0.6–1.5 | 800–2,000 chars × ₹3/1,000; 4–6 × ₹0.15–0.25 | OK |
| **Human call-back** | **₹2.0 / ₹6.0** | 10 % × 5 min × ₹3.2 = **₹1.6**; 20 % × 6 min × ₹3.2 = **₹3.8** | **Corrected** |
| **Total per completed profile** | **₹25 / ₹56** | 24.75 / 53.6 → **≈ ₹25 / ≈ ₹54** | **Corrected** |
| Pilot | ₹9.3–12.7 lakh | 5.5–8 + 3.8–4.7 | OK |
| National / year | ₹1.1–2.1 cr; 0.05–0.10 % | 108–210 lakh; 0.051–0.098 % of ₹2,140 cr | OK |
| Per beneficiary | ₹220–420; < ₹1 per ₹100 | 0.36–0.69 % of ₹60,700 | OK |
| Officer time | 30 h → 5 h; 18 staff-years | 40×45 min = 30 h; 40×7.5 = 5 h; 50,000×37.5 min = 31,250 h ÷ 1,760 = 17.8 | OK |
| Retention | 62 % → 73 % | +11 points = 18 % relative | OK |
| Money better used | ₹12.5–15 cr; 6–14× | 2,500 × ₹50,000–60,700; ÷ ₹1.1–2.1 cr | OK |
| Latency per turn | 1.2–2.2 s | 0.5 + 0.07–0.3 + 0.3–1.0 + 0.19–0.25 + 0.1–0.2 = 1.16–2.25 s | OK |

## External facts checked against sources (25 Sep 2026)
- CAG Report No. 20 of 2025: 56.14 lakh certified, 23.18 lakh placed (41 %) — confirmed (cag.gov.in press brief, PRS, ThePrint).
- Kilkari: 1.2 million calls/day; 50 % / 76 % / 99.5 % answered by 1st / 3rd / 9th attempt — confirmed (BMJ Global Health 2021, PMC8327807).
- NFHS-6 (2023-24): women with a phone they use 63.6 %, rural 57.4 % → 42.6 % of rural women without — confirmed (PIB PRID 2266600, Factly).
- Voice of India benchmark: 36,691 speakers, 15 languages, 139 clusters, 536 h — confirmed (arXiv 2604.19151).
- SC poverty ratios 2011-12 (Tendulkar): rural 31.5 %, urban 21.7 % — confirmed (Lok Sabha AU, NIRDPR statistics).
- PM-AJAY portal & AJAY app launched 26 May 2026 — confirmed (PIB PRID 2265106, 2265530).
- Sarvam-105B ₹29.28 / 1M input, ₹10.98 cached input, ₹73.20 / 1M output — confirmed (docs.sarvam.ai pricing).
- Sarvam-30B ≈ $0.03 per 1M tokens blended — confirmed (Artificial Analysis).
- ₹457.82 cr for 8,146 projects incl. 987 skill projects (2023-24, 2024-25) — confirmed (PIB PM-AJAY explainer).

## Not reachable from this environment (kept as stated in the sheet — re-check before upload)
- PIB PRID 2112697: 9,549 projects, ₹1,219.80 cr, 2,01,006 GIA beneficiaries (pib.gov.in blocked here).
- Saaras v3 ₹30/hour and Bulbul v3 ₹3/1,000 characters (sarvam.ai pricing page blocked here).
- Theme: the sheet and deck say "Agriculture, FoodTech & Rural Development"; the public SIH 2026 list says "Smart Education" for SIH26097 — confirm on the portal.

## Placeholders still to fill
Team ID (slide 1) · GitHub repo, live prototype, demo video and calculations-sheet links (slides 3 and 6).
