# Claude Code Best Practice

A reference collection for Claude Code workflows, setup notes, skills, and hook examples. It also contains separate Codex hook examples. Instructions can become outdated; verify product behavior against the current vendor documentation before use.

## Repository guide

| Document | Scope |
|---|---|
| [Day 0 setup](tutorial/day0/README.md) | Current setup source and status of the local setup notes |
| [Claude Code hook files](.claude/hooks/HOOKS-README.md) | This repository's Claude Code hook configuration and script |
| [Codex hook files](.codex/hooks/HOOKS-README.md) | This repository's Codex hook configuration and script |
| [Best-practice notes](best-practice/) | Reference material |
| [Development workflows](development-workflows/) | Workflow examples and notes |
| [Content review](CONTENT_REVIEW.md) | Prior claims removed and review scope |
| [Security guidance](SECURITY.md) | Data and command review guidance |

## Repository status

The recursive tree on branch `docs/reference-scope-and-evidence` was checked on 2026-10-02. It contains the linked README files and hook examples. No root `package.json`, root `SKILL.md`, `docs/README.md`, or root `docs/assets/banner.png` was found. The root MIT license is present.

No install, compatibility, benchmark, or test result is claimed here. The local setup pages and hook examples have not been validated against every current product version. The hook scripts and project configuration can run commands automatically; inspect them before enabling hooks in a trusted project.

For current Claude Code behavior, use the [official setup documentation](https://code.claude.com/docs/en/getting-started) and [hooks reference](https://code.claude.com/docs/en/hooks). For Codex, use the [official hooks documentation](https://learn.chatgpt.com/docs/hooks).
