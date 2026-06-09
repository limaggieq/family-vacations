---
tags: [project, travel]
status: active
area: travel
start: 2026-05-27
deadline: null
---

# Family Vacation Destinations

> [!info] Source-of-truth role
> Current owner for the family destination shortlist and publishing workflow until a specific dated trip project is opened.

## Context

London 2026 was a hit. The whole family is in. Now we need to figure out where to go next — and get everyone coordinated on dates before life fills up the calendar.

This project is a living reference for future group trips. Multi-household family — LAX and SEA origins, multiple generations. Format: **7 days, full Sunday arrival to full Saturday departure.**

## Rules

1. **International focus** — domestic trips handled separately (Hawaii on hold for now)
2. **No Mexico, no Latin America**
3. **Direct flight from SEA required** — non-negotiable filter; kids can't do a connection + long-haul
4. **7-day single basecamp** — one hotel for the full week; Iceland is the one road-trip exception

## The HTML Site

`family-vacations.html` — publishable to GitHub Pages. `destinations.js` is the content layer; update that file for any destination changes, then the site updates automatically.

**Workflow:** MD → confirm → destinations.js → HTML. Do not update JS until content is approved.

## Destinations

All 11 pass the SEA-direct filter. Ordered by flight time (shortest first). All content complete and live in site.

| # | Destination | SEA | LAX | Best Season | Format | Content |
|---|---|---|---|---|---|---|
| 1 | Reykjavik, Iceland | ✅ 7h 35m | ❌ connect | Jun – Aug | Road trip exception | ✅ in-site |
| 2 | Dublin, Ireland | ✅ 9h 10m | ✅ ~10h | May – Sep | Basecamp | ✅ in-site |
| 3 | Copenhagen, Denmark | ✅ 9h 15m | ↩️ connect | May – Aug | Basecamp | ✅ in-site |
| 4 | Amsterdam, Netherlands | ✅ 9h 45m | ✅ ~10.5h | Jun – Aug | Basecamp | ✅ in-site |
| 5 | Paris, France | ✅ 10h 20m | ✅ ~11h | Apr–Jun, Sep | Basecamp | ✅ in-site |
| 6 | Barcelona, Spain | ✅ 10h 40m | ↩️ via Madrid | May–Jun, Sep | Basecamp | ✅ in-site |
| 7 | Rome, Italy | ✅ 11h 00m | ✅ ~11.5h | Mar – May | Basecamp | ✅ in-site |
| 8 | Shanghai, China | ✅ 13h 05m | ✅ ~13h | Sep – Nov | Basecamp | ✅ in-site |
| 9 | Chengdu, China | ✅ 13h 25m (Hainan Air — verify freq) | ✅ ~15h 45m (Sichuan Air 3U3838, 3x/week Tue/Fri/Sun) | Mar–May, Sep–Nov | Basecamp | ✅ in-site |
| 10 | Hong Kong | ✅ 14h 00m | ✅ ~13.5h | Oct – Dec | Basecamp | ✅ in-site |
| 11 | Singapore | ✅ 16h 30m | ✅ ~17h | Nov – Jan | Basecamp | ✅ in-site |

**On hold:** Maui (domestic, separate consideration)
**Removed:** Portugal, Greece, Thailand, Japan — no SEA direct per the source matrix

## Chengdu Notes

Source plan: [May 2025 Chengdu Trip Plan](https://docs.google.com/document/d/1_xmseU3O2htc6Kkl9eBeGcwI-qEuW5HKaeUl2i9su8c/) — family already researched this in detail.
Key advantages: Giant Panda Base, Leshan Giant Buddha + Dujiangyan via bullet train, Sichuan food, Grand Hyatt adjacent to Chunxi Road / IFS / Taikoo Li.
Visa note: Maggie/Bill/Jordan already hold 10-year China visas. Extended family will need L visa (4–6 weeks in advance).
SEA routing: Hainan Air SEA–CKG, then HSR Chongqing → Chengdu. Verify frequency before committing.

## Next Actions

- [x] Confirm this destination list is final
- [x] Draft content for each destination (in chat for review before destinations.js)
- [x] Update destinations.js and HTML site with all 11 destinations
- [ ] Add your phone number to the CTA button (`sms:+1XXXXXXXXXX` placeholder in HTML)
- [ ] Share HTML link with family
- [ ] Collect date availability from both crews
