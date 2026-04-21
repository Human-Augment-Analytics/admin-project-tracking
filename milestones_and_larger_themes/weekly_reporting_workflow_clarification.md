# Milestones and Larger Themes Weekly Reporting Workflow Clarification Initiative

## Purpose

This initiative defines a standardized, end-to-end weekly reporting procedure for the **Milestones and Larger Themes** workflow in HAAG.

The objective is to ensure that weekly updates do not only report activity, but also provide clear, comparable visibility into:

* Milestone execution status
* Cross-project strategic alignment through larger themes
* Early signals of delivery risk

This clarification document is designed to improve consistency and accountability without introducing a heavy reporting burden or requiring new platforms.

---

## Organizational Context

HAAG already uses a mixed tracking environment:

* Weekly updates and coordination in Slack project channels
* GitHub issues and milestones for technical execution
* Progress visibility from the Progress-Tracker ecosystem and dashboard
* PM synthesis for leadership-level oversight

As documented in the repository:

* [Progress Bot and GitHub Issue Tracking](../github_progress_bot/README.md)
* [Future Work and Initiatives](../future_work_and_initiatives/README.md)
* [Milestones and Larger Themes](README.md)

The current challenge is not a lack of tools. The challenge is the lack of one consolidated procedural reference connecting these tools into a single weekly accountability chain for milestone- and theme-level progress.

---

## Problem Statement

Current weekly reporting often captures meaningful work, but strategic clarity is inconsistent across teams.

The core procedural gaps are:

1. Milestone status language is interpreted differently across projects.
2. Milestone updates are not always explicitly linked to larger themes.
3. Completion claims do not always include concise evidence.
4. At-risk milestones are identified, but escalation timing is inconsistent.
5. PMs must manually reconcile updates from multiple channels to infer strategic trajectory.

Without a clear procedure, teams can appear active while critical milestones drift, and leadership visibility becomes more reactive than proactive.

---

## Initiative Scope

This initiative focuses on **workflow clarification**, not platform redesign.

This initiative does:

* Standardize the minimum required fields for milestone and theme reporting
* Define weekly and monthly review cadence
* Clarify role ownership for update quality, escalation, and strategic review
* Connect weekly updates to GitHub milestone/issue artifacts and Progress-Tracker visibility

This initiative does not:

* Replace existing Slack or GitHub workflows
* Require every team to adopt new tooling
* Change advisor survey structure
* Redefine semester-level research goals

---

## Operational Environment (Current State)

Based on documentation review and initiative discovery:

1. Researchers execute tasks and share weekly progress in project channels.
2. PMs and advisors interpret progress through a mix of updates, issues, and milestone activity.
3. GitHub provides objective task and milestone status signals.
4. Progress bot systems can surface milestone/issue visibility at aggregate level.

The process works, but interpretation quality depends heavily on PM experience and manual synthesis.

---

## Clarified Weekly Workflow (Target State)

### Step 1: Milestone Update Preparation (Researcher / Owner)

For each active milestone, the assigned owner provides:

* Milestone title
* Status (`Not Started`, `In Progress`, `At Risk`, `Complete`)
* Due date (or target week)
* Dependency note (if applicable)
* One-sentence progress update
* Evidence link if `Complete` (issue, PR, artifact, demo note, or equivalent)
* Linked larger theme

### Step 2: Weekly Submission (Project Channel)

Weekly updates are submitted in the team’s standard reporting channel and must include milestone-level fields in concise format.

### Step 3: PM Quality Review

PM checks each milestone update for:

* Clear owner and due date
* Valid status label
* Evidence present for completed milestones
* Explicit theme mapping
* Escalation signal for any `At Risk` milestone

PM then marks each item as:

* Accepted
* Needs Clarification
* Escalated

### Step 4: GitHub Alignment Check

PM performs a lightweight consistency check between reported milestone status and GitHub artifacts:

* Milestone and linked issues reflect reported progress direction
* Blocked/at-risk claims have corresponding dependency context
* Completed claims have traceable technical evidence

This check is intended to reduce ambiguity, not to create extra administrative overhead.

### Step 5: Weekly PM Summary

PM posts a brief synthesis containing:

* Milestones completed
* Milestones at risk
* Required interventions
* Theme movement summary (which themes advanced, stalled, or need replanning)

### Step 6: Monthly Theme Review

Once per month, PM + advisor perform a theme-level review:

* Are current milestones still aligned with the stated larger themes?
* Which themes are progressing vs stagnating?
* Which roadmap adjustments are needed?

Monthly output: one short roadmap adjustment note per project.

---

## Standard Definitions

### Milestone Status Definitions

* **Not Started:** Milestone has scope and owner, but no active execution has begun.
* **In Progress:** Execution is actively underway with no current risk signal.
* **At Risk:** Delivery confidence is reduced due to blocker, dependency, scope issue, or pace risk.
* **Complete:** Milestone completion criteria are met and evidence is recorded.

### Larger Theme Definition

A larger theme is a strategic focus area that connects multiple milestones over time and explains the broader purpose of weekly execution.

---

## Required Reporting Fields (Minimum Schema)

Each active milestone update must include:

1. `milestone_title`
2. `owner`
3. `status`
4. `due_date_or_target_window`
5. `dependency_or_risk_note` (optional if none)
6. `progress_summary` (1-2 sentences)
7. `completion_evidence` (required if `Complete`)
8. `linked_larger_theme`
9. `next_action`

This minimum schema keeps reporting short while preserving decision-useful clarity.

---

## Escalation Rules

Escalation is triggered when any of the following occur:

1. A milestone remains `At Risk` across two consecutive weekly cycles.
2. A milestone due window is likely to be missed without scope adjustment.
3. A critical dependency owner is unresolved.
4. Milestone status cannot be validated after PM clarification request.

Escalation output must include:

* Responsible owner
* Blocking condition
* Resolution plan
* Updated expected delivery window

---

## Roles and Responsibilities

| Role | Responsibility |
| --- | --- |
| Student Researcher / Milestone Owner | Provide concise milestone updates and evidence when complete |
| Project Manager | Validate quality, enforce schema, reconcile with GitHub signals, escalate risk |
| Computational Advisor | Validate theme-level relevance and strategic fit |
| HAAG Leadership | Review monthly strategic visibility and support high-impact interventions |
| System (Progress Bot / Dashboard) | Provide aggregate milestone and issue visibility to complement weekly reporting |

---

## GitHub Resource Integration

This workflow explicitly uses existing GitHub tracking resources:

1. **GitHub milestones** as the shared unit for deliverable-level progress.
2. **GitHub issues** as task-level evidence tied to milestone execution.
3. **Progress-Tracker dashboard signals** as cross-project visibility for leadership and PM review.

Reference resource: [Progress-Tracker](https://github.com/Human-Augment-Analytics/Progress-Tracker/)

Local documentation reference: [github_progress_bot/README.md](../github_progress_bot/README.md)

---

## Pilot Design

### Phase 1: Baseline Observation (2 weeks)

* Observe current milestone updates without clarified schema enforcement.
* Record: missing owner fields, ambiguous status labels, missing evidence, unclear theme mapping.

### Phase 2: Protocol Introduction (3 weeks)

* Roll out the required reporting fields and status definitions.
* Apply PM quality review and escalation rules.
* Run weekly milestone synthesis and one monthly theme review.

### Phase 3: Evaluation and Iteration (1 week)

* Compare baseline and post-protocol quality.
* Collect PM and advisor feedback on clarity and overhead.
* Refine template wording and escalation thresholds where needed.

---

## Measurement Criteria

### Data Quality Metrics

* % active milestones with owner and due date
* % milestone updates with valid status labels
* % completed milestones with evidence
* % milestone updates explicitly linked to larger themes

### Workflow Reliability Metrics

* % weekly updates submitted on time
* % at-risk milestones escalated within one cycle
* Average clarification requests per team per week

### Strategic Visibility Metrics

* % projects with completed monthly theme review notes
* PM/advisor clarity score (1-5 scale)
* Leadership confidence in cross-project trajectory (qualitative pulse)

---

## Evaluation Criteria

The initiative will be considered directionally effective if:

1. Milestone update completeness improves materially from baseline.
2. Ambiguous status reporting decreases.
3. At-risk milestones are identified and acted on earlier.
4. Theme-level progress is easier to communicate during PM and leadership review.
5. Teams report improved clarity without reporting fatigue.

---

## Risks and Mitigations

### Risk 1: Overly verbose updates increase burden
Mitigation: enforce concise schema and 1-2 sentence progress summaries.

### Risk 2: Status inflation (`In Progress` overuse)
Mitigation: require due-date context and explicit `next_action` for each active milestone.

### Risk 3: Theme mapping becomes performative
Mitigation: monthly review requires discussion of actual strategic movement and roadmap adjustments.

### Risk 4: PM workload concentration
Mitigation: keep review lightweight, prioritize quality checks for active and at-risk milestones first.

---

## Implementation Artifacts

Recommended artifacts for operationalization:

* One-page milestone update template
* Weekly PM synthesis template
* Monthly theme review template
* Escalation log for recurring at-risk milestones

These artifacts should remain lightweight and reusable across project teams.

---

## Stakeholders

Primary Audience: Project Managers and student researchers  
Secondary Audience: Computational Advisors and mentors  
Tertiary Audience: HAAG Leadership and collaborators

---

## Expected End-of-Term Impact

By end of term, this clarified workflow should produce:

* More consistent milestone reporting across teams
* Earlier detection of schedule and dependency risk
* Better alignment between weekly execution and strategic goals
* Stronger cross-project visibility using existing GitHub-based resources

