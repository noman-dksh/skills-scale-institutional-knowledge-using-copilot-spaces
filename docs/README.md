# OctoAcme Project Management Docs

This README provides a central index and comprehensive overview of the OctoAcme project management process documents stored in the `docs/` folder. Use this as the starting point for team onboarding, process discovery, and linking into project repositories or Copilot Spaces.

## OctoAcme Project Management Overview

OctoAcme operates on a structured, lifecycle-driven approach to project delivery that emphasizes customer value, iterative delivery, and clear ownership across cross-functional teams. The process is anchored in five core phases: **Initiation** (validating business need and stakeholder alignment through a lightweight one-pager), **Planning** (breaking work into shippable increments with prioritized backlogs and acceptance criteria), **Execution** (building and testing with daily standups and weekly delivery syncs), **Release** (standardized deployment with pre-release checklists and rollback plans), and **Closure & Retrospective** (capturing learnings and driving continuous improvement). This lifecycle is underpinned by a principle of psychological safety, data-informed decisions, and clear ownership of outcomes.

Core responsibilities are distributed across defined personas: **Project Managers** coordinate delivery timelines, manage risks and dependencies, and ensure transparent communication across stakeholders; **Product Managers** own the product vision, prioritize the backlog, and validate solutions through metrics; **Developers** implement features to meet acceptance criteria, write tests, and collaborate on design; and **QA/Testing** validates quality and acceptance criteria. Weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates maintain alignment and enable rapid escalation when blockers arise.

Quality and execution rigor are enforced through a defined **Definition of Done**, CI/CD pipelines with automated testing and security scanning, small pull requests (≤400 lines preferred), and mandatory code review with at least one approval before merge. The team tracks velocity and burndown, maintains a **Risk Register** with impact/likelihood assessments and mitigation plans, and uses a **project board** (GitHub Projects) with standardized columns: Backlog → Ready → In Progress → In Review → QA → Done. Risk escalation follows a three-tier model: team-level triage in standups, PM escalation to Product Lead for cross-team dependencies, and sponsor-level escalation for business-impacting issues.

Communication is structured and proactive: status updates follow a template covering progress, next steps, risks, and decisions needed; incident communication includes triage summary, actions, timeline, and a blameless retrospective; and retrospectives (45–75 minutes) capture what went well, improvements, and prioritized action items (2–3 top items to avoid overload). By converting learning into documented action items with clear owners and due dates, OctoAcme embeds continuous improvement into its culture and reduces single-person dependency risk through centralized, versioned artifacts.

## Process Documentation Index

Navigate to any of the following documents to dive deeper into specific areas of the OctoAcme project management process:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Concise introduction to OctoAcme principles, core roles, key artifacts, and high-level lifecycle. Start here for a foundational understanding.

- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps and templates for validating and authorizing new projects. Includes the Project One-pager template, stakeholder alignment activities, and decision gate criteria.

- **[Project Planning](./octoacme-project-planning.md)** — Turning approved initiatives into an actionable plan and prioritized backlog. Covers kickoff, backlog item templates, estimation, Definition of Done, and risk/dependency mapping.

- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Daily and weekly rhythms, PR workflow conventions, quality standards, reporting metrics, and blocker escalation procedures. The primary guide for delivery teams.

- **[Risks & Communication](./octoacme-risks-and-communication.md)** — Maintaining the Risk Register, communication templates (weekly status, incident comms), escalation paths, and stakeholder communication strategies.

- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Release types, pre-release requirements checklist, deployment procedures, rollback playbook, and release notes template.

- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Running retrospectives, action item templates, tracking and measuring improvements, and building a continuous improvement culture.

- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed summaries of Developers, Product Managers, and Project Managers, including responsibilities, goals, and typical communication patterns used across OctoAcme docs.

## How to Use These Docs

- **For new team members:** Start with the [Project Management Overview](./octoacme-project-management-overview.md), then explore the docs that match your role and current project phase.

- **For project repositories:** Link to this README from project READMEs so team members can find the process docs quickly.

- **For Copilot Spaces:** Add this README and specific process docs to your Space to ground Copilot's knowledge in OctoAcme practices.

- **To propose updates or improvements:** Open an issue using the **"Add Content to Project Management Process Docs"** template (see [.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)).

- **To add new processes:** Create a new markdown file in the `docs/` folder following the same structure and format, then update this README with a link and brief description.

## Questions or Feedback?

If you have questions about these processes, suggested updates, or need clarification on a specific workflow, please:

- Tag your Project Manager or Product Lead in an issue
- Open a process-docs issue in this repository with the "Add Content to Project Management Process Docs" template
- Reference this README and the specific document(s) in your question for context
