# Born to Ruck — AI Context

## Project

Open-source science book on rucking (weighted walking). Quarto book project, MIT licensed.

- **Primary language:** English
- **Working version:** v0.3 Draft (February 2026)
- **Author:** Magnús Smári Smárason
- **Repo:** github.com/Magnussmari/born-to-ruck

## Working Rules

- **English version is primary.** All edits go to `chapters/` and `index.qmd` first.
- **Icelandic version (`is/`)** is a translation — do not edit unless specifically asked.
- **Log every change** in `dev/CHANGELOG.md` before committing. Every entry needs: date, what changed, why, which files.
- **Evidence standard:** Every factual claim must trace to a DOI in `references.bib`. Use Scite MCP to verify citations and find supporting/contrasting evidence.
- **Never hallucinate citations.** If Scite can't find it and the DOI doesn't resolve, it doesn't go in the book.
- **Render before committing** when chapter content changes: `quarto render .` from book root.
- **Commit style:** Conventional commits — `feat:`, `fix:`, `docs:`, `refactor:`.

## AI-Human Collaboration Model

This book is a reference implementation of AI-augmented science writing. Key principles:

1. **AI assists, human decides.** AI does literature retrieval, synthesis drafts, logical auditing. Human makes all editorial and evidence-quality judgments.
2. **Transparency over polish.** Document how AI was used, not just that it was used. Prompts, models, versions, verification steps.
3. **Evidence chains are auditable.** Every reference is verifiable via DOI. Scite.ai smart citations provide citing context. Chapter 13 discloses every evidence gap.
4. **Reproducibility matters.** The AI workflow should be documented well enough that another researcher could follow the same process.

## Tools Available

| Tool | Purpose |
|------|---------|
| **Scite MCP** | Citation verification, smart citations, evidence chain building, retraction checks |
| **Quarto** | Book rendering (HTML, PDF, EPUB) |
| **references.bib** | BibTeX bibliography — all 65 references |

## Key Files

| File | Purpose |
|------|---------|
| `index.qmd` | Prologue |
| `chapters/00-14, epilogue, appendices` | Book content |
| `_quarto.yml` | Quarto config |
| `references.bib` | Bibliography |
| `dev/CHANGELOG.md` | Change log (gitignored) |
| `dev/STATUS.md` | Project status (gitignored) |
| `MARKETING_PLAN.md` | Launch plan (gitignored) |

## Scite MCP Usage

When verifying or strengthening claims:
1. Search by DOI (preferred) or title to get paper metadata and smart citations
2. Use `term` + `dois` to extract full-text passages from specific papers
3. Check `editorialNotices` for retractions on every reference
4. Use contrasting citations to find counter-evidence — address it honestly in the text
5. Smart citation snippets are real full-text extracts — quote them as evidence

## Don't

- Don't edit `is/` chapters without being asked
- Don't add references not verifiable via DOI
- Don't skip the changelog
- Don't commit without rendering if content changed
- Don't "improve" prose the author didn't ask to change
