# OctoAcme Project Management Docs

This repository centralizes program and project management process documents for OctoAcme. The following guides are available to help all team members understand our approach, run consistent processes, and onboard efficiently.

---

## Project Management Processes (Overview)

OctoAcme's approach to project management centers on a **structured five-phase lifecycle**: **Initiation → Planning → Execution → Release → Retrospective**. Emphasizing five core principles—customer-first delivery, iterative increments, clear ownership, data-informed decisions, and psychological safety—each project begins with a lightweight project one-pager. This foundational artifact defines the problem statement, identifies key stakeholders, establishes measurable success metrics, and lists initial risks. Once reviewed and approved by leadership, teams move into detailed planning with clear decision gates.

Cross-functional collaboration is central to execution. Teams consist of a **Project Manager** (who coordinates delivery, schedules, and risk management), a **Product Manager** (who owns outcomes, defines requirements, and manages the backlog), **Developers** (who implement and test features), **QA/Testing personnel** (who validate quality and acceptance criteria), and engaged **Stakeholders** (who provide inputs and approvals). Communication is intentional and multilayered: daily or twice-weekly standups focus on progress and blockers; weekly team syncs review delivery status and flagged risks; weekly PM-PdM alignment meetings coordinate planning and prioritization; and monthly stakeholder updates ensure transparency. This rhythm ensures rapid blocker escalation (team → PM → Product Lead → Sponsor) and alignment across technical and business functions.

Delivery workflows leverage **GitHub Projects** with standardized board columns (Backlog → Ready → In Progress → In Review → QA → Done), small pull requests (≤400 lines when possible), and clear acceptance criteria linked to issues. Quality is embedded through unit tests, integration tests, end-to-end smoke tests, automated security scanning in CI, and manual QA for feature acceptance. **Risk management** is supported by a living risk register (tracked with ID, description, impact, likelihood, owner, and mitigation plan) and regular updates during weekly syncs. **Release management** requires thorough pre-release verification (all acceptance criteria met, CI passing, security scans complete, rollback plans documented), staged deployment to a staging environment with smoke tests, and post-deployment verification before production release.

The cycle closes with **retrospectives**, held after each sprint, release, or significant milestone. Teams reflect on what went well, what could be improved, and convert insights into prioritized action items with clear owners and due dates. These improvements feed directly back into future backlogs and processes, creating a continuous improvement culture. This feedback loop accelerates learning, reduces onboarding friction, and strengthens institutional knowledge across OctoAcme.

---

## Docs Index

Navigate to each process document to learn detailed guidance, checklists, templates, and best practices:

- **[Project Management Overview](octoacme-project-management-overview.md)** – High-level introduction to OctoAcme's principles, core roles, key artifacts, and communication cadence.

- **[Project Initiation](octoacme-project-initiation.md)** – Steps to validate a new project, align stakeholders, and create a lightweight project one-pager. Includes the decision gate for moving to planning.

- **[Project Planning](octoacme-project-planning.md)** – How to break work into shippable increments, estimate scope, identify dependencies, and create a prioritized backlog with acceptance criteria.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** – Day-to-day team rituals, GitHub Projects workflow, quality and testing standards, blocker escalation, and execution checklists.

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** – Risk register template and lifecycle, stakeholder communication strategies, weekly status templates, incident communication, and escalation paths.

- **[Release & Deployment](octoacme-release-and-deployment.md)** – Release types, pre-release requirements, deployment checklists, rollback and incident playbooks, and release notes templates.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** – Running retrospectives, capturing learnings, tracking action items, and building a continuous improvement culture.

- **[Roles & Personas](octoacme-roles-and-personas.md)** – Detailed descriptions of Developer, Product Manager, and Project Manager personas, including responsibilities, goals, and typical communication patterns.

---

## Getting Started

**For new team members:**
1. Start with [Project Management Overview](octoacme-project-management-overview.md) for a 5-minute orientation.
2. Read the doc corresponding to your current phase (e.g., [Project Initiation](octoacme-project-initiation.md) if you're starting a new project).
3. Bookmark this README and the [Roles & Personas](octoacme-roles-and-personas.md) guide for quick reference.

**For process updates or improvements:**
- Use the issue template `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to request updates.
- All updates should align with existing process docs and address documented gaps or improve clarity.

---

## Questions?

If you have questions about these processes, contact your Project Manager, Product Manager, or the process document owner listed in your project README.
