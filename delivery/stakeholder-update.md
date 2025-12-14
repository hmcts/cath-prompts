---
name: stakeholder_update
title: Stakeholder update
description: Creates a concise progress report for stakeholders highlighting achievements, blockers, and next steps.
category: delivery
tags: ["stakeholder","update","report","delivery","management"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T08:01:14.061Z
updated: 2025-12-14T08:01:14.061Z
arguments:
  - name: project/service_name
    description: Name of the project or service being reported on
    required: true
  - name: start_date
    description: Start date of the reporting period
    required: true
  - name: end_date
    description: End date of the reporting period
    required: true
  - name: sprint_goals
    description: Goals for the sprint/period
    required: true
  - name: key_deliverables_planned
    description: Key deliverables that were planned for this period
    required: true
  - name: team_composition
    description: Team members and their roles
    required: true
  - name: relevant_background
    description: Any relevant background context for stakeholders
    required: true
---

As a Delivery Manager, create a stakeholder update for {{project/service_name}} covering the period from {{start_date}} to {{end_date}}.

Context:
{{sprint_goals}}, {{key_deliverables_planned}}, {{team_composition}},  {{relevant_background}}

Instructions to follow:
- Use clear, non-technical language appropriate for senior stakeholders.
- Focus on outcomes and business value, not just outputs.
- Be transparent about challenges while demonstrating solutions.
- Keep the update concise - aim for one page.
- Use a professional, confident tone.
- Highlight both progress and any course corrections.

Output required:
1. Executive summary (2-3 sentences on overall status)
2. Key achievements and deliverables completed
- What was delivered
- Business value or impact
- User benefit
3. Progress against objectives/OKRs
- Current status (on track/at risk/off track)
- Supporting metrics or evidence
4. Current blockers or risks
- Issue description
- Impact on delivery
- Mitigation approach or support needed
5. Upcoming priorities for next period
6. Key decisions needed (if any)
7. RAG status (Red/Amber/Green) with brief rationale