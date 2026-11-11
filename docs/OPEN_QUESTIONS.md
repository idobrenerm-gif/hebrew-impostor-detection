# Open Questions

Questions not yet decided, or waiting on one of us. When resolved, move to **Resolved** with a pointer to the decision (D-XXX).

Format: `- [YYYY-MM-DD, raised by Name] Question — context / owner`

## Open
- [2026-11-11, Ido] How are prompts translated into the other 7 languages (machine translation, an LLM, native speakers)? Translation quality and style may itself become a signal.
- [2026-11-11, Ido] How do we keep content identical across prompt languages (same prompt template translated, no language-specific names or context) to avoid content shortcuts?
- [2026-11-11, Ido] How do we handle outputs that contain words or script from the prompt language: filter them, or keep and report separately?
- [2026-11-11, Ido] Which generator LLMs do we use, and which are held out for the cross-generator test?
- [2026-11-11, Ido] Which text genres do we generate (social-media posts, news-style, opinion, etc.), and how long should texts be?
- [2026-11-11, Ido] Dataset size per (generator, prompt language) cell.
- [2026-11-11, Ido] Additional research questions: cross-language generalization (train on some non-Hebrew prompt languages, test on unseen ones)? Is detection easier for languages far from Hebrew (Chinese) than close ones (Arabic)?
- [2026-11-11, Ido] Run a small pilot (2 generators, Hebrew vs. 2 languages, ~200 texts per cell, TF-IDF baseline) before committing to the full pipeline?
- [2026-11-06, Ido] Which small LLM for LoRA, and which LLM(s) for zero-shot / few-shot?
- [2026-11-06, Ido] Which measures do we use for synthetic data quality at each stage?
- [2026-11-11, Ido] Sources for related work (prompt-language effects on LLM output, translationese detection, AI-text attribution); the interim needs 3+ papers.
- [2026-11-11, Ido] Speaker split for the new proposal presentation.

## Resolved
- [2026-11-06, Ido] Is there an existing dataset of authentic Hebrew social-media posts, or do we collect manually? — Dropped: no human-written class in the new direction (D-012, D-015).
- [2026-11-06, Ido] Which generator LLMs for the impostor class, and which held out? — Replaced by the generator question above for the new direction (D-012).
- [2026-11-06, Ido] Include the machine-translated Hebrew extension in the first version? — Dropped with the v1 direction (D-012).
- [2026-11-06, Ido] How is an "account" defined for account-level classification? — Dropped: the new task is text-level only (D-012, D-013).
- [2026-11-06, Ido] Sources for current solutions (slide 1 of the v1 proposal). — Replaced by the related-work question above (D-012).
- [2026-11-06, Ido] Speaker split for the v1 proposal presentation. — Done; the v1 proposal was presented (D-012).
