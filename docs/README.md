# OctoAcme Project Management Docs

## Overview

OctoAcme follows a structured lifecycle approach to project management that spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. The process begins with a lightweight initiation phase where teams validate business need, identify stakeholders, and create a Project One-pager defining the problem, goals, and success metrics. Once approved at a decision gate, projects move into detailed planning where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a release plan is established.

Execution at OctoAcme is guided by iterative, team-based workflows supported by daily standups, weekly delivery syncs, and a structured PR process. Teams use project boards (GitHub Projects) with standardized columns to maintain visibility. Pull requests are kept small (≤400 lines where possible) and require at least one approval before merging, with automated CI testing and linting gates. Quality is embedded throughout execution via unit tests, integration tests, smoke tests for critical flows, and security scanning. The organization maintains a risk register updated weekly and escalates blockers through defined channels.

The project management structure defines clear roles and accountability: **Product Managers** own vision and prioritization; **Project Managers** coordinate delivery, schedules, and communications; and **Developers** implement features while collaborating on design and testability. Communication happens through a consistent cadence—weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates—with a single source of truth maintained in the project repository. Finally, OctoAcme emphasizes continuous improvement through post-sprint and post-release retrospectives that capture learnings and drive actionable improvements, closing the loop on team performance and process optimization.

## Quick Links to Process Docs

### Project Lifecycle

- **[Project Management Overview](octoacme-project-management-overview.md)** – High-level introduction to OctoAcme's principles, roles, and key artifacts. Start here for a complete understanding of our approach.

- **[Project Initiation](octoacme-project-initiation.md)** – Steps to validate business need, authorize new work, and confirm stakeholder alignment. Use this when kicking off a new project or feature proposal.

- **[Project Planning](octoacme-project-planning.md)** – Breaking work into shippable increments, estimating scope, and creating release plans. Use this after a project has been approved.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** – Day-to-day execution guidance, team rhythm, PR workflows, quality practices, and blocker escalation. Reference this throughout the project delivery phase.

- **[Release & Deployment](octoacme-release-and-deployment.md)** – Standardized procedures for preparing, deploying, and verifying releases. Use this before shipping features to production.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** – Running effective retrospectives and converting learnings into actionable improvements. Use this at the end of sprints or releases.

### Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** – Managing risks, dependencies, and stakeholder communication throughout the project lifecycle. Reference as needed for risk tracking and escalation.

- **[Roles & Personas](octoacme-roles-and-personas.md)** – Definitions of key project roles (Project Manager, Product Manager, Developer, QA) and their responsibilities. Useful for clarifying expectations and responsibilities.

## Getting Started

**For Project Managers:**
1. Start with [Project Management Overview](octoacme-project-management-overview.md) to understand the full lifecycle
2. Review [Project Initiation](octoacme-project-initiation.md) to learn how to kick off a new project
3. Deep dive into [Project Planning](octoacme-project-planning.md) to create actionable plans
4. Reference [Risk Management & Communication](octoacme-risks-and-communication.md) for ongoing risk and stakeholder management
5. Use [Execution & Tracking](octoacme-execution-and-tracking.md) and [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) throughout delivery

**For Product Managers:**
1. Review [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md)
2. Use [Project Initiation](octoacme-project-initiation.md) to define problem statements and success metrics
3. Reference [Project Planning](octoacme-project-planning.md) for backlog prioritization and acceptance criteria
4. Use [Risk Management & Communication](octoacme-risks-and-communication.md) for stakeholder updates

**For Developers:**
1. Start with [Execution & Tracking](octoacme-execution-and-tracking.md) to understand daily workflows and PR processes
2. Reference [Project Planning](octoacme-project-planning.md) for understanding acceptance criteria and Definition of Done
3. Review [Release & Deployment](octoacme-release-and-deployment.md) before shipping code to production
4. Participate in [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) sessions

**For QA/Testing:**
1. Review [Execution & Tracking](octoacme-execution-and-tracking.md) for quality and testing practices
2. Reference [Project Planning](octoacme-project-planning.md) for test planning and acceptance criteria
3. Use [Release & Deployment](octoacme-release-and-deployment.md) for pre-release verification

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Communication Cadence

- **Daily**: Team standups (15 minutes)
- **Twice weekly**: Delivery team syncs (or as agreed)
- **Weekly**: PM and Product Manager alignment
- **Monthly**: Stakeholder updates
- **Ad hoc**: Risk escalations as needed
