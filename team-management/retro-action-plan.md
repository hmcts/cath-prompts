---
name: retro_action_plan
title: Retrospective action plan
description: Converts retrospective feedback into prioritised, actionable improvement items with owners and timelines
category: team-management
tags: ["retrospective","action-plan","team-management","agile","continuous-improvement","prioritisation","owners","timelines","actions","success-criteria","dependencies"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T07:58:01.022Z
updated: 2025-12-14T07:58:01.022Z
arguments:
  - name: team_name
    description: Name of the team providing the retrospective feedback
    required: true
  - name: retro_feedback
    description: The retrospective feedback text to convert into an action plan
    required: true
---

As a Delivery Manager, convert the following retrospective feedback from the {{team_name}} team into a prioritized action plan:
{{retro_feedback}}

Instructions to follow:
- Group similar feedback themes together.
- Convert feedback into specific, measurable actions.
- Assign realistic owners and timelines.
- Prioritise actions based on impact and feasibility.
- Ensure actions are achievable within the next 1-2 sprints.
- Focus on continuous improvement rather than blame.

Output required:
1. Summary of key themes from the retrospective
2. Prioritised action items table containing:
- Action description
- Owner (or flag no owner)
- Due date
- Priority (High/Medium/Low)
- Success criteria
- Dependencies or support needed
3. Actions to start doing
4. Actions to stop doing
5. Actions to continue doing
6. Follow-up plan (how and when to review progress)
