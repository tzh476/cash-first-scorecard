# Worked examples

All three examples use public records only. They show the method, not a promise that the same programs are still open.

## Example A — keep: official bounty, small issue, later paid

- **Shape:** Official time-boxed open-source event. Issue open. Acceptance = merged PR + tests.
- **Why it scored ≥ 27:** Named payer, historical payouts, low competition at start, locally testable bug, no region gate.
- **What “paid” required:** Merge was not enough. Income was recorded only after the organizer confirmed PayPal payment.
- **Reusable rule:** Prefer official programs over README “we might pay.”

Public traces of this pattern: [microsoft/qdk#3291](https://github.com/microsoft/qdk/pull/3291) and [moth-quantum/QuantumBrush#56](https://github.com/moth-quantum/QuantumBrush/pull/56).

## Example B — keep: maintainer-paid bugfix

- **Shape:** Real repository, bounded fix, maintainer asked for a PayPal address after merge.
- **Why it scored ≥ 27:** One payer, one issue, verification possible, no contest crowd.
- **Risk that still existed:** Discretionary payment until the receipt arrived.
- **Reusable rule:** A merged PR is `submitted` or `merged_pending_payment`, never `paid`.

Public trace: [Farama-Foundation/PettingZoo#1384](https://github.com/Farama-Foundation/PettingZoo/pull/1384).

## Example C — reject: looks remote, fails payment and delivery

- **Shape:** Fixed-price marketplace card, two bids, ~USD 100–190, tagged remote.
- **Why it failed:** Client created the same day; “paid on delivery”; no funded milestone; physical discs and a hard drive had to be couriered; possible DVD-decryption tools.
- **Score:** Hard stop on unprotected payment + physical delivery.
- **Reusable rule:** Bid count is not diligence. Open the source page. If money is not escrowed, walk away.

## How to log a new example

Copy `05-due-diligence-template.md`, fill evidence links, then add one row to `02-scorecard.csv`. If you exclude it, write the reason in one sentence so you do not re-investigate next week.
