# OctoAcme Project Management Docs

Welcome to OctoAcme's project management documentation hub. This directory contains comprehensive guidance for running projects at OctoAcme, from initiation through retrospectives.

## Our Approach

OctoAcme follows a customer-first, iterative delivery model with clear ownership and data-informed decisions. We prioritize psychological safety and continuous improvement. All team members have equal access to processes, decisions, and rationale, enabling consistent, repeatable project execution and reducing single-person dependency risk.

## Project Lifecycle

Our projects follow these stages:

1. **Initiation** — Validate business need and align stakeholders with a Project One-pager that documents problem statements, success metrics, and resource needs
2. **Planning** — Break work into shippable increments with prioritized backlogs, acceptance criteria, and release timelines
3. **Execution** — Build, test, review, and iterate through daily standups, sprint planning, and CI/CD validation
4. **Release** — Deploy to production with pre-release checklists, smoke tests, rollback procedures, and stakeholder communication
5. **Close & Retrospective** — Capture learnings and drive continuous improvement through blameless retrospectives and action item tracking

## How OctoAcme Executes

OctoAcme emphasizes a team-based rhythm with clear roles and responsibilities:

- **Project Managers** coordinate delivery, manage schedules, risks, and communications while maintaining project documentation and status reporting
- **Product Managers** own the product vision, prioritize the backlog, define success metrics, and validate solutions through user research and data
- **Developers** implement features, write tests, collaborate on design and code reviews, and help identify technical risks
- **QA/Testing** validate quality and acceptance criteria

Teams maintain daily standups (15 min), weekly delivery syncs, and sprint-based workflows using GitHub Projects. Pull requests are kept small (≤400 lines when possible) with automated CI/CD testing, linting, and security scanning. A risk register is maintained throughout the project lifecycle, with blockers escalated through three levels: team-level triage, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. This cadence ensures transparency, prevents surprises, and keeps stakeholders informed.

## Documentation

### Core References

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to roles, artifacts, principles, and lifecycle
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed definitions of core roles (Project Manager, Product Manager, Developers, QA)

### Process Guides

- [Project Initiation](octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning](octoacme-project-planning.md) — Creating prioritized backlogs, estimating scope, defining acceptance criteria, and mapping dependencies
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day delivery, team rhythm, quality assurance, and blocker escalation
- [Release & Deployment](octoacme-release-and-deployment.md) — Standardized release process, deployment checklist, rollback procedures, and incident playbooks
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk identification, lifecycle, assessment, escalation paths, and stakeholder communication templates
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings, running retrospectives, and converting improvements back into documentation

## Quick Start

**New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our principles, roles, and lifecycle.

**Starting a new project?** Follow this workflow:
1. Read [Project Initiation](octoacme-project-initiation.md) and complete the initiation checklist
2. Move into [Project Planning](octoacme-project-planning.md) and create your backlog and release plan
3. Execute using the [Execution & Tracking](octoacme-execution-and-tracking.md) guide
4. Prepare for [Release & Deployment](octoacme-release-and-deployment.md)
5. Complete a [Retrospective](octoacme-retrospective-and-continuous-improvement.md) to capture learnings

**Looking for a specific process?** Use the documentation guide above to find the relevant guide. For role-specific guidance, see [Roles & Personas](octoacme-roles-and-personas.md).

**Managing risk or escalating issues?** Reference [Risk Management & Communication](octoacme-risks-and-communication.md) for risk registers, escalation paths, and stakeholder communication templates.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Manager
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

## Issue Templates

Process improvement and documentation updates are tracked via GitHub Issues. When you identify a gap or improvement opportunity in our process docs, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose changes collaboratively.
