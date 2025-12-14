---
name: product_roadmap
title: Product roadmap
description: Creates a prioritised roadmap with themes, features, and rationale aligned to strategic goals.
category: delivery
tags: ["product-management","roadmap","strategy","prioritization"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T08:06:55.362Z
updated: 2025-12-14T08:06:55.362Z
arguments:
  - name: product/service_name
    description: Name of the product or service
    required: true
  - name: timeframe
    description: Time period the roadmap covers (e.g., 'next 12 months', 'Q1-Q4 2024')
    required: true
  - name: business_goals
    description: Key business objectives and goals
    required: true
  - name: user_needs
    description: Primary user needs and pain points
    required: true
  - name: strategic_priorities
    description: Strategic priorities and focus areas
    required: true
  - name: constraints
    description: Key constraints (budget, timeline, technical, regulatory)
    required: true
---

As a Product Manager, create a product roadmap for {{product/service_name}} covering {{timeframe}}.

Strategic context:
{{business_goals}}, {{user_needs}}, {{strategic_priorities}}, {{constraints}}

Instructions to follow:
- Align roadmap items to strategic objectives and user outcomes.
- Group features into themes or initiatives.
- Balance quick wins with longer-term strategic bets.
- Include rationale for prioritisation decisions.
- Be realistic about capacity and dependencies.
- Keep the roadmap flexible - focus on outcomes over specific features for later periods.
- Use clear language that both technical and business stakeholders can understand.

Output required:
1. Strategic objectives the roadmap supports
2. Roadmap structure by time period (Now/Next/Later or quarterly):
3. For each initiative/theme:
- Theme name and description
- Strategic objective it supports
- Key features or capabilities included
- User value and expected outcomes
- Success metrics
- Dependencies
- Estimated timeframe
- Confidence level
3. Prioritisation rationale (why this sequence)
4. Key assumptions and risks
5. What's explicitly not included (and why)
6. Review and update cadence for the roadmap