# Born to Ruck

**The Science of Weighted Walking and the Exercise Your Body Was Built For**

*Magnus Smári Smarason — 23 February 2026 — Akureyri, Iceland*

---

A narrative nonfiction book synthesising the peer-reviewed evidence for rucking (loaded walking) as the single most complete human exercise. Fourteen chapters spanning evolutionary biomechanics, bone physiology, hormonal response, respiratory science, and practical programming.

## Read the book

- **Web:** [magnussmari.github.io/born-to-ruck](https://magnussmari.github.io/born-to-ruck)
- **PDF & EPUB:** See [Releases](https://github.com/Magnussmari/born-to-ruck/releases)

## Build from source

This book is built with [Quarto](https://quarto.org).

```bash
# Install Quarto (https://quarto.org/docs/get-started/)

# Render HTML
quarto render --to html

# Render PDF (requires TeX Live / XeTeX)
quarto render --to pdf

# Render EPUB
quarto render --to epub

# Render all formats
quarto render
```

## Structure

```
├── index.qmd                    # Prologue
├── chapters/
│   ├── 00-foreword.qmd          # Author's Foreword
│   ├── 01-the-running-lie.qmd   # Part I: The Wrong Road
│   ├── 02-the-cardio-industrial-complex.qmd
│   ├── 03-what-the-military-knows.qmd
│   ├── 04-the-osteogenic-window.qmd
│   ├── 05-born-to-carry.qmd     # Part II: The Porter Primate
│   ├── 06-the-testosterone-question.qmd
│   ├── 07-her-bones-her-rules.qmd
│   ├── 08-breathe-through-your-nose.qmd
│   ├── 09-the-pack-on-your-back.qmd  # Part III: The Five Movements
│   ├── 10-the-four-companions.qmd
│   ├── 11-feed-the-machine.qmd
│   ├── 12-decades.qmd           # Part IV: The Long Road
│   ├── 13-what-we-dont-know.qmd
│   ├── 14-put-on-the-pack.qmd
│   ├── epilogue.qmd
│   └── appendix-protocol.qmd
├── references.bib               # 51 primary references
├── _quarto.yml                  # Book configuration
└── LICENSE                      # MIT License
```

## Made with

- [scite.ai](https://scite.ai) — citation-verified literature access
- [Claude Code](https://claude.ai) with [PAI](https://github.com/danielmiessler/PAI) — manuscript generation
- Google Gemini 3.0 Flash – 3.1 Pro Preview — research and cross-verification
- [Perplexity](https://perplexity.ai) — additional research
- A custom AI research harness coordinating queries across multiple models

## License

[MIT License](LICENSE) — this knowledge should be free.

## Disclaimer

**This manuscript is not peer-reviewed.** It is an open-source experiment using AI tools applied to peer-reviewed research. Every claim is referenced. Every evidence gap is disclosed. See Chapter 13 for the research agenda.
