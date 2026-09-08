# CodexPotter ($loop)

A better /goal replacement — continuously reconciles the codebase toward your instructed goal or state (Ralph Wiggum pattern).

## Why

- **Codex-first** — Codex subscription is all you need; no extra LLM needed.
- **Auto-review / reconcile** — Review and polish multi rounds until fully aligned.
- **Clean-room** — Use clean context in each round, avoid context poisoning.
- **Seamless integration** — AGENTS.md, skills & MCPs just work.
- **Tiny footprint** — Uses <1k tokens for the worker profile.

## Getting started

```bash
npx codex-potter@next setup
```

Then use `$loop` in Codex CLI or Codex Desktop:

```plain
$loop Implement /ps endpoint according to docs/ps_design.md
```

## Skills

- `$loop` — run the reconciliation workflow
- `$compact-kb` — reorganize the local knowledge base

## Upstream

- Repository: https://github.com/breezewish/CodexPotter
- License: Apache-2.0
- npm: `codex-potter`
