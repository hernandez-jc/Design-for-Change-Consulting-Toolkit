# barriers-log.csv

Save the following content as:

```text
templates/barriers-log.csv
```

Use UTF-8 encoding and comma-separated values.

This template records the most important barriers identified in the Learning Checkup Scorecard. It focuses on barriers affecting learner adoption, administrator usability, content quality, and organizational change.

```csv
Barrier ID,Barrier category,Barrier description,Affected users,Related assessment area,Evidence or example,Business or learning impact,Related constraint ID,Related risk ID,Related dependency ID,Initial action type,Owner,Notes
B-01,Learner adoption,"[Describe the barrier]",Learners / Managers / Teachers,"[Add assessment area]","[Add evidence or example]","[Describe impact on adoption, learning, or business goals]",,,,"Quick win / Foundational / Deferred / Out of scope","[Add owner]","[Add notes]"
B-02,Administrator usability,"[Describe the barrier]",Moodle administrators / Teachers,"[Add assessment area]","[Add evidence or example]","[Describe impact on administration, maintenance, or reporting]",,,,"Quick win / Foundational / Deferred / Out of scope","[Add owner]","[Add notes]"
B-03,Content quality,"[Describe the barrier]",Learners / Teachers / L&D team,"[Add assessment area]","[Add evidence or example]","[Describe impact on relevance, clarity, currency, or accessibility]",,,,"Quick win / Foundational / Deferred / Out of scope","[Add owner]","[Add notes]"
B-04,Organizational change,"[Describe the barrier]",Business sponsor / L&D / Administrators / Learners,"[Add assessment area]","[Add evidence or example]","[Describe impact on ownership, maintenance, communication, or adoption]",,,,"Quick win / Foundational / Deferred / Out of scope","[Add owner]","[Add notes]"
```

## Barrier categories

| Category | Core question |
|---|---|
| Learner adoption | What prevents learners from finding, accessing, understanding, or completing learning? |
| Administrator usability | What makes it difficult for administrators or teachers to manage and maintain the Moodle environment? |
| Content quality | What reduces the relevance, clarity, currency, consistency, or accessibility of learning content? |
| Organizational change | What makes it difficult for the organization to sustain or adapt the learning ecosystem? |

## Field guidance

| Field | What to enter |
|---|---|
| **Barrier ID** | A unique identifier, such as `B-01`, `B-02`, or `B-03`. |
| **Barrier category** | Learner adoption, Administrator usability, Content quality, or Organizational change. |
| **Barrier description** | A short, specific description of the barrier. |
| **Affected users** | Learners, managers, teachers, administrators, L&D staff, IT staff, or business sponsors. |
| **Related assessment area** | The area from the Learning Checkup Scorecard where the issue was identified. |
| **Evidence or example** | A report, support request, learner comment, observation, screenshot reference, or other evidence. |
| **Business or learning impact** | The effect on adoption, usability, learning quality, compliance visibility, or business goals. |
| **Related constraint ID** | The constraint from `constraints-log.csv`, if applicable. |
| **Related risk ID** | The risk from `risks-log.csv`, if applicable. |
| **Related dependency ID** | The dependency from `dependencies-log.csv`, if applicable. |
| **Initial action type** | Quick win, Foundational, Deferred, or Out of scope. |
| **Owner** | The person or role best placed to address or validate the barrier. |
| **Notes** | Additional context, assumptions, or follow-up questions. |

## Example row

```csv
B-05,Learner adoption,"Learners cannot easily find role-relevant learning in the course catalogue",Learners / Managers,Learners and audiences,"Learners reported difficulty identifying which courses apply to their role","Learners may miss priority learning, reducing adoption and role readiness",C-01,R-01,D-01,Quick win,Moodle Learning Designer,"Confirm course categories and priority learner groups before proposing changes"
```

## Completion checklist

Before moving to the next template, confirm that:

- [ ] Each barrier has a unique ID.
- [ ] Each barrier is assigned to one category.
- [ ] Affected users are identified.
- [ ] Evidence or an example is recorded.
- [ ] The business or learning impact is described.
- [ ] Related constraints, risks, or dependencies are linked where applicable.
- [ ] An initial action type is recorded.
- [ ] An owner is identified.

## Next template

Continue to:

**[prioritization-matrix.csv](templates/prioritization-matrix.csv)**
