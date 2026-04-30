# Cartographer

A research tool that maps your thoughts as a hand-drawn city. Place what you've noticed. Ask the cartographer to find the patterns between.

A project of [Pindrop Silence](https://github.com/CaptainFuzzybeard).

---

## What this is

Cartographer is a research/thinking instrument. You arrive with something you're trying to understand — a question, a hunch, a few observations — and you place them on a graph paper grid. Questions for what you don't know. Observations for what you've noticed. Evidence for what you've brought in from outside. You connect them. You paint regions. You let the territory take a shape.

When you're ready, you ask the cartographer to look at what you've made. It tells you what it sees: tensions you hadn't named, insights forming across nodes you didn't connect, frameworks your inquiry rhymes with, honest uncertainty about what's missing.

The cartographer doesn't answer your question. It helps you see your inquiry more clearly than you did before you asked.

## Live URLs

- **[Landing page](./)** — the entry point
- **[Tool directly](./tool/)** — go straight to your work
- **[Start fresh](./tool/?fresh=1)** — a new empty inquiry every time
- **[Example: communities](./tool/?example=communities)** — pre-loaded inquiry on creator-led communities
- **[Example: studios](./tool/?example=studios)** — pre-loaded inquiry on small studios

## Repository structure

```
cartographer/
├── index.html                          ← landing page
├── tool/
│   └── index.html                      ← the prototype itself
├── docs/
│   └── reasoning_engine_v2.md          ← the LLM prompt that powers synthesis
├── banks/
│   └── concept_bank_v1.json            ← framework library used by the synthesis engine
└── examples/
    └── calcification.cartographer.json ← a sample inquiry users can import
```

## Status

v1 — April 2026. Currently uses scripted pattern detection for synthesis. LLM integration in progress.

## License

All rights reserved, Pindrop Silence, 2026.
