# git-lex-kit-solo

Personal agent memory kit for [git-lex](https://github.com/repolex-ai/git-lex).

One agent, one repo, persistent identity across conversations and projects.

## Document Types

- **Memory** — facts, observations, preferences, lessons learned
- **Decision** — personal choices with context and rationale
- **Task** — personal work items and todos
- **Research** — ongoing investigations and inquiry threads
- **Contact** — people and agents you interact with
- **Note** — freeform catch-all

## Install

```bash
git lex init --kit solo
```

## Files

- `solo.ttl` — OWL ontology (classes + properties)
- `solo-shapes.ttl` — SHACL validation shapes
