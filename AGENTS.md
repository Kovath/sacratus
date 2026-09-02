# Repository workflow

## Authority

- `main` is authoritative for Sacratus lore and repository instructions.
- Lore on `main` outside `working/` is canon, including lore in subdirectories. `working/` is explicitly non-canonical scratch space.
- `working/` may change freely; promoting material from it into canon requires explicit user review.
- `README.md` is human-facing navigation only; it does not establish canon or policy.
- Chat, model memory, brainstorming, README summaries, and unmerged PRs are not authoritative when they conflict with merged canon.
- Before asserting established lore, read the relevant canonical files.

## Canon statuses

- **LOCKED** — established; revise only with explicit user direction.
- **PROVISIONAL** — current answer, still subject to revision.
- **OPEN** — undecided; do not resolve silently.
- **UNKNOWN IN-UNIVERSE** — deliberately unresolved; do not invent an answer.
- **REJECTED** — discarded; do not reintroduce unless explicitly reconsidered.

A status may apply to any scope; the status itself is canonical.

## Document roles

Use `README.md` to navigate, then read the most specific relevant canon. Detailed subjects should have one primary canonical home; summaries elsewhere should stay concise.

When reorganizing canon, preserve meaning/status, avoid competing detailed copies, and update navigation/links as needed. Do not create files without a clear purpose.

## Consistency and lore review

Do not silently reconcile genuine canonical conflicts. First check status labels, era, perspective, and summary-vs-detail differences; otherwise surface the conflict unless established canon or the user resolves it.

When developing lore, check:

- internal, character, and institutional continuity;
- Warhammer 40,000 compatibility in chronology, scale, institutions, technology, Warp behavior, and any faction norms;
- tone/theme and unnecessary exceptionalism;
- preservation of `OPEN`, `PROVISIONAL`, and `UNKNOWN IN-UNIVERSE` uncertainty;
- knock-on effects elsewhere in canon.

Distinguish hard conflicts, soft tensions, open choices, and deliberate revisions. Do not manufacture objections when an idea fits. Verify external 40k lore when materially uncertain or edition-sensitive.

## AI GitHub workflow

AI actions performed through the user's GitHub account must remain distinguishable from human actions.

- AI-authored outward-facing GitHub prose must clearly identify itself as AI-generated.
- AI-generated commits must include `AI-Generated-By: ChatGPT`.
- PR descriptions should summarize meaningful canon additions, removals, reorganizations, and status changes.
