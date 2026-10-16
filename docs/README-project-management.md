# OctoAcme Project Management Docs

This README provides a concise overview of OctoAcme's project management processes and links to the full process documents in the docs/ folder.

OctoAcme runs projects with an iterative, evidence-driven lifecycle. Initiation focuses on validating the problem, defining stakeholders and success metrics, and producing a Project One-pager to guide decisions. Planning breaks approved initiatives into a prioritized backlog, clarifies acceptance criteria and the Definition of Done, estimates scope, and maps releases and milestones so the team shares a clear delivery plan. Execution is organized around short increments with a Git-centric workflow and explicit pull request conventions to keep changes small, reviewable, and tested before merge.

Day-to-day delivery is supported by a regular team rhythm: daily standups for progress and blockers, weekly delivery syncs for progress and risks, and demos at the end of each sprint or milestone. Work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and PRs are expected to reference issues, include acceptance criteria, run CI and linting, and require approvals per team policy. The PM and PdM maintain alignment through weekly syncs while stakeholders receive monthly updates and escalations follow a leveled path from team → PM → Product Lead → Sponsor.

Quality is embedded into each stage: developers write unit and integration tests, critical flows have end-to-end smoke tests, CI enforces automated checks and security scanning, and manual QA is used when necessary. Releases follow a checklist (pre-release checks, staged deployment to staging, smoke tests, and post-deploy verifications) with rollback and incident playbooks documented for safe recovery. Retrospectives capture learnings into tracked action items that are reviewed and prioritized to enable continuous improvement.

Links to full process documents (in-repo):
- [Overview — Project Management](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

Usage
- Place or keep this README in the docs/ folder as docs/README-project-management.md
- Update the links when new process documents are added

