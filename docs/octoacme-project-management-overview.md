# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Business Analyst (BA): clarifies requirements, constraints, and traceability.
- UX Designer: defines user experience flows and usability expectations.
- Developers: implement features, collaborate on design and testability.
- QA/Testing: define quality strategy and validate acceptance criteria.
- Scrum Master / Delivery Lead: facilitates ceremonies and removes delivery blockers.
- Stakeholder Champions: represent business domains and readiness needs.

## Accountability Model
- Use **A/R/C/I** in every phase artifact:
  - **A (Accountable):** single decision owner.
  - **R (Responsible):** contributors doing the work.
  - **C (Consulted):** experts consulted before decisions.
  - **I (Informed):** audiences notified after decisions.
- Track key ownership in [`octoacme-role-accountability-template.md`](./octoacme-role-accountability-template.md).

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Decision and Handoff Gates
- Initiation -> Planning: approved one-pager with named accountable owner.
- Planning -> Execution: prioritized backlog with acceptance criteria and dependency owners.
- Execution -> Release: quality and rollout readiness confirmed by PM + QA.
- Release -> Retrospective: outcome metrics, incidents, and follow-up actions captured.

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
