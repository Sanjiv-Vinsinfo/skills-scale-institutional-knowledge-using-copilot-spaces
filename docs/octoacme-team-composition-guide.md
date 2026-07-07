# OctoAcme — Team Composition & Resource Planning

## Purpose
Provide guidance on assembling effective project teams, staffing decisions, and resource planning based on project scope and complexity.

## Team Size and Composition

### Project Sizing Framework

Use this framework to determine team composition:

| Project Scale | Duration | Estimated Effort | Core Team | Additional Roles |
|---|---|---|---|---|
| **Minimal** | < 1 sprint | < 40 days | PM, PdM, 1-2 Devs | QA |
| **Small** | 1-2 sprints | 40-80 days | PM, PdM, 2-3 Devs | QA, Business Analyst |
| **Medium** | 2-4 sprints | 80-200 days | PM, PdM, 3-5 Devs | QA, Tech Architect, Scrum Master, Business Analyst |
| **Large** | 4-8 sprints | 200-400 days | PM, PdM, 5-8 Devs, Scrum Master | QA, Tech Architect, DevOps, Design Lead, Business Analyst |
| **Program** | 8+ sprints | 400+ days | PM, PdM, 8+ Devs, Scrum Master | Full complement of roles |

### Core Team Baseline

Every project should have:

1. **Project Manager (1)** – Owns schedule, risks, and cross-team coordination
2. **Product Manager/Lead (1)** – Owns priorities, acceptance criteria, and success metrics
3. **Developers (1+)** – Size based on work complexity and effort estimate
4. **QA/Testing (1 per 3-4 developers)** – Validates quality and manages test strategy

### Specialist Roles (Add as Needed)

Consider adding these roles based on project characteristics:

| Role | When to Add | Team Size |
|---|---|---|
| **Technical Architect** | Complex systems, new technology, high scalability needs | Medium+ projects |
| **Scrum Master** | Remote teams, complex dependencies, process challenges | Medium+ projects |
| **UX/Design Lead** | Consumer-facing features, significant UI changes, design system work | Medium+ projects |
| **DevOps/Infrastructure** | Infrastructure changes, CI/CD improvements, new platforms | Large projects |
| **Business Analyst** | Complex requirements, regulatory needs, process changes | Medium+ projects |
| **Stakeholder/Sponsor** | Strategic initiatives, executive visibility, cross-org alignment | All projects |

## Resource Planning

### Capacity Planning

1. **Identify available team members** across all relevant functions
2. **Assess capacity** – how much % time each person can allocate
3. **Map to skill requirements** – match roles to project needs
4. **Identify gaps** – flag missing expertise or overallocation
5. **Plan contingencies** – have backups for critical roles

### Allocation Model

**Full allocation**: 100% dedicated to project
- Best for: Core delivery roles, dedicated PMs
- Risk: Single points of failure

**High allocation** (70-80%): Primary commitment with other responsibilities
- Best for: Specialists, stakeholders
- Challenge: Context switching overhead

**Shared allocation** (30-50%): Shared across multiple projects
- Best for: Architects, QA leads, Business Analysts
- Risk: May delay critical path items

**Consultation allocation** (10-20%): Occasional input and guidance
- Best for: Senior stakeholders, subject matter experts
- Risk: May not provide sufficient depth

### Resource Planning Template

```
Project: [Name]
Duration: [Start Date - End Date]

## Core Team

| Role | Name | Allocation | Full/Part | Notes |
|---|---|---|---|---|
| Project Manager | | % | | |
| Product Manager | | % | | |
| Developer | | % | | |
| Developer | | % | | |
| QA/Testing | | % | | |

## Specialist Team (if needed)

| Role | Name | Allocation | Full/Part | Notes |
|---|---|---|---|---|
| Technical Architect | | % | | |
| Scrum Master | | % | | |
| UX/Design Lead | | % | | |
| DevOps Engineer | | % | | |
| Business Analyst | | % | | |

## Stakeholders

| Stakeholder | Role | Involvement | Approvals |
|---|---|---|---|
| | Sponsor | | |
| | Executive Stakeholder | | |
| | Department Lead | | |

## Risks & Mitigations

- **Risk**: [e.g., QA Lead not available] → **Mitigation**: [e.g., Cross-train Developer + Shared QA from another project]
- **Risk**: [e.g., Technical Architect overallocated] → **Mitigation**: [e.g., Assign Technical Lead from dev team]
```

## Cross-Functional Collaboration Practices

### Kickoff Alignment

Ensure all team members understand:

1. **Project vision and goals** – what success looks like
2. **Their specific role and responsibilities** – what they own
3. **Key dependencies** – who they need to coordinate with
4. **Communication rhythms** – standups, syncs, escalation paths
5. **Definition of Done** – quality and completion criteria

### Regular Touchpoints

| Frequency | Participants | Purpose |
|---|---|---|
| Daily | All delivery team | Status, blockers, dependencies |
| 2x/week | Core delivery team | Progress review, risk assessment |
| Weekly | PM, PdM, Leads | Planning, coordination, escalations |
| Weekly | Specialists (as needed) | Deep-dive on domain-specific topics |
| Bi-weekly | Extended team + Stakeholders | Demos, status updates, alignment |

### Decision Rights & Escalation

Clarify who decides what:

| Decision | Owner | Escalation Path |
|---|---|---|
| **Technical approach** | Technical Architect / Lead Dev | PM → PdM → Sponsor |
| **Feature scope** | Product Manager | PdM → Sponsor |
| **Release timing** | Project Manager | PM → PdM → Sponsor |
| **QA strategy** | QA Lead | QA → PM → PdM |
| **Process/workflow** | Scrum Master / PM | SM/PM → PdM |
| **Design standards** | Design Lead / PdM | Design → PdM → Sponsor |

## Common Pitfalls & How to Avoid Them

| Pitfall | Impact | Prevention |
|---|---|---|
| **Unclear role boundaries** | Duplication, gaps, confusion | Clear charter and decision rights |
| **Inadequate QA allocation** | Quality issues, delays | Plan QA effort = ~30-40% dev effort |
| **Missing specialist early** | Rework, technical debt | Include architects, designers in planning |
| **Over-allocated resources** | Burnout, context switching, delays | Monitor capacity, redistribute as needed |
| **Poor cross-functional communication** | Misalignment, rework, escalations | Regular syncs, shared visibility |
| **Single points of failure** | Risk if person unavailable | Cross-train, build redundancy for critical roles |

## Resource Planning Checklist

- [ ] Project size and complexity assessed
- [ ] Core team roles assigned with names
- [ ] Specialist roles identified and staffed
- [ ] Team capacity validated (no over-allocation)
- [ ] Backup/contingency plans for critical roles
- [ ] Stakeholders and sponsors identified
- [ ] Kickoff scheduled with full team
- [ ] Decision rights and escalation paths clarified
- [ ] Communication cadence agreed
- [ ] Definition of Done established
- [ ] Risk register includes resource risks
- [ ] Resource plan attached to project charter
