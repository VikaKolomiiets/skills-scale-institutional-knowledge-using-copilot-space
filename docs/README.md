# OctoAcme Project Management Docs

This README serves as a navigation guide for OctoAcme's project management documentation. It is intended to help team members, newcomers, and stakeholders quickly understand our processes and locate the relevant documents they need.

## Process Summary

OctoAcme follows a structured five-phase project lifecycle: **Initiation, Planning, Execution, Release, and Retrospective**. During initiation, teams validate business needs and create a lightweight Project One-pager defining the problem statement, objectives, success metrics, stakeholders, and initial risks. Once approved by the Product Lead and sponsors, the project moves to planning, where work is broken into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. Teams use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to track progress, enforce small pull requests (≤400 lines), require automated CI/CD testing and at least one approval before merging, and maintain quality through unit, integration, and end-to-end smoke tests.

OctoAcme operates with clearly defined roles to ensure accountability and alignment: **Project Managers (PMs)** coordinate delivery, schedules, risks, and communications; **Product Managers (PdMs)** define outcomes, prioritize backlogs, and measure success; **Developers** implement features and collaborate on design and quality; and **QA/Testing** validates acceptance criteria. The team maintains a consistent communication rhythm including daily standups (15 minutes), weekly delivery syncs, PM-PdM alignment meetings, and monthly stakeholder updates. Escalations follow a structured path: team-level triage → PM → Product Lead → Sponsor, with security incidents triggering a separate incident response playbook.

Risk management is embedded throughout the project lifecycle via a Risk Register that tracks ID, description, impact, likelihood, owner, mitigation plans, and status—reviewed weekly during syncs. Quality assurance is comprehensive, encompassing unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, security scanning in CI pipelines, and manual QA for feature acceptance when needed. Before production deployment, teams verify all acceptance criteria are met, passing tests and security scans, and maintain documented rollback and incident playbooks.

OctoAcme emphasizes continuous improvement through structured retrospectives held after each sprint, release, or milestone. These sessions capture what went well, identify improvements, prioritize 2–3 action items with clear owners and due dates, and track outcomes in the project backlog. Release governance is standardized with patch, minor, and major release types, pre-release checklists covering staging verification and smoke tests, and post-deployment announcements to stakeholders. Teams maintain observability through velocity tracking, burndown monitoring, success metrics dashboards, and regular stakeholder status reports—creating a culture grounded in data-informed decisions and psychological safety.

## Documentation

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

---

> **Note:** This README is intended to guide users and newcomers through OctoAcme's project management practices, improving navigability and ensuring consistent usage of the process documentation above.
