# OctoAcme Project Management Documentation

## Overview
OctoAcme's project management approach emphasizes iterative delivery, clear ownership, and measurable outcomes. We prioritize customer value, break work into small, testable increments, and keep communication and risk management visible. These documents centralize the processes, roles, and templates the team uses to initiate, plan, execute, release, and improve work.

## Quick Start
New to OctoAcme? Start here:
- Project Management Overview: docs/octoacme-project-management-overview.md

Recommended onboarding steps:
1. Read the Project Management Overview to understand roles and lifecycle.
2. Read Project Initiation if you are proposing a new initiative.
3. Read Project Planning when moving from approval into delivery.
4. Consult Execution & Tracking during implementation and day-to-day work.

## Process Lifecycle (summary)

### Project Initiation
Purpose: Validate and authorize work, align stakeholders, and create a lightweight plan.
Key artifacts: Project One-pager, stakeholder list, initial timeline and risk list.
See: docs/octoacme-project-initiation.md

### Project Planning
Purpose: Turn an approved initiative into an actionable plan and prioritized backlog.
Activities: kickoff, backlog creation, estimation, Definition of Done, release planning.
See: docs/octoacme-project-planning.md

### Execution & Tracking
Purpose: Manage day-to-day execution and track progress toward milestones.
Practices: project board columns (Backlog → Done), small PRs, CI checks, daily standups, weekly delivery syncs, and reporting (velocity, burndown).
See: docs/octoacme-execution-and-tracking.md

### Risks & Communication
Purpose: Identify, assess, mitigate, and communicate risks and dependencies.
Artifacts: Risk register, communication templates, escalation paths.
See: docs/octoacme-risks-and-communication.md

### Release & Deployment
Purpose: Standardize production releases to reduce risk and improve observability.
Includes: pre-release checks, deployment checklist, rollback and incident playbook, release notes template.
See: docs/octoacme-release-and-deployment.md

### Retrospective & Continuous Improvement
Purpose: Capture learnings and convert them into actionable improvements.
Practices: timeboxed retrospectives, prioritized action items tracked as issues, measuring impact of improvements.
See: docs/octoacme-retrospective-and-continuous-improvement.md

## Key Roles
Understand core responsibilities and expectations for the delivery team.
- Project Manager (PM)
- Product Manager (PdM)
- Developers
- QA/Testing
- Stakeholders
See: docs/octoacme-roles-and-personas.md

## Documentation Index (links)
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

## Quick Reference / FAQs
Q: Where do I start when proposing a new project?
A: Use the Project Initiation guide and fill the Project One-pager. Then create an issue using the "Add Content to Project Management Process Docs" template if you need doc updates.

Q: How are risks tracked?
A: Maintain a Risk Register (see Risk Management doc) and review it in weekly PM syncs.

Q: What goes in PR descriptions?
A: Link the related issue, include acceptance criteria, and ensure CI/linting passes before requesting review (see Execution & Tracking).

Q: How do I request a documentation update?
A: Use the issue template at .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Contribution & Review
- Proposed doc changes should be opened as pull requests with links to related issues.
- Use the issue template for process doc updates so changes are reviewed and tracked.

<!-- End of OctoAcme Project Management Documentation -->
