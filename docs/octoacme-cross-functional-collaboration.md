# OctoAcme — Cross-Functional Collaboration Guide

## Purpose
Provide patterns and best practices for effective collaboration between specialized roles to deliver integrated solutions.

## Collaboration Framework

### The Collaboration Loop

```
Plan → Design → Build → Validate → Release → Learn
  ↓      ↓       ↓       ↓        ↓       ↓
  PM     Arch    Dev     QA      Ops    Retro
  PdM    Design  Dev     Test    PM     All
  BA     Dev     QA      Prod    Comms
                                 Sponsors
```

Each phase requires specific roles to collaborate:

### Planning Phase Collaboration

**Primary participants**: PM, PdM, Technical Architect, Business Analyst, Stakeholder

**Key activities**:
1. Define business requirements and success metrics (PdM + BA + Stakeholder)
2. Identify technical constraints and architectural approach (Arch + Dev Lead)
3. Assess risks and dependencies (PM + all leads)
4. Create backlog with acceptance criteria (PdM + Arch + BA)
5. Estimate effort (Dev Team + Arch)

**Collaboration practices**:
- Use requirements translation sessions to align business and technical perspectives
- Document trade-offs and decisions for future reference
- Validate estimates across different specialties (dev time ≠ QA time ≠ design time)

**Outcome**: Agreed backlog, resource plan, and risk register

---

### Design Phase Collaboration

**Primary participants**: Technical Architect, UX/Design Lead, Developers, QA Lead

**Key activities**:
1. Create system and UX designs (Arch + Design Lead)
2. Design for testability (Arch + Dev + QA Lead)
3. Plan test approach (QA + Developers)
4. Design for operability (Arch + DevOps)
5. Review and align (All)

**Collaboration practices**:
- Parallel design streams (technical, UX, operations)
- Design reviews with diverse perspectives
- Testability and operability checks early
- Document assumptions and trade-offs

**Outcomes**: 
- Technical design document
- UX wireframes and specs
- Test plan
- Operational readiness checklist

---

### Build Phase Collaboration

**Primary participants**: Developers, QA Lead, Technical Architect (oversight), DevOps (as needed)

**Key activities**:
1. Daily standups: status, blockers, dependencies (All)
2. Code reviews with architectural guidance (Dev + Arch)
3. Continuous testing (Dev + QA)
4. Risk and issue escalation (Dev → PM)
5. Design problem-solving (Dev + Arch + Design)

**Collaboration practices**:
- Pair programming on complex or risky areas
- Continuous feedback loops between dev and QA
- Regular architect office hours for design questions
- Clear escalation paths for blockers

**Outcomes**:
- Completed features
- Test coverage metrics
- Risk/issue log updated
- Readiness for QA phase

---

### Validation (QA) Phase Collaboration

**Primary participants**: QA/Testing Lead, Developers, Product Manager, UX/Design Lead

**Key activities**:
1. Execute test plan (QA)
2. Triage and prioritize defects (QA + Dev + PM)
3. Validate acceptance criteria (QA + PdM)
4. Usability testing (QA + Design + PdM)
5. Performance and security validation (QA + Arch)

**Collaboration practices**:
- Defect triage sessions with dev and PM
- Test result transparency (visible metrics)
- Fast feedback loops for defect fixes
- Go/no-go decision with all key stakeholders

**Outcomes**:
- Defect report with priority and resolution
- Acceptance sign-off from Product Manager
- Readiness assessment for release

---

### Release Phase Collaboration

**Primary participants**: DevOps/Infrastructure, Developers, PM, Sponsor, Operations team

**Key activities**:
1. Deploy to staging (DevOps + Dev)
2. Run smoke tests and validation (DevOps + QA + Ops)
3. Deploy to production (DevOps)
4. Monitor and verify (Ops + DevOps)
5. Announce and celebrate (PM + Comms + Sponsor)

**Collaboration practices**:
- Coordinated deployment checklist
- Pre-defined escalation contacts
- Rollback plan agreement
- Post-deployment verification

**Outcomes**:
- Feature live in production
- Release notes distributed
- Stakeholders notified
- Monitoring active

---

### Retrospective Phase Collaboration

**Primary participants**: All team members

**Key activities**:
1. Gather feedback on what went well and what didn't (All)
2. Root cause analysis for major issues (Leads + relevant roles)
3. Identify action items for improvement (All contribute, owners assigned)
4. Celebrate successes (Team)

**Collaboration practices**:
- Blameless retrospectives
- Psychological safety for honest feedback
- Data-driven insights (metrics, logs)
- Equitable speaking time

**Outcomes**:
- Retrospective notes
- Action items with owners and due dates
- Improvements for next project

---

## Common Collaboration Patterns

### 1. The Async Design Review

**When to use**: Technical or UX decisions that don't need real-time discussion

**Process**:
1. Designer/Architect posts proposal with context and trade-offs
2. Stakeholders review asynchronously over 24-48 hours
3. Async feedback in comments
4. Decision made if consensus; if blocked, schedule sync
5. Document decision and move forward

**Best for**: Lower-risk decisions, time-zone challenges, parallel work streams

---

### 2. The Synchronous Decision Session

**When to use**: High-stakes decisions, conflicting opinions, complex trade-offs

**Process**:
1. Pre-read: context, proposals, concerns sent in advance
2. Quick intro: Frame the decision and options
3. Debate: Structured discussion of trade-offs
4. Decide: Decision maker calls the decision
5. Capture: Document decision and dissenting opinions
6. Communicate: Share decision with broader team

**Best for**: Strategic decisions, alignment needed across functions

---

### 3. The Pair Problem-Solving

**When to use**: Complex technical problem, cross-functional challenge, knowledge transfer

**Process**:
1. Define the problem clearly
2. Pair two people with different expertise (e.g., Dev + QA, or Arch + PM)
3. Work through problem space together
4. Document learnings and decision
5. Share outcome with team

**Best for**: Unblocking, learning, innovative solutions

---

### 4. The Dependency Checkpoint

**When to use**: Managing handoffs between teams or phases

**Process**:
1. Schedule checkpoint before dependency is needed
2. Review: Is the dependency complete and ready?
3. Test: Verify it meets requirements
4. Accept: Downstream team confirms readiness
5. Escalate: If not ready, escalate blockers

**Best for**: Cross-team coordination, preventing downstream surprises

---

## Role-Specific Collaboration Tips

### For Developers
- **Embrace architecture reviews** – view them as learning, not gatekeeping
- **Share progress early** – invite feedback on direction before completing work
- **Collaborate on testing** – work with QA on test strategy, not just test execution
- **Speak up about risks** – escalate technical concerns early

### For Product Managers
- **Involve teams early** – technical and QA input during requirements phase
- **Make priorities clear** – communicate trade-offs and rationale
- **Accept criteria over scope** – define quality and acceptance clearly
- **Be available for questions** – remove ambiguity fast

### For Project Managers
- **Coordinate, don't control** – enable team collaboration, don't dictate
- **Make dependencies visible** – track and communicate cross-team needs
- **Escalate appropriately** – don't let issues fester
- **Celebrate collaboration** – recognize cross-functional work

### For Architects
- **Document trade-offs** – help team understand why decisions were made
- **Be accessible** – office hours and quick consultations
- **Empower others** – teach principles, don't dictate implementation
- **Stay connected to execution** – understand real-world constraints

### For QA/Testing
- **Partner early** – engage in design phase, not just test phase
- **Provide metrics** – help team see quality signals
- **Coach on testing** – raise quality bar across all roles
- **Be a customer advocate** – represent user perspective

---

## Collaboration Health Checkup

Use these questions to assess collaboration effectiveness:

**Communication**
- [ ] Do all roles understand their responsibilities?
- [ ] Are decisions documented and communicated clearly?
- [ ] Are communication channels clear (sync, async, escalation)?

**Alignment**
- [ ] Does everyone understand project goals and success metrics?
- [ ] Are priorities aligned across all roles?
- [ ] Are trade-offs discussed transparently?

**Accountability**
- [ ] Are owners clear for each phase and decision?
- [ ] Do people take ownership without waiting for permission?
- [ ] Are blockers escalated promptly?

**Learning**
- [ ] Are retrospectives honest and blameless?
- [ ] Do team members learn from each other?
- [ ] Are improvements actually implemented?

**Trust**
- [ ] Do people give each other the benefit of the doubt?
- [ ] Is it safe to admit mistakes?
- [ ] Do people genuinely listen to each other?

**Performance**
- [ ] Are handoffs smooth between phases?
- [ ] Are rework and surprises minimized?
- [ ] Is the team delivering predictably?

If you answer "no" to more than 3 questions, schedule a team retrospective to address collaboration gaps.

---

## Collaboration Tools & Artifacts

### Required Artifacts
- **Project Charter** – accessible to all, updated weekly
- **Shared Backlog** – visible priority and status
- **Acceptance Criteria** – clear to all roles
- **Risk Register** – updated weekly
- **Decision Log** – captures what was decided and why

### Communication Channels
- **Daily Standup** – 15 min, all delivery team
- **Weekly PM+PdM sync** – planning and alignment
- **Async updates** – status in shared doc or wiki
- **Escalation channel** – clear path for blockers
- **Retrospective notes** – documented learnings

### Tools
- GitHub Issues/Projects for backlog and tracking
- GitHub Discussions for async collaboration
- Video calls (sync) for complex decisions
- Shared docs for planning and tracking

---

## When Collaboration Breaks Down

### Common Issues and Solutions

| Issue | Symptoms | Root Causes | Solutions |
|---|---|---|---|
| **Unclear accountability** | Finger-pointing, gaps | Roles not defined | Create RACI matrix, clarify decision rights |
| **Siloed work** | Surprises, rework | Insufficient syncs | Increase touchpoints, co-work on risks |
| **Misaligned priorities** | Conflicts, slower pace | Different success metrics | Align on goals in kickoff |
| **Escalation delays** | Issues fester, impacts grow | No clear escalation path | Document escalation process |
| **Low psychological safety** | People hide issues | Blame culture | Model blamelessness in retrospectives |
| **Knowledge hoarding** | Dependencies on individuals | No pairing or documentation | Require documentation, schedule pairing |

---

## Collaboration Checklist for Project Kickoff

- [ ] All roles represented and introduced
- [ ] Responsibilities and decision rights documented
- [ ] Communication cadence agreed (standups, syncs, escalation)
- [ ] Success metrics and goals shared
- [ ] Definition of Done discussed
- [ ] Risk register initialized with team input
- [ ] Collaboration tools configured and accessible
- [ ] First retrospective scheduled (even if mini)
- [ ] Trust-building activity completed
- [ ] Action items tracked and visible
