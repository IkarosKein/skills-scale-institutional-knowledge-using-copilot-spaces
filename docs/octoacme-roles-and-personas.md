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

### Interactions with Other Roles
- Work with Product Managers to clarify requirements and acceptance criteria.
- Work with Project Managers to provide estimates, report progress, and raise delivery risks.
- Collaborate with QA/Testing, UX/Design, Release/DevOps, Security, and Data/Analytics specialists on implementation quality and measurement.

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
- Align priorities and outcomes with Project Managers and Stakeholder/Customer Representatives.
- Partner with UX/Design and Developers to shape feasible, usable solutions.
- Use QA/Testing and Data/Analytics results to validate releases and product outcomes.
- Coordinate with Security and Release/DevOps leads on constraints and release readiness.

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
- Align scope and priorities with Product Managers and Stakeholder/Customer Representatives.
- Coordinate estimates and delivery progress with Developers.
- Facilitate readiness decisions with QA/Testing, UX/Design, Release/DevOps, Security, and Data/Analytics leads.

---

## QA/Testing

### Role Summary
QA/Testing personas own test strategy, acceptance validation, and quality feedback across the delivery lifecycle.

### Responsibilities
- Define test approaches and acceptance validation
- Create and maintain automated and manual test coverage
- Identify defects, quality risks, and release blockers
- Verify that acceptance criteria and Definition of Done requirements are met

### Goals
- Detect defects early and reduce production risk
- Keep quality criteria clear and measurable
- Improve testability and confidence in releases

### Typical Communication
- Test plans and defect reports
- Refinement and planning sessions
- Quality and release-readiness reviews

### Interactions with Other Roles
- Work with Developers to embed testability and coverage into implementation.
- Partner with Product Managers to validate acceptance criteria and with Project Managers to communicate quality risks.
- Coordinate with UX/Design on usability expectations and Release/DevOps on smoke tests and verification.

---

## UX/Design

### Role Summary
UX/Design personas translate customer needs into usable, accessible flows and prototypes while balancing technical and business constraints.

### Responsibilities
- Conduct or contribute to user research and discovery
- Create workflows, prototypes, and interaction specifications
- Define accessibility and usability requirements
- Review implementation and validate design quality

### Goals
- Deliver intuitive, accessible experiences
- Validate design decisions with users and evidence
- Reduce rework through clear design direction

### Typical Communication
- Design reviews and usability sessions
- Acceptance criteria and interaction specifications
- Design and implementation feedback

### Interactions with Other Roles
- Partner with Product Managers on problem validation and prioritized outcomes.
- Work with Developers on feasible implementation and with QA/Testing on usability and accessibility acceptance details.
- Provide Project Managers with design dependencies and Stakeholder/Customer Representatives with prototypes and validation results.

---

## Release/DevOps Engineer

### Role Summary
Release/DevOps personas own deployment automation, environments, operational readiness, and rollback preparedness.

### Responsibilities
- Maintain build and deployment pipelines
- Configure and manage environments
- Prepare smoke tests and release verification
- Document rollback and mitigation procedures
- Improve observability and operational resilience

### Goals
- Make releases repeatable and low-risk
- Reduce deployment lead time and recovery time
- Maintain reliable production and staging environments

### Typical Communication
- Release planning and change-control reviews
- Deployment runbooks and operational dashboards
- Incident coordination and post-release reviews

### Interactions with Other Roles
- Coordinate release plans and timing with Project Managers and Product Managers.
- Work with Developers and QA/Testing on packaging, smoke testing, and verification.
- Partner with Security on controls and threat mitigation and with Data/Analytics on operational metrics.

---

## Security Lead

### Role Summary
Security Lead personas define security requirements, assess delivery risks, and guide secure implementation and incident practices.

### Responsibilities
- Define security requirements and threat considerations
- Review designs and implementations for significant risk
- Coordinate security scans and vulnerability remediation
- Support incident triage and security risk escalation

### Goals
- Reduce security exposure across the delivery lifecycle
- Make security responsibilities clear and actionable
- Integrate preventive and detective controls into delivery

### Typical Communication
- Security reviews and risk assessments
- Vulnerability and remediation updates
- Incident notifications and escalation summaries

### Interactions with Other Roles
- Work with Developers on secure implementation and remediation.
- Coordinate controls and deployment readiness with Release/DevOps.
- Partner with Project Managers on security risks and timelines and with Product Managers on risk trade-offs.

---

## Data/Analytics Specialist

### Role Summary
Data/Analytics personas define and maintain success metrics, dashboards, experiment measurements, and evidence for delivery decisions.

### Responsibilities
- Define measurement plans and success metrics
- Build and maintain dashboards and reports
- Analyze experiments, usage, and delivery signals
- Clarify data-quality requirements and instrumentation

### Goals
- Improve the accuracy and availability of outcome data
- Enable evidence-based prioritization and delivery decisions
- Detect trends and issues quickly

### Typical Communication
- Metrics reviews and experiment readouts
- Dashboard and instrumentation requests
- Weekly status and outcome updates

### Interactions with Other Roles
- Partner with Product Managers to define and validate success metrics.
- Work with Developers and Release/DevOps to ensure instrumentation and observability.
- Support Project Managers with delivery and risk trends and QA/Testing with quality metrics.

---

## Stakeholder/Customer Representative

### Role Summary
Stakeholder/Customer Representative personas provide domain context, customer or business feedback, and timely validation of proposed outcomes.

### Responsibilities
- Represent stakeholder or customer needs and constraints
- Provide domain context and feedback
- Participate in priority, acceptance, and release discussions
- Validate outcomes against real-world needs

### Goals
- Improve alignment between delivered work and stakeholder needs
- Reduce ambiguity and late requirement changes
- Increase confidence that outcomes create intended value

### Typical Communication
- Stakeholder reviews and feedback sessions
- Roadmap and milestone updates
- Acceptance and release validation

### Interactions with Other Roles
- Help Product Managers clarify needs and success criteria.
- Support Project Managers with expectations, decisions, and communication.
- Collaborate with UX/Design on research and prototypes and with QA/Testing or Data/Analytics on outcome validation.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

