# OctoAcme — Retrospective & Continuous Improvement

## Purpose
Capture learnings and convert them into actionable improvements that feed back into the team's process and documentation.

## When
After each sprint, release, or important milestone. Also after incidents.

---

## Facilitator Pre-Retro Checklist

- [ ] Date, time, and video/meeting link shared with all participants at least 24 hours in advance
- [ ] Previous retro action items reviewed and status updated
- [ ] Anonymous input tool set up (e.g., FunRetro, EasyRetro, Miro, sticky notes)
- [ ] Agenda shared with team (format, timebox, norms)
- [ ] Safe-space reminder added to agenda: blameless, constructive, confidential

---

## Recommended Formats

### Format A — Start / Stop / Continue (default)
Good for sprints and regular team cadence.

| Column | Prompt |
|---|---|
| Start | What should we begin doing that we're not doing now? |
| Stop | What are we doing that's not adding value? |
| Continue | What's working well that we want to keep? |

### Format B — 4Ls (Liked / Learned / Lacked / Longed for)
Good for post-release or milestone retrospectives.

| Column | Prompt |
|---|---|
| Liked | What did you appreciate about this cycle? |
| Learned | What new insight did you gain? |
| Lacked | What was missing that would have helped? |
| Longed for | What do you wish we had done differently? |

### Format C — Incident Retrospective
Use after an outage, security event, or significant production issue. Focus on blameless systemic analysis.

| Section | Content |
|---|---|
| Timeline | Chronological sequence of events |
| Root causes | Underlying systemic factors (not individuals) |
| What went well | Detection, response, communication successes |
| What could be improved | Gaps in process, tooling, or runbooks |
| Action items | Specific, owned, time-boxed improvements |

---

## Retrospective Meeting Template

Copy this for each retrospective session.

```
## Retrospective — [Project / Sprint / Release Name]

| Field        | Value                          |
|--------------|--------------------------------|
| Date         | YYYY-MM-DD                     |
| Facilitator  | [Name]                         |
| Participants | [Names or team]                |
| Format used  | Start/Stop/Continue / 4Ls / Incident |

### Previous action items review
| Item | Owner | Status |
|------|-------|--------|
| …    | …     | Done / In Progress / Carry over |

### What went well
- …

### What could be improved
- …

### Top 2–3 action items (prioritized by vote)
| # | Action item | Owner | Due date | Success criteria |
|---|-------------|-------|----------|-----------------|
| 1 | …           | …     | …        | …               |
| 2 | …           | …     | …        | …               |
| 3 | …           | …     | …        | …               |

### Notes / parking lot
- …
```

---

## Running a Retrospective — Step-by-Step

1. **Open (5 min)** — Welcome, remind participants of norms (blameless, constructive), confirm timebox.
2. **Review previous actions (5–10 min)** — Quickly update status on items from the last retro.
3. **Gather input (10–15 min)** — Silent brainstorm; each person adds cards to the board.
4. **Group & discuss (15–20 min)** — Cluster similar cards, discuss themes, invite elaboration.
5. **Prioritize (5 min)** — Dot vote on the most important improvement areas.
6. **Commit to actions (10 min)** — Convert top themes into concrete, owned action items with due dates.
7. **Close (5 min)** — Appreciate contributions, confirm where action items will be tracked.

---

## Tracking Improvements

- Add action items to the project backlog or issues with clear owners and timelines.
- Review outstanding actions at the weekly PM sync.
- Mark items `Done` once verified — avoid silently dropping them.

---

## Closing the Loop

- When an action item results in a process improvement, update the relevant doc in `docs/` and note the change in the retrospective record.
- Use the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template to propose doc updates.

---

## Continuous Improvement Culture

- Measure the impact of action items where possible (e.g., cycle time, defect rate).
- Celebrate improvements — even small wins build momentum.
- Prefer small, iterative changes over large overhauls.
- If the same issue appears in three consecutive retros, escalate it as a risk.
