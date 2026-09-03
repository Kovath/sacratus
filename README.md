# Sacratus

A Warhammer 40,000 homebrew setting centered on the Sacratus system, its history, institutions, factions, and the Long Vigil.

This README is a human-facing map of the repository. It is intended to help readers find material, not to establish canon or repository policy.

## Start here

- [`timeline.md`](timeline.md) — setting-wide chronology and major historical periods.
- [`palatinae/`](palatinae/) — lore concerning the Palatinae Chapter.
- [`mechanicus/`](mechanicus/) — lore concerning the Mechanicus of Sacratus and the Forge World's industrial history.
- [`falkenrath/`](falkenrath/) — lore concerning the House Falkenrath Knight branch trapped within Sacratus.
- [`working/`](working/) — non-canonical scratch material, unresolved ideas, alternatives, and development notes.

As the setting expands, other factions, institutions, places, and major subjects may receive their own directories.

## Repository organization

Setting-wide material belongs at the repository root when it genuinely spans the setting. More focused material should live under the relevant subject or faction directory.

Major directories may contain their own `README.md` as a local navigation page. Those local READMEs can describe the documents within that subject without requiring the root README to duplicate their structure.

A typical shape is:

```text
README.md
AGENTS.md
timeline.md
<faction-or-subject>/
├── README.md
├── ...
working/
└── ...
```

The repository does not need to pre-create files or directories before a subject has enough material to justify them.

## Status labels

Lore documents may use these labels when a point is not simply settled canon:

- **LOCKED** — established;
- **PROVISIONAL** — current working answer, still subject to revision;
- **OPEN** — not yet decided;
- **UNKNOWN IN-UNIVERSE** — deliberately left without a definitive answer;
- **REJECTED** — considered and discarded.

For authoritative repository workflow, canon handling, and AI instructions, see [`AGENTS.md`](AGENTS.md).