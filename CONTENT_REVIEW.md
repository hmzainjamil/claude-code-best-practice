# README content review

Date: 2026-10-02

A recursive tree check on `docs/reference-scope-and-evidence` found the root, tutorial, Claude hook, and Codex hook README files. No root `package.json`, root `SKILL.md`, `docs/README.md`, or root `docs/assets/banner.png` was present; the root MIT license was present.

The root README now indexes the nested README files. The Day 0 guide routes installation and sign-in to the vendor's current setup documentation and warns that the OS-specific local notes are historical. Both hook README files now describe only repository-local files and link to current vendor references. Fixed event counts, version thresholds, and setup claims were removed.

No install, hook execution, test, or compatibility check was run. The remaining best-practice material was not fully reviewed for currentness.
