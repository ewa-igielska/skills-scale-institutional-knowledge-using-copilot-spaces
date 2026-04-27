# OctoAcme — Decision Log Template

## Purpose
Capture key decisions and their rationale so that anyone joining the project later can understand *why* a direction was chosen — not just *what* was decided. A living decision log reduces single-person dependency and prevents the same debates from recurring.

## When to use
Create a new entry whenever a significant decision is made, including architecture choices, scope trade-offs, process changes, vendor selections, or go/no-go calls.

---

## How to use

1. Copy the **Decision Entry Template** below for each new decision.
2. Add entries chronologically to the project's decision log (e.g., a `DECISIONS.md` file in the repo root or this file itself).
3. Link to supporting discussion (issue, meeting notes, RFC) wherever possible.
4. Revisit open decisions at weekly PM syncs and close them once implemented.

---

## Decision Entry Template

```
### Decision — [Short Title]

| Field              | Value                                      |
|--------------------|--------------------------------------------|
| **Decision ID**    | DEC-XXX                                    |
| **Date**           | YYYY-MM-DD                                 |
| **Status**         | Proposed / Approved / Superseded / Rejected |
| **Deciders**       | [Names or roles]                           |
| **Related issue**  | #<issue-number> or N/A                     |

#### Context
_What situation or problem prompted this decision? Include relevant constraints or background._

#### Options considered
1. **Option A** — [brief description]  
   - Pros: …  
   - Cons: …  
2. **Option B** — [brief description]  
   - Pros: …  
   - Cons: …  

#### Decision
_State the chosen option and the primary reason(s) for the choice._

#### Consequences
_What will change as a result? Note follow-up tasks, trade-offs accepted, or risks introduced._

#### Follow-up actions
- [ ] Action item (owner, due date)
```

---

## Decision Log Index

> Replace the sample rows below with real decisions for your project.

| ID      | Date       | Title                           | Status    | Deciders          |
|---------|------------|---------------------------------|-----------|-------------------|
| DEC-001 | YYYY-MM-DD | Example: Adopt GitHub Projects  | Approved  | PM, Tech Lead     |
| DEC-002 | YYYY-MM-DD | Example: Defer mobile support   | Approved  | PM, PdM           |

---

## Archiving superseded decisions
When a decision is superseded, do **not** delete the entry. Instead:
1. Update its `Status` to `Superseded`.
2. Add a reference to the new decision (e.g., "Superseded by DEC-005").

This preserves the historical context for onboarding and audits.
