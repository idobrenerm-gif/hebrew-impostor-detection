# Progress Log

Newest entries on top. Format: `## YYYY-MM-DD — Name — short title`, followed by bullets of what was done and what's next.

---

## 2026-11-11 — Ido — Pivot to prompt-language detection
- Presented the v1 proposal (Hebrew impostor detection). Lecturer feedback: intent to impersonate cannot be inferred from text; suggested detecting whether Hebrew LLM output came from a Hebrew prompt or a prompt in another language.
- Agreed with Oren to pivot (D-012). Decided task structure, prompt languages and no human class (D-013 to D-015).
- Archived all v1 material in `archive/v1-impostor-detection/` (D-016). Rewrote `docs/PROJECT.md`, `docs/OPEN_QUESTIONS.md`, `README.md` and `CLAUDE.md` for the new direction. Renamed the repo to `hebrew-prompt-language-detection`.
- Next: resolve the open data-generation questions (prompt translation, content control, generators), consider a small pilot, then build the new proposal deck.

## 2026-11-06 — Ido — Proposal deck PPTX and PDF
- Added `slides/proposal.pptx` and `slides/proposal.pdf` (7 slides each), exported from the Claude Slides artifact, per the course repo requirement (slides in PPT and PDF format).

## 2026-11-06 — Ido — Proposal deck saved to repo
- Exported the final proposal deck (7 slides: title, 5 content slides, closing slide) to `slides/proposal.html` as a standalone HTML file. Speaker notes are kept in hidden `<aside>` elements.
- Fixed an unreadable "held out" row in the cross-generator matrix (slide 6) before export.
- Oren's full name (Oren Yehezkel) is now on the title and closing slides.

## 2026-11-06 — Ido — Proposal slides
- Built the proposal deck (title + 5 slides: Motivating Use Case, Task Description, Models & Methods, Data, Metrics & KPIs) as a Claude Slides artifact: https://claude.ai/artifact/SSH5fz5UPxVFSo4gLNzQ6X (private to Ido until shared).
- Content taken only from `docs/`; open questions marked TBD on the slides (D-011). Speaker notes include a suggested speaker split (not agreed).
- Slide 1 "how it's handled today" is general background, not yet backed by sources.
- Checked course material (`1023_ProjectRequirements`): proposal is due in week 5; interim (week 9) needs 3+ related papers, dataset EDA and a baseline.
- Next: Oren reviews the deck; agree on the speaker split; resolve open questions before the interim.

## 2026-11-06 — Ido — Documentation setup
- Set up the documentation structure: `CLAUDE.md`, `docs/PROJECT.md`, `docs/DECISIONS.md`, `docs/PROGRESS.md`, `docs/OPEN_QUESTIONS.md`.
- Recorded the project idea and the decisions made so far (D-001 to D-009).
- Next: proposal slides (5 slides).
