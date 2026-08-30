# Repository workflow

## Source of truth

- The `main` branch is the authoritative source for Sacratus canon.
- Human-facing canon lives in top-level lore Markdown files rather than under a `canon/` directory.
- `README.md`, `AGENTS.md`, and repository configuration are metadata, not lore canon.
- The `working/` directory is non-canonical scratch space for AI-managed notes, unresolved questions, summaries, alternatives, and other material derived from ongoing chats.
- Chat context, model memory, and prior brainstorming are useful context but are not authoritative when they conflict with `main`.
- Before making claims about established lore, read the relevant top-level canon files when available.
- New brainstorming does not become canon until it is accepted by the user and merged into `main`.

## Canon status vocabulary

Use these statuses consistently when a fact or section is not simply ordinary established canon:

- **LOCKED** — Established setting fact. Do not revise without explicit user direction.
- **PROVISIONAL** — Current working decision that may still move. It may be questioned or revised, but its provisional status should be preserved until changed.
- **OPEN** — Question not yet decided. Do not silently resolve it.
- **UNKNOWN IN-UNIVERSE** — Deliberately unresolved within the setting. Do not invent a definitive answer unless the user explicitly changes this status.
- **REJECTED** — Previously considered idea that should not be reintroduced as canon unless explicitly reconsidered. Rejected ideas generally belong under `working/` rather than in human-facing canon files.

Statuses may apply to an individual fact, section, date, interpretation, or whole topic; they do not require one file per status.

## Canon changes

For AI-generated changes to canon or repository metadata:

- Do not push directly to `main`.
- Open a pull request for all changes.
- Add this commit trailer to AI-generated commits:

  `AI-Generated-By: ChatGPT`

- Identify AI-authored pull requests clearly in the PR description.
- Summarize meaningful canon additions, removals, and status changes in the pull request description.
- Do not treat an unmerged pull request as accepted canon.

## Working material

- Material under `working/` is explicitly non-canonical and may be revised, reorganized, summarized, or discarded by AI as the discussion evolves.
- The intended workflow is for AI to maintain `working/` without requiring human approval for each scratch-space update, while promotion from `working/` into top-level canon always requires a reviewed pull request to `main`.
- Do not promote working material into canon merely because it has persisted for a long time or appears internally consistent.
- When working notes conflict with merged canon, merged canon wins.
