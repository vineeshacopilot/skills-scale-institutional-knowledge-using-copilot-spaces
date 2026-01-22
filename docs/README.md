# OctoAcme Project Management Documentation

Welcome to the entry point for OctoAcme’s project management practices. This directory centralizes the processes, workflows, quality practices, and role definitions that guide how we plan, build, release, and learn from projects. Use these docs to onboard quickly, align your team, and access patterns for consistent delivery.

OctoAcme runs projects with a clear, iterative lifecycle that begins with a lightweight initiation step to surface the problem, objectives, stakeholders, and success criteria. Approved initiatives move into planning where work is decomposed into prioritized backlog items with acceptance criteria, estimates, dependencies, and a release plan. Planning produces a shared Definition of Done and a risk register used to track mitigations and owners.

During execution we follow a visible project board flow (Backlog → Ready → In Progress → In Review → QA → Done), a disciplined PR process (small PRs, issue links and acceptance criteria in PR descriptions, CI checks, required reviews), and a regular cadence of standups, delivery syncs, and demos to validate progress. Releases are handled with standard pre-release checks, automated pipelines where possible, staging smoke tests, post-deploy verification, and a rollback/incident playbook. After each milestone or incident we run a retrospective that produces a small set of prioritized action items tracked to closure.

Roles are explicit: Project Managers coordinate delivery, schedule and manage risks; Product Managers own outcomes and backlog prioritization; Developers implement and test; QA validates acceptance; stakeholders provide approvals. Quality assurance is embedded throughout via unit/integration/e2e tests, CI-enforced security scanning and linting, manual QA where needed, a Definition of Done, and post-release verification. These practices aim to increase predictability, reduce single-person dependencies, and foster continuous improvement.

## Contents — Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)  
- [Project Initiation Guide](octoacme-project-initiation.md)  
- [Project Planning](octoacme-project-planning.md)  
- [Execution & Tracking](octoacme-execution-and-tracking.md)  
- [Risk Management & Communication](octoacme-risks-and-communication.md)  
- [Release & Deployment](octoacme-release-and-deployment.md)  
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)  
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to propose changes or add new docs

To propose updates or add a new process document, use the issue template: “Add Content to Project Management Process Docs” (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). Link new content to the relevant process doc and include acceptance criteria.

## Purpose and scope

- Centralize OctoAcme’s project delivery practices in one searchable, versioned place.
- Accelerate onboarding, reduce knowledge silos, and make processes discoverable.
- Provide a common reference for project phases, artifacts, roles, communications, and quality checks.
