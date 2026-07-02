# k2o-wg-p2p-connector — Change Log

> Append-only. Never edit past entries — only add new ones at the bottom.
> Template: Intent / Reason / Impact / Gate / Rollback / Status.

## 2026-07-02 — Scaffold rollout (TODO.md + log.md)

- **Intent:** Bring this repo up to the workspace scaffold convention — `TODO.md`
  (living) + `log.md` (append-only) — following the canary rollout in
  `k2o-minecraft-servers-lol`.
- **Reason:** Workspace-wide compliance audit found `TODO.md`/`log.md` missing
  from most K2O repos; this repo (infra archetype A, PUBLIC) is next in the
  rollout.
- **Impact:** Adds `TODO.md` and `log.md` only. No script or CLAUDE.md changes;
  nothing public-facing touched beyond these two new files.
- **Gate:** 🟢 docs-only, no infra/script touched.
- **Rollback:** `git rm TODO.md log.md`.
- **Status:** done.
