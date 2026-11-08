# Work journal

## 2026-11-07 — Owner fork preserved for machine recovery

- Request: create an owner-controlled fork before a possible computer format. The
  fork is https://github.com/joelfuller2016/craft-anything, with upstream parent
  https://github.com/storytold/craft-anything and default branch `main` at creation
  source `56aa31976b4ff0950e6b34ba020b0a568d2462fa`.
- Verification: GitHub parent/default-branch metadata and fetched Git HEAD agree.
  Before this journal entry, all193 advertised branch/tag refs matched upstream.
- Preservation scope: Git source/history is forked. Published release binaries,
  package caches and private application data are separate recovery assets. Portable
  adapter/setup recovery is tracked in
  https://github.com/joelfuller2016/codex-portable-settings/pull/9; the application
  plan is https://github.com/joelfuller2016/apply-studio/issues/1.
- This checkpoint changes only `JOURNAL.md` under the owner's standing journal
  publication rule. Existing installed checkouts, runtime configuration and product
  code are untouched. No upstream code, build, provider or browser action was run.
  Whitespace, staged-file scope and remote commit readback are the relevant checks.
