# sos-deployment — Agent execution instructions

**Portfolio:** 14/16 (source row 14); **Lead agent:** ChatGPT; **specialty:** Runbook consolidation and architecture mapping; **independent reviewer:** Gemini (Infrastructure documentation review).
**Repository:** https://github.com/s-os-agency/sos-deployment
**Authoritative gates:** https://docs.google.com/spreadsheets/d/1MMk4Tx0k5rS7e_vOIFg-Dg022VEqXsdwqHibT9-3uOI/edit#gid=20261034
**Release dashboard:** https://docs.google.com/spreadsheets/d/1MMk4Tx0k5rS7e_vOIFg-Dg022VEqXsdwqHibT9-3uOI/edit#gid=20261035
**Disposition:** CLOSE AS REFERENCE; **accountable proposed engineering role:** Technical Portfolio Curator.

## Mandatory operating rules
- Existing root AGENTS.md owner instruction controls: do not add, restore or run software test suites, test-only workflows or scaffolding. Existing spreadsheet references to tests are superseded: obtain real source/build/configuration and operational readback evidence within the owner policy. Never claim tests were run or passed.
- Inspect canonical README, source, existing diffs and deployments before changes. Make the smallest reversible implementation change required. Do not merely write plans or invent launch statuses.
- The named lead is a proposed execution assignment, **not proof of an active external agent session**, OpenRouter invocation, or authority to use another agent's account. A reviewer is an independent second-pass assignment, not an approval already provided.
- Use only scoped provider access actually available. No blind deployment, destructive migrations, new permissions, purchases or exposure of credentials. Preserve backups and rollback.
- Attach evidence URL, UTC date, version/commit, deployed environment and observed result to the corresponding Exact Completion Gates row. Mark VERIFIED only for evidence-backed completion. Leave other gates OPEN; no fabricated real customer, revenue, PayPal or Ziina status.
- This is a NON-LAUNCH preservation/closure track; do not deploy an unnecessary duplicate service.

## Exact execution order

### Gate 14.1 — EXTRACTION
**Action:** Compare historical deployment requirements against current S-OS runbook; migrate only still applicable items with source citations.
**Acceptance outcome:** S-OS runbook contains valid retained requirements linked to original proposal.
**Evidence required:** actual source/commit, environment, timestamp, direct output/receipt, and reviewer; record in sheet. **Initial state: OPEN.**

### Gate 14.2 — CLOSE
**Action:** Mark documentation-only, remove from runtime publish checklist without deleting history.
**Acceptance outcome:** Preserved historical document and no active deployable classification.
**Evidence required:** actual source/commit, environment, timestamp, direct output/receipt, and reviewer; record in sheet. **Initial state: OPEN.**

## Completion handoff
Update each gate's verification state in Google Sheets and attach proof. Distinguish implementation from launch, customer acceptance from inquiries and settled payments from checkout creation. The lead produces the change receipt; the reviewer checks evidence independently. Do not announce completion until all required applicable gates pass. Report any unavoidable external authorization boundary specifically.

**Agent document author:** GPT-6 (instructions only; not a launch attestation).
