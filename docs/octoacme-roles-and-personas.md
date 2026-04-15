# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## New / Expanded Personas

The following personas are commonly involved in cross-functional projects but were previously under-described. Adding them clarifies responsibilities, reduces handoff friction, and improves accountability.

### UX Designer (or Product Designer)

Role Summary
Responsible for ensuring features meet user needs through research, design, and testing.

Responsibilities
- Conduct user research and synthesize findings
- Produce wireframes, prototypes, and interaction specifications
- Collaborate with PdM on requirements and acceptance criteria that reflect user needs
- Work with Developers and QA to ensure designs are implemented correctly
- Run or coordinate usability testing and incorporate feedback

Interactions
- PdM: Align on user problems, success metrics, and design priorities
- Developers: Clarify UI behaviors and constraints, review implementation
- QA: Define user-focused acceptance tests
- PM/Stakeholders: Provide artifacts for demos and stakeholder reviews

---

### Technical Writer

Role Summary
Creates and maintains user-facing documentation, release notes, and internal runbooks.

Responsibilities
- Draft and maintain user guides, API docs, and release notes
- Ensure docs reflect implemented behavior and known limitations
- Collaborate with Developers for technical accuracy and PdM for messaging
- Maintain internal operational runbooks and handoff materials for Support

Interactions
- Developers: Verify technical details, examples, and API changes
- PM/PdM: Ensure documentation aligns with product messaging and release timing
- Release Manager / Support: Coordinate release notes and post-release customer messaging

---

### Release Manager

Role Summary
Owns coordination and readiness for releases to reduce risk during deployment windows.

Responsibilities
- Create and maintain the release plan and schedule
- Coordinate cross-functional release readiness (Dev/QA/Support/Docs)
- Ensure pre-release checklists are completed and rollback plans exist
- Orchestrate communications for releases and verify post-deploy checks

Interactions
- PM/PdM: Agree on release scope and timing
- Developers/QA: Confirm CI, test, and smoke-test readiness
- Technical Writer: Ensure release notes are ready and accurate
- Support/Operations: Confirm on-call and runbook readiness

---

### Support / Operations Representative (Customer Success / SRE liaison)

Role Summary
Represents production and customer-facing operational concerns during planning and after release.

Responsibilities
- Bring production incidents, trends, and customer feedback into planning
- Validate monitoring, alerting, and runbooks for new releases
- Support post-release triage and escalation
- Provide input on operational risk and rollback readiness

Interactions
- Developers: Share production data and help reproduce issues
- PM/Release Manager: Advise on rollout strategies, canarying, and mitigation
- Technical Writer: Ensure runbooks and support notes are up to date

---

## Optional Additional Personas (pick as needed)

- Data Analyst: Validates success metrics and instrumentation, creates dashboards used to evaluate features.
- DevOps / Platform Engineer: Owns CI/CD pipeline, infra-as-code, and platform health related tasks.
- Security Liaison: Advises on security impact, threat modeling, and coordinates security reviews.

---

## Role Interaction Guidance / Lightweight RACI

For common project activities, use a lightweight RACI-like approach to prevent ambiguity:

- Responsible (R): Does the work
- Accountable (A): Final decision owner
- Consulted (C): Provides input; loop-in during design
- Informed (I): Kept updated

Sample mappings (adjust per project):

- Requirements & Acceptance Criteria: PdM (A), UX (C), Dev (C), PM (I)
- Implementation & Testing: Dev (R), QA (A), PM (I), PdM (C)
- Release Readiness: Release Manager (A), Dev (R), QA (R), Tech Writer (C), Support (C)
- Documentation & Runbooks: Tech Writer (R), Dev / Support (C), PM (I)

Consider adding a small "Role Interaction Matrix" table into project one-pagers when cross-functional handoffs have caused confusion.

---

## How to use these personas in the project docs

- Include the relevant personas and responsibilities in the Project One-pager ("Proposed team / roles").
- Use the role-responsibilities template (docs/templates/role-responsibilities-template.md) to capture role-specific expectations for each project.
- Assign a Release Manager for any non-trivial release; record their name in the release plan.
- Ensure Technical Writer and Support are looped into release planning early enough to prepare notes and runbooks.

---

## Rationale

Explicitly naming supporting personas reduces ambiguity, shortens feedback loops, and improves onboarding by capturing who owns what and how they should interact. This becomes especially important as teams scale and more cross-functional handoffs occur.
