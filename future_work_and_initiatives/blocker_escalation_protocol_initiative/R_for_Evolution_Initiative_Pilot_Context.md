# R for Evolution Initiative (Pilot Context Document)

## Overview

This initiative proposes implementing a **Structured Blocker Escalation Protocol** within the *R for Evolution* team to improve early detection and resolution of blocked work. While weekly reports and advisor check-ins provide visibility into progress, blockers may persist across multiple weeks without structured follow-up.

The proposed experiment introduces a lightweight, standardized method for identifying and responding to blockers within existing weekly reporting workflows. The goal is to reduce stalled work, improve intervention timing, and strengthen overall project momentum.

---

## Hypothesis

If a structured blocker escalation protocol is implemented within the existing weekly reporting system, then blocked tasks will be identified earlier and resolved more quickly, improving overall team progress and reducing task stagnation.

---

## Organizational Context

This initiative is part of the HAAG tracking working group and focuses specifically on the *R for Evolution* project.

Within HAAG, several procedures related to progress tracking are already in place:

- Weekly student report submissions in project Slack channels  
- Advisor review of weekly reports  
- Completion of a weekly advisor check-in survey  
- Slack bot aggregation of weekly reports (R for Evolution)  
- Informal identification and resolution of blockers during meetings  

Although blockers are already reported within weekly submissions, there is currently no standardized mechanism ensuring repeated blockers trigger structured follow-up.

---
## How the Escalation Process Will Work

This protocol does **not** require technical modifications to the existing Slack bot. The bot will continue surfacing blocker sections as part of its weekly summary. Escalation decisions will rely on structured human review by PM or advisor.

### 1. Weekly Blocker Visibility

- Students continue reporting blockers in their weekly reports.
- The Slack bot summarizes and surfaces all reported blockers in the project channel.
- The advisor reviews the weekly summary as part of the existing workflow.

### 2. Repeated Blocker Recognition

After reviewing the weekly summary, the advisor (or designated reviewer i.e. PM) asks:

> Does any blocker appear to be recurring from the previous week?

No automated matching is required. Recognition is based on human judgment and contextual awareness.

### 3. Week 2 Escalation Rule

If a blocker appears to persist into a second consecutive week:

- It must be explicitly discussed in the next team meeting.
- The root cause is clarified.
- A concrete next step or resolution plan is identified.

### 4. Week 3 Intervention

If a blocker persists into a third consecutive week:

- Advisor-level intervention is required.
- Additional support, dependency resolution, or restructuring may be considered.
- A clear action plan is documented.

### 5. Lightweight Tracking (Pilot Phase)

During the pilot period, recurring blockers may be logged manually for evaluation purposes in the project operations log. This tracking is observational and does not introduce additional reporting requirements for students.

---

## Discovery and Information Gathering

To understand current practices, information will be collected through:

- Reviewing past weekly reports in the R for Evolution Slack channel  
- Examining advisor survey responses for references to blockers  
- Observing how blockers are discussed during team meetings  
- Conducting brief structured conversations with the project advisor  
- Reviewing Slack bot summaries to identify recurring stalled tasks  

This process will establish how blockers surface, how frequently they persist, and how long they remain unresolved under the current workflow.

---

## Required Resources

Implementation and evaluation of this initiative will rely on:

- Slack message history from the R for Evolution channel  
- Advisor check-in survey responses  
- Slack bot-generated summaries  
- Advisor input and confirmation of workflow practices  
- Existing documentation of the progress tracking system  

---

## Proposed Validation Strategy

The protocol will be validated by:

- Confirming that the documented workflow accurately reflects actual team practices  
- Comparing blocker resolution timelines before and after implementation  
- Verifying consistent adherence to the escalation steps across multiple weeks  

---
## Validation Observations (Pilot – R for Evolution)

During the pilot phase, full quantitative validation was limited due to the absence of persistent multi-week blockers after implementation. However, several important observations were made.

### Implementation Milestones

- **Week 4:** Introduction of the weekly reports bot, which parsed submissions and posted structured summaries in the project channel  
- **Week 10:** Introduction of the Structured Blocker Escalation Protocol  

### Blocker Trends Over Time

| Week | Number of Blockers |
|------|-------------------|
| 3    | 0                 |
| 4    | 1                 |
| 5    | 3                 |
| 6    | 1                 |
| 7    | 4                 |
| 8    | 3                 |
| 9    | 2                 |
| 10   | 0 *(Protocol Introduced)* |
| 11   | 0                 |
| 12   | 1                 |
| 13   | 3                 |
| 14   | 0                 |

### Key Observations

- Blockers were present and fluctuated in the early and mid-semester period  
- Following improvements in reporting visibility (Week 4) and process clarity, blocker counts showed a general reduction  
- After the introduction of the escalation protocol (Week 10), **no persistent multi-week blockers were observed**, limiting the ability to test escalation triggers directly  

### Interpretation

While the absence of recurring blockers limited direct validation of escalation steps (Week 2 / Week 3), it suggests that:

- Increased visibility and accountability may have contributed to **earlier resolution of issues**  
- Clearer expectations around reporting and communication reduced the likelihood of blockers persisting across weeks  
- The presence of a structured escalation framework may have had a **preventative effect**, even when not explicitly triggered  

### Limitations

- No sufficient instances of multi-week blockers to fully validate escalation behavior  
- Reliance on manual observation rather than structured historical data comparison  
- External factors (process improvements, increased engagement) may have influenced results  

### Conclusion

Although full validation of escalation mechanics was not achieved, the pilot indicates that the introduction of structure, visibility, and accountability mechanisms contributes to smoother workflows and reduced blocker persistence. Further validation is recommended in future iterations with more controlled tracking of blocker recurrence.

---

## Organizational Need

This initiative addresses the need for early, consistent identification and resolution of blockers.

While weekly reporting provides visibility into project progress, delays may persist when blockers are repeatedly reported without structured escalation. The absence of a defined follow-up threshold can lead to extended task stagnation and unclear responsibility for intervention.

The Structured Blocker Escalation Protocol aims to reduce:

- The time a task remains blocked  
- Ambiguity around responsibility for resolution  
- Delayed leadership awareness of stalled work  

---

## Intended Audience

- **Primary:** Advisor of R for Evolution  
- **Secondary:** Student researchers on the team  
- **Tertiary:** HAAG leadership interested in scalable progress tracking mechanisms  
---

## Midterm Report

- [Initiative Reflection](midterm_initiative_reflection.md)
- [Operations Reflection](midterm_operations_reflection.md)

---