# Sacratus

The story of Sacratus and the Palatinae.

This repository is the source of truth for the setting. Chat is the workshop; merged repository content is authoritative.

## Start here

For a new reader:

1. [`palatinae/overview.md`](palatinae/overview.md) — what the Palatinae are;
2. [`timeline.md`](timeline.md) — the broad chronology of Sacratus;
3. [`palatinae/history.md`](palatinae/history.md) — how the Chapter became what it is.

For quick chronological checking, use [`palatinae/timeline.md`](palatinae/timeline.md). For individual Chapter Masters, use [`palatinae/constantines.md`](palatinae/constantines.md).

## Repository navigation

### Setting-wide

- [`timeline.md`](timeline.md) — grand chronology of Sacratus, including political, military, institutional, and Palatinae developments.

### Palatinae

- [`palatinae/overview.md`](palatinae/overview.md) — high-level Chapter identity and front door to Palatinae canon;
- [`palatinae/history.md`](palatinae/history.md) — narrative and causal history: how and why the Chapter changes over time;
- [`palatinae/timeline.md`](palatinae/timeline.md) — chronological reference focused specifically on Palatinae development;
- [`palatinae/constantines.md`](palatinae/constantines.md) — current combined record of the Constantines; intended to split into biographies when useful;
- [`palatinae/organization.md`](palatinae/organization.md) — companies, command, Varangians, Librarius, recruitment, manpower, and other institutional structure;
- [`palatinae/culture.md`](palatinae/culture.md) — beliefs, traditions, generational identity, memory, religion, and lived Chapter culture;
- [`palatinae/heraldry.md`](palatinae/heraldry.md) — colors, Chi-Sword variants, markings, armor provenance, and visual identity.

### Working material

- [`working/`](working/) — explicitly non-canonical scratch material, unresolved questions, alternatives, rejected ideas, and migration notes.

## Document roles

The Palatinae documents intentionally overlap at a high level but answer different questions:

- **Overview:** What are the Palatinae?
- **History:** How and why did they become that?
- **Timeline:** When did it happen?
- **Constantines:** Who held the office, and how did each shape the Chapter?
- **Organization:** How does the Chapter function?
- **Culture:** How does the Chapter understand itself and live?
- **Heraldry:** What does the Chapter look like, and what do its visual traditions mean?

Detailed subjects should have one primary canonical home. Other documents may summarize important facts and link to the governing document rather than maintaining independent detailed copies.

## Repository model

Everything on `main` is authoritative **except the `working/` directory**, which is explicitly non-canonical scratch space.

Lore may live at the repository root or inside subject folders. Folder structure is organizational only; moving a lore file into a subdirectory does not make it less canonical.

Current structure:

```text
README.md
AGENTS.md
timeline.md
palatinae/
├── overview.md
├── history.md
├── timeline.md
├── constantines.md
├── organization.md
├── culture.md
└── heraldry.md
working/
└── README.md
```

As the setting grows, additional subject folders or files can be introduced when they improve readability. There is no requirement to create empty documents before they are useful.

## Canon

All lore outside `working/` is canon once merged to `main`.

Canon does not mean that every question has a finalized answer. Where useful, canonical documents distinguish:

- **LOCKED** — established and not to be revised without explicit direction;
- **PROVISIONAL** — the current working answer, still subject to revision;
- **OPEN** — not yet decided;
- **UNKNOWN IN-UNIVERSE** — deliberately left without a definitive answer;
- **REJECTED** — considered and discarded.

When one of these labels appears in a canonical file, the status itself is authoritative. For example, an **OPEN** date is canonically open rather than permission for an AI to choose a date silently.

The root [`timeline.md`](timeline.md) is the setting-wide chronology. Subject timelines, such as [`palatinae/timeline.md`](palatinae/timeline.md), may overlap with it while emphasizing the history of a particular faction or institution.

## Working material

`working/` is the one explicitly non-canonical area of the repository. It can contain AI-maintained summaries, unresolved questions, possible developments, rejected ideas, continuity concerns, or other notes extracted from worldbuilding conversations.

Working material is allowed to be messy and to change without implying a canon change. A concept becomes canon only when it is deliberately promoted out of `working/` and merged to `main` through review.

The intended workflow is:

```text
conversation / brainstorming
          ↓
     working/ notes
          ↓
   explicit decision
          ↓
   canon change PR
          ↓
     reviewed merge
          ↓
         main
```

See `AGENTS.md` for the rules AI agents should follow when reading or modifying the repository.
