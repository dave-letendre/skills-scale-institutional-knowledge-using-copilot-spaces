# OctoAcme Project Management Docs

This repository contains the OctoAcme project management process documents. These guides help teams execute projects consistently, communicate effectively, and continuously improve delivery practices.

## Overview of OctoAcme Project Management Processes

OctoAcme operates a structured, lifecycle-based project management approach that emphasizes customer value, iterative delivery, and clear ownership. The framework spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business need and align stakeholders around a lightweight Project One-pager that captures the problem statement, success metrics, timeline, and resource needs. Once approved by sponsors, projects move into planning, where work is broken into shippable increments, prioritized with acceptance criteria, estimated, and mapped to milestones. This deliberate sequencing ensures that only well-defined, stakeholder-aligned work enters the delivery pipeline.

Execution at OctoAcme is managed through a consistent rhythm of daily standups, weekly delivery syncs, and sprint-based iterations using project boards with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests follow a lightweight discipline: small changesets (≤400 lines), automated CI/CD tests and linting, and at least one approval before merging. Quality is enforced through unit tests, integration tests, end-to-end smoke tests for critical flows, and security scanning in CI pipelines. The team also establishes a **Definition of Done** during planning to clarify what "complete" means, and uses dashboards and metrics (velocity, burndown, error rates, latency) to track progress and surface risks early. Three-tier blocker escalation—team triage → PM escalation → sponsor involvement—ensures that obstacles are surfaced quickly and resolved at the appropriate level.

OctoAcme's organizational structure centers on three core roles: **Project Managers** coordinate schedules, risks, and cross-team communication; **Product Managers** define outcomes, prioritize the backlog, and measure success; and **Developers** implement features, collaborate on design, and propose technical mitigations. This clear ownership model is reinforced by weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates. Communication is structured around templates for status updates, risk registers, and incident playbooks, with a single source of truth (project README or release documentation) maintained in the repository.

Release and continuous improvement close the loop. Pre-release gates include passing CI/security scans, drafted release notes, rollback plans, and smoke tests. After deployment, the team conducts post-release verification and announces changes to stakeholders. Following each sprint, release, or incident, teams hold timeboxed retrospectives (45–75 minutes) to capture what went well, identify improvements, and prioritize 2–3 actionable items with clear owners and due dates. This blameless, improvement-focused culture ensures that processes evolve based on lived experience, and lessons learned feed back into the living documentation—making OctoAcme's processes searchable, versioned, and continuously refined.

## Process Documents

Navigate to the relevant process guide for your current project phase:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, key artifacts, and lifecycle
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize new work, align stakeholders, and create a lightweight plan
- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and prioritized backlog
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, team rhythm, quality standards, and blocker escalation
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases to production with pre-release checks, deployment checklists, and rollback plans
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks, dependencies, and stakeholder updates
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Define typical roles (Developers, Product Managers, Project Managers) and responsibilities

## How to Use These Docs

- **New team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand core principles and roles
- **Starting a project**: Follow the [Initiation Guide](octoacme-project-initiation.md) and [Planning Guide](octoacme-project-planning.md)
- **In flight**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) for day-to-day guidance
- **Preparing to ship**: Review [Release & Deployment Guide](octoacme-release-and-deployment.md) for pre-release and deployment checklists
- **After delivery**: Hold a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Keeping These Docs Updated

- Keep each process doc up to date as practices evolve
- Link new or revised docs from this README
- Use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose additions or improvements
- Review and refine during retrospectives
