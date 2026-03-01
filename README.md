# HAAG Progress Tracking System - Master Readme

## Human-Augmented Analytics Group (HAAG)

### Overview

This repository documents the design, implementation, and operational workflow of the **HAAG Progress Tracking System**, a lightweight, scalable framework for monitoring researcher contributions, team progress, and publication readiness across distributed computational research teams.

It integrates existing research workflows (Slack, GitHub, weekly reports) with structured advisor evaluations and automated notifications to provide **transparent, fair, and timely visibility into project performance**.

---

## Repository Structure

admin-project-tracking/
│
├── README.md
├── weekly_reports_history/
│   ├── README.md
│   └── different_versions_of_reports/
│       ├── Example_semester1_report_redacted.pdf
│       ├── Example_semester2_report_redacted.pdf
│       ├── Example_semester3_report_redacted.pdf
│       └── Example_semester4_report_nochange_redacted.pdf
│
├── weekly_reports_advisors_survey/
│   └── README.md
│
├── github_progress_bot/
│   └── README.md
│
├── website_usage/
│   └── README.md
│
└── future_work_and_initiatives/
    ├── README.md
    ├── blocker_escalation_protocol_initiative.md
    └── weekly_reporting-workflow_clarification.md

---

## Folder Summaries

### 1. `weekly_reports_history`
Contains historical weekly reports submitted by student researchers. Includes the `different_versions_of_reports` folder with example reports from multiple semesters.

### 2. `weekly_reports_advisors_survey`
Documents the structure and usage of weekly advisor surveys, including submission process, evaluation fields, and automated notifications.

### 3. `github_progress_bot`
Houses the automated progress tracking bot, which monitors GitHub milestones and issues, providing dashboards and Slack notifications for leadership and project managers.

### 4. `website_usage`
Contains resources and documentation related to website usage metrics, monitoring workflows, and operational dashboards.

### 5. `future_work_and_initiatives`
Stores ongoing and proposed initiatives to improve operational workflows. Currently includes:
- **Structured Blocker Escalation Protocol**
- **Weekly Reporting Workflow Clarification**

New initiatives may be added collaboratively with students and HAAG team members.

---

## System Components

1. **Weekly Reports and Advisor Surveys**  
   Handles submission of weekly student reports and structured advisor evaluations. Provides automated Slack notifications to highlight team status and blockers.

2. **Progress Bot and GitHub Issue Tracking**  
   Automates monitoring of research progression via GitHub milestones and issues, providing dashboards and Slack notifications for both leadership and project managers.

---

## Roles and Responsibilities

| Role               | Responsibility                                                                                       |
| ------------------ | ---------------------------------------------------------------------------------------------------- |
| Student            | Submit weekly report and update assigned GitHub issues                                               |
| Advisor            | Review reports and submit weekly evaluation                                                          |
| Project Manager    | Track individual team progress, map tasks to code, and define roadmaps with Computational Advisors |
| Slack Bot          | Summarize reports                                                                                    |
| HAAG Leadership    | Maintain high-level view via dashboard, allocate resources, and intervene                            |
| System             | Send automated notifications                                                                         |

---

## Progress Evaluation Model

### Individual Contribution Evaluation

* Good
* Needs Improvement
* Poor

### Team Progress Evaluation

* On Track
* Needs Improvement
* Blocked

This dual-layer evaluation provides both individual and team-level visibility.

---

## Outcomes and Benefits

* Improved visibility and continuous progress tracking
* Standardized reporting and structured advisor feedback
* Early detection of blockers
* Fair and objective evaluation across teams
* Administrative efficiency through integration into existing workflows

---

## Future Work

* LLM-based automated report summaries
* Real-time dashboards
* GitHub activity integration
* Automated compliance tracking
* Cross-project performance analytics

---

## Authors

Human-Augmented Analytics Group (HAAG)  
Georgia Institute of Technology  

Contributors: HAAG Researchers, Advisors, and Leadership

---

## License

This project is licensed for research and academic use.

---
