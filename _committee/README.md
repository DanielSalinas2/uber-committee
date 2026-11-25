# The Committee

## Purpose
Stress-test Daniel's Uber Eats case (Case 1 · Zero defects, Case 2 · Product management) and prepare him for the panel. The committee learns the case fully, attacks every number and recommendation, documents what survives, and turns what doesn't into either a fix or a prepared answer.

The committee does **not** make Daniel's calls. It argues, he decides, the Clerk records.

## Who is here

| Group | Members | File |
|---|---|---|
| Officers | Chair, Clerk, Historian, Numbers Auditor | `members/officers/` |
| Human | Daniel Salinas (member, final call) | `members/human-daniel.md` |
| Merchant Operations | 5 | `subcommittees/merchant-ops.md` |
| Product & Delivery | 5 | `subcommittees/product-delivery.md` |
| Finance & Risk | 3 | `subcommittees/finance-risk.md` |
| Legal & Compliance | 3 | `subcommittees/legal-compliance.md` |
| Market & Competition | 4 | `subcommittees/market-competition.md` |
| Mock Panel | 5 | `subcommittees/mock-panel.md` |

30 seats in total (29 AI members plus Daniel). 11 members carry the **skeptic** temperament and are expected to attack, not agree. Some members are rarely needed; they are kept so the right voice exists when it is.

## How a session works (short version, full rules in `RULES.md`)
1. **Open.** The Chair opens a session with a code (`YYYY-MM-DD_CODE`), a one-sentence goal and the subcommittees convened. The Clerk creates the session folder from `templates/session/`.
2. **Historian first.** The Historian summarizes what past sessions and `knowledge/` already settled, and what was corrected before.
3. **Rounds.** The Chair picks who speaks. Members announce themselves, respond to each other from their own lens, and hand off explicitly. Every proposal gets at least two skeptic attacks before it can be decided.
4. **Daniel.** Daniel can interrupt at any time. His input goes to the front of the queue.
5. **Decide.** The Chair calls the question. Daniel decides. The Clerk records the decision, the reasoning and any dissent in `decisions.md`.
6. **Close.** The Chair closes the session. The Clerk overwrites `STATUS.md`, updates `sessions/INDEX.md`, and makes sure every artifact sits in the session folder.

## Where things go
- Anything produced in a session (decisions, Q&A prep, rewritten lines, research notes) → that session's folder.
- Anything the committee should know in every future session → `knowledge/` (the Clerk moves it there at close, with the session code as source).
