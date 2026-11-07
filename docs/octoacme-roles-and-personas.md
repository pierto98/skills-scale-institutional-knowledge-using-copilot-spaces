# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A project may combine roles when appropriate, but responsibilities and decision authority should remain clear. The project charter or governance plan should identify who fills each role and how decisions are escalated.

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
- Work with the Product Manager or Product/Business Owner to clarify requirements and acceptance criteria.
- Coordinate estimates, dependencies, and delivery progress with the Project Manager.
- Consult the Technical Lead on design standards and significant technical decisions.
- Work with the Quality Assurance Lead to make changes testable and resolve defects.

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
- Align product priorities and outcomes with the Executive Sponsor and affected stakeholders.
- Coordinate scope, sequencing, and delivery expectations with the Project Manager.
- Clarify product needs with the Business Analyst and Developers.
- Partner with the Quality Assurance Lead and Product/Business Owner on acceptance criteria and outcome validation.

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
- Coordinate governance, escalations, and organizational support with the Executive Sponsor.
- Align delivery plans and status with the Product Manager and Product/Business Owner.
- Coordinate work, dependencies, and delivery risks with Developers and the Technical Lead.
- Maintain the project risk and decision logs with input from the Risk, Security, or Compliance Owner.
- Coordinate readiness, communications, and handoffs with the Quality Assurance Lead, Change Management and Communications Lead, and relevant operations stakeholders.

---

## Executive Sponsors

### Role Summary
Executive Sponsors provide senior-level accountability for the business case and organizational support. They make or delegate decisions that are outside the authority of the delivery team.

### Responsibilities
- Confirm the project’s strategic alignment and continued business justification
- Secure appropriate organizational support and help resolve resource conflicts
- Approve major funding or scope changes when that authority is assigned to them
- Resolve escalations the Project Manager cannot address within the project team
- Support timely governance decisions and communicate executive-level priorities

### Goals
- Ensure the project remains aligned with organizational priorities
- Enable the team to address significant obstacles and cross-organizational dependencies
- Make escalated decisions promptly and transparently

### Typical Communication
- Governance reviews and milestone decisions
- Escalation discussions with the Project Manager
- Alignment with the Product Manager or Product/Business Owner on outcomes

### Interactions with Other Roles
- Partner with the Project Manager on governance, escalations, and organizational constraints; the sponsor does not take over day-to-day project coordination.
- Align strategic outcomes with the Product Manager or Product/Business Owner, who manages product priorities and business acceptance within delegated authority.
- Consult the Risk, Security, or Compliance Owner on material exposure and the Change Management and Communications Lead on organizational impacts.
- Make decisions only within the approval authority defined by the project’s governance arrangements.

---

## Product or Business Owners

### Role Summary
The Product or Business Owner represents the business need and is accountable for clarifying desired outcomes, business rules, and acceptance of delivered results. This role may be performed by a Product Manager when the project’s governance assigns both sets of responsibilities to that person.

### Responsibilities
- Define desired business outcomes and clarify business rules
- Provide or confirm business priorities and acceptance criteria
- Make business decisions within their delegated authority
- Review deliverables and confirm whether they meet agreed business needs
- Identify business stakeholders who need to contribute to requirements or acceptance

### Goals
- Ensure delivery addresses the intended business need
- Provide timely decisions and reduce ambiguity for the delivery team
- Confirm that completed work is useful and acceptable to its intended users

### Typical Communication
- Requirements and acceptance-criteria reviews
- Prioritization and scope discussions with the Product Manager and Project Manager
- Demonstrations, acceptance reviews, and outcome assessments

### Interactions with Other Roles
- Work with the Product Manager to align business outcomes, product vision, and backlog priorities; clarify who has final prioritization and acceptance authority.
- Coordinate with the Business Analyst to document requirements and resolve questions about business rules.
- Provide Developers and the Technical Lead with timely clarifications without directing technical implementation.
- Agree acceptance criteria with the Quality Assurance Lead and review evidence before business acceptance.
- Escalate decisions outside delegated authority to the Executive Sponsor.

---

## Business Analysts

### Role Summary
Business Analysts connect business needs to project requirements and delivery work. They elicit, analyze, document, and trace requirements but do not replace the Product Manager’s prioritization or the Product/Business Owner’s acceptance authority.

### Responsibilities
- Elicit requirements and process information from stakeholders
- Document business rules, requirements, assumptions, and dependencies
- Trace requirements to planned work, deliverables, and acceptance criteria
- Identify gaps, conflicts, and impacts when requirements change
- Facilitate clarification between business stakeholders and delivery teams

### Goals
- Make needs and requirements clear, testable, and traceable
- Reduce rework caused by misunderstandings or missing information
- Ensure relevant stakeholder input is captured and resolved

### Typical Communication
- Interviews and requirements workshops
- Process maps, requirement records, and decision logs
- Clarification and review sessions with business and delivery roles

### Interactions with Other Roles
- Elicit and validate business needs with the Product/Business Owner, Product Manager, and Stakeholder Representatives.
- Coordinate requirements, dependencies, and change impacts with the Project Manager.
- Explain requirements and business rules to Developers and the Technical Lead.
- Work with the Quality Assurance Lead to ensure requirements and acceptance criteria can be verified.
- Refer priority conflicts to the Product Manager and business acceptance decisions to the Product/Business Owner.

---

## Technical Leads or Solution Architects

### Role Summary
Technical Leads or Solution Architects guide technical design and implementation choices. They help the team understand technical dependencies, constraints, and risks while leaving project coordination to the Project Manager and product prioritization to the appropriate product or business role.

### Responsibilities
- Guide solution design, integration decisions, and technical standards
- Identify technical dependencies, feasibility concerns, and implementation risks
- Support estimates and technical sequencing with Developers and the Project Manager
- Review significant design choices and promote maintainability, reliability, and security
- Advise on technical readiness, operational needs, and release dependencies

### Goals
- Deliver a coherent, secure, maintainable technical solution
- Surface technical risks and constraints early
- Enable effective implementation, testing, and operation of the solution

### Typical Communication
- Technical design reviews and architecture records
- Estimates, dependency reviews, and risk discussions
- Coordination with Developers, Quality Assurance, and operations stakeholders

### Interactions with Other Roles
- Explain technical options and trade-offs to the Product Manager or Product/Business Owner without taking over business prioritization.
- Coordinate estimates, dependencies, and technical risks with the Project Manager.
- Guide Developers on implementation and design while encouraging collaborative review.
- Work with the Quality Assurance Lead on testability and technical quality, and with the Risk, Security, or Compliance Owner on relevant controls.
- Coordinate technical release and operational readiness with the appropriate operations stakeholders.

---

## Quality Assurance Leads

### Role Summary
Quality Assurance Leads coordinate quality planning and verification so that delivery teams have evidence about whether requirements and quality expectations are met. They report quality findings but do not independently approve business acceptance unless that authority is explicitly assigned.

### Responsibilities
- Define or coordinate the test approach and verification activities
- Confirm that requirements and acceptance criteria are testable
- Track defects, test progress, and relevant quality evidence
- Communicate quality risks, gaps, and readiness findings
- Coordinate with delivery roles to verify fixes and regression impacts

### Goals
- Provide timely, objective information about product quality
- Detect issues early and reduce the risk of defects reaching users
- Make release and acceptance decisions better informed by evidence

### Typical Communication
- Test plans, quality reports, and defect records
- Test-readiness and release-readiness reviews
- Coordination with Developers, product/business roles, and the Project Manager

### Interactions with Other Roles
- Work with the Product/Business Owner and Business Analyst to define verifiable acceptance criteria.
- Coordinate test scope and timing with the Project Manager.
- Work with Developers and the Technical Lead to reproduce, prioritize, and resolve defects.
- Share quality evidence with the Product/Business Owner, who makes business acceptance decisions, and with the designated release authority, who makes release decisions.
- Coordinate relevant security or compliance verification with the Risk, Security, or Compliance Owner.

---

## Change Management and Communications Leads

### Role Summary
Change Management and Communications Leads help affected people and organizations understand, prepare for, and adopt project changes. They coordinate change activities and communications but do not replace the Project Manager’s overall project coordination.

### Responsibilities
- Assess how project changes affect users, teams, processes, and operations
- Plan stakeholder communications, training, and adoption support
- Identify readiness concerns and recommend actions to address them
- Coordinate communication timing and channels with project milestones
- Gather feedback about adoption and communicate issues to the project team

### Goals
- Prepare affected groups for changes and reduce avoidable disruption
- Deliver clear, timely, audience-appropriate communications
- Support adoption and sustained use of project outcomes

### Typical Communication
- Stakeholder and impact assessments
- Communication and training plans
- Readiness reviews, feedback channels, and adoption updates

### Interactions with Other Roles
- Coordinate communication plans and milestones with the Project Manager.
- Align messages about intended outcomes with the Executive Sponsor and Product Manager or Product/Business Owner.
- Consult Stakeholder Representatives about audience needs and feedback.
- Coordinate training and operational handoffs with the relevant delivery and operations roles.
- Raise adoption risks to the Project Manager and, when needed, the Executive Sponsor.

---

## Risk, Security, or Compliance Owners

### Role Summary
Risk, Security, or Compliance Owners provide subject-matter oversight for assigned risks and obligations. They identify concerns, advise on controls and mitigations, and escalate issues through the project’s agreed governance.

### Responsibilities
- Identify and assess relevant risks, security concerns, and compliance obligations
- Recommend or define appropriate controls and mitigation actions within their authority
- Assign or coordinate owners and due dates for mitigation work
- Monitor evidence and report unresolved or material risks
- Advise the team when specialist review or escalation is required

### Goals
- Surface material risks and obligations early
- Ensure mitigations have accountable owners and are tracked
- Support informed decisions about residual risk and readiness

### Typical Communication
- Risk and control assessments
- Risk registers, mitigation plans, and evidence reviews
- Escalations and governance updates for material concerns

### Interactions with Other Roles
- Coordinate project-level risk tracking with the Project Manager, who maintains the overall project view and follow-up process.
- Work with the Technical Lead, Developers, and Quality Assurance Lead on technical controls and verification.
- Consult the Product/Business Owner and Business Analyst on business impact and requirements.
- Escalate material risks to the Executive Sponsor or the designated governance authority; do not assume authority to accept risk unless explicitly delegated.

---

## Stakeholder Representatives

### Role Summary
Stakeholder Representatives bring the perspectives of affected users, teams, or stakeholder groups into project planning and review. They provide input and feedback but do not automatically hold decision or approval authority for the groups they represent.

### Responsibilities
- Communicate stakeholder needs, constraints, and concerns to the project team
- Participate in relevant discovery, planning, review, and feedback activities
- Validate whether communications reach the intended stakeholder group
- Identify impacts or adoption concerns that may otherwise be missed
- Share project updates and gather feedback when authorized to do so

### Goals
- Ensure relevant stakeholder perspectives inform project decisions
- Help identify impacts and concerns early
- Support clear two-way communication between the project team and affected groups

### Typical Communication
- Workshops, interviews, and stakeholder reviews
- Feedback summaries and impact discussions
- Coordination with the Business Analyst and Change Management and Communications Lead

### Interactions with Other Roles
- Provide input to the Business Analyst and Product/Business Owner on needs, requirements, and business impacts.
- Work with the Change Management and Communications Lead to identify appropriate communication and adoption approaches.
- Coordinate participation and feedback with the Project Manager.
- Raise concerns to the Product Manager or Product/Business Owner for prioritization and to the Project Manager for delivery coordination.
- Represent stakeholder input without substituting for formal approval by the Executive Sponsor or designated decision-maker.

---

## Role Coordination Across the Project Lifecycle

The project’s governance or delivery plan should name the people filling applicable roles and identify decision owners. The following is a general coordination guide; actual accountability should be confirmed for each project.

| Project activity | Primary coordination or decision role | Roles commonly consulted |
| --- | --- | --- |
| Initiation and business justification | Executive Sponsor; Product/Business Owner | Product Manager, Project Manager, Business Analyst, Stakeholder Representatives |
| Requirements and planning | Product Manager or Product/Business Owner for priorities; Project Manager for the delivery plan | Business Analyst, Developers, Technical Lead, Quality Assurance Lead, Stakeholder Representatives |
| Execution and technical decisions | Developers and Technical Lead for implementation decisions; Project Manager for delivery coordination | Product Manager, Product/Business Owner, Business Analyst, Quality Assurance Lead |
| Risk and compliance review | Risk, Security, or Compliance Owner for subject-matter assessment; designated governance authority for risk acceptance | Project Manager, Executive Sponsor, Technical Lead, Developers, Quality Assurance Lead |
| Testing and business acceptance | Quality Assurance Lead for verification evidence; Product/Business Owner for business acceptance | Developers, Technical Lead, Business Analyst, Product Manager |
| Release and adoption readiness | Designated release authority for release decision; Project Manager for coordination | Quality Assurance Lead, Technical Lead, Change Management and Communications Lead, Risk/Compliance Owner, Product/Business Owner, operations stakeholders |
| Retrospective and improvement | Project Manager facilitates; team members contribute | Developers, Product Manager, Product/Business Owner, Stakeholder Representatives, other relevant roles |

When a person fills multiple roles, document which authority they are exercising for each decision. If responsibilities or approval authorities conflict, use the project’s documented escalation path rather than assuming authority.

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
