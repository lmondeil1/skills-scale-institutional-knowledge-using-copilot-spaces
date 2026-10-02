# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
Teams may combine roles to fit their size and skills; the responsibilities and decision boundaries below still need clear owners.

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

## UX/UI Designer

### Role Summary
UX/UI Designers turn user needs and product goals into clear, usable, and accessible experiences. They provide design expertise throughout delivery without owning product priority or implementation decisions.

### Responsibilities
- **Initiation and planning:** Contribute user research and journey insights; shape flows, prototypes, and design requirements with Product Managers; identify usability and accessibility needs early.
- **Execution:** Maintain design artifacts and explain interaction intent; review working software with Developers and QA, and resolve design questions or propose alternatives.
- **Release and retrospective:** Help validate the shipped experience, surface usability feedback, and recommend design improvements based on user feedback and outcomes.
- **Decision boundaries and handoffs:** Own design recommendations and design artifacts; Product Managers decide product scope and priority, while Developers decide implementation details with the Technical Lead. Hand off usable specs and assets before implementation and report design gaps promptly.
- **Collaboration:** Align with Product Managers on user problems and acceptance criteria; partner with Developers on feasibility and design implementation; keep Project Managers informed of design dependencies, review timing, and risks.

### Goals
- Make experiences useful, understandable, and accessible
- Reduce design ambiguity and late usability rework
- Validate design choices with users and delivery evidence

### Typical Communication
- Research findings, journey maps, prototypes, and design specs
- Design reviews and regular check-ins with Product Managers and Developers
- Usability findings and open design decisions shared on the project board

---

## Technical Lead / Architect

### Role Summary
Technical Leads / Architects guide solution design, integration, and technical quality so the team can deliver maintainable systems. They enable engineering decisions and do not replace Developers as implementation owners.

### Responsibilities
- **Initiation and planning:** Assess feasibility, architecture options, dependencies, and technical risks; advise on estimates, sequencing, and non-functional requirements with Developers.
- **Execution:** Facilitate design reviews, resolve cross-component technical questions, and monitor technical risks and integration; coordinate remediation with Developers.
- **Release and retrospective:** Confirm technical readiness evidence and migration or rollback considerations; review incidents and technical lessons to inform follow-up work.
- **Decision boundaries and handoffs:** Make or recommend technical design decisions within agreed standards and record consequential choices; escalate material scope, cost, or risk trade-offs to Product Managers and Project Managers. Developers own implementation and tests; hand off interfaces, decisions, and operational constraints to delivery and operations.
- **Collaboration:** Work with Developers on design, estimates, and reviews; explain feasibility and trade-offs to Product Managers; give Project Managers visibility into dependencies, decisions, and schedule risks.

### Goals
- Deliver secure, reliable, maintainable technical solutions
- Reduce integration risk and avoid unnecessary complexity
- Make technical trade-offs visible early

### Typical Communication
- Architecture decision records, diagrams, and technical design reviews
- Dependency and risk updates with Developers and Project Managers
- Feasibility and trade-off discussions with Product Managers

---

## Data Analyst / Analytics Lead

### Role Summary
Data Analysts / Analytics Leads define how product outcomes are measured and help teams interpret reliable data. They connect product questions to instrumentation, analysis, and actionable findings.

### Responsibilities
- **Initiation and planning:** Translate product goals into measurable questions and metric definitions; identify required events, data sources, privacy constraints, and reporting needs.
- **Execution:** Specify and review instrumentation with Developers; validate event quality and dashboards, and investigate data gaps or unexpected results.
- **Release and retrospective:** Verify measurement readiness before launch; analyze outcomes and communicate limitations and findings to guide iteration.
- **Decision boundaries and handoffs:** Own analytical methods and communicate data quality and uncertainty; Product Managers set product goals and make prioritization decisions. Developers implement instrumentation, and the analyst hands off event definitions and validation criteria before implementation.
- **Collaboration:** Agree with Product Managers on success measures and interpretation; coordinate event implementation and data validation with Developers; share measurement dependencies, risks, and findings with Project Managers.

### Goals
- Make product outcomes measurable and interpretable
- Improve confidence in instrumentation and reporting
- Help teams use evidence to make informed decisions

### Typical Communication
- Metric definitions, event specifications, and analysis notes
- Instrumentation reviews with Developers and Product Managers
- Dashboards and concise findings shared at milestones and retrospectives

---

## Security / Privacy Lead

### Role Summary
Security / Privacy Leads help teams identify and address security and privacy risks throughout delivery. They advise on controls and review evidence; required risk acceptance follows the organization’s established governance.

### Responsibilities
- **Initiation and planning:** Identify applicable security and privacy requirements, sensitive data, threats, and review needs; agree on appropriate assessments and mitigation owners with the team.
- **Execution:** Advise on secure design and privacy controls; review relevant implementation and test evidence, track findings, and escalate unresolved high-impact risks.
- **Release and retrospective:** Confirm required reviews and remediation evidence are complete; contribute to incident readiness and review security or privacy lessons after release.
- **Decision boundaries and handoffs:** Define or interpret security/privacy requirements and recommend approval or remediation; do not silently waive policy or accept organizational risk. Escalate exceptions through the designated governance owner. Hand findings and required controls to Developers, with status and release-impact updates to Project Managers.
- **Collaboration:** Work with Developers on threat mitigation and verification; help Product Managers understand user, regulatory, and scope implications; inform Project Managers of review gates, owners, deadlines, and escalations.

### Goals
- Protect users, data, and systems
- Surface risks early and enable timely remediation
- Ensure release decisions use documented review evidence

### Typical Communication
- Threat models, privacy assessments, security requirements, and findings
- Design and test reviews with Developers
- Risk and exception escalations through agreed project and governance channels

---

## Operations / Support Representative

### Role Summary
Operations / Support Representatives bring production-operability and customer-support perspectives into delivery. They help prepare teams to run, monitor, and support changes after release.

### Responsibilities
- **Initiation and planning:** Identify operational, support, and customer-impact requirements; contribute monitoring, service, documentation, training, and rollout needs to plans.
- **Execution:** Review operational procedures and support materials; coordinate with Developers on observability, deployment, and recovery needs, and flag readiness gaps.
- **Release and retrospective:** Participate in readiness checks and rollout communications; monitor agreed signals, route customer issues, and provide incident and support trends for follow-up.
- **Decision boundaries and handoffs:** Own operational and support recommendations and assigned runbooks; report unmet readiness requirements and use established escalation paths. The designated release owner decides whether to proceed. Receive release notes, known issues, runbooks, escalation contacts, and monitoring guidance before handoff to support.
- **Collaboration:** Coordinate with Developers on monitoring, deployment, and recovery; align with Product Managers on customer impact and feedback; work with Project Managers on readiness owners, release timing, communications, and escalations.

### Goals
- Make releases supportable and operationally observable
- Reduce customer impact and time to diagnose or recover
- Close the feedback loop between users, support, and delivery teams

### Typical Communication
- Readiness reviews, runbooks, support guides, and release notes
- Monitoring and incident updates with Developers and Project Managers
- Customer-impact and feedback summaries with Product Managers

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
