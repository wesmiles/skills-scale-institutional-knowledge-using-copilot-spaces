# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation. This folder contains the complete playbook for how OctoAcme manages projects, from initiation through retrospective and continuous improvement.

## About OctoAcme Project Management

OctoAcme follows a structured, customer-centric approach to project management that emphasizes:

- **Customer-first thinking**: Prioritizing customer value and usability in all decisions
- **Iterative delivery**: Shipping small, testable increments frequently
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measuring impact and iterating based on evidence
- **Psychological safety**: Encouraging feedback, learning, and continuous improvement

## OctoAcme Project Management Overview

OctoAcme follows a structured five-phase project lifecycle: **Initiation → Planning → Execution → Release → Close & Retrospective**. The approach is grounded in customer-first principles, iterative delivery, and data-informed decision-making.

### Key Processes & Workflows

**Initiation & Validation**: Projects begin with a lightweight Project One-pager that validates business need, identifies stakeholders, and confirms success metrics before moving to detailed planning. This early gate ensures alignment and authorization before significant resources are invested.

**Planning & Execution**: Once approved, the planning phase breaks work into prioritized backlog items with clear acceptance criteria, estimates scope using T-shirt sizing or story points, and creates a release plan with identified dependencies and risks. Execution follows GitHub Projects workflow (Backlog → Ready → In Progress → In Review → QA → Done) with small pull requests (≤400 lines), required automated testing and linting, and at least one approval before merge.

**Quality & Risk Management**: Quality is embedded throughout the lifecycle via unit tests, integration tests, end-to-end smoke tests, and security scanning in CI, with manual QA applied where needed. The project maintains a Risk Register (ID, Description, Impact/Likelihood, Owner, Mitigation, Status) that is reviewed weekly and escalated through three levels: team-level triage → PM escalation to Product Lead → sponsor-level escalation for business-impacting issues.

**Release & Continuous Improvement**: Releases follow a standardized checklist including pre-release verification, deployment to staging with smoke tests, and post-deploy verification. Major releases include rollback/incident playbooks, documented release notes, and stakeholder announcements. This structured approach—combined with retrospectives that capture learnings and convert them into actionable improvements—enables consistent, repeatable execution while building institutional knowledge and reducing single-person dependencies.

## Project Lifecycle

Every OctoAcme project follows this lifecycle:

1. **Initiation** - Validate the business need, align stakeholders, and decide to proceed
2. **Planning** - Break work into shippable increments and create an actionable plan
3. **Execution** - Build, test, review, and iterate toward milestones
4. **Release** - Deploy to production and verify success
5. **Close & Retrospective** - Capture learnings and drive continuous improvement

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features and collaborate on design and testability
- **QA/Testing**: Validates quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic guidance

## Documentation

### Project Lifecycle Guides

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) - Start here for a high-level introduction
- [OctoAcme Project Initiation Guide](./octoacme-project-initiation.md) - Validate and authorize work
- [OctoAcme Project Planning](./octoacme-project-planning.md) - Turn ideas into actionable plans
- [OctoAcme Execution & Tracking](./octoacme-execution-and-tracking.md) - Manage day-to-day execution
- [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md) - Release features to production safely
- [OctoAcme Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and improve processes

### Cross-cutting Topics

- [OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md) - Manage risks and keep stakeholders informed
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md) - Understand team roles and responsibilities

## How to Use This Documentation

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the guides in order: Initiation → Planning → Execution → Release
- **Need guidance on a specific topic?** Use the cross-cutting topics or refer to the checklist in each phase guide
- **Contributing improvements?** Use the process doc update template to propose changes

## Key Artifacts

Every OctoAcme project should include:

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Risk Register
- Acceptance Criteria & Definition of Done
- Retrospective notes and action items

## Communication Cadence

- **Daily standups** (15 min) - Focus on progress, blockers, and dependencies
- **Weekly sync** - PM + PdM alignment on status and decisions
- **Twice-weekly standups** - Delivery team sync (or as agreed)
- **Monthly stakeholder updates** - Progress and strategic updates
- **Ad-hoc escalations** - As needed for blockers and decisions

## Questions?

Refer to the relevant process document or reach out to your Project Manager or Product Manager for guidance.
