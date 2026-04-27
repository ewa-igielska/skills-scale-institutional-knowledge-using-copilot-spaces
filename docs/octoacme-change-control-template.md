# OctoAcme — Change Control Process & Template

## Purpose
Provide a lightweight, consistent process for evaluating, approving, and tracking changes to scope, timeline, or resources after a project has entered execution. Change control protects project commitments while giving teams a clear path to adapt when circumstances evolve.

## When to use
Raise a change request (CR) whenever a proposed change could affect:
- Agreed project **scope** (features added, removed, or significantly altered)
- **Timeline** or milestone dates
- **Budget** or resource allocation
- **Architecture** or technology choices already agreed upon
- **External dependencies** or third-party integrations

Minor clarifications that do not affect any of the above do not require a CR — use normal PR/issue tracking instead.

---

## Process Overview

```
1. Identify change need
        ↓
2. Raise a Change Request (CR) using the template below
        ↓
3. Impact assessment (PM + Tech Lead, ≤ 2 business days for standard CRs)
        ↓
4. Review & approval (PM + Sponsor for scope/timeline changes; Tech Lead for architecture)
        ↓
5. Decision recorded in Decision Log (see [Decision Log Template](octoacme-decision-log-template.md))
        ↓
6. Communicate decision to affected stakeholders
        ↓
7. Update project plan, backlog, and docs to reflect approved change
```

---

## Change Request Template

```
## Change Request — [Short Title]

| Field                | Value                                         |
|----------------------|-----------------------------------------------|
| **CR ID**            | CR-XXX                                        |
| **Date raised**      | YYYY-MM-DD                                    |
| **Raised by**        | [Name / role]                                 |
| **Status**           | Draft / Under Review / Approved / Rejected / Deferred |
| **Priority**         | Low / Medium / High / Critical                |
| **Related issue/PR** | #<number> or N/A                              |

### Description of change
_What is being changed and why? Be specific._

### Scope impact
_What work is added, removed, or modified? List affected features, components, or milestones._

### Timeline impact
_Will any milestone or release date shift? By how much?_

### Resource / budget impact
_Is additional effort or spend required? Provide a rough estimate._

### Risk assessment
_What new risks does this change introduce? How will they be mitigated?_

### Options considered
1. **Implement as described** — impact summary above  
2. **Alternative approach** — [describe]  
3. **Defer / do not implement** — impact of not making the change  

### Recommendation
_What does the PM / Tech Lead recommend and why?_

### Decision
_To be filled in by approver(s)_

- Decision: Approved / Rejected / Deferred  
- Approved by: [Name], [Date]  
- Conditions or caveats: _if any_
```

---

## Change Control Checklist

Use this checklist to ensure all steps are completed for each CR.

- [ ] CR raised and assigned a unique ID (CR-XXX)
- [ ] CR shared with PM and Tech Lead within 1 business day of identification
- [ ] Impact assessment completed (scope, timeline, resources, risks)
- [ ] Options and recommendation documented in the CR
- [ ] Review meeting or async review completed (≤ 2 business days)
- [ ] Decision recorded and CR status updated
- [ ] Decision log updated (see [Decision Log Template](octoacme-decision-log-template.md))
- [ ] Project plan and backlog updated to reflect the approved change
- [ ] Stakeholders notified of decision and downstream impact
- [ ] Affected documentation updated (e.g., planning doc, release plan)

---

## Escalation
If a CR cannot be resolved within the standard 2-business-day window — due to cross-team impact, budget implications, or strategic trade-offs — escalate to the Sponsor following the escalation path in [Risks and Communication](octoacme-risks-and-communication.md).

---

## CR Log

> Track all change requests for the project in this table.

| CR ID  | Date raised | Title                        | Status       | Approved by       |
|--------|-------------|------------------------------|--------------|-------------------|
| CR-001 | YYYY-MM-DD  | Example: Add export feature  | Approved     | PM, Sponsor       |
| CR-002 | YYYY-MM-DD  | Example: Defer API v2 work   | Deferred     | PM                |
