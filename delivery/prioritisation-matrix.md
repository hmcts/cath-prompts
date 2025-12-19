---
name: prioritisation_matrix
title: Feature prioritisation matrix
description: Evaluates and ranks features using a scoring framework (value, effort, risk, strategic fit).
category: delivery
tags: ["prioritisation","features","matrix","scoring","product-management", "criteria"]
difficulty: intermediate
author: Prompt Team
version: 1.0
created: 2025-12-14T08:09:20.557Z
updated: 2025-12-14T08:09:20.557Z
arguments:
  - name: product/service_name
    description: The name of the product or service being evaluated
    required: true
  - name: list_of_features
    description: List of features to evaluate and prioritise
    required: true
---

As a Product Manager, evaluate and prioritise the following features for {{product/service_name}}:
{{list_of_features}}

Instructions to follow:
- Score each feature consistently across multiple dimensions.
- Use evidence and data where available, clearly note assumptions.
- Consider both user value and business value.
- Be honest about effort and risk assessments.
- Provide clear rationale for scoring decisions.
- Recommend a prioritised sequence based on the analysis.

Output required:
1. Scoring framework definition:
- User value (1-5 scale with criteria)
- Business value (1-5 scale with criteria)
- Implementation effort (1-5 scale: 1=low, 5=high)
- Risk (1-5 scale: 1=low, 5=high)
- Strategic fit (1-5 scale with criteria)
2. Prioritisation matrix table:
- Feature name
- User value score + rationale
- Business value score + rationale
- Effort score + rationale
- Risk score + rationale
- Strategic fit score + rationale
- Total/weighted score
- Priority ranking
3. Visual representation (if possible): high value/low effort quadrant analysis
4. Top 5 recommended priorities with justification
5. Features to defer or deprioritise with explanation
6. Key assumptions made in scoring
7. Recommended next steps for top priorities
