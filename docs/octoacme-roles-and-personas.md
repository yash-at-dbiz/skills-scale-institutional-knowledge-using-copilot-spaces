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

## UX Designer

### Role Summary
Designs user flows, wireframes, and prototypes to ensure the product is usable, accessible, and aligned to user needs.

### Responsibilities
- Lead interaction and visual design for features; create wireframes and prototypes
- Conduct usability testing and incorporate feedback into designs
- Define accessibility requirements and checks
- Provide design assets and specifications to Developers

### Goals
- Improve usability and reduce user friction
- Ensure consistent visual language and accessible experiences

### Typical Communication
- Work closely with PdM during discovery and prioritization
- Provide design reviews in sprint planning and PRs
- Share mockups in weekly delivery sync

### Interactions with other roles
- **PdM:** Collaborate on problem definition, success criteria, and acceptance criteria for UI-related stories
- **Developers:** Hand off designs, clarify interactions and edge-cases, review PRs for UX implementation
- **QA:** Supply test scenarios related to usability and accessibility
- **PM:** Communicate scheduling and design-related dependencies

---

## Scrum Master

### Role Summary
Facilitates Agile ceremonies, coaches the team on process, and removes impediments that slow delivery.

### Responsibilities
- Facilitate standups, sprint planning, reviews, and retrospectives
- Coach the team on Agile practices and continuous improvement
- Track and remove blockers and impediments
- Shield the team from unplanned interruptions during a sprint
- Maintain sprint velocity metrics and burndown charts

### Goals
- Maximize team throughput and predictability
- Foster a healthy, self-organizing team culture
- Ensure process adherence without bureaucratic overhead

### Typical Communication
- Daily standup facilitation
- Sprint planning and retrospective notes
- Impediment log updates shared with PM and stakeholders

### Interactions with other roles
- **PM:** Escalate cross-team blockers; align on schedule and milestone impacts
- **PdM:** Ensure backlog is refined and stories are ready for sprint commitment
- **Developers:** Remove day-to-day impediments; support estimation and capacity planning
- **QA:** Coordinate test readiness within sprint timelines

---

## Business Analyst

### Role Summary
Gathers and documents requirements from stakeholders, defines acceptance criteria, and bridges the gap between business objectives and technical delivery.

### Responsibilities
- Elicit, document, and validate requirements from stakeholders
- Write clear acceptance criteria and user stories
- Map business processes and identify gaps or improvements
- Align requirements to measurable business outcomes
- Support UAT and sign-off coordination

### Goals
- Ensure requirements are complete, unambiguous, and testable
- Reduce rework caused by misunderstood requirements
- Bridge communication between business stakeholders and the delivery team

### Typical Communication
- Requirements workshops and stakeholder interviews
- Backlog grooming sessions with PdM and Developers
- Acceptance criteria documented in story tickets

### Interactions with other roles
- **PdM:** Translate business needs into prioritized product requirements; co-author user stories
- **Developers:** Clarify requirements and edge-cases during implementation
- **QA:** Co-define acceptance and test criteria; support UAT
- **PM:** Flag scope changes and dependencies; contribute to project documentation
- **Stakeholders:** Primary liaison for requirement gathering and sign-off

---

## Technical Lead

### Role Summary
Guides architectural decisions, sets code quality standards, and mentors engineers to ensure technical alignment with product goals.

### Responsibilities
- Define and communicate technical architecture and design patterns
- Review complex PRs and enforce coding standards
- Mentor engineers and support skill growth
- Identify and mitigate technical risks
- Coordinate with PdM and PM on technical feasibility and effort estimates

### Goals
- Maintain a scalable, maintainable, and secure codebase
- Reduce technical debt and unplanned rework
- Ensure the team ships reliable software on time

### Typical Communication
- Architecture decision records (ADRs)
- Code review comments and PR feedback
- Technical deep-dives with Developers and QA
- Feasibility and risk input in planning sessions

### Interactions with other roles
- **PM:** Provide technical input for scheduling, risk, and milestone planning
- **PdM:** Assess feasibility and trade-offs for proposed features
- **Developers:** Pair on complex problems, review PRs, set quality standards
- **QA:** Define test strategy for complex or high-risk changes
- **UX Designer:** Validate technical feasibility of proposed designs

---

## Support Engineer

### Role Summary
Handles post-release customer issues, channels feedback to the team, and helps maintain service reliability for end users.

### Responsibilities
- Triage and resolve customer-reported bugs and incidents
- Reproduce issues and file detailed bug reports for the development team
- Contribute to runbooks, FAQs, and user-facing documentation
- Monitor for post-deployment errors and alert the team
- Collect and synthesize customer feedback to inform product improvements

### Goals
- Minimize customer impact from defects and incidents
- Reduce time-to-resolution through good documentation and tooling
- Improve product quality through actionable feedback loops

### Typical Communication
- Incident reports and post-mortems
- Bug tickets with reproduction steps submitted to the development team
- Regular feedback summaries shared with PdM and PM

### Interactions with other roles
- **PM:** Escalate critical incidents; provide input for release timing decisions
- **PdM:** Share user feedback and pain points to inform prioritization
- **Developers:** Collaborate on bug reproduction, root-cause analysis, and fixes
- **QA:** Highlight recurring defect patterns; inform regression test coverage
- **Technical Lead:** Escalate systemic or architectural issues discovered in production

---

## Stakeholder — Legal / Finance / Compliance

### Role Summary
Provides requirements, constraints, and approvals related to legal, financial, and regulatory obligations that the product must satisfy.

### Responsibilities
- Review features and releases for legal and regulatory compliance
- Define compliance requirements and constraints (e.g., data privacy, accessibility mandates)
- Participate in key milestone reviews and release sign-offs
- Contribute to the risk register for legal or financial risks
- Escalate compliance blockers through the appropriate channels

### Goals
- Ensure the product meets all applicable legal, regulatory, and financial requirements
- Protect the organization from compliance risk
- Provide timely reviews to avoid blocking releases

### Typical Communication
- Milestone review and sign-off meetings
- Risk register and escalation documentation
- Policy or requirement briefs shared with PdM and PM

### Interactions with other roles
- **PM:** Communicate compliance timelines and approval dependencies
- **PdM:** Define non-functional and regulatory requirements that constrain product design
- **Technical Lead:** Review architectural or data-handling decisions for compliance implications
- **Developers:** Clarify compliance constraints affecting implementation (e.g., data retention, encryption)
- **Business Analyst:** Co-document compliance requirements in story acceptance criteria

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See also: [Role Responsibility Matrix](octoacme-role-responsibility-matrix.md) and [Release & Deployment Checklist](octoacme-release-and-deployment-checklist.md).

