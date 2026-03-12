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
UX Designers create intuitive, user-centered interfaces and workflows. They gather user research, conduct usability testing, and advocate for the end-user experience throughout the product lifecycle.

### Responsibilities
- Design wireframes, prototypes, and high-fidelity mockups
- Conduct user research, interviews, and usability tests
- Define and maintain design system components and patterns
- Translate product requirements into user-friendly flows
- Iterate on designs based on user feedback and data
- Document design decisions and rationale

### Goals
- Ensure product experiences are accessible, intuitive, and delightful
- Reduce user friction and support task completion
- Align design with product vision and technical feasibility

### Typical Communication
- Design review meetings with Product Managers and Developers
- Prototype walkthroughs and usability test readouts with QA and Stakeholders
- Handoff documentation (specs, annotations) shared with Developers

### Collaboration with Existing Roles
- **Product Managers**: Align on user needs, success metrics, and feature scope; participate in backlog refinement
- **Developers**: Provide detailed specs and assets; review implementation for design fidelity
- **QA/Testing**: Share acceptance flows and design expectations to inform test cases
- **Project Managers**: Report design deliverable status; flag design dependencies that affect timelines

---

## Technical Writer

### Role Summary
Technical Writers produce clear, accurate, and accessible documentation for features, APIs, processes, and end users. They ensure that knowledge is captured and shared effectively across the team and with customers.

### Responsibilities
- Author and maintain user guides, API references, release notes, and process docs
- Interview subject-matter experts to gather content
- Review and update documentation with each release
- Establish and enforce documentation standards and templates
- Identify documentation gaps and proactively fill them

### Goals
- Reduce support burden through clear self-service documentation
- Accelerate onboarding for new team members and users
- Maintain a single source of truth for product knowledge

### Typical Communication
- Documentation reviews with Developers and Product Managers before releases
- Coordination with Support Specialists to identify frequently asked questions
- Updates to docs repository alongside feature PRs

### Collaboration with Existing Roles
- **Developers**: Review technical accuracy of implementation docs and API references
- **Product Managers**: Align on feature descriptions, release notes, and documentation scope
- **Project Managers**: Coordinate documentation milestones within the release schedule
- **Support Specialists**: Incorporate common user questions into guides and FAQs

---

## Security Engineer

### Role Summary
Security Engineers identify, assess, and mitigate security risks across the project. They embed security practices into the development lifecycle and coordinate incident response.

### Responsibilities
- Conduct threat modeling and security reviews of new features
- Define and maintain security standards, policies, and runbooks
- Integrate and monitor security scanning tools in CI/CD pipelines
- Lead security incident response and post-incident reviews
- Advise Developers on secure coding practices
- Track and prioritize remediation of vulnerabilities

### Goals
- Minimize the attack surface and security risk exposure
- Achieve rapid detection and response for security incidents
- Build a security-aware engineering culture

### Typical Communication
- Security review meetings before major releases
- Vulnerability reports and remediation tracking shared with Developers and PMs
- Incident response communications to stakeholders and on-call teams
- Security-focused retrospectives after incidents

### Collaboration with Existing Roles
- **Developers**: Provide secure coding guidance; review PRs for security implications
- **Product Managers**: Advise on security trade-offs during prioritization
- **Project Managers**: Report security risks in the risk register; flag blockers affecting release readiness
- **Operations Lead**: Coordinate on infrastructure security and incident response procedures

---

## Operations Lead

### Role Summary
Operations Leads oversee release logistics, deployment pipelines, environment management, and operational health. They bridge development and production, ensuring smooth, low-risk deployments and reliable system operations.

### Responsibilities
- Own and maintain CI/CD pipelines and deployment automation
- Manage environment provisioning and configuration (dev, staging, production)
- Coordinate deployment windows and release scheduling
- Monitor system health, alerts, and on-call rotations
- Lead incident response for operational issues
- Document deployment runbooks and operational procedures

### Goals
- Achieve reliable, repeatable, and low-risk deployments
- Reduce mean time to recovery (MTTR) for incidents
- Maintain environment stability and operational observability

### Typical Communication
- Pre-release deployment readiness reviews with Developers and QA
- Incident status updates to stakeholders and on-call teams
- Post-deployment health reports and retrospectives

### Collaboration with Existing Roles
- **Developers**: Review infrastructure changes; assist with deployment debugging
- **Project Managers**: Coordinate deployment scheduling and notify of environment risks
- **Product Managers**: Communicate operational constraints affecting release timing
- **Security Engineers**: Align on infrastructure security controls and incident response procedures
- **QA/Testing**: Support smoke test execution in staging and production environments

---

## Support Specialist

### Role Summary
Support Specialists are the primary interface between users and the product team. They triage incoming questions and issues, resolve user-facing problems, and relay feedback to improve the product.

### Responsibilities
- Respond to and triage user support requests and bug reports
- Reproduce and document issues for the development team
- Maintain support knowledge base and FAQ documentation
- Escalate critical or systemic issues to the product and engineering team
- Track resolution status and communicate outcomes to users
- Surface recurring themes and user pain points to Product Managers

### Goals
- Achieve high user satisfaction and fast resolution times
- Reduce repeat issues through root-cause fixes and improved documentation
- Create a feedback loop between users and the product team

### Typical Communication
- Daily triage of support queue; weekly support review with PM and QA
- Bug reports and repro steps submitted as issues in the project tracker
- Escalation notifications to Project and Product Managers for critical issues

### Collaboration with Existing Roles
- **Product Managers**: Share user feedback trends to inform roadmap decisions
- **Developers**: Provide reproduction steps and context for bug fixes
- **QA/Testing**: Coordinate on validating fixes and confirming resolution
- **Technical Writers**: Contribute to FAQ and guide updates based on common questions
- **Project Managers**: Escalate critical customer-impacting issues for prioritization

---

## Data Analyst

### Role Summary
Data Analysts track project KPIs, analyze product usage and outcomes, and present actionable insights. They enable data-driven decisions across the team.

### Responsibilities
- Define, instrument, and monitor key performance indicators (KPIs)
- Build and maintain dashboards for project health and product metrics
- Analyze feature adoption, usage patterns, and outcome data
- Present findings and recommendations to Product Managers and stakeholders
- Support A/B test design and statistical analysis
- Ensure data quality and integrity across reporting systems

### Goals
- Enable confident, evidence-based product and project decisions
- Surface trends and anomalies before they become problems
- Quantify the impact of delivered features and improvements

### Typical Communication
- Bi-weekly metrics reviews with Product Managers and Project Managers
- Dashboard links shared in sprint reviews and stakeholder reports
- Ad-hoc analysis requests addressed within agreed SLAs

### Collaboration with Existing Roles
- **Product Managers**: Align on success metrics; provide data to validate prioritization decisions
- **Project Managers**: Contribute metrics to weekly status reports and retrospectives
- **Developers**: Coordinate on instrumentation and data pipeline implementation
- **UX Designers**: Share behavioral data to inform design decisions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

