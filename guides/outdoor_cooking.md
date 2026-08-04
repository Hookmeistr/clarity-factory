# MASTER SOURCE FILE — Outdoor Cooking Buyer's Guide

> **This is the single source of truth.** All deliverables (Word doc, Excel, web app) are
> *generated from* this file. Never edit the deliverables directly — edit this file, then regenerate.
> This file uses the subject-agnostic schema defined in `RESEARCH_FRAMEWORK_template.md`,
> so the same structure can be reused for any product category (lawnmowers, refrigerators, etc.).

---

## 0. PROJECT METADATA

| Field | Value |
|---|---|
| Project name | Outdoor Cooking Buyer's Guide (working title — see naming options in PROJECT_INSTRUCTIONS.md) |
| Product category | Outdoor cooking equipment (pellet, gas, charcoal, kamado, griddle) + fuel + accessories |
| Scope | All current-market brands, models, fuel, and accessories — neutral, no personal framing |
| Edition | Living document; edition label = year of most recent full update |
| Last FULL update | 2026-05-25 |
| Last update model | Claude Opus 4.7 |
| Next scheduled update | 2026-08-25 (quarterly) |
| Update cadence | Every 3 months (vertical refresh + horizontal scan — see Section 1) |
| Knowledge-cutoff caveat | AI training cutoff is ~Jan 2026; everything past that comes from live web search at update time |

---

## 1. HOW TO RUN AN UPDATE  *(instructions to the AI running a refresh)*

Every quarterly update MUST do BOTH of these passes. Skipping the horizontal pass causes
the guide to go stale by omission (it would miss new manufacturers entirely).

### 1A. VERTICAL refresh — re-verify what's already tracked
For each brand/model/pellet entry below, re-check and update: current price, availability,
discontinuation status, firmware/controller revisions, warranty changes, ownership changes.
Update the `verified` date on each entry you confirm. Flag anything that changed in the Changelog.

### 1B. HORIZONTAL scan — find what's NEW
Run the scan queries in the Discovery Log (Section 2). Look specifically for:
- New manufacturers entering the market (e.g., how Brisk It and Ninja entered recently)
- New product categories/form factors (e.g., pellet griddles, AI grills, electric-hybrid)
- New fuel/pellet brands or reformulations of existing ones
- New accessory makers worth listing
- Brands that exited, went bankrupt, or were acquired
Add any genuinely new, market-relevant entrant to the data sections and note it in the Changelog.

### 1C. Update protocol
1. Read this whole file first.
2. Run vertical + horizontal passes (aim ~25–50 targeted searches for a thorough refresh).
3. Update data sections + `verified` dates.
4. Write a dated entry in Section 9 (Changelog) summarizing exactly what changed.
5. Bump "Last FULL update" and "Next scheduled update" in Section 0.
6. Regenerate deliverables from the updated file.

---

## 2. DISCOVERY LOG  *(scan queries + when last run — drives the horizontal pass)*

| Scan query | Purpose | Last run | Notable result |
|---|---|---|---|
| "best pellet grills [year] new models" | New pellet models | 2026-05-25 | Traeger Woodridge line; Brisk It; Ninja; Z Grills dual-wall |
| "new pellet grill brand [year]" | New manufacturers | 2026-05-25 | Brisk It (AI), Ninja Woodfire (electric-hybrid) confirmed |
| "[brand] 2026 lineup new models prices" (per brand) | Per-brand refresh | 2026-05-25 | Recteq full 2026 relaunch; Traeger 40th-anniversary line |
| "best wood pellets [year] new brands" | Fuel refresh | 2026-05-25 | Kona (Ninja-optimized), Smokin' Brothers surfacing |
| "pellet grill griddle / flat top wood-fired" | New form factors | 2026-05-25 | Recteq Smokestone pellet griddle (new category) |
| "AI grill / smart grill [year]" | Tech trend | 2026-05-25 | Brisk It Vera AI 2.0; trend confirmed but AI still half-baked |
| "[competitor name] grill guide" | Competitive landscape | 2026-05-25 | "The Grill Buyer's Black Book" (Matt Garrison) on Lovable — name is taken |

**Next scan additions to try:** "best gas grill [year] new," "kamado [year] new models,"
"pellet grill recall [year]," "[brand] discontinued [year]," "outdoor kitchen trends [year]."

---

## 3. EVALUATION CRITERIA  *(what actually matters in this category)*

These are the dimensions every product is scored on. (For a different category, this section
is replaced with that category's criteria — the rest of the schema stays identical.)

- **Build quality / steel gauge** — 10–12ga = competition; 20+ga = thin/budget. 304 SS > 430 SS > powder-coated mild steel.
- **Temperature control** — True PID (±3–10°F) vs duty-cycle (±15–35°F). The single most important spec for low-and-slow.
- **Smoke production** — quality and adjustability of smoke output.
- **Sear / open-flame capability** — direct-flame access (slide-plate systems) and max temp.
- **WiFi / app ecosystem** — connectivity reliability + app maturity + cloud features.
- **Parts availability & repairability** — can you get parts in 5–10 years?
- **Warranty (length AND fulfillment reputation).**
- **Pellet/fuel efficiency.**
- **Overall value** — performance per dollar over expected lifespan.

Grade scale: A+ / A / A- / B+ / B / B- / C+ / C / C- / D / F.

---

## 4. DATA — MANUFACTURERS / BRANDS

> Schema per brand: name | parent/ownership | founded | HQ | manufacturing | warranty | tier | notes | verified date

### Pellet grill brands
- **Traeger** | Public (NASDAQ: COOK) | 1985 | Salt Lake City, UT | China (US design) | 3 yr | Mid-premium | Invented pellet grill; 40th-anniversary **Woodridge line launched** (Woodridge $799 / Woodridge Pro $999 / Woodridge Elite $1,599) replacing Pro series; Super Smoke Mode on Pro+; WiFIRE app is category-leading; Ironwood & Timberline upmarket. | 2026-05-25
- **Recteq** | Private | 2009 | Evans/Augusta, GA | China mfg, assembly/testing Augusta GA | 6 yr (bumper-to-bumper on many) | Upper-mid | Major **2026 relaunch**: RT-700 "The Bull" (~$1,199, all-304-SS firepot/deflector/drip pan), Flagship 1600 (~1,667 sq in), + NEW 2026: Bullseye Deluxe RT-380BD (to ~1,000°F sear), Smokestone RT-480SS pellet **griddle** ($749.99), Porch Pro RT-400PP (compact), RT-2500 BFG (competition, 2,535 sq in), Patio Legend 400, Road Warrior 340P, Deck Boss 800, E-Series Built-In 1300. Stainless-heavy; ~100k-cycle ceramic igniter. | 2026-05-25
- **Camp Chef** | Revelyst (fmr Vista Outdoor) | 1990 | Logan, UT | China (US design) | 3 yr | Upper-mid | Innovation leader: Slide & Grill direct flame, pull-out ash cleanout, Adjustable Smoke Control (1–10), 4 included probes. Woodwind 24 ($699) / Woodwind Pro 24 ($899, open-flame) / Woodwind Pro 36 ($1,199) / Apex (propane-assist). | 2026-05-25
- **Green Mountain Grills (GMG)** | Private | 2008 | Reno, NV | China (US design) | 3 yr | Mid | WiFi pioneer; dual-band stable WiFi, 2 probes, cloud firmware updates (rare). **Prime 2.0 platform**: Trek Prime 2.0 ($499 portable, 12V), Ledge Prime 2.0 ($899), Peak Prime 2.0 ($1,049), Peak Prime 2.0 Plus ($1,149+). Replaced old 2-piece "Open Flame" drip system with 1-piece adjustable pan + heat shield (slide back to sear). | 2026-05-25
- **Pit Boss** | Dansons Inc. | 1999 | Abbotsford, BC | China | 5 yr | Budget-mid | Walmart dominance; Flame Broiler open-flame standard; 5-yr warranty strong for price. PB700FB ($399), Austin XL 1000 ($499), Pro Series 850 ($599, PID+WiFi), Platinum/Lockhart combo (cabinet + grill). Now markets pellets as "100% All-Natural." | 2026-05-25
- **Louisiana Grills** | Dansons Inc. | 1999 | Abbotsford, BC | China | Varies | Budget-mid | Parallel Dansons brand; heavy component/firmware overlap with Pit Boss. | 2026-05-25
- **Weber** | Public (NYSE: WEBR) | 1952 | Palatine, IL | USA/China | up to 10 yr (Searwood) | Mid-premium | **Searwood replaced the troubled SmokeFire** (Gen 1 had grease-fire/jam issues). Searwood 600 (648 sq in) / Searwood XL 600 (972 sq in); DirectFlame mode, swappable griddle/rotisserie accessories; **won multiple "best pellet 2026" titles**. Smoque ($699) / Smoque XL ($999) more affordable entries. | 2026-05-25
- **Yoder Smokers** | Yoder Mfg. | 2009 | Hutchinson, KS | USA (Kansas) | 3 yr parts / longer structural | Premium USA | Competition gold standard; 10-ga steel; YS480S (~$1,699), YS640S (~$2,699, 335 lb), YS1500S (~$5,499). Best cold-weather/repairability/resale. | 2026-05-25
- **MAK Grills** | MAK Enterprises | 2006 | Dallas, OR | USA (Oregon) | 3 yr parts / lifetime structural (orig owner) | Premium USA | Hand-built, 304 SS, FlameZone direct fire; built-to-order (4–10 wk lead). 1/2 Star General (~$1,999–$3,499). | 2026-05-25
- **Grilla Grills** | Private | 2012 | Holland, MI | China (US design) | 4 yr | Mid | Direct-to-consumer; strong smoke + temp value. Silverbac Alpha ($849), Grilla Alpha (vertical, $949), Kong (kamado-pellet hybrid). | 2026-05-25
- **Z Grills** | Private | 2017 | China (US dist.) | China | 3 yr parts | Budget | OEM-style direct-to-consumer value. **NEW: 700 Dual-Wall insulated** (PID 3.0, ~28 hr hopper, 2 probes) closes cold-weather gap; 700E ($399), 1000E ($499). | 2026-05-25
- **Brisk It** | Private (startup) | ~2023 | USA | China | Varies | Budget-mid (tech-forward) | **NEW ENTRANT.** "First grill with generative AI" (Vera AI). Origin 580 (~$849), Origin 940 (~$1,099), Zelos-450 (~$296 sale / entry). Verdict: hardware punches above price; AI ("Vera") still half-baked — buy for hardware, ignore AI. App quality good for category. | 2026-05-25
- **Ninja (SharkNinja)** | Public (NYSE: SN) | n/a (grills ~2022) | Needham, MA | China | 1 yr typ. | Budget/compact | **NEW CATEGORY ENTRANT.** Woodfire line = electric heat + real-wood-pellet *flavor* (pellets are flavor only, not fuel). OG321 (~$290), XL Pro (~$399), OG701/OG901 combos. Compact; condo/townhome-friendly (no open flame). 6–7-in-1 (grill/smoke/bake/roast/air-fry/broil). Small smoke box (~½ cup pellets). | 2026-05-25
- **Oklahoma Joe's** | Char-Broil LLC | 1987 | Kansas City area | China | 3 yr | Budget | Offset heritage > pellet line; Rider pellet series competent but unremarkable. | 2026-05-25
- **Masterbuilt** | Masterbuilt Mfg. | 1973 | Columbus, GA | China | 1 yr | Budget | **Gravity Series** (charcoal + digital control) is the standout — charcoal flavor with pellet-like control (560/800/1050). Pellet line secondary. | 2026-05-25
- **Napoleon** | Wolf Steel Ltd. | 1976 | Barrie, ON | Canada/China | Lifetime burners / 15-yr housing | Premium (gas focus) | Best as gas-grill maker (Prestige 500 ~$999–1,199). Pellet entry newer/less proven. | 2026-05-25

### Adjacent / other-format brands (covered in quick-reference)
- **Blackstone** — dominant flat-top/griddle (36" Pro ~$399–599). | 2026-05-25
- **Kamado Joe** — ceramic kamado leader (Classic III ~$1,599–1,799; Big Joe III ~$2,499); better value than Big Green Egg. | 2026-05-25
- **Big Green Egg** — original ceramic kamado; premium, accessory-heavy. | 2026-05-25
- **PK Grills** — cast-aluminum charcoal, American-made, durable (PK360 ~$349–449). | 2026-05-25

### Ownership / OEM truths to retain
- Pit Boss + Louisiana Grills = same parent (Dansons) — shared firmware, fireboxes, augers.
- Z Grills is OEM-style; similar hardware appears under many private-label/Amazon brands.
- Traeger is publicly traded → cost pressure on mid-tier components.
- Camp Chef owned by Revelyst (fmr Vista Outdoor) but retains R&D independence.
- Recteq mfg in China, assembly/testing Augusta, GA.

---

## 5. DATA — PRODUCTS / MODELS

> Schema: brand | model | MSRP/street | cook sq in | hopper lb | temp range | controller | wifi | open flame | steel | warranty | made in | grades(build/temp/wifi/value/parts/overall) | notes | verified
> (This is the table that feeds the Excel "Comparison" sheet. Kept as a list here for diff-ability.)

- Traeger | Woodridge | $799 | 575 | 20 | 165–500°F | D2 PID | Yes | No | Mid steel | 3yr | China | B/A-/A+/B-/A/B+ | Base of new 40th-anniv line | 2026-05-25
- Traeger | Woodridge Pro | $999 | ~700–970 | 22 | 165–500°F | D2 PID | Yes | No | Mid steel | 3yr | China | B+/A-/A+/B/A/A- | Super Smoke Mode; pellet sensor; best-value Traeger | 2026-05-25
- Traeger | Woodridge Elite | $1,599 | ~970 | 22 | 165–500°F | D2 PID | Yes | No | Mid steel | 3yr | China | B+/A/A+/B/A/A- | Premium Woodridge | 2026-05-25
- Traeger | Ironwood XL | $1,799 | 924 | 22 | 165–500°F | D2 PID | Yes | No | Mid steel | 3yr | China | B+/A/A+/B/A/A- | Downdraft exhaust; large families | 2026-05-25
- Traeger | Timberline XL | $3,499+ | 1,320 | 24 | 165–500°F | D2 PID | Yes | No | 304 SS | 3yr | China | A/A+/A+/C+/A/A- | Induction burner; full stainless; very pricey | 2026-05-25
- Recteq | RT-700 "The Bull" | $1,199 | 702 | 40 | 200–700°F | Prop PID | Yes | No | 304 SS int | 6yr | China(assy GA) | A-/A+/A/A/B+/A+ | Flagship-favorite; all-SS where it matters | 2026-05-25
- Recteq | Flagship 1600 | $1,099–1,399 | 1,667 | 40 | 200–700°F | Prop PID | Yes | No | 304 SS int | 6yr | China(assy GA) | A-/A+/A/A/B+/A+ | Huge capacity; best overall value pick | 2026-05-25
- Recteq | Bullseye Deluxe RT-380BD | ~$749 | 380 | 15 | 200–~1,000°F | Prop PID | Yes | Yes | SS int | 6yr | China | B+/A+/A/A/B+/A | NEW 2026; kettle form; accepts 22.5" Weber accessories; real searing | 2026-05-25
- Recteq | Smokestone RT-480SS (pellet griddle) | $749.99 | n/a (griddle) | — | — | Prop PID | Yes | n/a | SS | 6yr | China | B+/A/A/B+/B+/A- | NEW 2026; wood-fired griddle — new form factor | 2026-05-25
- Recteq | Porch Pro RT-400PP | TBD | compact | — | — | Prop PID | Yes | No | SS int | 6yr | China | B+/A/A/B+/B+/A- | NEW 2026; balconies/small patios | 2026-05-25
- Recteq | RT-2500 BFG | premium | 2,535 | 53 | 180–700°F | Prop PID | Yes | No | SS heavy | 6yr | China | A/A+/A/B/A/A | Competition-scale, 3-rack | 2026-05-25
- Camp Chef | Woodwind 24 | $699 | 811 | 22 | 160–500°F | True PID | Yes | No | Mid steel | 3yr | China | B+/A/B+/A/A-/A- | Ash cleanout; entry | 2026-05-25
- Camp Chef | Woodwind Pro 24 | $899 | 811 | 22 | 160–650°F | True PID | Yes | Yes | Mid steel | 3yr | China | B+/A/B+/A+/A-/A | TOP VALUE PICK; Slide & Grill + PID + ash cleanout | 2026-05-25
- Camp Chef | Woodwind Pro 36 | $1,199 | 1,236 | 22 | 160–650°F | True PID | Yes | Yes | Mid steel | 3yr | China | A-/A/B+/A/A-/A | Large; all CC advantages | 2026-05-25
- Green Mountain | Trek Prime 2.0 | $499 | 219 | 9 | 150–450°F | PID | Yes | No | Mid steel | 3yr | China | B/B/A-/A/B+/B+ | Best tailgate pellet; 12V | 2026-05-25
- Green Mountain | Ledge Prime 2.0 | $899 | 432 | 18 | 150–550°F | PID | Yes | Slide-to-sear | Mid steel | 3yr | China | B/B+/A-/A-/B+/A- | Most popular GMG | 2026-05-25
- Green Mountain | Peak Prime 2.0 | $1,049 | 513 | 22 | 150–550°F | PID | Yes | Slide-to-sear | Mid steel | 3yr | China | B/B+/A-/B+/B+/B+ | Flagship GMG | 2026-05-25
- Pit Boss | PB700FB | $399 | 700 | 21 | 180–500°F | Digital | No | Yes | Thin steel | 5yr | China | C+/B-/NA/A/B/B | Budget value; Flame Broiler | 2026-05-25
- Pit Boss | Austin XL 1000 | $499 | 1,000 | 21 | 180–500°F | PID | No | Yes | Thin steel | 5yr | China | C+/B/NA/A/B/B+ | Large budget; Walmart staple | 2026-05-25
- Pit Boss | Pro Series 850 | $599 | 850 | 21 | 180–500°F | PID | Yes | Yes | Mid steel | 5yr | China | B-/B/B-/A-/B/B+ | Best Pit Boss for serious cooks | 2026-05-25
- Weber | Searwood 600 | $899 | 648 | 20 | 200–600°F | Prop PID | Yes | DirectFlame | Mid steel | 10yr | China | B+/B+/B+/A-/A/A- | Won best-pellet-2026; griddle/rotisserie accessories | 2026-05-25
- Weber | Searwood XL 600 | $1,299 | 972 | 22 | 200–600°F | Prop PID | Yes | DirectFlame | Mid steel | 10yr | China | A-/A-/B+/A-/A/A | Large; 10-yr warranty standout | 2026-05-25
- Weber | Smoque | $699 | 462 | 17 | 180–600°F | Rapid PID | Yes | No | Mid steel | 3yr | China | B+/B+/B+/B+/A/B+ | Affordable 2025 entry | 2026-05-25
- Yoder | YS640S | $2,699 | 640 | 20 | 150–600°F | ITC3 PID | Yes | Limited | 10ga US | 3/5yr | USA | A+/A+/B/B-/A+/A | Gold standard; generational | 2026-05-25
- Yoder | YS480S | $1,699 | 480 | 18 | 150–600°F | ITC3 PID | Yes | Limited | 10ga US | 3/5yr | USA | A+/A/B/B/A+/A- | Starter Yoder | 2026-05-25
- MAK | 2 Star General | ~$2,799 | 616 | 40 | 150–600°F | Prop PID | Yes | Yes | 304 SS | Lifetime struct. | USA | A+/A+/B+/C/A+/A | FlameZone; built to order | 2026-05-25
- Grilla | Silverbac Alpha | $849 | 692 | 20 | 180–500°F | True PID | Yes | No | Mid steel | 4yr | China | B/A-/B+/A-/B+/A- | Underrated; great smoke | 2026-05-25
- Z Grills | 700 Dual-Wall | ~$599 | ~700 | 20 | 180–450°F | PID 3.0 | Some | No | Dual-wall ins. | 3yr | China | B-/B/NA/A-/C+/B | NEW; insulated; cold-weather value | 2026-05-25
- Z Grills | 700E | $399 | 700 | 20 | 180–450°F | PID | No | No | Thin steel | 3yr | China | C+/B-/NA/A-/C+/B- | Best ultra-budget | 2026-05-25
- Brisk It | Zelos-450 | ~$296–450 | ~450 | 12 | 165–500°F | PID + AI | Yes | Limited | Mid steel | varies | China | B/B+/A-/A/C+/B+ | NEW; AI(Vera) gimmicky, hardware strong, good app | 2026-05-25
- Brisk It | Origin 580 | ~$849 | 580 | 20 | 165–500°F | PID + AI | Yes | No | Mid steel | varies | China | B/B+/A-/B+/C+/B+ | NEW; AI auto-cook; durability mid | 2026-05-25
- Ninja | Woodfire OG321 | ~$290 | small (~141 sq in) | n/a (flavor box) | up to ~700°F | Electric + dial | No(base) | Sear | Mid | 1yr | China | B/B+/NA/A/C/B | NEW CATEGORY; electric heat + wood *flavor*; condo-friendly; small | 2026-05-25
- Ninja | Woodfire XL Pro | ~$399 | larger | n/a | up to ~700°F | Electric + app(some) | Some | Sear | Mid | 1yr | China | B/B+/B-/A-/C/B+ | NEW; bigger Woodfire | 2026-05-25

---

## 6. DATA — FUEL (WOOD PELLETS)

> Schema: brand | purity grade | transparency | base/filler | oils | mfg | moisture | ash | $/lb | availability | best use | verified

- **Lumber Jack** | A+ | A+ | 100% species, round-log/green-chip, bark-on primary wood in blends (more flavor, lower ash than debarked 100%) | None | Medford, WI | 5–7% | <0.5% | ~$1.00–1.25 | Specialty/online | Authenticity, all-around | 2026-05-25
- **CookinPellets** | A+ | A+ | 100% hardwood, explicitly no oak/alder filler; Perfect Mix (hickory/cherry/maple/apple) | None | USA | 5–7% | <0.3% | ~$1.00 (40lb ~$38.99) | Amazon/BBQ stores | Long cooks, flavor purity | 2026-05-25
- **Jealous Devil** | A+ | A | 100% S. American hardwood (quebracho etc.), very dense | None | S. America | 5–6% | <0.5% | ~$1.10–1.30 | Amazon/specialty | Long brisket, max BTU | 2026-05-25
- **BBQr's Delight** | A | A+ | 100% species, small-batch; Jack Daniel's barrel oak | None | Harrison, AR | 5–7% | <0.5% | premium | Specialty | Variety/experimenting | 2026-05-25
- **Bear Mountain BBQ** | A | A | PNW hardwood, blends disclosed; Chef's Choice Signature ~$11.97/20lb | Minimal veg oil (disclosed) | Susanville, CA | 5–8% | <0.7% | ~$0.60–1.00 | Walmart/Home Depot/Lowe's | Value quality, all-purpose | 2026-05-25
- **B&B** | B+ | B+ | Hardwood blend; great value (40lb ~$19.99 at Academy, regional) | None | TX | 6–8% | <1.0% | ~$0.50–0.95 | Academy/specialty | Budget quality, Texas-style | 2026-05-25
- **Kingsford BBQ** | B | B | Oak base blends (disclosed-ish) | None | USA | 6–9% | <1.0% | ~$0.75–0.90 | Big-box | Consistent casual | 2026-05-25
- **Kona** | B | B | Variety packs optimized for Ninja Woodfire / countertop grills | None | USA | n/a | low | varies | Amazon | Ninja/compact grills (NEW relevance) | 2026-05-25
- **Smokin' Brothers** | B+ | B | Small brand, praised flavor in forums | None disclosed | USA | n/a | n/a | varies | Specialty | Flavor-seekers (emerging) | 2026-05-25
- **Weber Pellets** | B | B | Oak/hickory blend; some report ashy | None | USA | 6–8% | <1.0% | ~$0.80–0.95 | Home Depot/Weber | Weber owners | 2026-05-25
- **Traeger Pellets** | B- | B- | Alder/oak base + flavor wood (disclosed in support docs, NOT on bag); soy oil in specialty blends | Soy oil (specialty) | USA (multi-mill) | 6–9% | <1.0% | ~$0.80–1.00 | Everywhere | Convenience/fallback | 2026-05-25
- **Pit Boss Pellets** | C+ | C | Oak blend; now marketed "100% All-Natural" (~$8.97/20lb, 44.9¢/lb mesquite) | Minimal/possible | China/USA | 7–9% | 1.0–1.5% | ~$0.45–0.80 | Walmart | Budget casual | 2026-05-25
- **Royal Oak (charcoal pellets)** | special | C- | 100% charcoal pellets — different category (high-heat/searing/humid) | n/a | USA | n/a | n/a | varies | Big-box | High-heat sear, not classic smoke | 2026-05-25
- **Cowboy Brand** | D | D | High filler, dust, moisture issues — auger jams | Unknown | Unknown | 9–12% | 2%+ | cheap | Hardware | AVOID for pellet grills | 2026-05-25

### Pellet truths to retain
- No federal standard governs BBQ-pellet composition disclosure — "Hickory" can be mostly oak/alder base.
- NEVER use heating pellets (softwood/bark/binders) in a food grill — toxic smoke.
- Most experienced cooks agree flavor differences between *quality* brands are subtle; composition mainly affects ash/cleanup + efficiency.
- Ninja Woodfire uses pellets for flavor only (electric heat) → wants high-smoke, clean-burn, low-ash pellets, not high-BTU fuel pellets.

---

## 7. DATA — ACCESSORIES (worth-it list)

- **Instant-read thermometer** (most important accessory): ThermoWorks Thermapen One (~$99), Lavatools Javelin Pro Duo (~$45–60 value pick).
- **Leave-in wireless probes**: ThermoWorks Smoke X (~$189), MEATER (~$69–269), Inkbird IBT-4XS (~$35–45 budget).
- **Thermal blanket** (cold-weather, −20–40% pellet use): brand-specific, ~$32–99.
- **Grill cover** (brand-specific, not optional): ~$40–120.
- **Cast iron / GrillGrate sear panels** (~$40–80) for sear upgrade.
- **Pizza stone / attachment** (GMG, Camp Chef) for wood-fired pizza.
- **Skip**: grill mats, smoker tubes (fix pellet quality instead), grill lights (use headlamp), branded cleaning kits.

---

## 8. KEY TRENDS (for narrative sections; refresh each update)

1. **AI grills arrive but underdeliver** — Brisk It's Vera AI is the headline; consensus = buy for hardware, ignore AI for now. Watch this space.
2. **Electric-hybrid + flavor-box category** — Ninja Woodfire created a real new segment (electric heat + wood flavor) for condos/townhomes/small spaces.
3. **Pellet griddles / multi-function** — Recteq Smokestone signals wood-fired griddle as emerging form factor; multi-function cookers expanding.
4. **Cold-weather engineering goes downmarket** — Z Grills Dual-Wall brings insulation to budget tier; narrows premium gap.
5. **Searing arms race** — direct-flame access and ~1,000°F capability spreading (Recteq Bullseye Deluxe, Camp Chef Slide & Grill, Weber DirectFlame).
6. **Warranty as differentiator** — Weber 10-yr (Searwood), Recteq 6-yr, MAK lifetime structural; warranty length increasingly a buying lever.
7. **Pellet transparency pressure** — "100% hardwood/species" marketing rising as consumers learn about filler/oak-base practices.

---

## 9. CHANGELOG  *(append-only; newest first)*

### 2026-05-25 — Full rebuild on deep research pass (Opus 4.7)
- **Added new manufacturers:** Brisk It (AI grills), Ninja (Woodfire electric-hybrid category).
- **Traeger:** added 40th-anniversary Woodridge line (Woodridge/Pro/Elite); noted Pro-series replacement; Super Smoke Mode.
- **Recteq:** full 2026 relaunch — RT-700 "The Bull," Flagship 1600, NEW Bullseye Deluxe RT-380BD (~1,000°F), Smokestone pellet griddle (new form factor), Porch Pro, RT-2500 BFG; clarified China-mfg/Augusta-GA-assembly.
- **Weber:** clarified Searwood replaced SmokeFire; Searwood won "best pellet 2026"; added Smoque line.
- **Z Grills:** added 700 Dual-Wall (insulated, PID 3.0).
- **GMG:** updated to Prime 2.0 platform; noted 1-piece pan + slide-to-sear replacing old 2-piece Open Flame.
- **Pellets:** added Kona (Ninja-optimized) + Smokin' Brothers; noted Pit Boss "100% All-Natural" rebranding; current pricing refreshed; Lumber Jack round-log/bark-on detail added.
- **Competitive:** confirmed "The Grill Buyer's Black Book" (Matt Garrison, Lovable) — name collision; this project must rename + differentiate.
- **Trends section rewritten** around AI, electric-hybrid, pellet griddles, cold-weather budget engineering, searing, warranty, transparency.
- **Framing:** removed all personal/GMG-owner framing — guide is now neutral and broad-audience.

### (Prior) 2025 first edition
- Initial build; spot-checked research; personal framing present; later flagged as stale + too narrow.
