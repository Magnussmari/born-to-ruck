# Born to Ruck

**The Science of Weighted Walking and the Exercise Your Body Was Built For**

*Magnus Smári Smarason — Akureyri, Iceland*

**v2.1 — March 2026 — Evidence Integration Edition**

---

A narrative nonfiction book synthesising the peer-reviewed evidence for rucking (loaded walking) as the single most complete human exercise. Fourteen chapters spanning evolutionary biomechanics, bone physiology, hormonal response, respiratory science, and practical programming — plus a whole-book GRADE evidence audit, counter-evidence integration, and a transparency appendix documenting the adversarial bias review that reshaped every chapter.

## Read the book

- **Web:** [magnussmari.github.io/born-to-ruck](https://magnussmari.github.io/born-to-ruck)
- **PDF & EPUB:** See [Releases](https://github.com/Magnussmari/born-to-ruck/releases)

## What changed in v2.0

An adversarial "honest oracle" review found confirmation bias in all 12 original research prompts. The book was revised to integrate counter-evidence honestly:

- **79 references** (up from 51), all DOIs machine-verified via scite.ai
- **9 wrong DOIs corrected** (14% of original bibliography)
- **GRADE evidence tables** in every evidence-heavy chapter
- **Counter-evidence presented first** — chondroprotective running data, Beavers 2025 negative RCT, EHMC scope correction, military injury epidemiology, nasal breathing limitations
- **New Appendix C: "The Honest Oracle"** — full bias audit trail and self-correction methodology
- **New Appendix D: "The Parallel Research Sprint"** — how 11 parallel AI agents produced ~5,000 lines of counter-evidence in 25 minutes

See [CHANGELOG](updates/CHANGELOG.md) for complete details.

## Build from source

This book is built with [Quarto](https://quarto.org).

```bash
# Install Quarto (https://quarto.org/docs/get-started/)

# Render all formats
quarto render

# Render HTML only
quarto render --to html

# Render PDF (requires TeX Live / XeTeX)
quarto render --to pdf

# Render EPUB
quarto render --to epub
```

## Structure

```
├── index.qmd                           # Prologue
├── chapters/
│   ├── 00-foreword.qmd                 # Author's Foreword (ICMJE AI disclosure)
│   ├── 01-the-running-lie.qmd          # Part I: The Wrong Road
│   ├── 02-the-cardio-industrial-complex.qmd
│   ├── 03-what-the-military-knows.qmd
│   ├── 04-the-osteogenic-window.qmd
│   ├── 05-born-to-carry.qmd            # Part II: The Porter Primate
│   ├── 06-the-testosterone-question.qmd
│   ├── 07-her-bones-her-rules.qmd
│   ├── 08-breathe-through-your-nose.qmd
│   ├── 09-the-pack-on-your-back.qmd    # Part III: The Five Movements
│   ├── 10-the-four-companions.qmd
│   ├── 11-feed-the-machine.qmd
│   ├── 12-decades.qmd                  # Part IV: The Long Road
│   ├── 13-what-we-dont-know.qmd        # GRADE Scorecard
│   ├── 14-put-on-the-pack.qmd
│   ├── epilogue.qmd
│   ├── appendix-protocol.qmd           # Appendix A: The Akureyri Protocol
│   ├── appendix-prompting.qmd          # Appendix B: Prompting Your Protocol
│   ├── appendix-honest-oracle.qmd      # Appendix C: The Honest Oracle
│   └── appendix-research-sprint.qmd    # Appendix D: The Parallel Research Sprint
├── references.bib                       # 79 references, all DOIs verified
├── updates/CHANGELOG.md                 # Version history
├── _quarto.yml                          # Book configuration
└── LICENSE                              # MIT License
```

## Made with

- [scite.ai](https://scite.ai) — citation verification, DOI audit, smart citations
- [Claude Code](https://claude.ai) with [PAI](https://github.com/danielmiessler/PAI) — manuscript generation, evidence integration, adversarial bias audit
- Google Gemini 3.0 Flash – 3.1 Pro — research and cross-verification
- [Perplexity](https://perplexity.ai) — additional research
- [Quarto](https://quarto.org) — book rendering (HTML, PDF, EPUB)

## License

[MIT License](LICENSE) — this knowledge should be free.

## Disclaimer

**This manuscript is not peer-reviewed.** It is bias-audited, bias-corrected, and bias-documented. Every claim is referenced. Every evidence gap is disclosed. Every evidence-heavy chapter includes a GRADE confidence table. See Chapter 13 for the whole-book GRADE scorecard and the research agenda. See Appendix C for the full bias audit trail.
