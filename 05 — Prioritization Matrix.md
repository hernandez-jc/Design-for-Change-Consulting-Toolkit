# 05 — Prioritization Matrix

This page converts the barriers, constraints, risks, and dependencies recorded in **[04 — Barriers and Constraints](docs/04-barriers-and-constraints.md)** into a short list of practical improvement priorities.

Its purpose is to select a manageable number of actions for the 10-day roadmap. The goal is not to solve every issue, but to identify the improvements with the greatest practical value within the project’s constraints.

---

## Purpose

The Prioritization Matrix helps the project team:

- Compare possible improvements using the same criteria.
- Separate quick wins from foundational improvements.
- Avoid committing to work that cannot be completed or meaningfully advanced in 10 days.
- Select actions that support learner adoption, administrator usability, content quality, and organizational change.
- Create a clear basis for the 10-day roadmap.

Use the barriers log, constraints log, risks log, and dependencies log from the previous page as the input for this matrix.

---

## How to use this page

1. List the most important barriers or improvement opportunities.
2. Describe each proposed action in practical terms.
3. Score each action for impact, effort, risk, and urgency.
4. Calculate a priority score.
5. Assign an action type.
6. Select only the actions that can realistically be started or completed within 10 working days.
7. Carry the selected actions into the **[06 — 10-Day Roadmap](docs/06-10-day-roadmap.md)**.

---

## Prioritization criteria

Use the same four criteria defined in the project charter.

| Criterion | Question | Scale |
|---|---|---|
| **Impact** | How much will this improve learner experience, adoption, usability, content quality, or business value? | 1–5 |
| **Effort** | How much time, skill, coordination, or technical work is required? | 1–5 |
| **Risk** | How significant is the risk if this issue is not addressed, or if the change is implemented poorly? | 1–5 |
| **Urgency** | How soon does this need to be addressed? | 1–5 |

### Scoring guide

| Score | Impact | Effort | Risk | Urgency |
|---:|---|---|---|---|
| 1 | Very low | Very high | Very low | Not urgent |
| 2 | Low | High | Low | Low urgency |
| 3 | Moderate | Moderate | Moderate | Moderate urgency |
| 4 | High | Low | High | High urgency |
| 5 | Very high | Very low | Very high | Immediate |

For **Effort**, a lower score means less effort is required. A lower effort score makes an action more suitable for a short roadmap.

---

## Priority score

Use this simple calculation:

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

The score is a decision aid, not a replacement for judgment. A high score should still be reviewed against constraints, dependencies, and the project objective.

---

## Prioritization matrix

Complete one row for each proposed improvement.

| ID | Related barrier | Proposed action | Assessment area | Impact (1–5) | Effort (1–5) | Risk (1–5) | Urgency (1–5) | Priority score | Action type |
|---|---|---|---|---:|---:|---:|---:|---:|---|
| P-01 | B-01 |  |  |  |  |  |  |  | Quick win / Foundational / Deferred / Out of scope |
| P-02 | B-02 |  |  |  |  |  |  |  | Quick win / Foundational / Deferred / Out of scope |
| P-03 | B-03 |  |  |  |  |  |  |  | Quick win / Foundational / Deferred / Out of scope |
| P-04 | B-04 |  |  |  |  |  |  |  | Quick win / Foundational / Deferred / Out of scope |

---

## Action types

Use these categories consistently with the Learning Checkup Scorecard.

| Action type | Meaning | Roadmap suitability |
|---|---|---|
| **Quick win** | High practical value with relatively low effort and manageable risk. | Suitable for the 10-day roadmap. |
| **Foundational improvement** | Important for long-term adaptability, quality, or governance, but requires more coordination. | Include only if it can be scoped into a manageable first step. |
| **Deferred item** | A valid issue that should be addressed in a later improvement cycle. | Record it, but do not include it in the 10-day roadmap. |
| **Out-of-scope item** | Requires a separate project, budget, decision, or specialist input. | Escalate or document for future consideration. |

---

## Selection rules

Select actions for the 10-day roadmap only if they meet these conditions:

- The action supports a confirmed business goal or learning outcome.
- The action addresses a documented barrier or improvement need.
- The action is feasible within the identified constraints.
- The action has a clear owner.
- The action has a defined deliverable.
- Dependencies are known or can be managed.
- Success can be observed or measured in a simple way.
- The action does not require a separate budget, major technical change, or full content redevelopment.

A practical 10-day roadmap should usually include:

- One to three quick wins.
- Optional: one foundational improvement that can be started with a limited first step.
- No more actions than the available team capacity can support.

---

## Example prioritization

This example is illustrative only. Replace it with findings from the organization’s own discovery and scorecard.

| ID | Related barrier | Proposed action | Assessment area | Impact | Effort | Risk | Urgency | Priority score | Action type |
|---|---|---|---|---:|---:|---:|---:|---:|---|
| P-01 | Learners cannot find role-relevant learning | Improve course category names and add a short “Where to start” guide | Learners and audiences | 4 | 2 | 3 | 4 | 15 | Quick win |
| P-02 | Priority videos are not captioned | Add captions and transcripts to the three most-used videos | Accessibility and inclusion | 5 | 3 | 4 | 4 | 16 | Quick win |
| P-03 | Reports are not used consistently | Create a simple reporting guide for managers | Data and reporting | 3 | 2 | 2 | 3 | 12 | Quick win |
| P-04 | Content ownership is unclear | Define content owners and review dates for priority courses | Governance and change readiness | 4 | 3 | 4 | 3 | 14 | Foundational |
| P-05 | HR data is managed manually | Integrate HR and Moodle user data | Integrations and interoperability | 5 | 5 | 4 | 3 | 12 | Out of scope |

In this example, P-01, P-02, P-03, and a limited first step of P-04 could be considered for the 10-day roadmap. P-05 would be documented as out of scope for this cycle.

---

## Review checklist

Before creating the roadmap, confirm that:

- [ ] Each proposed action is linked to a documented barrier.
- [ ] Each action supports a business goal or learning outcome.
- [ ] Impact, effort, risk, and urgency have been scored.
- [ ] Priority scores have been calculated consistently.
- [ ] Constraints, risks, and dependencies have been considered.
- [ ] The proposed actions are feasible within 10 working days.
- [ ] Each selected action has a potential owner and deliverable.
- [ ] Deferred and out-of-scope items are documented for future review.

---

## Next page

Continue to the action plan:

**[06 — 10-Day Roadmap](docs/06-10-day-roadmap.md)**
```
