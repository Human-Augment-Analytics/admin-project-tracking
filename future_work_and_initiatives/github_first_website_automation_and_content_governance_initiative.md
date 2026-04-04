# GitHub-First Website Automation and Content Governance Initiative

## Purpose

This initiative proposes a GitHub-first procedure for keeping the HAAG public website current while reducing the amount of manual maintenance required from admins.

The main idea is that project-level information should be structured and maintained inside GitHub repositories, while the Georgia Tech WordPress website should act as a lightweight portal that points people to the right projects, publications, events, and stable program information.

This initiative also addresses a second gap: HAAG needs a clearer procedure for community engagement content such as seminars, events, and community-facing announcements. Those items should be submitted in a structured way, approved lightly by admins, and published with as much automation as possible.

---

## Organizational Context

The current HAAG website includes a mix of project pages, program pages, seminar posts, event pages, role-specific pages, and historical attempts at organizing projects by unit or domain.

Across these iterations, the same problems have repeated:

* project information becomes stale when it must be updated in both GitHub and WordPress
* dedicated website maintenance roles are hard to sustain
* researchers are not incentivized to maintain separate website pages
* event and seminar updates do not have a standard submission procedure
* some stable pages remain important, but they are mixed together with content that changes too often

At the same time, HAAG is already using GitHub for research coordination and progress visibility. This creates an opportunity to move public-facing maintenance closer to the workflows researchers already use.

This initiative also overlaps with related work on high-level project summaries and GitHub-based update visibility. The goal here is to focus on the middle procedural layer: what should be required at the project level, what belongs on the website, and how community-facing content should move from request to publication.

---

## Problem Statement

HAAG currently lacks a sustainable website procedure that:

1. keeps project information current without requiring duplicate WordPress maintenance
2. allows events, seminars, and community content to be submitted through a consistent workflow
3. distinguishes between frequently changing content and stable website-owned information
4. uses GitHub and automation to reduce admin burden over time

Without a clearer procedure, public information will continue to decay because it depends on parallel manual updates and roles that are difficult to sustain.

---

## Core Proposal

This initiative proposes three connected changes.

### 1. Standardize Project-Level GitHub Structure

Each active project repository should include a required public-facing `README` structure with:

* project title
* short summary
* status
* maintainer or lead
* unit or program, if applicable
* tags or research areas
* recent update date
* links to outputs, publications, or demos when available

Instead of asking projects to maintain a separate website page, HAAG would link to or summarize this repository information from WordPress.

### 2. Create a Community Content Submission Procedure

Any faculty member, computational advisor, or researcher who wants to advertise an event, seminar, or blog-style community item should submit it in a structured format.

Ideally, this would happen through GitHub using issue templates, pull requests, or another standardized intake mechanism.

The proposer should own:

* event details
* logistics
* materials
* follow-up recap information, if needed

Admins should primarily own:

* approval
* scope check
* publication consistency

### 3. Clarify Which Information Belongs on the Website

The website should retain ownership of stable, curated information such as:

* front page messaging
* program pages
* contact pathways
* publications summaries
* selected highlights

Project-specific technical and frequently changing information should remain in GitHub.

---

## Observations from Initial Review

Initial review suggests the following:

1. Historical website pages captured useful information but did not establish a repeatable maintenance procedure.
2. Several page types were created successfully once, but not sustained over time.
3. Project pages are especially vulnerable to duplication because the same information often already exists in GitHub.
4. Community engagement content, especially seminars and events, needs a clearer request-to-publication workflow.
5. Publications may be one of the best candidates for a GitHub-assisted update process, especially if closed projects are required to add publication links in their repositories.
6. A future automation layer could reduce manual work significantly, but only if the repository structure is standardized first.

---

## Proposed Workflow

### Project Visibility Workflow

1. Project lead updates repository `README` using the required structure.
2. Project lead submits a GitHub-based website intake request.
3. Admin reviews completeness and public suitability.
4. If approved, the project is linked from a WordPress hub page or generated summary.
5. Ongoing updates happen in GitHub, not in duplicate WordPress text.
6. When the project closes, the lead adds publication or final output links.
7. Closed projects feed publications and archive pathways.

### Community Event and Seminar Workflow

1. Proposer submits an event or seminar request using a standard template.
2. Admin reviews whether the event fits scope and whether required details are present.
3. If approved, the proposer handles setup and materials.
4. Admin or automation publishes the item to website channels.
5. Post-event materials are added and the item is archived when no longer active.

### Stable Information Workflow

1. Admin or program lead identifies needed changes to stable content.
2. They determine whether the content should live in WordPress or point to GitHub instead.
3. Stable pages are updated only when needed and reviewed on a semester cadence.

---

## Working Hypothesis

If HAAG standardizes project repository structure, routes project and event updates through GitHub-based procedures, and limits WordPress to a portal and stable-information layer, then the website will remain more current with less admin effort and less duplicate work for researchers.

---

## Pilot Design

The initiative can be piloted in three short phases.

**Phase 1: Discovery and Template Definition**

* identify required fields for project repository `README` files
* define the minimum metadata needed for public project visibility
* define a standard submission template for seminars, events, and community content
* identify which current website pages are stable versus duplication-heavy

**Phase 2: Small Pilot**

* pilot the GitHub project intake process with a small set of active projects
* pilot the event and seminar submission process with one or two items
* test whether admins can approve and publish with less manual rewriting

**Phase 3: Automation Exploration**

* test whether GitHub Actions or export scripts can generate project summaries
* test whether publication updates can be partially automated from project closure metadata
* test whether approved community items can feed website or social channels in a reusable way

---

## Measurement Criteria

The initiative can be evaluated using a combination of operational and qualitative measures.

1. Project documentation completeness
   * percentage of active projects with required `README` structure
   * percentage of public project links pointing to current repositories

2. Website freshness
   * number of stale project pages removed or replaced
   * percentage of public projects whose displayed status matches repository status

3. Admin effort
   * estimated monthly time spent on website maintenance
   * number of updates that require duplicate manual WordPress writing

4. Community engagement process clarity
   * turnaround time from event request to publication
   * number of incomplete submissions returned for revision

5. Researcher and admin feedback
   * whether project leads feel the process fits their existing workflow
   * whether admins feel the burden shifts from rewriting to approval

---

## Evaluation Criteria

The initiative will be considered directionally effective if:

* more active projects are publicly visible through current GitHub repositories
* project updates no longer require routine duplicate WordPress editing
* event and seminar publication follows a repeatable submission-and-approval procedure
* admins report lower ongoing maintenance burden
* stable pages become easier to audit and keep accurate

---

## Scope Boundaries

This initiative does not:

* require an immediate full rebuild of the HAAG website
* require every possible automation feature to be implemented at once
* replace related work on high-level project dashboards or broader summary systems

This initiative does:

* define a practical website maintenance procedure
* propose required project-level GitHub structure
* propose a workflow for seminars, events, and other community content
* identify where automation should be introduced over time

---

## Stakeholders

Primary Audience: HAAG admins and website stewards  
Secondary Audience: Project leads, researchers, faculty, and computational advisors submitting public-facing content  
Tertiary Audience: HAAG leadership and collaborators working on GitHub-based visibility systems
