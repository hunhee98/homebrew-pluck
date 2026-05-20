# homebrew-pluck

Homebrew tap for [pluck](https://github.com/hunhee98/pluck) — fast,
token-friendly code reading for AI coding agents.

## Install

```bash
brew tap hunhee98/pluck
brew install pluck
```

Installs two binaries:

- `pluck` — CLI for ad-hoc retrieval (`pluck search`, `pluck grep`, …)
- `pluckd` — MCP server that AI coding agents (Claude Code, Codex,
  Cursor, …) call via stdio.

After install, register `pluckd` as an MCP server in your agent. See
[pluck's agent-install docs](https://github.com/hunhee98/pluck/blob/main/docs/AGENT_INSTALL.md)
for per-agent config examples (Claude Code / Codex / Cursor).

## Upgrade

```bash
brew upgrade pluck
```

## Issues

Formula bugs go in this repo's issue tracker. For pluck behavior /
feature requests / language support, file at
[hunhee98/pluck/issues](https://github.com/hunhee98/pluck/issues).

## Versions

The formula tracks pluck's tagged GitHub releases. The latest
formula in this tap reflects the most recent published version on
[crates.io](https://crates.io/crates/pluck-cli).
