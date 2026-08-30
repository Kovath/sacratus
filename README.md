# Sacratus

The story of Sacratus and the Palatinae.

This repository is the source of truth for the setting. Chat is the workshop; merged repository content is authoritative.

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
├── timeline.md
└── constantines.md
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

## Palatinae

The [`palatinae/`](palatinae/) directory contains Chapter-focused canon:

- [`overview.md`](palatinae/overview.md) — high-level identity, organization, culture, heraldry, and strategic role;
- [`timeline.md`](palatinae/timeline.md) — the Chapter's history viewed through Palatinae development rather than the entire Sacratus system;
- [`constantines.md`](palatinae/constantines.md) — the current combined record of the Constantines. Individual biographies can be split into separate files later if the material becomes large enough to benefit from it.

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
