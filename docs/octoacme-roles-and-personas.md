# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles are assigned to fit the project; multiple responsibilities may be shared by one person on a small team.

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

### Interactions with Other Roles
- Work with the Product Manager to clarify outcomes and with the UX/Design Lead to implement usable experiences.
- Coordinate with the Project Manager on estimates, dependencies, and delivery risks.
- Collaborate with QA/Testing on acceptance evidence and with Security and Operations roles on safe, observable releases.

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

### Interactions with Other Roles
- Partner with the Stakeholder/Sponsor to confirm priority and funding and with the UX/Design Lead on customer needs.
- Work with the Project Manager on scope, dependencies, and trade-offs.
- Align with the Release Manager and Support/Operations Representative on customer impact, release scope, and post-release feedback.

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

### Interactions with Other Roles
- Coordinate scope and sequencing with the Product Manager and delivery capacity with Developers and the Delivery Facilitator.
- Work with the Release Manager on release plans, the Security Lead on risk decisions, and Support/Operations on readiness.
- Escalate unresolved constraints or decisions to the Stakeholder/Sponsor.

---

## Release Manager

### Role Summary
The Release Manager owns release readiness and coordinates planned deployments, rollback decisions, and stakeholder announcements.

### Responsibilities
- Maintain the release calendar and deployment approvals
- Confirm that acceptance criteria, CI checks, release notes, and rollback plans are ready
- Coordinate deployment and post-deploy verification
- Communicate release status and manage release-related risks

### Goals
- Deliver releases safely and predictably
- Minimize deployment-related disruption
- Improve release traceability and operational readiness

### Typical Communication
- Release readiness reviews and deployment briefings
- Go/no-go decisions and status updates
- Post-release verification and incident handoffs

### Interactions with Other Roles
- Confirms implementation readiness with Developers and acceptance evidence with QA/Testing.
- Aligns scope and customer impact with the Product Manager and schedule and risk coverage with the Project Manager.
- Coordinates rollback and incident readiness with Security, Support/Operations, and on-call teams.

---

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master or Delivery Facilitator improves team flow by facilitating ceremonies, resolving impediments, and coaching sustainable delivery practices.

### Responsibilities
- Facilitate planning, daily coordination, reviews, and retrospectives
- Identify and remove delivery impediments
- Coach the team on transparent workflow and healthy prioritization boundaries
- Protect focus from disruptive, unagreed work

### Goals
- Improve predictability and team flow
- Reduce recurring blockers and unplanned interruptions
- Strengthen a culture of inspection and continuous improvement

### Typical Communication
- Team ceremonies and backlog readiness discussions
- Impediment tracking and retrospective facilitation
- Regular delivery-health updates

### Interactions with Other Roles
- Partners with the Project Manager on coordination, dependencies, and risks.
- Supports Developers and QA/Testing in maintaining a clear and usable workflow.
- Works with the Product Manager to keep backlog priorities clear without taking ownership of product decisions.

---

## UX/Design Lead

### Role Summary
The UX/Design Lead represents users throughout discovery and delivery, defining coherent and accessible experiences and validating usability.

### Responsibilities
- Lead or facilitate user research and experience discovery
- Create interaction designs, prototypes, and design specifications
- Maintain design-system and accessibility consistency
- Validate usability and incorporate evidence from testing

### Goals
- Improve usability and accessibility
- Align product decisions with real user needs
- Reduce late-stage design rework

### Typical Communication
- Design reviews and usability sessions
- Research findings and design specifications
- Accessibility and acceptance-criteria discussions

### Interactions with Other Roles
- Translates outcomes into user needs with the Product Manager and stakeholder feedback with Sponsors.
- Works with Developers on feasibility, implementation quality, and trade-offs.
- Collaborates with QA/Testing to define usability and accessibility acceptance expectations.

---

## Security Lead

### Role Summary
The Security Lead identifies security requirements and risks, advises teams on controls, and coordinates security reviews and incident response.

### Responsibilities
- Define applicable security requirements and threat considerations
- Review high-risk designs and security findings
- Coordinate assessments and remediation priorities
- Advise on incident response and security escalation

### Goals
- Reduce security risk and prevent avoidable vulnerabilities
- Enable secure delivery without unclear ownership
- Improve incident readiness and response

### Typical Communication
- Threat and risk reviews
- Security findings and remediation updates
- Incident coordination and escalation notices

### Interactions with Other Roles
- Works with Developers on secure implementation and remediation.
- Partners with QA/Testing on security validation and with the Release Manager on release readiness.
- Provides risk context to the Project Manager and decision support to stakeholders and Sponsors.

---

## Support/Operations Representative

### Role Summary
The Support/Operations Representative represents operational readiness, supportability, monitoring, incident ownership, and customer-impact considerations.

### Responsibilities
- Assess operational and support readiness
- Define monitoring, alerting, runbooks, and handoff requirements
- Surface known issues and recurring customer-impact patterns
- Coordinate operational incident intake and escalation

### Goals
- Improve supportability and observability
- Reduce incident resolution time and customer disruption
- Ensure teams are prepared to operate what they deliver

### Typical Communication
- Operational readiness reviews
- Support handoffs and known-issue summaries
- Incident and customer-impact updates

### Interactions with Other Roles
- Collaborates with Developers and QA/Testing on observability and troubleshooting.
- Works with the Release Manager on deployment readiness and communications.
- Provides customer feedback and known issues to the Product Manager and schedules operational risks with the Project Manager.

---

## Stakeholder / Sponsor Representative

### Role Summary
The Stakeholder/Sponsor Representative provides organizational decision authority, confirms priority and funding, and helps resolve cross-functional constraints.

### Responsibilities
- Confirm project priorities and authorized scope
- Provide or secure funding and resource decisions
- Resolve high-impact cross-organizational dependencies
- Approve major trade-offs and business-risk decisions

### Goals
- Maintain alignment with organizational priorities
- Enable timely decisions on funding and scope
- Remove strategic barriers to project success

### Typical Communication
- Milestone reviews and executive status updates
- Decision records and escalation discussions
- Sponsor or steering-group briefings

### Interactions with Other Roles
- Receives status, risks, and recommendations from the Project Manager.
- Confirms outcomes and priority trade-offs with the Product Manager.
- Resolves dependencies and provides approvals for Developers, UX/Design, Security, and other delivery roles when authority is required.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Assign roles based on project scale; some responsibilities may be combined on smaller teams.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

