---
"@changesets/action": patch
---

Fix `cwd` input not being passed to `readChangesetState`, causing changesets to be read from the wrong directory in monorepo setups.
