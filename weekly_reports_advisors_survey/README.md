# Weekly Reports and Advisor Surveys

## Overview

This document focuses on the submission and evaluation of weekly student reports and advisor surveys within the HAAG Progress Tracking System.

Students submit structured weekly reports documenting:

* Completed work
* Work in progress
* Blockers
* Next steps

Reports are uploaded directly to project-specific Slack channels.

**Benefits:**

* Creates a continuous historical record
* Ensures consistent documentation of progress
* Enables advisors to monitor activity asynchronously

---

## Advisor Weekly Check-In Survey

Advisors submit structured weekly evaluations assessing:

| Field                   | Description                            |
| ----------------------- | -------------------------------------- |
| Advisor Name            | Faculty or project advisor             |
| Lab                     | Associated research lab                |
| Project                 | Project name                           |
| Researcher Contribution | Good / Needs Improvement / Poor        |
| Team Progress           | On Track / Needs Improvement / Blocked |
| Notes                   | Optional qualitative observations      |

This creates standardized evaluation data across all teams.

---

## Automated Slack Notifications

Survey submissions trigger automated Slack notifications:

| Status            | Notification              |
| ----------------- | ------------------------- |
| On Track          | Green checkmark           |
| Needs Improvement | Yellow warning            |
| Blocked           | Alert requiring attention |

This allows leadership to quickly identify teams requiring intervention.

---

## Slack-Integrated Workflow

To eliminate platform fragmentation, HAAG centralized tracking within Slack.

Previous workflow:

* Git → work
* Slack → communication
* Basecamp → reporting

New workflow:

* GitHub → research work
* Slack → reporting, communication, visibility
* Survey → structured evaluation

This removes duplicate reporting effort and improves real-time visibility.

---

## Slack Report Summary Bot

A Slack bot automatically parses weekly reports and generates summaries using pattern matching.

Example extracted summary:

Researcher: Alice  
Completed:  
- Implemented data preprocessing pipeline  

In Progress:  
- Model training optimization  

Blocked:  
- Waiting for dataset access approval  

**Benefits:**

* Reduces advisor review time
* Highlights blockers quickly
* Improves visibility without replacing full report review

---
