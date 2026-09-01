# Repository workflow

## Authority

- `main` is authoritative for Sacratus lore and repository instructions.
- Lore on `main` outside `working/` is canon, including lore in subdirectories.
- `AGENTS.md` and repository configuration are authoritative operational instructions, not lore.
- `README.md` is human-facing navigation only; it does not establish canon or policy.
- `working/` is explicitly non-canonical scratch space.
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

For Palatinae material:

- `overview.md` — what the Chapter is.
- `history.md` — how and why it became that.
- `timeline.md` — when events happened.
- `constantines.md` — holders of the Constantinian office, their careers, motives, and reigns.
- `organization.md` — structure, offices, companies, recruitment, manpower, and institutional mechanics.
- `culture.md` — beliefs, traditions, memory, religion, and lived culture.
- `heraldry.md` — colors, markings, armor provenance, and visual traditions.

When reorganizing canon, preserve meaning/status, avoid competing detailed copies, and update navigation/links as needed. Do not create files without a clear purpose.

## Consistency and lore review

Do not silently reconcile genuine canonical conflicts. First check status labels, era, perspective, and summary-vs-detail differences; otherwise surface the conflict unless established canon or the user resolves it.

When developing lore, check:

- internal, character, and institutional continuity;
- Warhammer 40,000 compatibility in chronology, scale, institutions, technology, Warp behavior, and Astartes norms;
- tone/theme and unnecessary exceptionalism;
- preservation of `OPEN`, `PROVISIONAL`, and `UNKNOWN IN-UNIVERSE` uncertainty;
- knock-on effects elsewhere in canon.

Distinguish hard conflicts, soft tensions, open choices, and deliberate revisions. Do not manufacture objections when an idea fits. Verify external 40k lore when materially uncertain or edition-sensitive.

## AI GitHub workflow

AI actions performed through the user's GitHub account must remain distinguishable from human actions.

- Never push AI-generated changes directly to `main`; use a branch and PR.
- AI-authored outward-facing GitHub prose must clearly identify itself as AI-generated.
- AI-generated commits must include `AI-Generated-By: ChatGPT`.
- Use non-attributable actions such as approvals, merges, or reactions only when explicitly requested.
- PR descriptions should summarize meaningful canon additions, removals, reorganizations, and status changes.
- Unmerged PRs are not canon.

## Working material

`working/` may change freely and may contain unresolved ideas, alternatives, rejected concepts, continuity notes, and discussion summaries. Merged canon overrides it. Moving material from `working/` into canon requires user review through a PR.