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

## QA/Test Lead

### Role Summary
QA/Test Leads define and execute quality assurance strategy, validate acceptance criteria, and ensure software meets quality standards before release. They collaborate with developers and product managers to define testability requirements and quality metrics.

### Responsibilities
- Define test strategy and acceptance criteria validation approach
- Design and maintain test plans (unit, integration, end-to-end, smoke tests)
- Conduct quality reviews and acceptance testing
- Identify, document, and track defects
- Collaborate with developers on testability and quality standards
- Conduct security and performance testing where applicable

### Goals
- Ensure all features meet acceptance criteria before release
- Catch defects early in the development cycle
- Minimize post-release issues and support burden
- Maintain high quality standards and team confidence

### Typical Communication
- Quality reviews and test status in standups
- Defect reports and test coverage metrics
- Acceptance criteria discussions during planning
- Release readiness sign-offs

### Interaction with Existing Roles
- **Developers**: Collaborate on test design, testability requirements, and defect resolution
- **Product Managers**: Validate feature acceptance criteria and define quality expectations
- **Project Managers**: Report test status and readiness in delivery tracking
- **Technical Leads**: Align on test strategy for architectural components
- **DevOps/Release Engineers**: Coordinate smoke testing and release validation

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, requirements, approvals, and resource support. They have decision authority and represent customer or business interests in project oversight.

### Responsibilities
- Provide business requirements and success criteria
- Make go/no-go decisions at key project gates
- Approve project charter, scope, and resource allocation
- Receive and review project status and risk reports
- Escalate or resolve business-level blockers
- Communicate outcomes to broader organizational stakeholders

### Goals
- Ensure project delivers measurable business value
- Maintain alignment with organizational strategy and priorities
- Enable rapid decision-making and risk resolution
- Maximize return on investment

### Typical Communication
- Monthly or milestone-based stakeholder briefings
- Review of Project One-pager and success metrics
- Approval of major scope or timeline changes
- Risk escalation notifications

### Interaction with Existing Roles
- **Project Managers**: Report status, escalate risks, and seek approvals
- **Product Managers**: Align on business priorities and success metrics
- **Developers**: Provide business context and acceptance criteria
- **Technical Leads**: Approve technical approach and resource needs
- **QA/Test Leads**: Validate quality expectations and release sign-offs

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide architectural guidance, assess technical feasibility, and help design solutions that are scalable, maintainable, and aligned with long-term system strategy. They mentor developers and guide technical decision-making.

### Responsibilities
- Evaluate technical feasibility and estimate effort for complex features
- Design system architecture and integration points
- Review technical designs and code for alignment with standards
- Identify and mitigate technical risks
- Mentor junior developers and guide technical practices
- Participate in retrospectives to improve technical processes

### Goals
- Deliver scalable, maintainable, and secure solutions
- Reduce technical debt and long-term maintenance burden
- Enable team autonomy through clear architectural guidance
- Support continuous technical improvement

### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments and guidance
- Technical risk identification and mitigation strategies
- Sprint retrospectives and learning sessions

### Interaction with Existing Roles
- **Developers**: Mentor on technical practices and provide architectural guidance
- **Project Managers**: Identify technical risks and estimate effort for complex work
- **Product Managers**: Advise on technical trade-offs and feasibility
- **QA/Test Leads**: Guide test strategy for complex architectural components
- **DevOps/Release Engineers**: Ensure deployment architecture aligns with system design

---

## DevOps/Release Engineer

### Role Summary
DevOps and Release Engineers manage deployment infrastructure, CI/CD pipelines, and release execution. They ensure reliable, repeatable deployments and maintain system observability in production.

### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Configure and maintain deployment infrastructure (staging, production)
- Manage secrets, configuration, and environment setup
- Execute deployments and rollbacks
- Monitor system health and performance post-deployment
- Document and automate release procedures

### Goals
- Enable fast, reliable, repeatable deployments
- Minimize deployment risk and downtime
- Maintain production system stability and observability
- Reduce manual release effort through automation

### Typical Communication
- Release coordination and deployment windows
- CI/CD status and pipeline health
- Post-deployment verification and incident response
- Infrastructure and automation improvements

### Interaction with Existing Roles
- **Developers**: Automate testing and deployment in CI/CD pipelines
- **Project Managers**: Coordinate release scheduling and deployment windows
- **QA/Test Leads**: Execute smoke tests and post-deployment verification
- **Technical Leads**: Implement deployment architecture and infrastructure
- **Stakeholders/Sponsors**: Provide release updates and incident notifications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interaction with Existing Roles" sections to understand cross-functional workflows and dependencies.
