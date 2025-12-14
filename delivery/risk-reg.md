---
name: risk_reg
title: Risk Register
description: Identifies and documents project risks with impact assessment, mitigation strategies, and monitoring plans.
category: delivery
tags: ["risk","register","management","delivery","assessment"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T08:03:51.915Z
updated: 2025-12-14T08:03:51.915Z
arguments:
  - name: project/service_name
    description: Name of the project or service
    required: true
  - name: project_phase
    description: Current phase of the project
    required: true
  - name: timeline
    description: Project timeline and key milestones
    required: true
  - name: key_dependencies
    description: Key dependencies and external factors
    required: true
  - name: team_capacity
    description: Team capacity and resource availability
    required: true
  - name: any_known_issues
    description: Any known current issues or problems
    required: true
---

As a Delivery Manager, create or update a risk register for {{project/service_name}}.

Current context:
{{project_phase}}, {{timeline}}, {{key_dependencies}}, {{team_capacity}}, {{any_known_issues}}

Instructions to follow:
- Identify both current and potential future risks.
- Assess risks realistically across technical, resource, schedule, and stakeholder dimensions.
- Propose practical mitigation strategies, not theoretical ones.
- Assign clear ownership for monitoring and mitigation.
- Distinguish between risks (uncertain events) and issues (current problems).
- Use standard risk assessment criteria (likelihood × impact).

Output required:
1. Risk register table containing:
- Risk ID
- Risk description
- Category (Technical/Resource/Schedule/Stakeholder/External)
- Likelihood (High/Medium/Low)
- Impact (High/Medium/Low)
- Overall risk score
- Current status (Active/Monitoring/Closed)
- Mitigation strategy
- Contingency plan
- Owner
- Review date
2. Risk trend analysis (are risks increasing or decreasing)
3. Top risks requiring immediate attention
4. Recommended actions for leadership
5. Escalation criteria (when to escalate risks)