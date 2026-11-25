# uber-committee

An AI committee I use to attack my own work before someone else does.

**Context.** Final case for the Uber Eats *Merchant Product & Ops Manager* role (Case 1 · Zero defects, Case 2 · Product management). I submitted the deck on **24 Nov 2026**. I convened this committee on **25 Nov 2026** to stress-test what I submitted and to prepare for the panel on 26 Nov. The decisions in the deck are mine; this committee exists to challenge them.

**What it is.** A standing committee of AI agents that lives in files:

- A **Chair** runs every session and is the only member I normally talk to.
- **Members** sit on subcommittees (merchant ops, product & delivery, finance & risk, legal & compliance, market & competition, and a mock interview panel). About a third of them are skeptics by design.
- A **Historian** reads past sessions and the AI log before anything is decided, so old decisions and corrections aren't lost.
- A **Clerk** keeps `STATUS.md` as the current state (not a log), files every artifact in the session folder, and records dissent.
- I sit on the committee as a member. I set the goal, push on direction and make the final call.

**How to run it.** In Cursor, run the `/committee` command (`.cursor/commands/committee.md`). In Claude Code, run `/committee` (`.claude/commands/committee.md`). The agent reads the whole committee, the Chair gives a status update and asks what I want to do next.

**Layout**

```
_committee/
├── README.md              how the committee works
├── RULES.md               turn-taking, announcements, handoffs, research protocol, decisions
├── STATUS.md              current state (overwritten each session)
├── members/               one file per member (officers + subcommittee members + me)
├── subcommittees/         charter, members and when to convene each subcommittee
├── knowledge/             what the committee knows: brief summary, deck, my decisions, numbers, research
├── templates/             session, decision and research templates
└── sessions/
    ├── INDEX.md           every session, its goal and outcome
    └── 2026-11-25_STRESS/ session 1: attack the submitted deck + mock panel
```

**Confidentiality.** No data set lives here. Numbers appear only as verified aggregates in `knowledge/numbers.md`. The case material is confidential, so this repo should stay private.
