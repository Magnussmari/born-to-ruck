# Changelog

All notable changes to *Born to Ruck* are documented here.

## [v2.0] — 2026-03-03

### The Honest Oracle Revision

An adversarial bias audit found confirmation bias in all 12 original research prompts. Eleven parallel AI research agents produced ~5,000 lines of counter-evidence in 25 minutes. Every chapter was revised to integrate the findings honestly. The book's thesis is preserved; its epistemic stance is transformed from advocacy to genuine scientific inquiry.

### Evidence Fortress
- **References:** 65 → 79 (14 new counter-evidence references added)
- **DOI audit:** All 79 DOIs machine-verified via scite.ai; **9 wrong DOIs corrected** (14% of original bibliography pointed to completely wrong papers)
- **Zero retractions** found across the entire bibliography
- **`link-citations: true`** — every reference in HTML links to its DOI

### Chapter Revisions (All 14 Chapters + Prologue)

**CRITICAL revisions:**
- **Ch 1 (The Running Lie):** New counter-evidence section presenting chondroprotective meta-analyses (Alentorn-Geli 2017, N=125,810: recreational runners 3.5% OA vs 10.2% sedentary). EHMC scoped to >81 km/week. Epigraph reframed. GRADE evidence table.
- **Ch 6 (The Testosterone Question):** Zero rucking hormone data acknowledged. EHMC scoped to elite athletes. Gaviglio load difference made explicit (200–300 kg vs 16 kg). New section on recreational running and testosterone. GRADE evidence table.

**HIGH priority revisions:**
- **Ch 3 (What the Military Knows):** Military injury cost section (Orr 2014/2016: 34% injury rate). Ecological fallacy callout box.
- **Ch 4 (The Osteogenic Window):** Beavers 2025 negative finding (JAMA RCT, N=150: weighted vest did NOT prevent bone loss). "80% injury" softened to 37–56%.
- **Ch 7 (Her Bones, Her Rules):** Gai 2025 (<5% BW recommended for older adults vs book's 15–30%).
- **Ch 8 (Breathe Through Your Nose):** "Most evidence-free element" disclosure. Ventilatory ceiling (Mapelli 2025: VO₂ reduced 8–22%). Eight contraindications. "Non-negotiable" → "foundational rule."
- **Ch 13 (What We Don't Know):** +2,500 words. "What the Running Evidence Actually Shows," "The Beavers Negative," "The GRADE Scorecard" (10-row whole-book evidence summary).

**MEDIUM/LOW revisions:**
- **Prologue:** "dramatically inferior" → "dramatically undervalued"; qualified testosterone claim
- **Ch 2:** Rucking's own commercial ecosystem acknowledged; running mortality data cited
- **Ch 5:** Evolutionary narrative unfalsifiability caveat
- **Ch 10:** Resistance training mortality data (Saeidifard 2019)
- **Ch 12:** "The Longevity Evidence We Do Not Have" — running has mortality data, rucking has none
- **Ch 14:** Opening summary rewritten with qualified evidence language; nasal breathing fallback added

### GRADE Evidence Tables
- Added to every evidence-heavy chapter (Ch 1, 3, 4, 6, 7, 8, 13)
- Whole-book GRADE scorecard in Ch 13 (10 rows, most claims Very Low)

### Transparency Layer (NEW)
- **Appendix C: "The Honest Oracle"** (~4,200 words) — bias discovery, before/after prompt examples, 11-agent sprint documentation, chapter-by-chapter revision trail, 5-step honest oracle protocol
- **Foreword:** ICMJE-compliant AI tools disclosure; self-correction paragraph ("bias-audited, bias-corrected, bias-documented")

---

## [v1.2] — 2026-02-23

### Evidence Quality Polish
- **Ch. 6 (Testosterone):** Added qualifier on Gaviglio et al. farmer's walk data — acute testosterone response is load-dependent; extrapolating strongman data to recreational rucking loads overstates likely effect
- **Ch. 8 (Nasal Breathing):** Qualified nasal breathing + core stability synergy as strong mechanistic inference, not established EMG-validated fact
- **References:** Fixed citation attribution — Calamai et al. (2024), not Eser et al., for VE/VCO₂ cardiac study

### Stylistic Polish
- **All chapters:** Eliminated repetitive AI crutch phrases ("Read that again," "This is not a metaphor," "Let that settle") — kept first occurrence, rewrote or removed subsequent instances
- **Ch. 8:** Added beginner nasal breathing ramp — CO₂ tolerance is trainable, practical progression from rest → unloaded walks → light load before enforcing the gate

### Balance & Tone Polish
- **Ch. 1:** Added acknowledgment that running/HIIT work for people who tolerate them — rucking is the better baseline, not the only answer
- **Ch. 2:** Tempered "Cardio Industrial Complex" rhetoric — problem is structural incentives, not conspiracy; industry has produced genuine good
- **Ch. 9:** Added Red Flags cross-reference callout at chapter opening — safety boundaries before progression protocols
- **Ch. 11:** Added framing for nutritional precision — "learn the numbers, internalise the pattern, then eat like a human being"
- **Ch. 14:** Added balance philosophy closing — not a guru book, no certification, no app, just a practice
- **Foreword:** Added Garmin/wearable balance note — two-year watch detox after Strava, now uses 30-day summaries, body comes first

## [v1.1] — 2026-02-23

### Added
- **Ch. 11 (Feed the Machine):** New section "How to Eat This Much Without Panic" — practical caloric density strategies for readers transitioning from chronic under-eating, addresses fat-gain anxiety with metabolic adaptation science
- **Ch. 9 (The Pack on Your Back):** New section on footwear and foot mechanics — wide toe box, zero/low-drop soles, metatarsal splay under load, ankle support thresholds
- **New Appendix:** "Prompting Your Protocol" — template AI prompts for personalised load progression and nutrition targets using the Akureyri Protocol

### Changed
- **Ch. 1 (The Running Lie):** Softened anti-running rhetoric — running reframed as emergency/specialised gear rather than evolutionary mistake; acknowledges Endurance Running Hypothesis (Bramble & Lieberman) upfront
- **Ch. 8 (Breathe Through Your Nose):** Clarified Bohr effect vs. mechanical governor — at Zone 2 intensities O₂ delivery is rarely limiting; nasal breathing's true value is preventing threshold crossover

### Fixed
- Updated Gemini model reference from "3.1 Pro Preview" to "3.1 Pro"
- Corrected foreword: father's shoulder story (Magnus started, father finished; master stonemason details)
- Added .env and .py to .gitignore

## [v1.0] — 2026-02-23

### Initial Release
- 14 chapters, prologue, author's foreword, epilogue, appendix protocol
- 84,000+ words
- 51 primary references
- MIT Licensed
- Published to GitHub with PDF, EPUB, and web versions
