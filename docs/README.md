# OctoAcme Project Management Docs

This set of documents captures how OctoAcme organizes and runs projects to deliver customer value reliably and iteratively. The README below provides a concise overview of core processes, roles, workflows, and links to the detailed process documents in this folder.

OctoAcme follows a lightweight, iterative lifecycle that moves from a focused Project One‑pager and initiation gate into planning, execution, release, and retrospective. Projects are planned into small, shippable backlog items with clear acceptance criteria and a shared Definition of Done. Core artifacts — Project One‑pager, roadmap/release plan, sprint backlog, acceptance criteria, risk register, and retrospective action items — serve as the single sources of truth and guide decisions throughout the project.

Day‑to‑day workflows are board‑driven and built around a disciplined pull‑request process. Teams use a project board with columns such as Backlog → Ready → In Progress → In Review → QA → Done. Pull requests should be small, reference the related issue, include acceptance criteria, and pass automated CI (unit, integration, linting, and security scans) before review. Testing includes unit and integration tests, targeted end‑to‑end smoke tests for critical flows, and manual QA when necessary. Release and deployment follow a checklist-driven pipeline with staging verification, post‑deploy checks, rollback/playbook procedures, and post-release verification.

Roles and personas create clear ownership: Product Managers set outcomes and prioritize work; Project Managers coordinate timelines, risks, and stakeholder communication; Developers implement and test features and participate in reviews; QA/Test owners validate acceptance criteria and maintain test plans; stakeholders provide approvals and sponsorship. Communication cadence includes daily standups, weekly delivery syncs (with demos), weekly PM+PdM alignment, and monthly stakeholder updates. Risks are tracked in a register reviewed at weekly syncs and escalations flow from team triage → PM → Product Lead → Sponsor (security incidents follow the security runbook). Retrospectives convert learnings into prioritized, tracked action items to drive continuous improvement.

## Project Management Docs Index

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution and Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk & Communication](docs/octoacme-risks-and-communication.md)
- [Release and Deployment](docs/octoacme-release-and-deployment.md)
- [Retrospectives & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

How to use these docs

- Keep the Project One‑pager and README updated as the single source of truth for project status.
- Add process-specific artifacts into this docs folder or `.copilot/` to make them available to Copilot Spaces.
- When preparing a release, follow the Release & Deployment checklist and draft release notes using the template in that document.

Related issue: #2