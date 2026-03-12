# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

## Escalation Checklist
- [ ] Issue identified and documented with description, impact, and timestamp
- [ ] Initial triage completed by team lead or on-call
- [ ] Level 1: Team-level resolution attempted (daily standup or async)
- [ ] Level 2 (if unresolved): PM notified and escalated to Product Lead + dependent teams
- [ ] Level 3 (if business-impacting): Sponsor-level escalation initiated
- [ ] Stakeholders notified with current status and expected resolution timeline
- [ ] Resolution confirmed and communicated to all affected parties
- [ ] Post-incident or post-escalation retrospective scheduled

## Communication Checklist
- [ ] Stakeholder groups identified and listed for this project
- [ ] Communication frequency and format agreed (weekly, milestone-based, etc.)
- [ ] Single source of truth for project status identified (README, release doc, or dashboard)
- [ ] Weekly status update sent using the status template
- [ ] Risk register reviewed and updated this week
- [ ] Incident communications issued (if applicable) with triage summary, actions, and timeline
- [ ] Post-incident blameless retrospective completed (if applicable)
