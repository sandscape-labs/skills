# Sandscape Skills

Agent Skills for working on [Sandscape](https://sandscape.app) games from any
coding agent — Claude Code, OpenAI Codex, Cursor, OpenCode, and other tools that
read the open `SKILL.md` standard.

## Install

Into every detected tool, globally, non-interactively:

```bash
npx -y skills@latest add sandscape-labs/skills -g -y
```

Or target specific tools / a single skill:

```bash
npx -y skills add sandscape-labs/skills --skill sandscape-cli -g -a claude-code codex cursor opencode -y
```

> Prefer no third-party installer? The Sandscape CLI ships the same skill:
> `npx -y @sandscape/cli@latest skill install`.

## Skills

- **sandscape-cli** — drive the `@sandscape/cli` local-dev round-trip
  (login → pull → edit → push), import your own game, and publish. AI asset
  generation stays on the Sandscape platform.

## Getting started

After installing, the agent authorizes the CLI once (device-code login), then
works locally. See each skill's `SKILL.md` for the full workflow.

[![skills.sh](https://skills.sh/b/sandscape-labs/skills)](https://skills.sh/sandscape-labs/skills)
