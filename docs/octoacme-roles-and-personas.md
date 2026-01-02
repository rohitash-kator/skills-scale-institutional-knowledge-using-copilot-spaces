# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

## Purpose and How to Use This Document

**Purpose**: This document establishes a shared understanding of roles, responsibilities, and interactions across OctoAcme projects. Each persona clarifies what they own, how they collaborate with other roles, and what signals indicate successful handoffs.

**How to Read**: Each persona includes:
- **Role Summary**: A brief description of the persona's purpose
- **Responsibilities**: Key activities and deliverables
- **Primary Touchpoints**: How they interact with other roles
- **Example Deliverables**: Concrete outputs they produce
- **Handoff Criteria**: Signals that indicate readiness to pass work to another role

**When to Introduce a Persona**: Not every project requires every persona. Introduce roles based on:
- **Project complexity**: Larger, cross-functional efforts benefit from specialized roles
- **Risk level**: High-stakes projects may need dedicated Quality Leads or Change Managers
- **Data sensitivity**: Projects handling critical data require Data Stewards
- **Organizational needs**: Align personas with your team structure and stakeholder expectations

Start with core roles (Developer, Product Manager, Project Manager) and add specialized personas as needed.

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

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They elicit, analyze, and document requirements, ensuring that solutions address actual business needs and are feasible to implement.

### Responsibilities
- Gather and validate business requirements from stakeholders
- Translate business needs into detailed functional requirements and user stories
- Create process flows, use case diagrams, and acceptance criteria
- Facilitate requirements workshops and validation sessions
- Maintain requirements traceability and change logs
- Collaborate with UX to ensure designs meet business requirements

### Primary Touchpoints
- **Product Manager**: Align on product vision, prioritize requirements, validate business value
- **Project Manager**: Coordinate on scope, timeline, and resource planning
- **Engineering Lead**: Ensure technical feasibility, clarify implementation details
- **QA**: Define test scenarios based on acceptance criteria
- **Internal Customer**: Validate requirements and sign off on proposed solutions

### Example Deliverables
- Requirements documents with acceptance criteria
- User stories with acceptance criteria in backlog format
- Process flow diagrams and workflow documentation
- Requirements traceability matrix
- Business rules documentation

### Handoff Criteria
**BA hands off requirements to Engineering when:**
- Acceptance criteria are documented and stakeholder-approved
- UX designs are validated (if applicable)
- Dependencies and data requirements are listed
- Business rules and edge cases are clarified
- Success metrics are defined

---

## Quality Lead

### Role Summary
Quality Leads ensure that quality standards are met throughout the development lifecycle. They define testing strategy, coordinate QA activities, and serve as the gatekeeper for release readiness.

### Responsibilities
- Define and maintain Definition of Done and quality standards
- Create test strategies and test plans for features and releases
- Coordinate testing activities across functional, integration, and performance testing
- Track defect metrics and advocate for quality improvements
- Sign off on release readiness based on quality gates
- Mentor team members on testing best practices

### Primary Touchpoints
- **Engineering Lead**: Align on test coverage, automated testing strategy, and technical quality
- **Product Manager**: Understand user scenarios, prioritize testing efforts
- **Project Manager**: Report on quality status, identify risks to timeline
- **Business Analyst**: Validate test scenarios match acceptance criteria
- **Release/Operations Owner**: Coordinate release testing and production readiness

### Example Deliverables
- Test strategies and test plans
- Test case documentation and test results
- Defect reports and quality metrics dashboards
- Release readiness checklists and signoff documentation
- Quality retrospectives and improvement recommendations

### Handoff Criteria
**Quality Lead signs off on release when:**
- All priority 1 and 2 defects are resolved or have approved workarounds
- Test coverage meets agreed-upon thresholds (e.g., 80% unit test coverage)
- Critical user journeys pass end-to-end testing
- Performance benchmarks are met
- Release notes and known issues are documented

---

## Change Manager

### Role Summary
Change Managers facilitate organizational and process changes, ensuring smooth transitions with minimal disruption. They coordinate communication, training, and adoption activities.

### Responsibilities
- Assess change impact across teams, processes, and systems
- Develop change management plans and communication strategies
- Coordinate stakeholder engagement and training activities
- Track change adoption metrics and address resistance
- Update process documentation to reflect changes
- Facilitate change review boards and approval processes

### Primary Touchpoints
- **Project Manager**: Align on change timeline, coordinate stakeholder communication
- **Product Manager**: Understand user impact, plan rollout strategy
- **Engineering Lead**: Assess technical changes, coordinate deployment timing
- **Internal Customer**: Communicate changes, gather feedback, provide training
- **Business Analyst**: Update requirements and process documentation

### Example Deliverables
- Change impact assessments
- Stakeholder communication plans and announcements
- Training materials and knowledge base articles
- Change approval documentation
- Adoption metrics and feedback reports

### Handoff Criteria
**Change Manager approves process/scope change when:**
- Impact analysis is complete and documented
- Stakeholders are informed and key approvers have signed off
- Updated documentation is available
- Training (if needed) is scheduled or delivered
- Rollback plan is documented for significant changes

---

## Internal Customer

### Role Summary
Internal Customers represent the business users or teams who will use the delivered solution. They provide requirements input, validate solutions, and serve as acceptance gatekeepers.

### Responsibilities
- Articulate business needs and success criteria
- Participate in requirements validation and design reviews
- Provide timely feedback during demos and UAT
- Sign off on solution acceptance based on defined criteria
- Champion adoption and provide user feedback post-launch
- Escalate issues or concerns to stakeholders

### Primary Touchpoints
- **Business Analyst**: Provide requirements, validate proposed solutions
- **Product Manager**: Communicate needs, prioritize features
- **QA**: Participate in UAT, report bugs and usability issues
- **Change Manager**: Receive training, provide feedback on change adoption
- **Project Manager**: Communicate availability, coordinate on timeline

### Example Deliverables
- Requirements input and validation feedback
- UAT results and sign-off documentation
- User feedback and enhancement requests
- Use case examples and scenario documentation
- Adoption and satisfaction feedback

### Handoff Criteria
**Internal Customer accepts solution when:**
- Core functionality meets documented acceptance criteria
- Solution is usable in real-world scenarios (UAT passed)
- Known issues are acceptable or have documented workarounds
- Training and support materials are available
- Sign-off criteria defined at project kickoff are met

---

## Data Steward

### Role Summary
Data Stewards ensure data quality, consistency, and governance across systems. They own data definitions, monitor data integrity, and coordinate data-related requirements.

### Responsibilities
- Define and maintain data dictionary and data standards
- Monitor data quality metrics and coordinate remediation
- Coordinate data governance policies and compliance requirements
- Validate data migration and integration accuracy
- Ensure data security and privacy requirements are met
- Facilitate data access requests and ownership clarification

### Primary Touchpoints
- **Engineering Lead**: Define data models, validate technical implementation
- **Business Analyst**: Clarify data requirements, define business rules
- **Product Manager**: Prioritize data quality improvements, align on data roadmap
- **QA**: Validate data integrity in testing environments
- **Compliance/Security**: Ensure data governance and privacy requirements

### Example Deliverables
- Data dictionary and glossary
- Data quality reports and dashboards
- Data governance policies and standards documentation
- Data validation rules and acceptance criteria
- Data migration and reconciliation reports

### Handoff Criteria
**Data Steward approves data deliverables when:**
- Data definitions are documented in data dictionary
- Data quality metrics meet agreed thresholds (e.g., completeness, accuracy)
- Data validation rules are implemented and passing
- Data migration (if applicable) is reconciled and verified
- Data access controls and privacy requirements are validated

---

## Why This Matters

Clearly defined personas improve collaboration and accountability. When everyone understands who owns what, handoffs become smoother, gaps are caught earlier, and teams can scale effectively. These personas provide:

- **Clarity**: Reduces ambiguity about who makes decisions and owns deliverables
- **Efficiency**: Clear handoff criteria minimize back-and-forth and rework
- **Scalability**: New team members can quickly understand role expectations
- **Quality**: Defined responsibilities ensure quality gates aren't skipped
- **Alignment**: Shared language for cross-functional collaboration

Use these personas as a framework to tailor roles to your project's specific needs.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

