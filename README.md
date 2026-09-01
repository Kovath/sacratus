# Sacratus

The story of Sacratus and the Palatinae.

This repository is the source of truth for the setting. Chat is the workshop; merged files on `main` are canon.

## Repository model

Human-facing canon lives in top-level Markdown files. The repository should stay easy to browse without requiring readers to descend through a large documentation hierarchy.

Expected examples as the setting grows:

```text
README.md
AGENTS.md
timeline.md
palatinae.md
sacratus-system.md
institutions.md
constantines.md
working/
```

The list above is illustrative, not a requirement to create empty files before they are useful.

### Canon

Top-level lore documents on `main` are authoritative. Canon changes require review through a pull request before they are merged.

Where useful, canon can distinguish:

- **LOCKED** — established and not to be revised without explicit direction;
- **PROVISIONAL** — the current working answer, still subject to revision;
- **OPEN** — not yet decided;
- **UNKNOWN IN-UNIVERSE** — deliberately left without a definitive answer;
- **REJECTED** — considered and discarded, usually recorded only in working material so it is not accidentally reintroduced.

### Working material

`working/` is non-canonical scratch space. It can contain AI-maintained summaries, unresolved questions, possible developments, rejected ideas, continuity concerns, or other notes extracted from worldbuilding conversations.

Working material is allowed to be messy and to change without implying a canon change. A concept becomes canon only when it is deliberately promoted into a top-level lore document and merged to `main` through review.

The intended long-term workflow is:

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
