# Instructions for Claude (shared by both team members)

This project is worked on by two people, **Ido** and **Oren**, each with their own Claude.
Chat history is NOT shared and NOT a source of truth. **This repository is the single source of truth.**

## At the start of every session
1. `git pull` (or re-clone) to get the latest state.
2. Read, in order: `docs/PROJECT.md`, `docs/DECISIONS.md`, `docs/PROGRESS.md`, `docs/OPEN_QUESTIONS.md`.
3. Treat anything not written in these files as unknown. Do not rely on memory of past chats.

## During and at the end of every session
Every decision and every piece of progress must be recorded in the repo before the session ends:
- **New or changed decision** → append an entry to `docs/DECISIONS.md` (never delete old entries; mark them `Superseded by D-XXX`).
- **Work done** (code, data, research, slides, experiments) → add a dated entry at the top of `docs/PROGRESS.md`.
- **Open question / something waiting on the other person** → add to `docs/OPEN_QUESTIONS.md`; move it to `Resolved` with a pointer to the decision when answered.
- **Change to scope, task definition or methods** → update `docs/PROJECT.md` as well.
- Every entry says **who** (Ido / Oren) and the **date** (YYYY-MM-DD).

If a decision was discussed but not agreed by both, log it as an open question, not a decision.

## Git workflow
- Documentation updates (`docs/`, `CLAUDE.md`, `README.md`): commit directly to `main`.
- Code and experiments: work on a branch named `<name>/<topic>` (e.g. `oren/baseline-tfidf`) and open a PR; document it in `PROGRESS.md` anyway.
- Always `git pull --rebase` before pushing. On conflicts in docs files, keep both sides' entries.
- Commit messages in English, prefixed with the author: `[Ido] ...` / `[Oren] ...`.

## Language
- Everything in the repo (code, comments, docs, commit messages): **English only**.
- Chat with the user: Hebrew is fine.

## Repo layout
- `docs/` — project documentation (see above).
- `slides/` — presentation exports. Proposal deck (week 5): `slides/proposal.pptx`, `slides/proposal.pdf` (exported from the Claude Slides artifact) and `slides/proposal.html` (standalone HTML export).
- Code, data and experiment folders will be added as the project grows; record the layout here when they are.
