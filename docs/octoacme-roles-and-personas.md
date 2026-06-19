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

## Delivery Lead

### Role Summary
Delivery Leads coordinate cross-functional delivery activities, maintain the release plan, and manage day-to-day execution risks. They ensure that iterations move forward smoothly and retrospectives drive continuous improvement.

### Responsibilities
- Coordinate cross-functional delivery activities and maintain the release plan
- Track milestone progress and manage day-to-day execution risks
- Run iteration planning and retrospective meetings
- Identify and escalate blockers and dependencies
- Maintain delivery metrics and cadence (velocity, burndown, cycle time)

### Goals
- Ensure consistent, predictable delivery cadence
- Reduce execution risk through active dependency management
- Foster psychological safety and continuous learning

### Typical Communication
- Daily standups focused on blockers and progress
- Weekly delivery planning and risk reviews
- Retrospective facilitation and action item tracking
- Ad-hoc escalations to PM/PdM for resource or schedule issues
- Coordination with DevOps and QA for deployments and testing

### Interactions
- Works closely with Project Manager (PM) and Product Manager (PdM) to translate roadmap into delivery timelines
- Escalates resource or schedule issues to PM/PdM
- Coordinates with DevOps and QA for deployments and test scheduling
- Supports team retrospectives and iteration planning

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers lead user research, usability testing, design artifact creation, and accessibility validation. They provide acceptance criteria and prototypes that guide feature development and ensure solutions meet user needs.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create design artifacts (wireframes, prototypes, specifications)
- Define accessibility requirements and validate compliance
- Provide design acceptance criteria and design specs for features
- Collaborate on user workflows and experience edge cases

### Goals
- Ensure features are usable and meet customer needs
- Reduce rework by validating designs early
- Maintain high accessibility and usability standards

### Typical Communication
- Design specs and prototypes in design tools
- Usability testing reports and feedback
- Accessibility checklists and validation notes
- Collaboration in planning meetings and design reviews

### Interactions
- Partners with Product Manager (PdM) to define user outcomes and success criteria
- Hands off designs to Developers with clear specifications
- Coordinates with QA for usability and accessibility validation
- Participates in sprint planning to scope design work

---

## Security & Compliance Lead

### Role Summary
Security and Compliance Leads assess security and compliance risks, define requirements for sensitive features, coordinate vulnerability scanning and remediation, and sign off on compliance checkpoints. They ensure that projects meet security and regulatory standards.

### Responsibilities
- Assess security and compliance risks during planning and execution
- Define security and compliance requirements for sensitive features
- Coordinate vulnerability scanning, penetration testing, and remediation
- Review PRs and releases for security impact
- Sign off on compliance checkpoints and release gates
- Engage in threat modelling for high-risk features

### Goals
- Reduce security and compliance risks to acceptable levels
- Enable fast, secure delivery without delaying releases
- Maintain audit trails and regulatory compliance

### Typical Communication
- Threat modelling sessions during planning
- Security review checklists and audit logs
- Vulnerability reports and remediation tracking
- Sign-off on compliance checkpoints before release

### Interactions
- Engages during planning for threat modelling of high-risk features
- Reviews PRs and releases for security impact
- Works with DevOps for hardened configurations and runtime controls
- Participates in incident response and post-mortems

---

## Release Manager

### Role Summary
Release Managers own release scheduling, runbooks, rollback plans, release notes, and post-deploy verification coordination. They ensure predictable, low-risk releases and rapid communication with stakeholders.

### Responsibilities
- Own release scheduling and communicate release windows
- Create and maintain release runbooks and rollback plans
- Draft and publish release notes
- Coordinate post-deploy verification and smoke testing
- Communicate release status and known issues to stakeholders and support
- Triage and escalate production issues post-release

### Goals
- Minimize release risk and deployment downtime
- Achieve rapid, reliable deployments
- Maintain clear stakeholder and support communication

### Typical Communication
- Release schedules and deployment windows
- Release notes and known-issues documentation
- Post-deploy verification reports
- Stakeholder and support notifications before and after releases

### Interactions
- Coordinates with Delivery Lead to finalize release scope and timeline
- Works with DevOps for deployment execution and rollback
- Coordinates with Support and Customer Success for post-release communication
- Ensures Security Lead has signed off on release
- Participates in incident response if deployment issues occur

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers maintain CI/CD pipelines, observability, environment provisioning, and runtime reliability. They implement deployment automation and rollback mechanisms that enable fast, safe releases.

### Responsibilities
- Maintain and improve CI/CD pipelines (build, test, deploy automation)
- Configure and manage staging and production environments
- Implement observability, logging, monitoring, and alerting
- Provision infrastructure and manage infrastructure-as-code
- Implement deployment automation and rollback mechanisms
- Support incident response and production troubleshooting

### Goals
- Enable fast, reliable, automated deployments
- Maintain high observability and mean-time-to-recovery (MTTR)
- Reduce manual deployment effort and human error

### Typical Communication
- CI/CD pipeline documentation and status
- Infrastructure-as-code repositories and deployment logs
- Monitoring dashboards and alert definitions
- Incident reports and post-mortem action items

### Interactions
- Supports Developers with CI/CD pipelines and local environment setup
- Collaborates with Release Manager on deployment execution and rollback
- Works with Security Lead to implement hardened configurations and security controls
- Participates in incident response and runbook updates
- Provides metrics and logs to PM/PdM for success measurement

---

## Customer Success / Support Liaison

### Role Summary
Customer Success and Support Liaisons represent customer-facing feedback, triage production issues, and communicate support impact to the team. They bridge customer needs and product priorities.

### Responsibilities
- Gather and communicate customer feedback from support channels
- Triage production issues and escalate critical problems
- Track customer-impacting bugs and feature requests
- Communicate support metrics and trends to the product team
- Participate in prioritization discussions with impact of issues on customers
- Support release communications and known-issues documentation

### Goals
- Ensure customer feedback informs product decisions
- Reduce time-to-resolution for customer-impacting issues
- Maintain high customer satisfaction and retention

### Typical Communication
- Support ticket summaries and issue reports
- Customer feedback and feature request tracking
- Customer impact assessments during bug triage
- Post-release customer communication

### Interactions
- Works with PM and PdM on prioritization of bug fixes and feature requests based on customer impact
- Coordinates with Release Manager for post-release communications to customers
- Participates in incident response for customer-impacting issues
- Provides usage data and customer trends to Data Analyst and PdM

---

## Business Analyst

### Role Summary
Business Analysts translate stakeholder needs into clear acceptance criteria, manage requirements traceability, and support effort estimation. They ensure alignment between business objectives and technical execution.

### Responsibilities
- Translate stakeholder needs and business requirements into clear acceptance criteria
- Manage requirements traceability across project artifacts
- Support effort estimation and complexity assessment
- Document business context and decision rationale
- Validate that delivered solutions meet business objectives
- Identify requirements gaps and dependencies

### Goals
- Ensure requirements are clear and testable
- Reduce rework and scope creep through clear specifications
- Maintain traceability from business need to delivery

### Typical Communication
- Requirements specifications and acceptance criteria
- Traceability matrices and impact analysis
- Estimation support and complexity assessments
- Business context documentation and decision logs

### Interactions
- Works with Product Manager (PdM) and PM to refine backlog items and ensure business alignment
- Supports Developers by clarifying requirements and acceptance criteria
- Coordinates with QA to ensure acceptance criteria are testable
- Participates in planning and requirements review meetings

---

## Data Analyst

### Role Summary
Data Analysts define and validate success metrics, set up instrumentation and telemetry, and analyze experiment and usage data. They enable data-driven decisions and measure the impact of delivered features.

### Responsibilities
- Define success metrics aligned with business and product objectives
- Design and implement instrumentation and telemetry
- Analyze experiment, usage, and performance data
- Create dashboards and reports for stakeholders
- Identify trends and anomalies that inform product decisions
- Support hypothesis validation and iterative improvements

### Goals
- Enable data-driven decision-making across the organization
- Measure and demonstrate business impact of delivered features
- Identify opportunities for optimization and improvement

### Typical Communication
- Success metrics definitions and measurement plans
- Instrumentation and telemetry documentation
- Data analysis reports and dashboards
- Hypothesis validation results and recommendations
- Trend reports and anomaly alerts

### Interactions
- Partners with Product Manager (PdM) to define success metrics and measure outcomes
- Works with Developers to ensure metrics are correctly implemented
- Provides data-driven insights to PM for risk surfacing and iteration planning
- Supports DevOps with performance and reliability metrics
- Collaborates with Customer Success on usage trends and customer segmentation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these personas in checklists, templates, and decision points across other process documents.
