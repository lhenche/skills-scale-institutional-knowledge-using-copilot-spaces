# OctoAcme Project Processes

This folder collects OctoAcme's project management processes, guiding teams from idea to delivery and continuous improvement. OctoAcme follows a simple lifecycle: Initiation (validate the business need and produce a Project One-pager), Planning (break work into shippable increments with a prioritized backlog, estimates, and a Definition of Done), Execution (iterative development, code review, QA, and tracking), Release (pre-release checks, smoke tests, and observability), and Close & Retrospective (capture learnings and follow up on action items). Core artifacts — one-pagers, roadmaps, backlogs, risk registers, and retrospectives — are maintained in the repo as the single sources of truth.

Day-to-day workflows are Git-centric and lightweight. Teams manage work on a project board with columns such as Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are intentionally small, link back to the issue and acceptance criteria, and run automated CI checks and security scans before review. PRs require at least one approval and passing CI before merge. There are checklists and templates for execution and releases to ensure deployments are repeatable and auditable.

Roles and responsibilities are explicit so ownership and decision-making are clear. The Project Manager (PM) coordinates delivery, schedules, risks, and communications; the Product Manager (PdM) defines outcomes, prioritizes the backlog, and measures success; developers implement and test features; QA validates acceptance criteria and test coverage; stakeholders provide input and approvals. Personas and role descriptions are included to standardize handoffs and expectations across the team.

Communication and quality assurance are tied to cadence and risk management. Regular rhythms include daily standups to surface blockers, weekly delivery syncs for progress and risks, weekly PM–PdM alignment, and monthly stakeholder updates. QA practices require unit and integration tests, end-to-end smoke tests for critical flows, CI-based security scanning, and manual QA where needed. A simple risk register is maintained and reviewed regularly; escalation paths and incident templates ensure predictable, blameless responses to production issues.

Index of process documents in this folder:
- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-risks-and-communication.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md

How to use these docs:
- Keep the Project One-pager and release notes updated in each project repo.
- Use the issue template `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to suggest updates.
- If you want Copilot Spaces to use a process doc as context, add a copy into `.copilot/` per the project guidance.
