# OctoAcme Project Management Docs

This folder contains the OctoAcme project management process documents. The README below provides a comprehensive summary of our approach and direct links to each document for easy discovery.

## Overview of OctoAcme Project Management Processes

OctoAcme operates through a structured, customer-first approach that emphasizes iterative delivery, clear ownership, and continuous learning. The organization follows a five-phase lifecycle with defined workflows, roles, and communication cadences to ensure projects deliver value efficiently while maintaining quality and team alignment.

### Five-Phase Lifecycle

1. **Initiation**: Capture project intent with a one-pager charter, align stakeholders on goals and constraints, and decide go/no-go for planning. Establishes the problem statement, high-level timeline, and key stakeholders.

2. **Planning**: Create a prioritized backlog with acceptance criteria, estimate scope and effort, identify dependencies and technical risks, and build a release plan with milestones. Defines the scope, resources, and roadmap for execution.

3. **Execution & Tracking**: Deliver work in small, testable increments using GitHub Projects boards, pull requests with CI checks, and code reviews. Teams conduct daily standups (15 min) and weekly delivery syncs to surface blockers, progress, and flagged risks. Quality is embedded through automated testing, security scanning, and manual QA where needed.

4. **Release & Deployment**: Execute pre-release checks, automated deployments to staging and production, post-deploy verification, and stakeholder announcements. Ensures quality gates are met before customers receive new features or fixes.

5. **Retrospective & Continuous Improvement**: Team conducts retrospectives to capture learnings, action items, and process improvements. Improvements are prioritized and tracked in the backlog for future sprints.

### Core Principles

- **Customer-first**: Prioritize customer value and usability in all decisions.
- **Iterative delivery**: Deliver small, testable increments to gather feedback early.
- **Clear ownership**: Each project has a named Project Manager and Product Lead responsible for delivery and direction.
- **Data-informed decisions**: Measure impact and iterate based on evidence and metrics.
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives.

### Core Roles & Responsibilities

**Developers** design, build, test, and deliver software components. They collaborate on design and code reviews, assist in estimation and planning, and help identify technical risks and mitigation strategies.

**Product Managers** define the product vision, problem statements, and success metrics. They prioritize the roadmap and backlog based on customer and business value, collaborate with engineering on trade-offs, and validate solutions through user research.

**Project Managers** coordinate all delivery activities including schedules, risks, and dependencies. They facilitate key meetings (kickoffs, planning, retrospectives), maintain project documentation, and ensure stakeholder alignment through regular status updates and escalations.

### Communication Cadence

- **Weekly sync** between PM + Product Manager to align on priorities, blockers, and risks
- **Twice-weekly standups** for delivery team (or as agreed per project) to track progress and escalate blockers
- **Monthly stakeholder updates** with status, metrics, and decisions needed
- **Ad-hoc escalations** as needed for critical issues or decisions

### Key Workflows & Practices

**Project Boards**: Use GitHub Projects with columns: Backlog → Ready → In Progress → In Review → QA → Done

**Pull Requests**: Keep PRs small (≤400 lines when possible), include issue links and acceptance criteria in descriptions, require automated tests/linting to pass in CI, and need at least one approval before merging.

**Quality & Testing**: Unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, security scanning in CI, and manual QA for feature acceptance when needed.

**Risk Management**: Maintain a Risk Register tracking identified risks by impact, likelihood, ownership, mitigation plan, and status. Review and update weekly during delivery syncs.

**Status Tracking**: Monitor velocity, burndown, and success metrics defined in project charters. Use dashboards to track key signals (errors, latency, usage, test coverage).

---

## Documents

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, principles, core roles, key artifacts, and project lifecycle.

- **[Project Initiation Guide](octoacme-project-initiation.md)** — How to start a new project: problem statement, stakeholder alignment, timeline, and go/no-go decisions.

- **[Project Planning](octoacme-project-planning.md)** — Building the backlog, estimation, identifying dependencies and risks, and creating the release plan.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution: team rhythm, workflows, pull request standards, quality practices, metrics, and blocker escalation.

- **[Risks & Communication](octoacme-risks-and-communication.md)** — Risk identification and management, stakeholder communication templates, and escalation paths.

- **[Release & Deployment](octoacme-release-and-deployment.md)** — Pre-release checks, deployment procedures, verification, and post-release communication.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running retrospectives, capturing learnings, and driving ongoing process improvements.

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed role definitions for Developers, Product Managers, and Project Managers, including responsibilities, goals, and typical communications.

---

## How to Use These Docs

**New team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) and your [Roles & Personas](octoacme-roles-and-personas.md) document to understand the organization's approach and your responsibilities.

**Starting a new project**: Follow [Project Initiation](octoacme-project-initiation.md) to establish charter and stakeholder alignment, then [Project Planning](octoacme-project-planning.md) to build your roadmap and backlog.

**During execution**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day workflows and [Risks & Communication](octoacme-risks-and-communication.md) for managing risks and keeping stakeholders informed.

**At release time**: Use [Release & Deployment](octoacme-release-and-deployment.md) to ensure quality gates and communication.

**After project close**: Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture learnings and improve future projects.

---

## Feedback & Updates

These documents represent our current best practices and are living artifacts. If you notice gaps, inconsistencies, or opportunities for improvement, please:

- Open an issue or discussion in the repository
- Propose edits via pull request
- Share feedback in retrospectives or team syncs

We improve these processes continuously based on team feedback and project outcomes.
