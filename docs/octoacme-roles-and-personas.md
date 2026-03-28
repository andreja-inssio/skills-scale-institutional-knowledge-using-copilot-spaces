# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Roles are organized into two groups:
- **Core Delivery Roles**: Developers, Product Managers, and Project Managers — directly accountable for building and shipping features.
- **Support & Specialist Personas**: UX Designer, DevOps Engineer, Documentation Specialist/Technical Writer, Support/Customer Success Lead, and Security Lead — provide specialized expertise that enables and enhances delivery.

---

## Core Delivery Roles

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

## Support & Specialist Personas

---

## UX Designer

### Role Summary
Advocates for user experience and accessibility in all project outputs, ensuring that features are usable, delightful, and inclusive.

### Responsibilities
- Conduct user research, usability testing, and synthesize findings into actionable insights
- Design wireframes, prototypes, and high-fidelity mockups
- Define and maintain design systems and accessibility standards
- Collaborate with Product Managers and Developers to ensure features meet user needs
- Review pull requests and sprint deliverables for usability and design consistency

### Goals
- Maximize usability and user satisfaction across all product surfaces
- Ensure accessibility compliance and inclusive design
- Reduce user-facing issues through early design validation

### Typical Communication
- Design reviews and prototype walkthroughs with Product Managers and Developers
- Participation in sprint planning and review meetings
- Usability findings reports shared with the full team

### Interactions with Other Roles
- **Product Managers**: Co-define user stories, acceptance criteria, and success metrics from a user perspective.
- **Developers**: Provide design specs and usability feedback during implementation; review PRs affecting the UI.
- **Project Managers**: Flag design dependencies or scope changes that affect timelines.
- **Documentation Specialist**: Ensure user-facing documentation reflects the actual UI and user flows.

---

## DevOps Engineer

### Role Summary
Ensures robust, reliable, and secure deployment pipelines and production environments, enabling teams to ship confidently and recover quickly from incidents.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Monitor infrastructure health, performance, and reliability
- Implement and enforce security controls in the deployment pipeline
- Coordinate with Developers for releases, rollback plans, and incident response
- Manage environment configuration, secrets, and access controls

### Goals
- Enable fast, reliable, and safe deployments
- Minimize production incidents and mean time to recovery (MTTR)
- Maintain infrastructure compliance with security and operational standards

### Typical Communication
- Release coordination meetings with Project Managers and Developers
- Incident response communication channels
- Infrastructure and pipeline status updates in project boards

### Interactions with Other Roles
- **Developers**: Review release readiness, define deployment steps, and support incident triage.
- **Project Managers**: Communicate deployment windows, risks, and production status.
- **Security Lead**: Implement security controls and respond to findings from security reviews.
- **Support/Customer Success Lead**: Provide production health context during incidents or release issues.

---

## Documentation Specialist / Technical Writer

### Role Summary
Maintains clear, accurate, and up-to-date documentation for users and internal teams, ensuring that processes, features, and onboarding materials reflect actual practice.

### Responsibilities
- Gather technical information from subject matter experts across all roles
- Produce and maintain user guides, API references, process docs, and onboarding materials
- Ensure project and process documentation is consistent, current, and accessible
- Review pull requests that affect documentation or user-facing content
- Attend retrospectives to capture lessons learned and update runbooks accordingly

### Goals
- Reduce knowledge silos and onboarding friction
- Ensure documentation quality keeps pace with product and process changes
- Make it easy for any team member to find authoritative information

### Typical Communication
- Regular syncs with Developers and Product Managers for feature documentation
- Retrospective participation for process improvement notes
- PR reviews and documentation feedback loops with the full team

### Interactions with Other Roles
- **Developers**: Interview for technical accuracy, review PRs for doc impact.
- **Product Managers**: Align on user-facing messaging and release notes.
- **Project Managers**: Ensure process docs (risk registers, meeting notes) are up to date.
- **UX Designer**: Coordinate on user interface copy, tooltips, and onboarding flows.
- **Support/Customer Success Lead**: Incorporate common support questions into documentation to reduce ticket volume.

---

## Support / Customer Success Lead

### Role Summary
Represents user and customer perspectives post-release, managing feedback loops and ensuring delivery teams are informed of real-world product impact.

### Responsibilities
- Track and triage support tickets and user feedback
- Champion feature requests and bug reports from customers to Product Managers
- Assist with drafting and reviewing release notes and customer-facing communications
- Communicate project status and release impacts to external stakeholders
- Close the feedback loop between delivery teams and end users

### Goals
- Ensure a smooth user experience from release through ongoing use
- Reduce support ticket volume through proactive communication and documentation
- Strengthen customer trust and satisfaction

### Typical Communication
- Regular feedback summaries shared with Product Managers and Project Managers
- Participation in release readiness reviews and post-release check-ins
- Customer-facing communications and announcements

### Interactions with Other Roles
- **Product Managers**: Provide quantitative and qualitative customer feedback to inform prioritization.
- **Project Managers**: Flag critical or high-volume issues that require escalation or urgent fixes.
- **Developers**: Report production bugs with reproduction steps and customer impact context.
- **Documentation Specialist**: Identify gaps in user-facing documentation based on common support questions.

---

## Security Lead

### Role Summary
Ensures security best practices are applied throughout the project lifecycle, from design to production, and leads the response to security incidents.

### Responsibilities
- Review system architecture and design for security risks and vulnerabilities
- Conduct or coordinate security reviews, penetration testing, and threat modeling
- Define and enforce security standards and compliance requirements
- Assist with security incident response, triage, and post-incident review
- Promote a security-conscious culture across all roles

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure compliance with company and industry security standards
- Minimize impact and recovery time from security incidents

### Typical Communication
- Security review sessions during project planning and design phases
- Participation in release planning to verify security requirements are met
- Security incident notifications and post-mortems

### Interactions with Other Roles
- **Developers**: Provide security requirements, review code for vulnerabilities, and support remediation.
- **DevOps Engineer**: Define and validate security controls in the CI/CD pipeline and infrastructure.
- **Project Managers**: Flag security risks in the risk register and communicate compliance requirements.
- **Product Managers**: Advise on security implications of product decisions and data handling.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Core Delivery Roles are responsible for day-to-day delivery; Support & Specialist Personas provide expertise that improves quality, safety, and sustainability of delivery.

