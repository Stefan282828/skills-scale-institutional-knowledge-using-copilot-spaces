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

## QA Lead (new)

### Role Summary
The QA Lead owns the test strategy, ensures quality gates are defined, and coordinates verification activities across manual and automated testing.

### Responsibilities
- Define test strategy and quality gates for releases
- Coordinate automated and manual testing efforts
- Own acceptance test criteria validation with PM/PdM
- Maintain test runbooks and QA dashboards
- Communicate quality status and risks to PM/Dev/Stakeholders

### Goals
- Reduce production defects and regression risk
- Ensure acceptance criteria are verifiable and traceable
- Improve test coverage for critical flows

### Typical Communication
- Participate in planning to advise on test scope and timelines
- Report QA status in weekly syncs and pre-release checks
- Join retrospectives to improve testing practices

---

## Solution Architect (new)

### Role Summary
The Solution Architect designs and validates high-level system architecture and ensures technical solutions align with business needs and long-term maintainability.

### Responsibilities
- Produce architecture sketches and decision records for complex features
- Validate technical feasibility and identify integration constraints
- Recommend trade-offs, non-functional requirements, and migration paths
- Help estimate technical complexity and risk

### Goals
- Maintain architectural consistency and scalability
- Reduce rework due to architectural trade-offs
- Ensure technical risks are explicit and mitigated early

### Typical Communication
- Consult during planning and design reviews
- Provide architecture guidance to Developers and PMs
- Document major decisions (ADR) and communicate to stakeholders

---

## Scrum Master / Agile Coach (new)

### Role Summary
The Scrum Master or Agile Coach helps the delivery team adopt and maintain effective Agile practices, remove blockers, and improve team health and delivery flow.

### Responsibilities
- Facilitate ceremonies (standups, planning, retrospectives)
- Remove impediments and escalate when necessary
- Coach team on agile practices and continuous improvement
- Track team health and foster psychological safety

### Goals
- Improve predictability and team throughput
- Reduce cycle time by removing process blockers
- Foster continuous improvement and shared ownership

### Typical Communication
- Work closely with PM and Developers to surface issues
- Drive retrospective follow-ups and action tracking
- Support onboarding of new team members on process

---

## Business Analyst (new)

### Role Summary
The Business Analyst gathers, clarifies, and documents requirements to ensure a shared understanding between stakeholders and the delivery team.

### Responsibilities
- Elicit requirements from stakeholders
- Write user stories and acceptance criteria
- Create process flows and use-case examples
- Trace requirements to delivered work and validate acceptance

### Goals
- Reduce rework due to ambiguous requirements
- Improve acceptance-test quality and traceability
- Speed up refinement and planning by preparing clear stories

### Typical Communication
- Bridge Product and Engineering in refinement sessions
- Work with QA to define acceptance test scenarios
- Help stakeholders validate requirements and scope

---

## UX/UI Designer (new)

### Role Summary
UX/UI Designers own the user experience design, validate usability, and provide design assets and guidance for implementation.

### Responsibilities
- Create user flows, wireframes, and UI mocks
- Validate usability via research or lightweight testing
- Provide assets, style guidance, and accessibility considerations
- Collaborate with Product, Dev, and QA to iterate on UI

### Goals
- Maximize usability and accessibility of delivered features
- Reduce rework between design and implementation
- Ensure consistent visual and interaction patterns

### Typical Communication
- Join discovery and planning sessions to align on design scope
- Hand off designs with clear acceptance criteria and assets
- Participate in usability validation and post-release reviews

---

## How these personas interact

This section describes common handoffs and interactions between personas to make responsibilities and accountability explicit.

- Product Manager (PdM) ↔ Business Analyst
  - PdM sets outcomes and priorities; BA translates into concrete user stories and acceptance criteria.
  - Interaction points: discovery, backlog refinement, acceptance validation.

- PdM ↔ UX/UI Designer
  - PdM provides objectives; Designer proposes flows and validates usability.
  - Interaction points: discovery, design reviews, pre-release validation.

- PM ↔ Scrum Master / Agile Coach
  - PM focuses on delivery governance and external stakeholders; Scrum Master focuses on team flow and ceremonies.
  - Interaction points: sprint planning, weekly syncs, retrospectives.

- Developers ↔ QA Lead
  - Developers implement features; QA Lead ensures test coverage and verifies acceptance criteria.
  - Interaction points: PRs, test run coordination, pre-release QA sign-off.

- Developers ↔ Solution Architect
  - Architect reviews designs and helps de-risk technical approaches.
  - Interaction points: design reviews, complex stories, ADRs.

- QA Lead ↔ Business Analyst
  - BA provides acceptance criteria; QA maps those to test scenarios.
  - Interaction points: story refinement, acceptance verification.

- All roles ↔ Stakeholders
  - Regular stakeholder communication coordinated by PM and PdM with participation as needed from other roles.

---

## Usage guidance

- Add or adapt persona definitions for your team as needed. Not every project will require every persona — mark personas as "assigned" in the Project One-pager when relevant.
- Use the Roles & Personas matrix (docs/roles-and-personas-matrix.md) for a RACI-style view of responsibilities for common activities.
- Before work begins, confirm which personas are assigned (even if one person fills multiple roles) and add that to the project README or One-pager.
