# OctoAcme Project Management Framework

Welcome to the OctoAcme Project Management Documentation. This folder contains the complete framework and processes used to plan, execute, and deliver projects at OctoAcme.

## Overview

OctoAcme is a customer-first, iterative project delivery framework designed to:
- Maximize customer value and usability
- Deliver software in small, testable increments
- Maintain clear ownership and accountability
- Make decisions based on data and evidence
- Foster psychological safety and continuous learning

This documentation serves as the single source of truth for how we run projects, manage teams, and communicate progress.

## Core Principles

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments and gather feedback early
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

## Project Lifecycle

OctoAcme projects follow a structured five-phase lifecycle:

Initiation → Planning → Execution → Release → Close & Retrospective


## Process Documents

### 📋 Project Lifecycle Phases

#### 1. [Project Initiation Guide](./octoacme-project-initiation.md)
**When**: Whenever a new project idea or feature proposal is ready to be explored

Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.

Key activities:
- Confirm business need and measurable outcomes
- Identify stakeholders and champions
- Define success criteria and initial timeline
- Complete the Project One-pager
- Make go/no-go decision for planning

#### 2. [Project Planning](./octoacme-project-planning.md)
**When**: After project approval, before execution begins

Turn an approved initiative into an actionable plan and backlog for delivery.

Key activities:
- Conduct project kickoff with stakeholders and delivery team
- Create prioritized backlog with acceptance criteria
- Estimate scope using T-shirt sizing or story points
- Define Definition of Done (DoD)
- Identify dependencies and integration points
- Create release plan and milestone map

#### 3. [Execution & Tracking](./octoacme-execution-and-tracking.md)
**When**: During active project development and delivery

Guidance for managing day-to-day execution and tracking progress toward project milestones.

Key activities:
- Daily standups (15 min) focused on progress, blockers, and dependencies
- Weekly delivery syncs to show progress and flag risks
- Maintain project board with: Backlog, Ready, In Progress, In Review, QA, Done
- Execute pull request workflow with automated testing and code review
- Ensure quality through unit tests, integration tests, and QA
- Monitor key metrics and dashboards

#### 4. [Release & Deployment Guide](./octoacme-release-and-deployment.md)
**When**: Moving features from development to production

Standardize how OctoAcme releases features to production to reduce risk and improve observability.

Key activities:
- Verify all acceptance criteria are met
- Confirm passing CI and security scans
- Prepare release notes and rollback plans
- Execute staged deployment: staging → production
- Perform post-deploy verifications
- Announce release to stakeholders

#### 5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
**When**: After each sprint, release, or important milestone

Capture learnings and convert them into actionable improvements.

Key activities:
- Conduct retrospective session (45–75 minutes)
- Discuss what went well and what could improve
- Create action items with clear owners and timelines
- Track and measure impact of improvements
- Celebrate wins and iterate

### 🎯 Cross-Cutting Concerns

#### [Risk Management & Communication](./octoacme-risks-and-communication.md)
Ongoing throughout all phases

Identify, manage, and communicate risks and dependencies.

Key activities:
- Maintain risk register with ID, description, impact, likelihood, owner, and mitigation
- Review risks at weekly syncs
- Communicate status to stakeholders regularly
- Escalate blockers: Team-level → PM → Product Lead → Sponsor
- Follow incident communication playbooks

#### [Project Management Overview](./octoacme-project-management-overview.md)
Reference guide for the entire framework

Provides a concise introduction to how OctoAcme runs projects, core roles, key artifacts, and communication cadence.

### 👥 Roles & Personas

#### [Roles and Personas](./octoacme-roles-and-personas.md)

Defines typical roles and responsibilities used across OctoAcme projects:

- **Developers**: Design, build, test, and deliver software components
- **Product Managers**: Define what should be built and measure outcomes
- **Project Managers**: Coordinate delivery, manage schedules, risks, and communications
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and business context

## Key Artifacts

Every OctoAcme project should maintain:

- **Project Charter / One-pager**: Problem statement, objectives, success metrics, timeline
- **Roadmap and Release Plan**: High-level priorities and delivery schedule
- **Sprint/Iteration Backlog**: Prioritized, estimated work items with acceptance criteria
- **Risk Register**: Tracked risks, mitigations, and status
- **Definition of Done**: Shared quality standards
- **Release Notes**: Summary of changes and migration steps
- **Retrospective Notes**: Learnings and action items

## Communication Cadence

- **Daily**: 15-minute team standups
- **Weekly**: PM + Product Manager alignment, delivery team standups
- **Weekly/Monthly**: Stakeholder status updates
- **As-needed**: Risk escalations and incident communications

## Getting Started

**New team members**:
1. Start with [Project Management Overview](./octoacme-project-management-overview.md) for context
2. Read [Roles and Personas](./octoacme-roles-and-personas.md) to understand your role
3. Review the phase-specific guide relevant to your current project stage

**Project managers**:
1. Use [Project Initiation Guide](./octoacme-project-initiation.md) to kick off new projects
2. Follow [Project Planning](./octoacme-project-planning.md) to create actionable plans
3. Reference [Risk Management & Communication](./octoacme-risks-and-communication.md) for ongoing management
4. Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings

**Product managers**:
1. Review [Project Management Overview](./octoacme-project-management-overview.md)
2. Lead [Project Initiation Guide](./octoacme-project-initiation.md) activities
3. Define success criteria and acceptance criteria in [Project Planning](./octoacme-project-planning.md)
4. Track metrics outlined in [Execution & Tracking](./octoacme-execution-and-tracking.md)

**Developers**:
1. Understand the [Project Lifecycle](./octoacme-project-management-overview.md)
2. Review [Execution & Tracking](./octoacme-execution-and-tracking.md) for PR and code review workflows
3. Participate in retrospectives per [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Issue Templates

Request updates to these process documents using the standardized issue template: [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

## Contributing to This Framework

Process improvements are encouraged! If you find gaps, ambiguities, or opportunities to enhance these docs:

1. Create an issue using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
2. Describe the gap and proposed improvement
3. Submit a pull request with your changes
4. Have it reviewed by the project management team

## Questions or Feedback?

These documents represent our shared understanding of how we work. Your feedback helps us keep them current and useful. Please reach out or create an issue if you have suggestions!

---

**Last Updated**: 2026-05-08  
**Maintained by**: OctoAcme Project Management Team
