# Standard Operating Procedure: Milestones and Larger Themes Workflow Clarification

**Document Type:** Standard Operating Procedure (SOP)  
**Intended Audience:** Project Managers at HAAG  
**Version:** 1.0  
**Date:** April 2026

---

## Purpose

This SOP gives Project Managers a step-by-step process for running milestone-centered weekly reporting in HAAG. The procedure is designed to make milestone status, delivery risk, and strategic alignment easier to interpret across teams. The system does not replace existing reporting channels. Instead, it clarifies how to use existing Slack and GitHub workflows with a shared structure.

---

## Background

HAAG teams already report progress regularly, but reporting quality can vary from team to team. Some updates focus heavily on what individual researchers did without making it clear whether a milestone actually moved forward. In other cases, milestones are mentioned, but the status terms are inconsistent, evidence of completion is weak, or the milestone is not clearly tied to the larger direction of the project.

This procedure addresses that gap by defining milestones as the primary unit of weekly operational reporting and larger themes as the primary unit of monthly strategic review. The goal is to create a workflow where PMs can interpret progress faster, identify risk earlier, and explain project direction more clearly to advisors and leadership.

---

## Key Concepts

### Milestones

Milestones are concrete, time-bounded deliverables that represent meaningful units of project progress. A milestone should be specific enough that a PM can determine whether it is complete, at risk, or still in progress. Milestones should have a clear owner, a due date or target window, and an identifiable completion condition.

Examples:

* complete benchmark comparison for model version 2
* draft methods section for conference submission
* validate data preprocessing pipeline on the full dataset

### Larger Themes

Larger themes are broader strategic directions that connect multiple milestones across a semester or project phase. A theme explains why a set of milestones matters and what longer-term goal those milestones support.

Examples:

* publication readiness
* model reliability and evaluation
* data pipeline stabilization

### Core Principle

Weekly reporting should answer two questions:

1. Did a milestone move?
2. If so, did that movement advance a larger theme?

The procedure is meant to keep reporting focused on progress quality and direction, not just activity volume.

---

## Tools and Operational Context

This procedure assumes the team already uses the following:

* Slack project channels for weekly communication
* GitHub issues and milestones for technical coordination, where applicable
* Existing PM review or team sync cadence

No new tool is required. The PM uses the current reporting channel and any existing GitHub artifacts to validate milestone movement and completion evidence.

---

## Roles and Responsibilities

| Role | Responsibility |
| --- | --- |
| Project Manager | Primary operator of the procedure; validates updates, requests clarification, tracks risk, and runs monthly theme review |
| Student Researcher / Milestone Owner | Submits concise milestone progress information and flags blockers early |
| Computational Advisor | Reviews larger-theme alignment and supports roadmap adjustments during periodic review |
| HAAG Leadership | Benefits from clearer milestone visibility and can intervene when recurring risk becomes visible |

The PM is the main audience and enforcement point for this SOP.

---

## Required Reporting Fields

Every active milestone update must include the following minimum fields:

1. `milestone_title`
2. `owner`
3. `status`
4. `due_date_or_target_window`
5. `progress_summary`
6. `linked_larger_theme`
7. `next_action`

The following field is required only when applicable:

* `dependency_or_risk_note`

The following field is required for completed work:

* `completion_evidence`

These fields keep updates brief while ensuring the PM has enough information to make a judgment without relying on outside assumptions.

---

## Standard Status Definitions

Use these exact status definitions:

* **Not Started**: Milestone is defined and assigned, but work has not begun.
* **In Progress**: Work is actively moving and there is no immediate delivery risk.
* **At Risk**: The milestone may miss its target due to blocker, dependency, pacing issue, or scope uncertainty.
* **Complete**: The milestone meets its completion condition and supporting evidence is available.

PMs should enforce these definitions consistently across all active milestones.

---

## Procedure

### Phase 1: Initial Setup

**Estimated time:** 30 to 45 minutes for setup, plus one team walkthrough if needed

#### Step 1: Identify Active Larger Themes

Meet with the lead researcher and/or computational advisor to identify the current strategic themes for the project.

Each theme should:

* describe a meaningful strategic direction
* be broad enough to include multiple milestones
* be understandable to someone outside the immediate task context

Aim for 2 to 4 active themes for one project phase.

#### Step 2: Identify or Review Active Milestones

For each project, list the active milestones that will be tracked in weekly reporting.

Each milestone must have:

* a clear name
* an owner
* a due date or target time window
* a completion condition
* one linked larger theme

If a milestone cannot be linked to a larger theme, the PM should ask whether the milestone is actually necessary or whether the theme framework needs revision.

#### Step 3: Communicate the Reporting Standard

Share the required reporting fields and status definitions with the team.

Make clear that:

* weekly reporting is milestone-centered
* each milestone must link to one larger theme
* completed milestones must include evidence
* `At Risk` is a useful warning signal, not a negative label

Researchers should understand that the PM is not asking for longer reports. The goal is higher clarity with minimal added writing.

#### Step 4: Establish Review Cadence

Confirm the following cadence:

* weekly milestone update review by the PM
* monthly larger-theme review with the PM and advisor

This cadence should be integrated into the team's existing meeting structure where possible.

---

### Phase 2: Weekly Milestone Reporting

#### Step 1: Researcher or Owner Prepares Update

For each active milestone, the owner prepares a brief update using the required fields.

The update must communicate:

* what moved
* what status the milestone is in now
* what happens next
* whether there is any risk or dependency concern

#### Step 2: Update Is Submitted in Existing Channel

The update is posted in the team's normal weekly reporting location, typically the Slack project channel.

The PM should not require a separate tool, duplicate form, or parallel reporting document unless the team already uses one for the same purpose.

#### Step 3: PM Reviews Update Quality

The PM checks whether the milestone update:

* includes all required fields
* uses the standard status labels correctly
* links the milestone to a valid larger theme
* provides evidence if the milestone is marked complete
* clearly states the next action

If the update is incomplete or ambiguous, the PM marks it as needing clarification and follows up in the same weekly cycle.

#### Step 4: PM Validates Against Existing Work Evidence

Where GitHub issues, pull requests, documents, or demos exist, the PM performs a lightweight validation check to confirm that the reported milestone movement is supported by actual work artifacts.

This step is not meant to create extra surveillance. Its purpose is to keep milestone reporting reliable and comparable.

#### Step 5: PM Produces Weekly Milestone Summary

At the end of weekly review, the PM should be able to summarize:

* which milestones advanced
* which milestones completed
* which milestones are at risk
* which larger themes moved forward
* what intervention is needed before the next cycle

This summary can be used in team syncs, advisor check-ins, or higher-level project oversight.

---

### Phase 3: Escalation and Intervention

Escalation should occur when any of the following happen:

1. A milestone remains `At Risk` for two consecutive weekly cycles.
2. A milestone is likely to miss its due window without scope or timeline adjustment.
3. A critical dependency is unresolved and blocking forward movement.
4. The PM cannot validate milestone status after requesting clarification.

When escalation is needed, the PM records:

* the milestone name
* the owner
* the blocking condition
* the immediate next step
* who is responsible for resolving the issue
* the updated expected delivery timeline

Escalation should happen inside the team's existing decision-making structure. The PM does not need to invent a separate bureaucracy for this.

---

### Phase 4: Monthly Larger-Theme Review

At least once per month, the PM and computational advisor review the larger themes for the project.

This review should answer:

1. Which themes advanced this month?
2. Which milestones contributed to that movement?
3. Which themes are stalled or under-supported?
4. Are current milestones still aligned with the right strategic direction?
5. Does the roadmap need reprioritization, re-scoping, or added support?

The output should be one short note per project documenting any strategic adjustment.

This is the point where the procedure moves beyond task tracking and becomes a strategic planning tool.

---

## Integration with HAAG's Existing Structure

This procedure is designed to fit HAAG's current operations:

* Slack remains the communication layer for weekly reporting.
* GitHub can remain the evidence layer for milestone progress where technical artifacts already exist.
* PMs continue acting as synthesis points rather than asking researchers to produce long standalone reports.
* Advisors can participate at the larger-theme review stage without needing to manage weekly operations directly.

The procedure integrates through existing cadence rather than by requiring a new platform or new recurring meeting.

---

## Enforcement Mechanism

The procedure is enforced through four lightweight checks:

1. required reporting fields
2. fixed status definitions
3. PM clarification requests within the same cycle
4. explicit escalation rules for recurring risk

This keeps the process realistic. Enforcement happens through the PM's normal operational role, not through a separate compliance system.

---

## Success Metrics

Track the following indicators over time:

| Metric | What It Measures |
| --- | --- |
| Milestones with clear owner and due date | Completeness of core reporting fields |
| Milestones using valid status labels | Consistency of status language |
| Completed milestones with evidence | Reliability of completion claims |
| Milestones linked to larger themes | Strategic alignment visibility |
| At-risk milestones escalated within one cycle | Responsiveness to delivery risk |
| Monthly theme review completed | Continuity of strategic oversight |

These measures are intended to show whether the procedure improves clarity without creating unnecessary overhead.

---

## Quick Reference: PM Checklist

### Initial Setup

- [ ] Define active larger themes
- [ ] Define active milestones and assign owners
- [ ] Link every milestone to one larger theme
- [ ] Share required reporting fields and status definitions
- [ ] Confirm weekly and monthly review cadence

### Every Week

- [ ] Review milestone updates for completeness
- [ ] Validate status label usage
- [ ] Request clarification where needed
- [ ] Check evidence for completed milestones
- [ ] Identify and record at-risk milestones
- [ ] Summarize milestone and theme movement

### Every Month

- [ ] Review larger themes with advisor
- [ ] Check whether milestones are still strategically aligned
- [ ] Document roadmap adjustments
- [ ] Reassess whether any theme is under-supported or stalled

---

## Final Note

This SOP is intentionally lightweight. Its value comes from making weekly progress easier to interpret and easier to act on. If used consistently, it gives HAAG a clearer view of whether projects are not just active, but moving in the right direction.
