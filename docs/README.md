# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This folder contains the core process guides and templates used to initiate, plan, execute, release, and improve projects at OctoAcme. These living documents are intended to centralize our workflows, clarify roles and responsibilities, and make it easy for new and existing team members to find the right guidance at the right time.

## Project management processes (brief overview)
OctoAcme runs projects with an iterative, customer-first mindset supported by a simple lifecycle: Initiation → Planning → Execution → Release → Close & Retrospective. Each initiative starts with a lightweight one‑pager to validate the problem, success metrics, and stakeholders; planning breaks approved work into prioritized backlog items with acceptance criteria and estimates; execution uses a project board and disciplined pull‑request practices to move increments to done; releases follow checklists and smoke tests; and retrospectives capture improvements that feed back into the backlog.

Workflows emphasize structured planning and lightweight governance. New ideas begin with project initiation and stakeholder alignment, move into sprintable planning with clear Definition of Done, and are executed using a shared project board (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests should be small when possible, include links to the originating issue and acceptance criteria, and pass CI (including tests and security scans) before requesting review. Escalation paths and risk management are documented so blockers can be surfaced and resolved quickly.

Roles and communication are explicit: core personas include Product Managers (define outcomes), Project Managers (coordinate delivery and risks), Developers (implement and test), QA (validate acceptance criteria), and Stakeholders (provide guidance and approvals). The team cadence includes daily standups, weekly PM/PdM syncs, regular demos at the end of sprints or milestones, and monthly stakeholder updates. Quality is enforced through unit and integration tests, end‑to‑end smoke tests for critical flows, CI security scanning, and manual QA for acceptance when needed. Release and rollback playbooks are used to reduce production risk.

## Documentation (core process guides)
- [Project Management Overview](./octoacme-project-management-overview.md) — High-level approach, principles, roles, and artifacts.
- [Project Initiation](./octoacme-project-initiation.md) — One‑pager, stakeholder alignment, decision gate for planning.
- [Project Planning](./octoacme-project-planning.md) — Backlog creation, estimates, Definition of Done, release planning.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Team rhythm, PR workflow, tracking, and escalation.
- [Risks & Communication](./octoacme-risks-and-communication.md) — Risk register, stakeholder communication templates, and escalation.
- [Release & Deployment](./octoacme-release-and-deployment.md) — Release types, pre‑release checks, deployment and rollback playbook.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and tracking improvements.
- [Roles & Personas](./octoacme-roles-and-personas.md) — Role definitions and responsibilities.

## Quick Start
- New to OctoAcme? Start with the Project Management Overview.
- Starting a new project? Complete the Project Initiation one‑pager.
- Planning delivery? Follow Project Planning and create backlog items with acceptance criteria.
- In active delivery? Use Execution & Tracking and the project board to drive work to Done.
- Preparing a release? Follow Release & Deployment and run staging smoke tests.

## Contributing
These documents are living artifacts. To propose updates or additions, open an issue using the "Add Content to Project Management Process Docs" template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). Suggested changes should reference the related document and include a short rationale and acceptance criteria.
