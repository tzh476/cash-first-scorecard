# Cash-First Scorecard

Score each opportunity before you write code, a pitch, or a proposal.
Maximum 40 points. **Below 27: do not start.** Any hard stop is an immediate no.

## Hard stops (any one fails → exit)

- Reward already paid, reserved, or closed
- No escrow, official program, or documented payer history
- Parent thread is crowded (`/claim`, mass scoped PRs, reward-farm)
- Region, residency, or ID gate you cannot truthfully meet
- Requires a wallet lock, unpaid video, or hardware you do not have
- Explicit ban on AI-assisted or proxy work, if that is how you work
- Client is brand-new and payment is “on delivery” with no funded milestone
- You would have to invent experience, location, or a portfolio

## Scoring (0–5 each)

| Dimension | 0 | 5 |
|---|---|---|
| Payment trust | No payer / no record | Escrow or official paid history |
| Task still live | Closed or stale | Open and confirmed by source |
| Competition | Multiple mature submissions | No claim, no competing PR |
| Acceptance clarity | Subjective vibe | Testable acceptance criteria |
| Skill fit | Needs fake credentials | You can deliver from current public work |
| Local verification | Cannot reproduce | Core path and a counterexample both testable |
| Maintainer / editor response | Silent or hostile | Recent external acceptances |
| Time | Weeks of meetings | 2–8 hours to a complete submission |

## Risk deductions

- Public legal name required: −5
- Upfront fee or “buy access”: hard stop
- Prize pool huge, repo tiny, no escrow: −5
- 100+ participants, top 3 only: −4
- Video or paper required: −3 to −5

## Expected value

```
EV = advertised_pay
    × P(still_open)
    × P(accepted)
    × P(payment_arrives)
    − hours × your_hourly_floor
    − cash/compute cost
    − reputation risk
```

If EV is below 2× your time cost, stop. Advertised prize pools are not income.

## Status labels (use these, nothing looser)

- `paid` — payer confirmed, money moved
- `awarded` — won, not yet paid
- `submitted` — sent, not accepted
- `candidate` — diligence only
- `excluded` — do not reopen without new first-party evidence
