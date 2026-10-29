# Starx security review — 29 October 2026

**Status:** preliminary read-only assessment. No unauthorized curve trade has been demonstrated. The recommended fixes are proposed work; no contract or wallet changes were deployed.

## Read or download

- [PDF report — 9 pages](Starx-Security-Review-2026-10-29.pdf)
- [Editable Markdown report](Starx-Security-Review-2026-10-29.md)
- [HTML version — download and open in a browser](Starx-Security-Review-2026-10-29.html)
- [Complete team package, including evidence](Starx-Security-Review-2026-10-29-Team-Package.zip)
- [Artifact SHA-256 checksums](SHA256SUMS.txt)

The ZIP contains the report formats, recorded RPC evidence, repository commit manifest, archived public CLI README and ABIs, launchpad disassembly, an optional read-only helper, and its own file-integrity manifest.

## Proposed follow-up

| Item | Priority | Classification |
| --- | --- | --- |
| SR-01 — Establish the required wallet-provenance guarantee | P1 | Architecture risk; complete exploitability unresolved |
| SR-02 — Review administrative controls and monitoring | P2 | Confirmed governance design property |
| SR-03 — Match deployed contract sources and complete authorization testing | P1 | Review-completion blocker |
| SR-04 — Clarify curve versus post-graduation pool scope | P3 | Expected behavior; documentation |

Priorities describe the proposed order of work, not CVSS scores. Proposed owner roles and acceptance criteria are in the report. No named reviewers or assignees have been selected.

## Validation boundaries

The active-curve checks are pinned to X Layer block **74,498,680**, and initial observations to block **74,498,079**. Simulations used zero amounts. A complete nonzero trade, full alternative UserOperation, and all deployed SmartWallet authorization paths were not validated.

Keep verified observations, unverified exploitability, and remediation proposals distinct when discussing the report.
