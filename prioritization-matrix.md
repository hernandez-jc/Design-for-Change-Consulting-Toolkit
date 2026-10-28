# prioritization-matrix.csv

Save the following content as:

```text
templates/prioritization-matrix.csv
```

Use UTF-8 encoding and comma-separated values.

This template converts the barriers recorded in `barriers-log.csv` into prioritized improvement actions for the 10-day roadmap.

```csv
Priority ID,Related barrier ID,Related assessment area,Proposed action,Expected benefit,Impact (1-5),Effort (1-5),Risk (1-5),Urgency (1-5),Priority score,Action type,Proposed owner,Required access or approval,Dependencies,Success measure,Include in 10-day roadmap,Notes
P-01,B-01,"[Add assessment area]","[Describe the proposed action]","[Describe the expected benefit]",4,2,3,4,15,Quick win,"[Add owner]","[Add access or approval needed]","[Add dependency]",,Yes / No,"[Add notes]"
P-02,B-02,"[Add assessment area]","[Describe the proposed action]","[Describe the expected benefit]",4,2,3,4,15,Quick win,"[Add owner]","[Add access or approval needed]","[Add dependency]",,Yes / No,"[Add notes]"
P-03,B-03,"[Add assessment area]","[Describe the proposed action]","[Describe the expected benefit]",4,2,3,4,15,Quick win,"[Add owner]","[Add access or approval needed]","[Add dependency]",,Yes / No,"[Add notes]"
P-04,B-04,"[Add assessment area]","[Describe the proposed action]","[Describe the expected benefit]",4,2,3,4,15,Foundational,"[Add owner]","[Add access or approval needed]","[Add dependency]",,Yes / No,"[Add notes]"
```

## Prioritization criteria

| Criterion | Question | Scale |
|---|---|---|
| Impact | How much will this improve learner experience, adoption, usability, content quality, or business value? | 1–5 |
| Effort | How much time, skill, coordination, or technical work is required? | 1–5 |
| Risk | How significant is the risk if this issue is not addressed, or if the change is implemented poorly? | 1–5 |
| Urgency | How soon does this need to be addressed? | 1–5 |

## Priority score

Use this calculation:

```text
Priority score = Impact + (6 - Effort) + Risk + Urgency
```

The maximum possible score is 20.

| Priority score | Suggested interpretation |
|---:|---|
| 16–20 | High priority: consider for the 10-day roadmap |
| 11–15 | Medium priority: consider if capacity and dependencies allow |
| 6–10 | Lower priority: defer to a later cycle |
| 5 or below | Do not prioritize in this cycle |

## Action types

| Action type | Meaning | Roadmap suitability |
|---|---|---|
| Quick win | High practical value with relatively low effort and manageable risk. | Suitable for the 10-day roadmap. |
| Foundational | Important for long-term adaptability, quality, or governance, but requires more coordination. | Include only if it can be scoped into a manageable first step. |
| Deferred | A valid issue that should be addressed in a later improvement cycle. | Record it, but do not include it in the 10-day roadmap. |
| Out of scope | Requires a separate project, decision, budget, or specialist input. | Escalate or document for future consideration. |

## Field guidance

| Field | What to enter |
|---|---|
| **Priority ID** | A unique identifier, such as `P-01`, `P-02`, or `P-03`. |
| **Related barrier ID** | The barrier ID from `barriers-log.csv`, such as `B-01`. |
| **Related assessment area** | The area from the Learning Checkup Scorecard. |
| **Proposed action** | A short, practical description of the improvement. |
| **Expected benefit** | The expected improvement for learners, administrators, content quality, or business goals. |
| **Impact** | 1–5, where 5 means very high impact. |
| **Effort** | 1–5, where 1 means very low effort and 5 means very high effort. |
| **Risk** | 1–5, where 5 means very high risk. |
| **Urgency** | 1–5, where 5 means immediate. |
| **Priority score** | Calculated using the formula above. |
| **Action type** | Quick win, Foundational, Deferred, or Out of scope. |
| **Proposed owner** | The person or role accountable for the action. |
| **Required access or approval** | Moodle access, report access, content approval, stakeholder approval, or other requirement. |
| **Dependencies** | People, systems, approvals, or events that may affect delivery. |
| **Success measure** | A simple way to confirm whether the action achieved its intended purpose. |
| **Include in 10-day roadmap** | Yes or No. |
| **Notes** | Additional context, assumptions, or follow-up actions. |

## Example row

```csv
P-05,B-05,Learners and audiences,"Improve course category names and add a short Where to start guide","Learners can more easily find role-relevant learning",4,2,3,4,15,Quick win,Moodle Learning Designer,"Moodle administrator access","Confirmation of priority learner groups","Learners can locate priority learning more easily",Yes,"Focus on the highest-priority learner groups only"
```

## Selection checklist

Before creating the 10-day roadmap, confirm that each selected action:

- [ ] Is linked to a documented barrier.
- [ ] Supports a business goal or learning outcome.
- [ ] Has a calculated priority score.
- [ ] Has a proposed owner.
- [ ] Has a defined deliverable or success measure.
- [ ] Fits within the project constraints.
- [ ] Has manageable dependencies.
- [ ] Can be completed or meaningfully advanced within 10 working days.

## Next template

Continue to:

**[10-day-roadmap.csv](templates/10-day-roadmap.csv)**
