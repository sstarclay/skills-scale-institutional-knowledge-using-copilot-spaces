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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy, test planning, and acceptance validation. They collaborate with Developers and Product Managers to define quality standards and ensure features meet acceptance criteria before release.

### Responsibilities
- Define quality standards and test strategy for the project
- Create and maintain test plans aligned with acceptance criteria
- Coordinate automated and manual testing efforts
- Validate features meet quality gates before promotion to production
- Identify and prioritize quality risks
- Support incident investigation and quality improvements

### Goals
- Deliver defect-free or high-quality releases
- Reduce production issues through effective testing
- Establish scalable, repeatable test processes
- Enable continuous quality feedback

### Typical Communication
- Planning sessions (quality requirements and test strategy)
- Daily standups (test progress and blockers)
- Code review discussions (test coverage and quality concerns)
- Pre-release quality gates and sign-offs
- Post-release incident reviews

### Cross-functional Interactions
- **With Developers**: Collaborates on test strategy, reviews code for testability, identifies quality risks
- **With Product Managers**: Validates acceptance criteria and defines quality expectations
- **With DevOps/Release Engineers**: Coordinates smoke testing and release validation
- **With Tech Lead/Architect**: Reviews architecture for testability and quality concerns

---

## DevOps/Release Engineer

### Role Summary
DevOps/Release Engineers manage deployment pipelines, infrastructure, and release automation. They enable fast, safe, and repeatable deployments while maintaining system reliability and observability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure and deployment environments (staging, production)
- Automate deployment, monitoring, and rollback procedures
- Coordinate release scheduling and deployment windows
- Maintain release runbooks and incident playbooks
- Monitor system health and performance metrics
- Troubleshoot deployment issues and support rollbacks

### Goals
- Enable frequent, low-risk deployments
- Minimize deployment-related downtime and failures
- Automate repetitive operational tasks
- Maintain high system availability and observability

### Typical Communication
- Release planning meetings (deployment strategy and windows)
- Infrastructure and capacity planning discussions
- Daily operations and monitoring reviews
- Incident response and post-mortems
- Documentation of runbooks and playbooks

### Cross-functional Interactions
- **With Project Managers**: Coordinates release timelines and deployment windows
- **With Developers**: Troubleshoots deployment issues and provides deployment guidance
- **With QA/Testing Lead**: Coordinates smoke testing and deployment validation
- **With Security/Compliance Officer**: Integrates security scanning and compliance checks into pipelines
- **With Support/Operations Lead**: Handoff runbooks and operational procedures

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure the project meets security standards, compliance requirements, and risk policies. They work cross-functionally to embed security practices and reduce organizational and customer risk.

### Responsibilities
- Define security requirements and compliance needs for the project
- Review architecture and design for security risks
- Ensure security testing and scanning are integrated into CI/CD
- Coordinate compliance assessments and audits
- Investigate security incidents and coordinate response
- Track and report on security and compliance metrics
- Advise on data protection, encryption, and access controls

### Goals
- Prevent security breaches and compliance violations
- Embed security into the development process
- Reduce risk to customers and the organization
- Maintain compliance with applicable regulations

### Typical Communication
- Design and architecture reviews (security assessment)
- Planning meetings (compliance and security requirements)
- Security scanning and test result reviews
- Incident response (security incidents)
- Risk register reviews and updates
- Compliance reporting and stakeholder briefings

### Cross-functional Interactions
- **With Tech Lead/Architect**: Reviews technical designs for security risks and compliance
- **With Developers**: Provides security guidance and conducts code security reviews
- **With DevOps/Release Engineers**: Integrates security scanning and compliance checks into CI/CD
- **With Project Managers**: Escalates security risks and compliance blockers
- **With Stakeholder/Sponsor**: Reports on compliance status and risk posture

---

## Tech Lead/Architect

### Role Summary
Tech Leads and Architects provide technical authority, guide design decisions, and ensure the project follows architectural principles and best practices. They enable Developers to build scalable, maintainable solutions.

### Responsibilities
- Define technical vision and architectural approach
- Review and approve technical designs
- Guide solution design and technology choices
- Mentor Developers and support technical problem-solving
- Identify technical risks and propose mitigations
- Ensure adherence to coding standards and best practices
- Participate in code reviews and architecture discussions

### Goals
- Build scalable, maintainable, and performant systems
- Reduce technical debt and rework
- Align projects with organizational technology standards
- Enable team growth and capability building

### Typical Communication
- Design and architecture review meetings
- Code review discussions and mentoring
- Technical spike and feasibility analyses
- Planning sessions (technical estimates and risks)
- Engineering leadership and strategy discussions

### Cross-functional Interactions
- **With Developers**: Reviews technical designs, mentors on best practices, provides technical guidance
- **With Project Managers**: Estimates technical complexity and identifies risks during planning
- **With QA/Testing Lead**: Ensures architecture supports testability and quality requirements
- **With Security/Compliance Officer**: Reviews architecture for security and compliance requirements
- **With DevOps/Release Engineers**: Ensures system design supports deployment and operational requirements

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide executive oversight, approve funding and scope decisions, and ensure the project aligns with organizational strategy. They represent business priorities and make key go/no-go decisions.

### Responsibilities
- Approve project charter and resource allocation
- Set strategic priorities and business objectives
- Make trade-off decisions on scope, timeline, and budget
- Remove organizational blockers and escalated issues
- Provide executive visibility and communicate with leadership
- Approve major milestones and go-live decisions
- Support retrospectives and lessons-learned reviews

### Goals
- Deliver business value and strategic outcomes
- Ensure efficient use of organizational resources
- Maintain organizational alignment and transparency
- Support team success through sponsorship and advocacy

### Typical Communication
- Executive steering committee and leadership briefings
- Project charter and milestone approvals
- Escalation handling for organizational blockers
- Monthly or quarterly stakeholder updates
- Post-project reviews and ROI assessments

### Cross-functional Interactions
- **With Project Managers**: Reviews project health, approves key decisions, removes blockers
- **With Product Managers**: Aligns product strategy with business objectives and funding
- **With Security/Compliance Officer**: Approves risk acceptance and compliance strategy
- **With Team Leadership**: Makes resource and priority decisions affecting multiple initiatives

---

## Support/Operations Lead

### Role Summary
Support/Operations Leads coordinate post-release support, customer operations, and incident response. They ensure smooth handoff from development to operations and maintain system reliability and customer satisfaction.

### Responsibilities
- Prepare support team for release (runbooks, FAQs, training)
- Coordinate customer communications and support escalations
- Manage production incidents and outages
- Monitor system health and customer-reported issues
- Gather customer feedback and operational insights
- Support root-cause analysis and corrective actions
- Coordinate upgrades, patches, and maintenance activities

### Goals
- Ensure smooth customer experience post-release
- Minimize production downtime and customer impact
- Resolve customer issues quickly and effectively
- Provide operational insights for continuous improvement

### Typical Communication
- Pre-release planning (support readiness and runbooks)
- Knowledge transfer and team training sessions
- Daily monitoring and incident calls
- Escalation of critical issues to development teams
- Customer feedback and operational metrics reporting
- Post-incident reviews and action item tracking

### Cross-functional Interactions
- **With Project Managers**: Coordinates release timing and support readiness planning
- **With Developers**: Escalates production issues and provides customer feedback
- **With DevOps/Release Engineers**: Coordinates incident response and rollback decisions
- **With QA/Testing Lead**: Validates release quality through production monitoring
- **With Product Managers**: Provides operational insights and customer feedback for prioritization

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional interactions highlight how personas work together to ensure project success.
