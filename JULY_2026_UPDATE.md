# July 2026 Update — Corrected Contribution Totals

> Addendum to the [Q2 2026 Impact Report](IMPACT_REPORT_Q2_2026.md). The Q2 report is preserved as published; this note corrects figures that a full verification pass showed were **undercounted**, and updates statuses that changed since May.

In July 2026 we verified every community pull request directly against the GitHub API and rebuilt the [PR Tracking Dashboard](https://github.com/code-orange-dev/PR-tracking-dashboard) so that **every merged PR carries a direct link**.

## Corrected totals (as of July 2026)

| Metric | Q2 report said | Verified |
| --- | --- | --- |
| PRs opened | 18+ | **130+** |
| PRs merged | 12+ | **92** |
| Active contributors | 12 | 11 (with merged/open PRs and public handles) |
| Distinct projects | 20+ | 30+ |

The Q2 figures were conservative baselines carried over from the April dashboard; the verification pass surfaced substantial contribution activity that had not been logged.

## Status changes since the Q2 report

- **Arowolo** — first rust-payjoin PR ([#1659](https://github.com/payjoin/rust-payjoin/pull/1659)) **merged** June 19, 2026 (report said "approved, awaiting merge"); 3 rust-payjoin merges total
- **Peter** — [Bitcoin Core #34885](https://github.com/bitcoin/bitcoin/pull/34885) **merged** April 2026, plus 13 further merges across kernel-node, rust-bitcoin, rust-bitcoinkernel, and bdk-ffi (report said "under review")
- **Psychemist** — [LDK #4293](https://github.com/lightningdevkit/rust-lightning/pull/4293) **merged** January 2026 (report said "under review")
- **Muhammad** — no longer "emerging": 7 merges including [rust-bitcoin #6394](https://github.com/rust-bitcoin/rust-bitcoin/pull/6394) and [Floresta #1001](https://github.com/getfloresta/Floresta/pull/1001), plus an open [Bitcoin Core PR](https://github.com/bitcoin/bitcoin/pull/35320)
- **Mwihoti** — first **merged** rust-payjoin PR ([#1589](https://github.com/payjoin/rust-payjoin/pull/1589)), May 2026
- **Razor** — 4 peer-observer merges (report listed 2)
- **Chaitika** — 17 merges in 2026 on the Silent Payments stack ([CypherCommons/shroud](https://github.com/CypherCommons/shroud))

## Counting policy (unchanged, now enforced)

Merged = accepted by the upstream maintainer, direct PR link required. PRs to a contributor's own repos or to non-Bitcoin projects are not counted. Contributions made before a member joined Code Orange are marked and excluded from program-outcome claims.

Full detail, updated monthly: [PR Tracking Dashboard](https://github.com/code-orange-dev/PR-tracking-dashboard)

*Next full report: Q3 2026 (August).*
