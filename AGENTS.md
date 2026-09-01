# Repository workflow

## Source of truth

- The `main` branch is the authoritative source for Sacratus lore and repository instructions.
- Lore content on `main` outside `working/` is canon. This includes lore organized in subdirectories such as `palatinae/`; canon is not restricted to top-level files.
- `AGENTS.md` and repository configuration are authoritative operational instructions, not in-universe lore.
- `README.md` is a human-facing navigation aid only. It is not an authoritative source for canon or repository policy; when it conflicts with canonical lore or `AGENTS.md`, defer to those sources.
- Material under `working/` is explicitly non-canonical scratch space.
- A canonical document may contain **PROVISIONAL**, **OPEN**, **UNKNOWN IN-UNIVERSE**, or **REJECTED** material. In those cases, the *status itself* is canonical even when the underlying question is unsettled.
- Chat context, model memory, prior brainstorming, and README summaries are useful context but are not authoritative when they conflict with merged canonical lore.
- Before making claims about established lore, read the relevant canonical repository files when available.
- New brainstorming does not become canon merely because it appears in chat or model context. It becomes canon when it is deliberately written into a lore document outside `working/`, reviewed by the user, and merged into `main`.

## Canon status vocabulary

Use these statuses consistently when a fact or section is not simply ordinary established canon:

- **LOCKED** — Established setting fact. Do not revise without explicit user direction.
- **PROVISIONAL** — Current working decision that may still move. It may be questioned or revised, but its provisional status should be preserved until changed.
- **OPEN** — Question not yet decided. Do not silently resolve it.
- **UNKNOWN IN-UNIVERSE** — Deliberately unresolved within the setting. Do not invent a definitive answer unless the user explicitly changes this status.
- **REJECTED** — Previously considered idea that should not be reintroduced as canon unless explicitly reconsidered. Rejected ideas generally belong under `working/`; when recorded in canon, the rejection itself is authoritative.

Statuses may apply to an individual fact, section, date, interpretation, or whole topic; they do not require one file per status.

## Navigation and document roles

Use `README.md` as the human-facing navigation map for the repository. It can help identify likely files, but it does not establish canon or policy. When the repository structure changes, keep its navigation links and document descriptions current for human readers.

Canonical documents should have distinct jobs. For the Palatinae material, use these roles unless the repository later establishes a more specific structure:

- `overview.md` — **What is this subject?** A concise synthesis and entry point. It may repeat important facts for readability, but should not become the detailed canonical home for every topic it mentions.
- `history.md` — **How and why did this subject become what it is?** The primary narrative and causal historical account. It explains developments, transitions, consequences, and historical context rather than serving as a fact dump.
- `timeline.md` — **When did things happen?** A chronological reference optimized for dates, sequence, reigns, periods, and quick continuity checks. It should not carry long narrative explanations better suited to `history.md`.
- `constantines.md` — **Who held the Constantinian office and how did each shape the Chapter?** The current biographical and reign-focused canonical home. Split it into a directory of biographies only when the material warrants it.
- `organization.md` — **How does the Chapter function?** The primary home for companies, offices, command relationships, recruitment, manpower structure, specialist bodies, and other institutional mechanics.
- `culture.md` — **How does the Chapter understand itself and live?** The primary home for beliefs, traditions, memory, religion, generational identity, customs, attitudes, and lived Chapter culture.
- `heraldry.md` — **What does the Chapter look like, and what do its visual traditions mean?** The primary home for colors, badges, markings, armor provenance, visual distinctions, and modeling-relevant heraldic rules.

These categories may overlap at a summary level. Their distinction is by **purpose**, not by forbidding a fact from ever being mentioned in more than one document.

## Referential consistency and canonical ownership

Each detailed subject should have one **primary canonical home**. Other files may summarize the subject when necessary for comprehension, but should link or defer to the primary home for detailed treatment.

When reading canon:

1. Use `README.md` only to identify the relevant subject area and likely governing documents.
2. Read the subject overview when broad context is needed.
3. Read the most specific canonical document governing the question before making a detailed claim. Do not rely solely on an overview when a specialized document exists.
4. For historical questions, distinguish narrative causation (`history.md`) from chronological precision (`timeline.md`). Consult both when the answer depends on both.
5. For a Constantine's motives, personality, career, or succession, prefer the Constantine material; for the wider consequences of the reign, consult the relevant history and specialized subject files as needed.
6. Consult cross-cutting documents together when a question spans domains rather than assuming one file contains the entire answer.

When writing or reorganizing canon:

- Put new detailed material in the document whose role most directly owns the subject.
- Keep summaries concise outside the primary home. Avoid maintaining multiple independent detailed versions of the same lore.
- When moving detailed material to a more appropriate canonical home, update or shorten older copies so they do not become competing authorities.
- Preserve useful cross-references between documents when a reader would reasonably need to move from one subject to another.
- When creating, renaming, moving, splitting, or deleting canonical files, update `README.md` navigation in the same change.
- When a large file is split, preserve an overview or index at the old conceptual entry point when that improves discoverability.
- Do not create a new file merely because a possible category exists. Split material when the new document has a clear purpose and enough substance to justify independent navigation.

## Resolving apparent conflicts

Do not silently choose between contradictory canonical statements.

First determine whether the apparent conflict is intentional:

- a more specific document may elaborate on a summary without contradicting it;
- a `PROVISIONAL`, `OPEN`, `UNKNOWN IN-UNIVERSE`, or `REJECTED` label may explain the difference;
- two statements may represent different eras, perspectives, or in-universe interpretations.

If two canonical files genuinely conflict and no status or context resolves the conflict:

- surface the inconsistency rather than inventing a reconciliation;
- prefer neither file solely because it is longer, newer, or more specific unless the repository explicitly establishes that precedence;
- when making a repository change, resolve the inconsistency only when the user's decision or already-established canon clearly determines the answer;
- update all affected summaries and cross-references when a conflict is deliberately resolved.

## Lore compliance review during discussion

When discussing new lore, revisions, interpretations, or expansions, perform a lightweight **lore compliance review** against the relevant repository canon before treating the idea as fitting the setting.

The review should check, as applicable:

- **Internal continuity** — Does the idea conflict with established dates, people, institutions, geography, manpower, causality, or status labels?
- **Character continuity** — Does it fit the established motives, personality, capabilities, relationships, and historical role of the people involved?
- **Institutional continuity** — Does it respect how the Palatinae, Concordat, Mechanicus, Sororitas, mortal military, and other institutions are established to function?
- **Thematic continuity** — Does it preserve the setting's established tone, constraints, and major thematic choices rather than weakening them through convenience or escalation?
- **Warhammer 40,000 compatibility** — Does it fit known 40k lore, scale, institutions, technology, Warp behavior, Astartes capabilities, and Imperial norms without requiring an unsupported exception?
- **Specialness budget** — Does it add another major mystery, unique privilege, legendary connection, irreplaceable relic, or exceptional capability where the setting is already deliberately restrained?
- **Uncertainty preservation** — Does it accidentally answer something marked `OPEN` or `UNKNOWN IN-UNIVERSE`, or strengthen a `PROVISIONAL` idea into certainty?
- **Knock-on effects** — If accepted, what existing documents, relationships, chronology, or later events would logically need to change?

The review does not need to be presented as a rigid checklist in every conversational response. Integrate it naturally into critique and development. When an idea fits cleanly, say so without manufacturing objections. When there is a meaningful issue, identify whether it is:

- a **hard conflict** with established canon or external 40k lore;
- a **soft tension** that can work but needs explanation or tradeoffs;
- an **open design choice** not currently constrained by canon;
- or a **deliberate revision** that is viable if existing canon is changed knowingly.

Do not reject an idea merely because it changes canon. The purpose of the review is to make the consequences explicit so the user can choose whether to preserve, adapt, or revise the existing material.

When external Warhammer 40,000 lore is materially uncertain, edition-sensitive, or likely to have changed, verify it before presenting a compliance judgment as fact.

## AI identity and attribution

GitHub actions performed by AI through the user's account must not be presented as though the user personally wrote or performed them.

- Any outward-facing text authored by AI and posted under the user's identity must clearly identify itself as AI-generated.
- This applies to pull request descriptions, issue bodies, top-level pull request or issue comments, inline review comments and replies, review summaries, and similar human-facing GitHub content.
- Prefer a short marker at the beginning of the content, such as `AI-generated by ChatGPT.` or `AI-assisted change proposed from ChatGPT.`
- Do not write comments in the user's voice without this attribution, even when the content merely summarizes a requested change or says that feedback has been addressed.
- Commit messages for AI-generated commits must include the trailer:

  `AI-Generated-By: ChatGPT`

- For GitHub actions that cannot carry an attribution label, such as reactions or approval/merge actions, do not use them merely to express the user's judgment. Perform them only when the user has explicitly requested that specific action.

The general rule is: if an AI action could reasonably be mistaken for an action personally authored or expressed by the user, make the AI origin explicit whenever the GitHub surface allows it.

## Canon changes

For AI-generated changes to canon or repository metadata:

- Do not push directly to `main`.
- Open a pull request for all changes.
- Summarize meaningful canon additions, removals, reorganizations, and status changes in the pull request description.
- Do not treat an unmerged pull request as accepted canon.
- When reorganizing canon, preserve meaning and status rather than silently strengthening provisional material into settled fact.
- Before completing a structural change, check that navigation, relative links, document-role descriptions, and primary canonical homes remain consistent.

## Working material

- Material under `working/` is the sole explicitly non-canonical area of the repository.
- It may be revised, reorganized, summarized, or discarded by AI as the discussion evolves.
- `working/` may contain unresolved questions, provisional alternatives, rejected ideas, continuity concerns, summaries of active discussions, and possible future developments.
- Do not promote working material into canon merely because it has persisted for a long time or appears internally consistent.
- When working notes conflict with merged canon, merged canon wins.
- Promotion from `working/` into a canonical lore path is a canon change and requires user review through a pull request.