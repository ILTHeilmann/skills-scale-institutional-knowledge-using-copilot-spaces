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
UX Designers ensure that user-centered design principles are embedded throughout project delivery. They translate user needs and business goals into intuitive interfaces and validated design solutions.

### Responsibilities
- Conduct user research (interviews, usability tests, surveys) to surface real user needs
- Create wireframes, prototypes, and high-fidelity designs for review
- Define and document UX acceptance criteria alongside product specs
- Validate designs through usability testing before development begins
- Maintain and evolve the design system and pattern library
- Iterate on designs based on feedback from developers, QA, and stakeholders

### Goals
- Deliver experiences that are usable, accessible, and aligned with user expectations
- Reduce rework by catching UX issues before implementation
- Build a shared design language across the product

### Typical Communication
- Design reviews with Product Manager and Developers at requirements and sprint planning phases
- Usability test findings shared with Product Manager and Project Manager
- Design handoff assets (Figma, Storybook, etc.) with annotated specs for Developers
- Participation in retrospectives to surface UX-related friction

### Interactions with Existing Roles
- **Product Manager:** Collaborates on defining problem statements, user personas, and success metrics. Reviews prioritized backlog items to validate UX implications before sprint start.
- **Developers:** Provides detailed design specs and annotated prototypes; participates in code reviews to verify visual fidelity. Raises design debt as backlog items.
- **Project Manager:** Flags design milestones and dependencies; raises blockers (e.g., pending user research results) in weekly delivery syncs.
- **Lifecycle touchpoints:** Initiation (user research to frame the problem), Planning (UX acceptance criteria, design milestones), Execution (design reviews, handoff), Release (post-deploy UX monitoring and feedback collection).

---

## DevOps Engineer

### Role Summary
DevOps Engineers streamline and automate the build, deployment, and infrastructure management practices that enable the team to ship reliably and at pace.

### Responsibilities
- Design, maintain, and improve CI/CD pipelines and deployment automation
- Manage cloud infrastructure, environments (dev, staging, production), and configuration
- Define and enforce security, compliance, and reliability standards in pipelines
- Monitor production health (uptime, error rates, latency) and respond to incidents
- Support release rollbacks and post-incident root-cause analysis
- Collaborate on capacity planning and cost optimization

### Goals
- Reduce time from commit to production with safe, automated pipelines
- Maintain system reliability and minimize mean time to recovery (MTTR)
- Shift security and quality checks left into the development workflow

### Typical Communication
- Release readiness sync with Project Manager before each deployment window
- Pipeline or infrastructure change notifications to Developers and QA Lead
- Incident reports and post-mortem summaries shared with Project Manager and stakeholders
- Participation in sprint planning to size infrastructure and automation work

### Interactions with Existing Roles
- **Developers:** Defines branching, build, and merge standards; reviews infrastructure-as-code PRs; pairs on debugging pipeline failures.
- **QA Lead:** Integrates automated test suites into CI pipelines; coordinates staging environment availability for QA runs.
- **Project Manager:** Communicates deployment schedules, downtime windows, and incident status. Updates the risk register with infrastructure risks.
- **Lifecycle touchpoints:** Planning (CI/CD design, environment setup), Execution (pipeline maintenance, automated testing integration), Release (deployment execution, smoke tests, rollback), Retrospective (incident learnings, pipeline improvement actions).

---

## QA Lead

### Role Summary
The QA Lead champions quality best practices and test strategies across the project, ensuring that features meet acceptance criteria and that defects are caught early.

### Responsibilities
- Draft and maintain the overall test strategy and test plans (unit, integration, end-to-end, regression)
- Coordinate manual and automated testing efforts across the team
- Verify that acceptance criteria are testable and clearly defined before sprint start
- Triage, prioritize, and track defects through resolution
- Own the QA column on the project board and report quality metrics
- Define and enforce the team's Definition of Done quality gates
- Facilitate user acceptance testing (UAT) with stakeholders where required

### Goals
- Catch defects as early as possible in the development cycle
- Maintain a stable, well-understood test suite that supports confident releases
- Drive a culture of shared quality ownership across the team

### Typical Communication
- Test planning sessions with Product Manager and Developers at sprint start
- Defect triage meetings or async updates on high-priority bugs
- Quality metrics and test coverage reports shared in weekly delivery sync
- Go/no-go recommendation to Project Manager before each release

### Interactions with Existing Roles
- **Product Manager:** Collaborates to ensure acceptance criteria are testable; raises concerns about scope ambiguity before work is started.
- **Developers:** Reviews and improves automated test coverage; pairs on complex test scenarios; unblocks failing CI checks.
- **Project Manager:** Escalates blocking defects or test infrastructure issues during standups; provides release readiness sign-off.
- **DevOps Engineer:** Aligns on test environment stability, CI integration, and automated pipeline triggers.
- **Lifecycle touchpoints:** Planning (test strategy, DoD quality gates), Execution (test execution, defect tracking, QA board column), Release (release readiness sign-off, regression run), Retrospective (quality metrics review, process improvements).

---

## Data Analyst

### Role Summary
Data Analysts provide data-driven insights through collection, analysis, and reporting to guide product and project decisions at every stage of the lifecycle.

### Responsibilities
- Define and instrument project success metrics and key performance indicators (KPIs)
- Build and maintain dashboards and reports for team and stakeholder visibility
- Design and analyze experiments (A/B tests, feature flags) in collaboration with the Product Manager
- Interpret results and surface actionable insights to inform backlog prioritization
- Identify data quality issues and coordinate with Developers on instrumentation fixes
- Support retrospectives with quantitative data on delivery and product performance

### Goals
- Make data accessible and understandable for all team members
- Enable evidence-based prioritization and decision making
- Ensure reliable, consistent instrumentation across features

### Typical Communication
- Metrics review with Product Manager and Project Manager at planning and retrospective stages
- Data quality or instrumentation issues raised as backlog items with Developers
- Dashboard links and analysis summaries shared in stakeholder updates
- Experiment readout sessions with Product Manager and relevant stakeholders

### Interactions with Existing Roles
- **Product Manager:** Aligns on success metrics definitions and experiment design; provides data to validate or challenge prioritization decisions.
- **Project Manager:** Supplies delivery metrics (velocity, cycle time, defect rate) for status reports and retrospectives.
- **Developers:** Collaborates on analytics instrumentation (event tracking, logging) and reviews data pipelines for correctness.
- **Lifecycle touchpoints:** Initiation (baseline metrics, success criteria definition), Planning (KPI alignment, dashboard setup), Execution (monitoring, experiment analysis), Release (release impact measurement), Retrospective (data-backed retrospective insights).

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See the [RACI Matrix](octoacme-raci-matrix.md) for a summary of who is Responsible, Accountable, Consulted, and Informed for each key project activity.

