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

## 2026-11-07: Evidence reuse and static web investigation review

- Request: review this owned tool with a bounded inexpensive worker and use it in the authorized application investigation. Starting main `4897296558a41dd502404537c424de34f062ee11` was fetched and clean. A gpt-6-luna/max worker reviewed capabilities; the parent independently read docs/tools.md, the session evidence retention/resolution implementation and docs/codex.md.
- Findings: existing evidence export/import and on-disk resolution already support the requested reuse direction. No concrete missing engine feature was established; no speculative issue was created. The issue tracker was enabled for the owner's requested issue workflow.
- Tool use: installed CLI 0.3.0 inspected a self-collected anonymous public HTTP capture and inert JavaScript using documented per-run static analysis access. The initial Clean Room refusal is retained. Persistent mode, target execution, builder access and device/runtime operations were unchanged. Exact receipts and parser limitations belong in https://github.com/joelfuller2016/apply-studio.
- Boundary/cost: existing engine checkout, source and global configuration were preserved. Static candidate extraction does not establish runtime API reachability or authenticated feature coverage. Worker dollar/token telemetry is unavailable. This journal-only record receives whitespace/staging/remote readback checks; no product build, test pass or upstream sync is claimed.
