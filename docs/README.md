# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects with a clear, iterative lifecycle that moves work from initiation through planning, execution, release, and continuous improvement. Projects begin with a lightweight validation step—a Project One-pager that defines the problem, SMART objectives, and success metrics—then proceed into planning where the delivery team builds a prioritized backlog, estimates scope, and defines a Definition of Done. Key artifacts (Project One-pager, release plan, backlog items, and a risk register) live in this docs/ folder and serve as the single source of truth for scope, timelines, and decisions.

Workflows emphasize small, testable increments and predictable delivery. The team uses a project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done) and follows a pull-request-driven workflow that favors small PRs with issue links and clear acceptance criteria. CI (tests, linting, and security scans) must pass before review and merging; team policy requires at least one approval. Sprint planning is timeboxed and items must meet the Definition of Done before being pulled into an iteration.

Roles and responsibilities are explicitly defined so ownership and decisions are clear: Product Managers set outcomes and success metrics, Project Managers coordinate delivery and risk, Developers implement and test, QA validates acceptance criteria, and Stakeholders provide inputs and approvals. These persona definitions are intended to be used as prompts for role-specific guidance and help ensure each deliverable (e.g., acceptance criteria, test plans, and release notes) has a clear owner.

Communication and quality assurance are tightly coupled into the cadence and tooling. The team runs daily standups for blockers, a weekly delivery sync for progress and risk review, and demos at the end of sprints or milestones. QA practices include unit and integration tests, smoke tests for critical flows, manual QA when required, and automated security scanning in CI. Risks are tracked in a lightweight register and escalated through a three-level path (team → PM → sponsor) as needed, while retrospectives capture learnings and convert them into tracked action items that feed back into the backlog.

## Quick Start by Role
- Project Managers: Start with octoacme-project-management-overview.md
- Product Managers: See octoacme-project-initiation.md for defining success metrics and the Project One-pager template
- Developers: Reference octoacme-execution-and-tracking.md for sprint workflows and PR guidance
- QA/Testing: See execution-and-tracking and release-and-deployment docs for test and release requirements
- All roles: Review octoacme-roles-and-personas.md to understand responsibilities and communication expectations

## Project Lifecycle (links)
1. Initiation → octoacme-project-initiation.md  
2. Planning → octoacme-project-planning.md  
3. Execution & Tracking → octoacme-execution-and-tracking.md  
4. Release & Deployment → octoacme-release-and-deployment.md  
5. Close & Improve → octoacme-retrospective-and-continuous-improvement.md

## Cross-cutting Concerns
- Risk & Communication → octoacme-risks-and-communication.md  
- Roles & Personas → octoacme-roles-and-personas.md

## How to Use These Docs
- Keep documentation updated as processes evolve.  
- Reference the appropriate doc during each project phase.  
- Use provided templates and checklists to standardize delivery.  
- Propose improvements via the repository's process doc update issues.

**Acknowledgement**  
This README is intended as a central index and quick reference to help team members and new hires find the right process guidance quickly. For detailed guidance, open any linked document in this folder.
